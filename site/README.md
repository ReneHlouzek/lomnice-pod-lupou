# Web – první návrh

## Aktuální stav
- `index.html` obsahuje první responzivní návrh úvodní stránky v čistém HTML a CSS, bez externích knihoven.
- Návrh má navigaci, úvodní blok, přehled oblastí, rozpočtové roky 2024–2026, metodiku a odkazy na zdrojový archiv.
- Zatím nejde o plně datově napojenou aplikaci. Graf v úvodu je výslovně označen jako ilustrační a nesmí být zaměňován za skutečná čísla.
- Připraven workflow `.github/workflows/pages.yml`, který po povolení GitHub Pages nasazuje obsah složky `site/`.
- Veřejné nasazení ještě není potvrzeno. V nastavení repozitáře je potřeba vybrat **Settings → Pages → Build and deployment → Source: GitHub Actions**. Integrační nástroj dostupný v této relaci neumožňuje změnit nastavení Pages přímo.

## Zapnutí veřejného webu
1. Otevřít [nastavení GitHub Pages](https://github.com/ReneHlouzek/lomnice-pod-lupou/settings/pages).
2. V části **Build and deployment** nastavit **Source** na **GitHub Actions**.
3. Pokud GitHub nabídne potvrzení nebo výběr workflow, zvolit workflow **Deploy static site to GitHub Pages**.
4. Otevřít kartu **Actions** a ověřit, že workflow doběhne úspěšně.
5. Po úspěšném nasazení bude projektová stránka standardně dostupná na adrese [https://renehlouzek.github.io/lomnice-pod-lupou/](https://renehlouzek.github.io/lomnice-pod-lupou/). GitHub může potřebovat několik minut na první publikaci.

## Zásady dalšího vývoje
1. Každý graf musí mít srovnatelná data, popsané jednotky, období, definici ukazatele a odkaz na původní zdroj.
2. Ke grafům doplnit přístupnou tabulkovou alternativu.
3. Schválený rozpočet, rozpočet po změnách a skutečnost zobrazovat odděleně.
4. U každého zjištění rozlišovat ověřený fakt, interpretaci a otevřenou otázku.
5. Neprezentovat rozpočtovou nesrovnalost jako důkaz pochybení bez ověření primárním zdrojem.
6. Otestovat zobrazení na mobilu, klávesnicí a se čtečkou obrazovky.
7. Před veřejným spuštěním zkontrolovat všechny odkazy, popisky, kontrast a aktuálnost údajů.

## Další doporučené kroky
1. Dokončit první zapnutí Pages a ověřit výsledek v prohlížeči.
2. Zkontrolovat návrh na mobilu i desktopu a upravit vizuální styl podle zpětné vazby.
3. Přidat stránku s detailním rozpočtem 2024–2026 a přístupnou tabulkou.
4. Vytvořit strojově čitelnou datovou vrstvu s metadaty a zdrojovými odkazy.
5. Teprve po validaci dat napojit grafy a ukazatele.
