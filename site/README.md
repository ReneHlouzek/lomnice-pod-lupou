# Web – informační portál Lomnice pod lupou

## Obrazovky a aktuální stav

- `index.html` – hlavní stránka s finančními ukazateli, navigací a metodikou.
- `finance.html` – srovnání rozpočtových údajů 2024–2026 a kontrolní zjištění.
- `dotace.html` – dotační radar napojený na centrální API projektu `ReneHlouzek/dotacni-radar-lomnice`. Načítá až 500 záznamů z `/grants`, statistiky z `/stats` a seznam evidovaných zdrojů z `/sources`. Umožňuje hledání, filtr podle tematické oblasti, stavu a poskytovatele. Pokud API není dostupné, zobrazí se záložní seznam sedmi příležitostí a upozornění, že nejde o úplnou evidenci.
- `zakazky.html` – funkční vyhledávání a filtry nad datovým indexem projektu `ReneHlouzek/lomnice-verejne-zakazky`. Index poskytuje 163 projektových celků v čase jeho poslední synchronizace; počet se mění.
- `investice.html` – vyhledávání projektů a dynamický detail s dostupnými událostmi, cenami, zdroji a potvrzenými smluvními vazbami.
- `app.js` – sdílená logika datových obrazovek.
- `assets/styles.css` – responzivní design pro desktop i mobil.

## Datové zdroje

- Veřejný katalog zakázek a smluv: [lomnice-verejne-zakazky](https://github.com/ReneHlouzek/lomnice-verejne-zakazky).
- Strojově čitelný index: `data/index.json` ve výše uvedeném repozitáři.
- Detail projektu: `data/projects/<id>.json`.
- Potvrzené vazby smluv a dodatků: `data/contract_links.json`.
- Centrální dotační evidence a API: [dotacni-radar-lomnice](https://github.com/ReneHlouzek/dotacni-radar-lomnice); veřejné API: `https://dotacni-radar-lomnice.onrender.com`.
- Centrální radar eviduje importy z DotaceEU, SFŽP, Ministerstva kultury, NRB, MMR, MPSV, AOPK a Jednotného dotačního portálu. Záznamy z automatického katalogu nemusejí být jednotlivé skutečné dotační výzvy; stav, termín a podmínky se musí ověřit na oficiálním zdroji.

Datový katalog zakázek se načítá za běhu z veřejného `raw.githubusercontent.com`. Pokud se zdroj nedá načíst, stránka má zobrazit chybové upozornění a ne falešná nulová data. Zdrojový index a detail se mohou aktualizovat nezávisle na tomto webu.

## Důležitá metodická omezení

1. Počet projektových celků není počet jednotlivých smluv, zakázek ani plateb.
2. Smluvní cena není automaticky uhrazená částka; neznámá platba není nula.
3. Cena s DPH a bez DPH se nesmí bez upozornění srovnávat.
4. Vazba dodatku na základní smlouvu se zobrazuje jako potvrzená pouze tehdy, pokud ji podporuje důkaz v datovém katalogu.
5. Otevřená dotační výzva není žádost, přiznaná dotace ani příjem peněz.
6. Zmínka o možné dotační vhodnosti není potvrzením způsobilosti projektu.
7. Plán, rozpočet po změnách a skutečné plnění jsou různé kategorie.
8. Automatická klasifikace a upozornění jsou podněty k ověření, nikoli důkaz pochybení.

## Nasazení

Web se nasazuje pomocí `.github/workflows/pages.yml` ze složky `site/`. Workflow se spouští po změně souborů `site/**` na větvi `main` a lze jej spustit také ručně. Stav nasazení je dostupný v kartě Actions.

## Další práce

1. Otestovat živé načítání dat a zobrazení všech tří obrazovek na desktopu i mobilu.
2. Ověřit kvalitu záznamů v centrálním dotačním katalogu; oddělit skutečné výzvy od obecných odkazů na programy, doplnit způsobilé žadatele, termíny, alokace a datum kontroly.
3. Propojit zakázky a investice s rozpočtovými položkami, usneseními, dotačními rozhodnutími a skutečnými úhradami.
4. Přidat přístupné tabulkové alternativy a ověřit ovládání klávesnicí.
5. Automaticky testovat odkazy, strukturu JSON a chyby načítání.
