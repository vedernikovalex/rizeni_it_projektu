# 2. část semestrálního projektu: Spolubyt

Obsahový podklad týmu k 2. prezentaci a k písemnému dokumentu. Zadání a termíny viz [podklady.md](podklady.md). Odevzdání do Moodlu a do MS Teams dělá Saša.

| Soubor | Obsah |
|---|---|
| `spolubyt-semestralni-projekt.docx` | písemný dokument (32 stran) se všemi body zadání: idea, Lean Canvas, Business Model Canvas, persony, architektura, harmonogram, Business Case, rizika, Use Case diagram, scénáře, wireframy |
| `spolubyt-semestralni-projekt-nahled.pdf` | náhled písemného dokumentu v PDF |
| `spolubyt-business-case.xlsx` | Business Case na 5 let: předpoklady, uživatelé a příjmy, provoz, lidské zdroje po měsících, NPV, citlivost, grafy |
| `spolubyt-rizika.xlsx` | registr 14 rizik a jedné příležitosti se zdůvodněním hodnocení, Paretova analýza, matice rizik |
| `spolubyt-use-case.drawio` | Use Case diagram (UML 2.5, černobílý), zdroj pro draw.io |
| `spolubyt-use-case.png` | Use Case diagram jako obrázek |
| `spolubyt-cast-2.pptx` | prezentace 2. části, 17 slajdů |

## Pokyny z hodiny 11. 11.

- Business Case podobně jako vzorový Excel z Moodlu, horizont 5 let.
- Pesimistický scénář o 15 až 20 % horší, volíme 15 %.
- Uživatele odhadnout ze statistik studentů, s trendem a odlivem, růst nemá být exponenciála.
- Příjmy nesmí stát na reklamě, zisk má vyjít mezi 2. a 3. rokem, NPV za 5 let s mírou ČNB.
- Náklady včetně facility.
- Rizika ve tvaru „když příčina, spouští událost, tak efekt“, škály, Pareto, strategie akceptovat, přenést, vyhnout se, snížit.
- Hranice systému v Use Case diagramu není povinná, ale vyučující ji uvítá. Máme ji.
- Scénáře a wireframy alespoň dva, ne přihlášení ani registrace.
- Prezentace 15 minut. Odevzdání lichý týden, středa: 24. 11. 2026 23:59, prezentace 25. 11.

## Business Case

- Rok 1 = 12/2026 až 11/2027: celý vývoj podle harmonogramu (3 025 100 Kč lidé a 257 950 Kč materiál), spuštění 18. 8. 2027.
- Trh: Praha 49 300, Brno 22 988, ostatní města 40 692, celkem 112 980 studentů mimo koleje, k tomu 50 % za mladé pracující.
- Podíl na trhu: Praha 7 / 18 / 26 / 30 / 32 %, Brno od roku 2 (9 / 18 / 23 / 26 %), ostatní města od roku 3 (6 / 12 / 15 %). Odliv 35 % ročně.
- Ceny: Premium hledání 149 Kč měsíčně, inzerát 299 Kč na 30 dní, Premium domácnost 199 Kč měsíčně za domácnost.
- Zdarma: 3 žádosti o prohlídku měsíčně, rozpočítání nájmu, evidence výdajů a QR platby. Ceny jsou proti 1. části vyšší (99 / 199 / 99 Kč nestačilo na zisk ve 3. roce).
- Inzeráty jsou v první sezóně (od spuštění do listopadu 2027, rok 1 modelu) zdarma jako opatření k riziku R1, placené od roku 2.
- Facility 120 000 Kč ročně (coworking a sídlo firmy).
- Pesimistický scénář = příjmy × 0,85. Diskontní míra 4 % (2T repo sazba ČNB), citlivost s diskontní sazbou ČNB 3 %.

