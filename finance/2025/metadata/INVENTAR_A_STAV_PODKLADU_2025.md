# Rok 2025 – inventář zdrojových podkladů

Stav k 20. 10. 2026. Zdrojovou sadu tvoří 24 PDF souborů dodaných v ZIP archivu. Soubory jsou nyní roztříděny do podadresářů podle typu dokumentu; původní názvy jsou z větší části převedeny do jednotné podoby.

## Přijaté dokumenty

- Rozpočet: návrh rozpočtu, návrh se závaznými ukazateli, schválený rozpočet a kopie pro úřední desku.
- Rozpočtová opatření: č. 1–10. V archivu je jeden soubor pro každé číslo opatření. Původní název RO č. 1 obsahoval překlep „Rozpočetové opatření č.1“; není doloženo, že by šlo o obsahový duplikát.
- Plnění rozpočtu: FIN 2-12 M k 31. 12. 2025.
- Závěrečný účet za rok 2025 – schválený.
- Účetní výkazy: rozvaha, výkaz zisku a ztráty, příloha účetní závěrky, přehled peněžních toků a přehled změn vlastního kapitálu.
- Inventarizační zpráva 2025.
- Zpráva o výsledku přezkoumání hospodaření města za rok 2025.
- Samostatný PDF dokument „Finanční audit Lomnice nad Popelkou 2025“ – analytický materiál, nikoli zpráva zákonného auditora.

## Umístění v repozitáři

- `rozpocty/`: návrh a schválený rozpočet.
- `rozpoctova-opatreni/`: RO 1–10.
- `hospodareni/`: FIN 2-12 M, závěrečný účet, zpráva o přezkoumání a inventarizace.
- `ucetni-vykazy/`: rozvaha, výsledovka, příloha, peněžní toky a změny vlastního kapitálu.
- `analyzy/`: pracovní analýza a kontrolní zprávy.
- `metadata/`: inventář a metadata.

## Zjištění kontroly kvality zdrojů

1. Závěrečný účet uvádí schválení celoročního hospodaření dne 24. 6. 2026, usnesení 34/26/Z.
2. Zpráva o přezkoumání uvádí, že nebyly zjištěny chyby a nedostatky ani rizika s negativním dopadem do budoucna. Zákonné přezkoumání však nenahrazuje samostatné hodnocení hospodárnosti a budoucích provozních nákladů jednotlivých investic.
3. V RO č. 2 a 3 jsou nesoulady mezi souhrnnými tabulkami, položkovými změnami a navazujícími opatřeními. V RO č. 7 a 8 nesouhlasí souhrnná výdajová čísla s návazností; v RO č. 9 je v hlavičce tabulky chybné číslo opatření. Podrobnosti jsou v `../analyzy/KONTROLA_NAVAZNOSTI_RO_2025.md`.
4. FIN 2-12 M uvádí skutečné příjmy a výdaje před konsolidací 411,567 mil. Kč a 414,396 mil. Kč; po konsolidaci 187,645 mil. Kč a 190,475 mil. Kč. Hrubé částky proto nelze srovnávat s údaji po konsolidaci bez výslovného vysvětlení.
5. Účetní výsledek běžného období je 23,972 mil. Kč; nejde o rozpočtové saldo ani volnou hotovost.
6. Zůstatky bankovních účtů uvedené v závěrečném účtu činí 43,079 mil. Kč. Samy o sobě nevyjadřují volnou disponibilní rezervu.

## Další postup

1. Požádat o export upraveného rozpočtu po jednotlivých RO z účetního systému, zejména pro RO č. 2, 3, 7 a 8.
2. Dovést aritmetickou kontrolu FIN 2-12 M a porovnat ji se závěrečným účtem a účetními výkazy.
3. Navázat investiční výdaje na konkrétní akce, smlouvy, dodatky, faktury, dotace a platby.
4. Rozpadnout nedokončený dlouhodobý hmotný majetek 64,923 mil. Kč na konkrétní projekty.
5. Provést srovnání let 2024–2025 až po sjednocení definic a označení rozdílů v metodice.

**Metodické upozornění:** chybějící údaj není nula; schválený rozpočet není upravený rozpočet ani skutečnost; účetní zisk není rozpočtové saldo; smluvní cena není skutečně zaplacená částka; finanční signál není důkaz pochybení.
