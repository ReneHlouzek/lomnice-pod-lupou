# Finanční podklady města za rok 2025

Tento adresář slouží ke zpracování finančních dokumentů za rok 2025 podle stejné metodiky jako rok 2024.

## Stav k 20. 10. 2026

**Zdrojová sada byla dodána a obsahuje 24 PDF souborů.** Zahrnuje rozpočet a jeho návrhy, rozpočtová opatření č. 1–10, FIN 2-12 M, závěrečný účet, účetní výkazy, inventarizační zprávu, zprávu o přezkoumání hospodaření a pracovní analytickou zprávu.

- Inventář a stav zdrojů: [metadata/INVENTAR_A_STAV_PODKLADU_2025.md](metadata/INVENTAR_A_STAV_PODKLADU_2025.md)
- Pracovní finanční analýza: [analyzy/FINANCNI_ANALYZA_2025_PRACOVNI_VERZE_1.md](analyzy/FINANCNI_ANALYZA_2025_PRACOVNI_VERZE_1.md)

## Doporučená struktura
- `rozpocty/` – schválený rozpočet a návrhy rozpočtu
- `rozpoctova-opatreni/` – rozpočtová opatření číslovaná podle schválení
- `hospodareni/` – FIN 2-12 M, závěrečný účet, inventarizace a zpráva o přezkoumání
- `ucetni-vykazy/` – rozvaha, výkaz zisku a ztráty, příloha a další výkazy
- `investice/` – přehled akcí a návaznost na smlouvy, dodatky, faktury a platby
- `analyzy/` – kontrolní poznámky a finální analýza
- `metadata/` – seznam zdrojů, data získání, období, kontrolní součty a stav ověření

## Kontrolní postup
1. Zaevidovat všechny zdrojové dokumenty a ověřit, že sada je úplná.
2. Přepsat schválený rozpočet, upravený rozpočet a skutečnost odděleně.
3. Aritmeticky ověřit příjmové a výdajové třídy, konsolidaci a saldo proti FIN 2-12 M.
4. Porovnat hlavní hodnoty se závěrečným účtem a účetními výkazy.
5. Rekonstruovat RO 1–10 v chronologickém pořadí a označit významné přesuny.
6. Vybrat významné investice a dohledat rozpočtové změny, smlouvy, dodatky, faktury a úhrady.
7. Vytvořit srovnání 2024–2025 až po ověření srovnatelnosti ukazatelů.

## Srovnávací základna
Rok 2024 je předán jako verze 1 s výslovně evidovanými omezeními v `../2024/analyzy/PREDANI_ROKU_2024.md`. Při srovnání se musí používat stejné definice agregátů, zejména u příjmů a výdajů před/po konsolidaci.

## Metodické zásady
Chybějící údaj není nula. Schválený rozpočet není skutečnost. Účetní zisk není rozpočtové saldo ani volná hotovost. Finanční signál je podnět k ověření, nikoli důkaz pochybení.