| Kč | Rok 1 | Rok 2 | Rok 3 | Rok 4 | Rok 5 | Celkem |
|---|---:|---:|---:|---:|---:|---:|
| Lidské zdroje (projekt a provoz) | 3 617 100 | 3 504 000 | 4 560 000 | 4 992 000 | 4 992 000 | 21 665 100 |
| Materiál projektu | 257 950 | 0 | 0 | 0 | 0 | 257 950 |
| Cloud infrastruktura | 19 098 | 139 861 | 212 511 | 256 284 | 276 723 | 904 477 |
| Externí služby (BankID, mapy, e-mail) | 37 059 | 128 267 | 186 517 | 198 503 | 195 326 | 745 672 |
| Licence a nástroje | 4 671 | 30 450 | 40 950 | 45 150 | 45 150 | 166 371 |
| Facility (coworking, sídlo firmy) | 20 000 | 120 000 | 120 000 | 120 000 | 120 000 | 500 000 |
| Marketing | 100 000 | 350 000 | 450 000 | 400 000 | 400 000 | 1 700 000 |
| Právní a účetní služby | 20 000 | 100 000 | 100 000 | 100 000 | 100 000 | 420 000 |
| Poplatky obchodů a platební brány | 24 881 | 403 709 | 722 628 | 929 868 | 1 027 695 | 3 108 780 |
| **Náklady celkem, optimistický** | 4 100 759 | 4 776 287 | 6 392 606 | 7 041 804 | 7 156 894 | 29 468 350 |
| **Příjmy, optimistický** | 259 176 | 4 205 300 | 7 527 370 | 9 686 126 | 10 705 154 | 32 383 126 |
| **Zisk, optimistický** | −3 841 583 | −570 987 | 1 134 765 | 2 644 321 | 3 548 260 | 2 914 776 |
| **Příjmy, pesimistický** | 220 300 | 3 574 505 | 6 398 265 | 8 233 207 | 9 099 381 | 27 525 657 |
| **Zisk, pesimistický** | −3 876 727 | −1 141 226 | 114 053 | 1 330 883 | 2 096 641 | −1 476 376 |
| Kumulovaný zisk, optimistický | −3 841 583 | −4 412 570 | −3 277 805 | −633 484 | 2 914 776 | |
| Kumulovaný zisk, pesimistický | −3 876 727 | −5 017 953 | −4 903 900 | −3 573 017 | −1 476 376 | |
| Aktivní uživatelé | 5 176 | 16 743 | 29 969 | 38 564 | 42 621 | |

- NPV při 4 %: 1 963 850 Kč (optimistický) a −1 820 426 Kč (pesimistický). NPV při 3 %: 2 180 774 Kč a −1 744 100 Kč.
- Zisk v obou scénářích od roku 3. Návratnost v optimistickém scénáři v roce 5, v pesimistickém až po roce 5.
- Citlivost (list Citlivost): NPV je nulová při konverzi do Premium domácnost 25,8 % (optimistický) a 34,6 % (pesimistický). Při 20 % vychází NPV −2,68 mil. Kč, při 80 % placených inzerátů +0,17 mil. Kč.

## Rizika

Škála 1 až 10, závažnost = P × D, hranice kvadrantů 5. Tři nejzávažnější rizika tvoří 38 % celkové závažnosti.

| ID | Riziko | P | D | P × D | Kvadrant | Strategie | Vlastník |
|---|---|---:|---:|---:|---|---|---|
| R1 | Málo nabídek pokojů na startu | 7 | 9 | 63 | kritická | Snížit | Marketingový specialista |
| R2 | Zpoždění vývoje před sezónou | 6 | 9 | 54 | kritická | Snížit | Projektový manažer |
| R3 | Podvodné profily a inzeráty | 6 | 8 | 48 | kritická | Snížit | Backend developer |
| R4 | Nízká ochota platit | 6 | 7 | 42 | kritická | Snížit | Projektový manažer |
| R5 | Špatná doporučení matchingu | 6 | 6 | 36 | kritická | Snížit | Projektový manažer |
| R6 | Únik osobních dat | 3 | 10 | 30 | významná | Přenést | Backend developer |
| R7 | Odchod klíčového vývojáře | 4 | 7 | 28 | významná | Snížit | Projektový manažer |
| R8 | Vstup konkurence na český trh | 4 | 6 | 24 | významná | Snížit | Marketingový specialista |
| R9 | Přetížení serverů v sezóně | 6 | 4 | 24 | běžná | Snížit | Backend developer |
| R10 | Překročení rozpočtu | 6 | 4 | 24 | běžná | Snížit | Projektový manažer |
| R11 | Přetížení zákaznické podpory | 7 | 3 | 21 | běžná | Snížit | Projektový manažer |
| R12 | Aplikace jako platební služba | 2 | 9 | 18 | významná | Vyhnout se | Právník – externí |
| R13 | Výpadek BankID nebo platební brány | 3 | 4 | 12 | bezvýznamná | Akceptovat | Backend developer |
| R14 | Změna pravidel App Store / Google Play | 3 | 4 | 12 | bezvýznamná | Akceptovat | Frontend / mobilní developer |

