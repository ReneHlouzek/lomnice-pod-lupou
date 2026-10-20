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
### Rok 2024
- Do repozitáře byla zařazena sada 21 PDF a identifikována rozpočtová opatření č. 1–8; soubor `Z.pdf` obsahově odpovídá RO č. 3.
- [Revidovaná finanční analýza (PDF – verze 2)](finance/2024/analyzy/Financni_analyza_Lomnice_nad_Popelkou_2024_revidovana_v2.pdf).
- [Kontrola klíčových údajů](finance/2024/analyzy/KONTROLA_KLICOVYCH_UDAJU_2024.md).
- [Rekonstrukce rozpočtových údajů](finance/2024/analyzy/REKONSTRUKCE_ROZPOCTOVYCH_UDAJU_2024.md).
- [Předání roku 2024 a známá omezení](finance/2024/analyzy/PREDANI_ROKU_2024.md).
- [Opravený inventář zdrojových PDF](finance/2024/metadata/INVENTAR_2024_OPRAVENY.md).
- Rok 2024 slouží jako srovnávací základna verze 1; není označen za úplný audit všech výdajů a investičních plateb.

### Rok 2025
- Založen pracovní prostor [`finance/2025/`](finance/2025/README.md) se standardní strukturou a kontrolním postupem.
- Dalším krokem je zaevidovat zdrojové dokumenty za rok 2025, ověřit úplnost sady a přepočítat hlavní rozpočtové agregáty podle FIN 2-12 M.

## Metodické omezení
Repozitář je pracovní analytický projekt, nikoli účetní evidence města ani auditní stanovisko. Před zveřejněním závěrů je nutné ověřit je vůči primárním dokumentům. Rozdíly v agregovaných řádcích je nejprve třeba vysvětlit definicí a rozsahem položek; samy o sobě nedokazují pochybení.
