# Kontrola klíčových údajů finanční analýzy 2024

**Datum:** 20. 10. 2026  
**Účel:** průběžná kontrola čísel z analytického PDF vůči dodaným primárním dokumentům. Nejde o úplný audit všech účetních položek.

## Hodnoty ověřené proti závěrečnému účtu / účetním výkazům

| Ukazatel | Ověřená hodnota | Primární zdroj | Poznámka |
|---|---:|---|---|
| Příjmy po konsolidaci za 2024 | 180 650 286,18 Kč | Závěrečný účet 2024, část 2.5 „Rozpočtová odpovědnost“ | V analýze zaokrouhleno na 180,650 mil. Kč. |
| Skutečné výdaje | 163,640 mil. Kč | FIN 2-12 M a závěrečný účet, přehled plnění rozpočtu | Proti upravenému rozpočtu 187,151 mil. Kč je rozdíl 23,511 mil. Kč. Neoznačovat automaticky jako úsporu. |
| Bankovní účty k 31. 12. 2024 | 56 907 393,83 Kč | Závěrečný účet 2024, strana 8 | Součet zůstatků bankovních účtů. |
| Finanční majetek netto k 31. 12. 2024 | 56 954 649 Kč | Závěrečný účet 2024, strana 8; rozvaha | Není totožný s prostým součtem bankovních účtů; rozdíl je přibližně 47,3 tis. Kč. V textu rozlišovat bankovní účty a finanční majetek. |
| Nedokončený dlouhodobý hmotný majetek | 49 087 293,99 Kč (2024); 29 366 354,18 Kč (2023) | Rozvaha, strana 1; závěrečný účet, strana 8 | Meziroční nárůst přibližně 19,721 mil. Kč. Sám o sobě nedokazuje problém; vyžaduje seznam jednotlivých akcí. |
| Dlouhodobé úvěry | 28 108 396 Kč (2024); 39 208 800 Kč (2023) | Rozvaha, strana 3; závěrečný účet, strany 9–11 | Pokles jistiny přibližně 11,100 mil. Kč. |
| Závazky celkem | 42 648 019,75 Kč (2024); 55 315 277,32 Kč (2023) | Rozvaha, strana 3; závěrečný účet, strana 9 | Jde o účetní závazky celkem, nikoli pouze o úvěry. |
| Účetní výsledek hospodaření | 33 515 752,67 Kč | Rozvaha, strana 3; závěrečný účet, strana 8 | Zaokrouhlení 33,516 mil. Kč je správné. Nezaměňovat s rozpočtovým saldem ani hotovostí. |
| Nedaňové příjmy | 21 154 326,80 Kč | FIN 2-12 M, strana 14; závěrečný účet, strana 3 | Závěrečný účet na téže straně uvádí v jiném řádku „Běžné a kapitálové příjmy“ 21 568 tis. Kč. Bez definice nelze částky považovat za tutéž veličinu. |
| Plánované saldo výhledu 2025–2028 | −23; −13; −30; −22 mil. Kč | Střednědobý výhled 2025–2028, strana 1 | Součet plánovaných schodků je 88 mil. Kč. Jde o plán, nikoli skutečný výsledek. |
| Dluh / průměr příjmů | 16,11 % | Závěrečný účet, část 2.5, strana 11 | Podíl je pod zákonnou hranicí 60 % uvedenou v dokumentu. |

## Opravy formulací v analytickém PDF

1. Uvádět bankovní zůstatky 56,907 mil. Kč odděleně od účetního finančního majetku 56,955 mil. Kč.
2. Rozdíl 23,511 mil. Kč mezi upraveným rozpočtem výdajů a skutečností popisovat jako nedočerpání / rozdíl proti upravenému rozpočtu, nikoli bez dalšího jako úsporu.
3. U nedaňových příjmů použít 21,154 mil. Kč podle FIN 2-12 M a upozornit, že řádek 21 568 tis. Kč v závěrečném účtu má jiný název.
4. U nedokončeného majetku, pohledávek a změn rozpočtu formulovat další kroky jako kontrolní otázky, ne jako důkaz pochybení.
5. Ve zdrojích uvést RO č. 3, uložené v repozitáři pod názvem `Z.pdf`.

## Co ještě není uzavřeno

- Nebyla provedena kompletní nezávislá rekonstrukce každé rozpočtové položky a každého součtu.
- Nebyla ověřena každá investice proti smlouvám, dodatků, fakturám a bankovním platbám.
- Revidovaný PDF soubor je vytvořen lokálně, ale jeho binární obsah zatím nebyl publikován do GitHubu; odkaz ke stažení je v konverzaci. Dokud nebude soubor nahrán a znovu stažen ke kontrole, nelze říci, že je revidované PDF publikované v repozitáři.
