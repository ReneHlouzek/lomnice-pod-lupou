# Lomnice pod lupou

Veřejně dohledatelný a zdrojově doložený přehled financí, investic, dotací, smluv a veřejných zakázek města Lomnice nad Popelkou.

## Zásady
- Původní dokumenty a veřejné zdroje musí být dohledatelné.
- Schválený rozpočet, upravený rozpočet a skutečnost se vedou odděleně.
- Chybějící údaj není nula.
- Cena smlouvy, rozpočtovaný výdaj, přiznaná dotace a skutečně uhrazená částka nejsou zaměnitelné.
- Automatické upozornění je podnět k ověření, nikoli důkaz pochybení.
- Neúspěšný import nesmí přepsat poslední validní výstup.
- Každé zveřejněné finanční tvrzení má mít zdroj, stranu/řádek, období a jednotku.

## Oblasti
- `finance/` – finanční podklady po letech včetně rozpočtů, rozpočtových opatření, účetních výkazů, závěrečných účtů a analýz.
- `docs/` – architektura, datový model a metodika.
- `schemas/` – validační schémata.
- `scripts/` – import, extrakce a validace.
- `data/` – odvozené strojově čitelné výstupy.
- `site/` – budoucí veřejný web.
- `tests/` – testy importu a validace.

## Aktuální stav finančních podkladů
- Rok 2024: do repozitáře byla zařazena sada 21 PDF.
- Rozpočtová opatření č. 1–8 za rok 2024 jsou identifikována; soubor `Z.pdf` obsahově odpovídá RO č. 3.
- Kontrola finanční analýzy vůči primárním dokumentům probíhá. Otevřené body jsou uvedeny v `finance/2024/analyzy/STAV_KONTROLY_2024.md`.
- Opravený inventář 21 PDF je v `finance/2024/metadata/INVENTAR_2024_OPRAVENY.md`. Původní inventář `INVENTAR_PRVNI_DAVKY.md` zachovává historický záznam první kontroly.
- Analytické dokumenty jsou pracovní výstupy a nenahrazují oficiální účetní výkazy ani přezkoumání hospodaření.
- Další rok bude zpracován po uzavření a zdokumentování sady 2024.

## Metodické omezení
Repozitář je pracovní analytický projekt, nikoli účetní evidence města ani auditní stanovisko. Před zveřejněním závěrů je nutné ověřit je vůči primárním dokumentům. Rozdíly v agregovaných řádcích je nejprve třeba vysvětlit definicí a rozsahem položek; samy o sobě nedokazují pochybení.
