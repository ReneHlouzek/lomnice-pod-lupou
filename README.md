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
- Rozdíl v číslech je nejprve nutné vysvětlit definicí a rozsahem položek; sám o sobě nedokazuje pochybení.

## Oblasti
- `finance/` – finanční podklady po letech včetně rozpočtů, rozpočtových opatření, účetních výkazů, závěrečných účtů a analýz.
- `docs/` – architektura, datový model a metodika.
- `schemas/` – validační schémata.
- `scripts/` – import, extrakce a validace.
- `data/` – odvozené strojově čitelné výstupy.
- `site/` – budoucí veřejný web.
- `tests/` – testy importu a validace.

## Aktuální stav finančních podkladů
- Rok 2024: do repozitáře byla zařazena sada 21 PDF. Probíhá věcná kontrola finanční analýzy vůči primárním dokumentům.
- Rozpočtová opatření č. 1–8 za rok 2024 jsou identifikována. Soubor `Z.pdf` obsahově odpovídá RO č. 3.
- Zjištěné otevřené body a postup kontroly jsou v `finance/2024/analyzy/STAV_KONTROLY_2024.md`.
- Inventář dokumentů je v `finance/2024/metadata/INVENTAR_PRVNI_DAVKY.md`.
- Finanční analýzu za rok 2024 zatím nepovažovat za finální, dokud nebudou uzavřeny ověřovací body a publikována revidovaná verze.
- Další roky budou doplňovány až po uzavření a zdokumentování předchozí sady.

## Metodické omezení
Repozitář je pracovní analytický projekt, nikoli účetní evidence města ani auditní stanovisko. Před zveřejněním závěrů je nutné ověřit je vůči primárním dokumentům. Případné nesrovnalosti formulovat věcně a bez nepodložených obvinění.
