# Architektura

Stávající repozitáře zůstávají vlastníky svých importních procesů. Tento projekt bude integrační a prezentační vrstvou, která načítá jejich ověřené veřejné výstupy a přidává finanční dokumentaci.

## Finanční data
1. Originální PDF jsou uložena v `finance/<rok>/`.
2. `metadata.json` eviduje původ, období, kontrolní hash a stav zpracování.
3. Skripty extrahují text/tabulky a vytvářejí kontrolní report.
4. Ověřená analytická data jsou publikována odděleně v `data/finance/`.
5. Web zobrazuje údaj spolu s odkazem na zdroj a stránku.

## Spolehlivost
- Tajné údaje se do repozitáře neukládají.
- Neúspěšné zpracování nesmí nahradit poslední validní výstup.
- Automatické vazby mezi projekty, smlouvami, dotacemi a financemi musí nést úroveň jistoty a důkaz.
