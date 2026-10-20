# Inventář a obsahová kontrola dokumentů – rok 2024

**Kontrola provedena:** 20. 10. 2026  
**Rozsah:** všech 20 věcných PDF z dodaného ZIP archivu + kontrola jejich zařazení v repozitáři.  
**Metoda:** kontrola otevření PDF, počtu stran, textové vrstvy, identifikace účetního období, názvu dokumentu, schvalovacích údajů a porovnání názvů/obsahu. Originální PDF nebyla upravována; přesuny zachovávají původní Git blob.

## Výsledek kontroly

- Všech **20 PDF lze otevřít** a z každého se podařilo vytěžit text. Počty stran jsou uvedeny níže.
- Nebyla zjištěna přesná duplicita podle SHA-256 v dodaném ZIPu.
- Rozpočtová opatření **č. 1 až 8 jsou kompletní jako číselná řada v dodané sadě**. To samo o sobě nepotvrzuje, že jde o všechny případné přílohy či zveřejněné verze.
- Dokument „FIN 2 - 12 M“ je výkaz FIN 2-12 M sestavený k 12/2024.
- Účetní výkazy (rozvaha, výsledovka, příloha, peněžní toky, změny vlastního kapitálu) uvádějí období 12/2024 a identifikují město IČO 00275905.
- Závěrečný účet uvádí schválení zastupitelstvem dne 25. 6. 2025, usnesení 30/25/Z.
- Zpráva o přezkoumání je za rok 2024. Závěrečný účet popisuje zjištěný nedostatek ve střednědobém výhledu, který byl napraven; současně uvádí, že nebyla zjištěna závažná rizika s negativním dopadem do budoucna. Nelze to zkracovat na „bez jakýchkoli nedostatků“.
- PDF „Finanční analýza…“ je pracovní analytický dokument datovaný 19. 10. 2026, nikoli oficiální výkaz města ani statutární audit. Závěry z něj je nutné ověřovat proti primárním zdrojům.

## Zařazení souborů

### `finance/2024/rozpocty/`
| Soubor | Rozsah | Zjištění / důvod zařazení |
|---|---:|---|
| `Fin_24_02.pdf` | 4 strany | Rozpočtový přehled pro rok 2024; obsahuje příjmy, výdaje a financování v tis. Kč. Název souboru sám neurčuje formální typ sestavy. |
| `Fin_24_03.pdf` | 5 stran | Podrobný rozpis rozpočtu 2024 podle položek/odpovědností; obsahuje rozpočtové položky a příspěvkové organizace. |
| `Střednědobý výhled rozpočtu 2025-2028.pdf` | 1 strana | Výhled na roky 2025–2028. |
| `Fin_6_23.pdf` | 1 strana | Střednědobý výhled schválený 26. 4. 2023, usnesení 11/23/Z; tabulka pokrývá zejména roky 2024–2025. Jde o starší verzi výhledu, zachována odděleně od výhledu 2025–2028. |

### `finance/2024/rozpoctova-opatreni/`
| Soubor | Rozsah | Zjištění / důvod zařazení |
|---|---:|---|
| `RO_1.pdf` | 1 strana | Rozpočtové opatření č. 1, rok 2024. |
| `Rozp.opat.č.2.pdf` | 1 strana | Rozpočtové opatření č. 2, rok 2024. |
| `Z.pdf` | 2 strany | Rozpočtové opatření č. 3; schváleno ZM 26. 6. 2024, usnesení 28/24/Z. Název souboru je neprůhledný, ale obsah určil zařazení. |
| `RO č.4 - usnesení.pdf` | 1 strana | Rozpočtové opatření č. 4; podle textu schválila rada města. |
| `Rozpočtové opatření č.5 - na web.pdf` | 2 strany | RO č. 5; schváleno ZM 25. 9. 2024, usnesení 56/24/Z. |
| `Rozpočtové opatření č.6.pdf` | 1 strana | RO č. 6; schválila rada města 21. 10. 2024, usnesení 269/24/R. |
| `Rozpočtové opatření č.7.pdf` | 1 strana | RO č. 7; schváleno ZM 4. 12. 2024, usnesení 69/24/Z. |
| `Rozpočtové opatření č.8.pdf` | 1 strana | RO č. 8; schválila rada města 16. 12. 2024, usnesení 342/24/R. |

### `finance/2024/hospodareni/`
| Soubor | Rozsah | Zjištění / důvod zařazení |
|---|---:|---|
| `FIN 2-12M.pdf` | 22 stran | Oficiální výkaz FIN 2-12 M, sestavený k 12/2024; město Lomnice nad Popelkou, IČO 00275905. |
| `Závěrečný účet 2024 - schválený.pdf` | 13 stran | Schválený závěrečný účet za rok 2024; schválení 25. 6. 2025, usnesení 30/25/Z. |
| `Zprava o výsledku přezkoumání hospodaření města.pdf` | 18 stran | Zpráva Libereckého kraje o přezkoumání hospodaření města za rok 2024. |

### `finance/2024/ucetni-vykazy/`
| Soubor | Rozsah | Zjištění / důvod zařazení |
|---|---:|---|
| `Rozvaha.pdf` | 3 strany | Rozvaha k 12/2024. |
| `Výkaz zisku a ztráty.pdf` | 2 strany | Výkaz zisku a ztráty k 12/2024. |
| `Příloha.pdf` | 6 stran | Účetní příloha k 12/2024. |
| `Přehled o peněžních tocích.pdf` | 1 strana | Přehled peněžních toků k 12/2024. |
| `Přehled o změnách vlastního kapitálu.pdf` | 1 strana | Přehled změn vlastního kapitálu k 12/2024. |

### `finance/2024/analyzy/`
| Soubor | Rozsah | Zjištění / důvod zařazení |
|---|---:|---|
| `Financni_analyza_Lomnice_nad_Popelkou_2024.pdf` | 9 stran | Pracovní analýza datovaná 19. 10. 2026. Není primárním účetním dokumentem; tvrzení a čísla je nutné doložit citací na původní výkaz. |

## Omezení a navazující kontrola

1. Kontrola potvrzuje čitelnost a identifikaci dokumentů, nikoli úplnou věcnou auditní kontrolu všech řádků a součtů.
2. Před analytickým výpočtem je třeba porovnat schválený rozpočet, jednotlivá rozpočtová opatření, upravený rozpočet a skutečnost z FIN 2-12 M a závěrečného účtu.
3. Rozpočtové výhledy jsou různé verze s různými daty schválení; neslučovat je bez označení platnosti.
4. Hodnoty v rozpočtových tabulkách jsou často v tisících Kč, účetní výkazy jsou v Kč. Při převodu jednotek uvádět zdroj a jednotku.
5. Při publikaci každého zjištění uvádět dokument, stranu/část, období a jednotku. Chybějící údaj neznamená nulu; rozpočtová položka není automaticky dokladem skutečné platby.