Příležitost P1: spolupráce s univerzitami a kolejemi (strategie využít).

Vlastníky rizik jsou jen role, které zůstávají i v provozním týmu (architekt a business analytik po spuštění končí).

## Use Case diagram

UML 2.5, černobílý, s hranicí systému, 24 případů užití, 5 aktérů a 2 externí systémy.

- **Uživatel** (obecný aktér): Registrovat se, Přihlásit se.
- **Hledající:** Vyplnit dotazník životního stylu, Procházet doporučené pokoje, Zobrazit detail inzerátu, Požádat o prohlídku.
- **Nabízející:** Vystavit inzerát pokoje, Vybrat zájemce podle kompatibility, Potvrdit žádost o prohlídku.
- **Člen domácnosti:** Spravovat domácnost a dohodu o soužití, Spravovat rozpis úklidu, Přidat společný výdaj, Vyrovnat dluh QR platbou, Vyúčtovat energie, Ohodnotit spolubydlícího, Aktivovat Premium domácnost, Pozvat spolubydlícího do domácnosti.
- **Administrátor:** Moderovat inzeráty a profily.
- **Vložené a rozšiřující případy:** Spočítat kompatibilitu, Filtrovat podle lokality a dojezdu, Odeslat zprávu, Aktivovat Premium hledání, Ověřit identitu přes BankID, Zaplatit službu.
- Zaplatit službu «extend» Vystavit inzerát pokoje: v první sezóně do listopadu 2027 je inzerát zdarma.
- Aktivovat Premium domácnost «extend» Vyúčtovat energie: vyúčtování energií je placené, rozpočítání nájmu, výdaje a QR platby jsou zdarma.
- Scénáře a wireframy: Procházet doporučené pokoje a Požádat o prohlídku. Plné znění scénářů je v písemném dokumentu, kapitola 10.

## User journey

| Krok | Co Tereza dělá | Případ užití | Wireframe |
|---|---|---|---|
| 1 | Vyplní dotazník | Vyplnit dotazník životního stylu | 1 |
| 2 | Projde nabídky | Procházet doporučené pokoje | 2 |
| 3 | Otevře detail | Zobrazit detail inzerátu | 3 |
| 4 | Pošle žádost | Požádat o prohlídku | 4 |
| 5 | Zaplatí Premium | Aktivovat Premium hledání | 5 |

## Otevřené body pro tým

- Odsouhlasit vyšší ceny služeb proti 1. části a položku facility.
- Rozdělit, kdo co prezentuje (15 minut).
- Ověřit termín a místo odevzdání písemného dokumentu v MS Teams.
- Před odevzdáním otevřít Excely a dokument v MS Office a zkontrolovat vzhled.

## Zdroje

- Cushman & Wakefield, Student Housing 2026: https://www.cushmanwakefield.com/cs-cz/czech-republic/news/2026/09/student-housing-2026
- ČSÚ, Vysoké a vyšší odborné školy: https://csu.gov.cz/vysoke-a-vyssi-odborne-skoly
- ČSÚ, Školství v Jihomoravském kraji 2024/2025: https://csu.gov.cz/jhm/skolstvi-v-jihomoravskem-kraji-ve-skolnim-roce-20242025
- Echo24.cz, nejsilnější ročník uchazečů (data MŠMT): https://www.echo24.cz/a/HMRAT/zpravy-domaci-na-vysoke-skoly-dorazi-nejsilnejsi-rocnik-uchazecu-msmt-financovani
- Novinky.cz, průzkum STEM/MARK pro Residomo: https://www.novinky.cz/clanek/finance-spolubydleni-jako-prvni-krok-k-osamostatneni-milenialove-ho-vitaji-40289523
- ČNB, 2T repo sazba 4,00 % a diskontní sazba 3,00 % (stav 15. 11. 2026): https://www.cnb.cz
- Úplný seznam zdrojů je v písemném dokumentu.
