# Řízení IT projektů (INFON3, ZS 26/27) – podklady

Hlavní zdroj pravdy pro práci na předmětu a semestrálním projektu. Vychází z Moodle kurzu
<https://moodle.czu.cz/course/view.php?id=14322> a materiálů ze cvičení (stav k 28. 10. 2026).

## Kurz

| | |
|---|---|
| Garant, přednášející | Ing. Petra Pavlíčková, Ph.D. – pavlickovap@pef.czu.cz |
| Cvičící | Ing. Matěj Brnka – brnka@pef.czu.cz |
| Komunikace | kanál v MS Teams |
| Odevzdávání | odevzdávárny v Moodlu (dílčí části, stačí jeden člen týmu); prezentaci 1. části podle slajdu 2. cvičení také „nahrát do MS Teams“; finální dokument do složky v MS Teams. Název týmu/kanálu v Teams Moodle neuvádí – spravuje ho cvičící |

## Podmínky zápočtu a zkoušky

- **Zápočet:** min. 18 bodů z 30 za semestrální projekt + docházka na cvičení (max. 1 absence).
- **Zkouška – písemná část:** test v Moodlu v PC učebně, nutné min. 60 %. Při nesplnění se opakuje test.
- **Zkouška – ústní část:** prezenčně, látka z přednášek i cvičení. Při nesložení se opakuje i písemná část.

## Termíny

Stav Moodlu k 12. 11. 2026 (termíny už jsou aktualizované; 3. část jako samostatná odevzdávárna zmizela):

| Odevzdání | Lichý týden | Sudý týden |
|---|---|---|
| 1. část | 27. 10. (st) / 29. 10. (pá) | 3. 11. (st) / 5. 11. (pá) |
| 2. část | 24. 11. 2026 23:59 (st) / 26. 11. (pá) | 1. 12. 2026 23:59 (st) / 3. 12. (pá) |

Chodíme pravděpodobně v lichém týdnu na středeční seminář (11. 11. vyučující řekl „za 14 dní“) → 2. část do **24. 11. 2026 23:59**.

## Témata cvičení

1. Úvod do předmětu, sestavení týmů, zadání semestrálního projektu, Lean Canvas
2. Harmonogram, persony, Lean Canvas
3. **Prezentace 1. části** projektu
4. Business Case, rizika, Use Case, User Journey a wireframes
5. Agilní hra
6. **Prezentace 2. části** projektu

Popisky 5. a 6. cvičení jsou v Moodlu prohozené; platí pořadí ze slajdů 1. cvičení (výše).

## Semestrální projekt

### Téma

- Musí to být **software** (aplikace, web).
- Ideálně z vlastní životní zkušenosti – studium a život studenta, zaměstnání, stáž, cestování, bydlení apod.
- Díra na trhu a inovace, jasná cílová skupina.
- Hlavní zdroj financování od více uživatelů (ne reklama, ne business angels).

### Bodování (max. 30)

| Část | Body |
|---|---|
| 1. prezentace | max. 10 |
| 2. prezentace | max. 10 |
| Písemný dokument | max. 10 |

### 1. část – prezentace a odevzdání

Odevzdává se finální verze prezentace, případně přílohy (např. soubor MS Project). Stačí odevzdání
jedním členem týmu.

1. **Lean Canvas** – bloky podle šablony z Moodlu:
   - Problém; Alternativy (konkurence a jejich řešení)
   - Řešení (co aplikace nabízí pro každý problém zvlášť)
   - Jedinečnost řešení / hodnota pro zákazníka
   - Nefér výhoda (co máme navíc, proč zaplatí právě nám)
   - Zákazníci; První vlaštovky (koho oslovíme nejdříve)
   - Jak měřit úspěch (metriky)
   - Distribuční kanály
   - Struktura nákladů; Struktura příjmů
2. **Architektura aplikace** – high-level schéma.
3. **Harmonogram včetně ohodnocení a sazeb**
   - identifikace hlavních činností, ocenění zdrojů a pracnosti => náklady projektu
   - Ganttův diagram s vazbami mezi činnostmi, ideálně v MS Project – doporučení, ne povinnost
     (slajd uvádí „nejlépe v MS Project“, odevzdávárna „případně přílohy“); alternativa např. Excel
     nebo ProjectLibre
   - typy vazeb: Finish–Start, Start–Start, Finish–Finish, Start–Finish
4. **Persony** (cca 3)
   - jméno, příjmení, fotografie, demografie (věk, bydliště, zaměstnání), zdravotní stav a omezení
   - ekonomický status, životní úroveň, vlastnosti, motivace, zájmy
   - jak, kdy a proč bude aplikaci používat; proč je naším zákazníkem
   - osy charakteru: laik × odborník, konzervativní × moderní, kvalita × kvantita, šetří × utrácí, smysl pro humor
   - typy: zákazník, potenciální zákazník, anti-zákazník

### 2. část – prezentace a odevzdání

Moodle ji rozděluje do dvou odevzdávárn (2. a 3. část) se stejným termínem.

1. **Business Case** (MS Excel, horizont 5 let)
   - náklady po měsících/letech: personální, infrastruktura (SW, HW, licence, cloud), facility, marketing; vývoj i provoz v dalších letech; vychází z harmonogramu
   - model růstu uživatelů – **ne exponenciála**, nepravidelný růst, ideálně podložený statistikou
   - model příjmů podle počtu uživatelů (ne reklama, ne business angels)
   - zisk a návratnost v optimistickém a pesimistickém scénáři; do černých čísel mezi 2. a 3. rokem
   - **NPV** za 5 let, diskontní sazba podle ČNB
2. **Rizika** (MS Excel)
   - formulace: „když <příčina> spouští <událost>, tak <efekt>“
   - u rizika: popis, pravděpodobnost, dopad, vlastník, mitigace, závažnost (pravděpodobnost × dopad), strategie
   - škály např. 1–3 nebo 1–10; graf rizik dle Paretova pravidla (řešit 20 % nejkritičtějších)
   - kritická rizika důsledně kontrolovat, žlutá mají plán, zelená a modrá se neřeší
   - strategie: akceptovat, přenést, vyhnout se, snížit
3. **Use Case diagram** (UML) – aktéři, jednotlivé funkcionality, vazby include a extend
4. **Use Case scénáře – alespoň 2**, na funkcionality z User Journey, **ne přihlášení, registrace apod.**
   - tabulka Krok | Role (Systém / Uživatel) | Popis + alternativní scénáře (4a, …)
   - ze scénáře musí být jasné, jak systém naprogramovat
5. **Wireframes – alespoň 2 obrazovky** na User Journey, **ne přihlášení, registrace apod.**
   - User Journey = rozhodovací momenty, které vedou k hodnotě, za kterou zákazník platí
   - kroky jsou Use Cases z diagramu; obrazovky musí vysvětlovat, co má uživatel udělat
   - v projektu stačí 1 User Journey

### Písemný dokument

Spojení a popis všech částí projektu ve strukturovaném textovém dokumentu. Kompletní obsah podle
souboru „Zadání semestrálních projektů“:

- Idea – inovační myšlenka, základní info
- Business model – Business Model Canvas, Lean Canvas
- Harmonogram – Gantt s vazbami
- Business Case (5 let) – náklady, výnosy (optimistický a pesimistický odhad), NPV
- Matice rizik – seznam, výskyt, dopad, kritičnost, mitigace
- Architektura – high-level schéma
- Persony – cca 3
- UC diagram – UCs, vazby, aktéři (UML)
- 2 UC scénáře
- Wireframes konkrétního procesu

### Šablona „Business Case – inspirace“

Struktura vzorového Excelu (aplikace pro studenty v Praze, 121 900 studentů jako trh):

- náklady: Storage, Database, Server (Azure, kurz 22 CZK/USD), HR, Marketing; součty za Y-1 až Y-5
- HR: obsazení rolí po měsících (Developer, Analysis, Tester, Support, Marketing, PM, CEO) × měsíční mzdy
- příjmy: 3 balíčky (249 / 349 / 499 CZK) s podílem uživatelů 20 / 48 / 12 %, podíl na trhu roste 7 → 29 %
- pesimistický scénář = optimistický × 0,83
- NPV s diskontní sazbou 7 %

Vzorec NPV v šabloně je chybný (sčítá nediskontovaný rozdíl příjmů a nákladů s diskontovanými zisky
a `H11/1+L22` kvůli prioritě operátorů nediskontuje). Pro vlastní výpočet použít standardní
NPV = Σ CF_t / (1 + r)^t, např. Excel `=NPV(r; CF1:CF5)`.

## Agilní hra (5. cvičení)

- Tým 4–6 členů. Za tým se vyplní jeden e-mail do tabulky pro přístup do **Jira** (SharePoint odkaz v Moodlu).
- Předpoklad: znalost agilního řízení, Scrum a Kanban boardu; prostudované „Zadání hry“; 90 minut.
- **Domácí příprava:** v souboru `Analýza rizik studenti.xlsx` vyplnit sloupec **Postoj k riziku**
  (Akceptovat / Snížit / Vyhnout se). Rozpočet na ošetření rizik je 195 000 Kč.

| # | Riziko | P | D | Význam | Cena ošetření | Omezení při akceptaci |
|---|---|---|---|---|---|---|
| 1 | Vypršení platnosti licencí | 2 | 3 | 6 | 50 000 | sprint zkrácen na polovinu |
| 2 | Zastaralý HW pracovních stanic | 3 | 5 | 15 | 85 000 | polovina sprintu, druhá polovina jen na změnu priorit |
| 3 | Neakceptování grafických návrhů | 3 | 5 | 15 | 55 000 | celý sprint i review nebudou grafické návrhy akceptovány |
| 4 | Špatná zpětná vazba od zákazníka | 4 | 5 | 20 | 60 000 | zákazník nekomunikuje, dotazy jen ve sprint planningu |
| 5 | Onemocnění člena týmu | 3 | 4 | 12 | 40 000 | jeden losem vybraný člen nepracuje |
| 6 | Výpadek prototypovacího nástroje | 2 | 5 | 10 | 85 000 | jen papírové návrhy, které nelze akceptovat |
| 7 | Výpadek serveru | 3 | 3 | 9 | 40 000 | nelze nahlížet do zadání |

Ošetření všech rizik stojí 415 000 Kč (pravidla uvádějí „cca 350 tisíc“).

- **Průběh:** předprojektová fáze (10 min, prioritizace backlogu ve Figmě, konečnou prioritu určuje PO)
  → opakovaně: tah kartičky Událost (spouští riziko) → Sprint planning (2–3 min) → Sprint (cca 8 min)
  → Sprint review (2–3 min, akceptace zákazníkem).
- Nástroje: Jira (Kanban board), Figma / draw.io.
- Konec po 5. sprintu nebo dříve, pokud backlog neobsahuje žádné Critical (A) a High (B) požadavky.

## Materiály v Moodlu

| Materiál | Odkaz |
|---|---|
| 1. cvičení (slajdy, zadání projektu) | <https://moodle.czu.cz/mod/resource/view.php?id=913459> |
| Vytvoření týmů (SharePoint) | <https://moodle.czu.cz/mod/url/view.php?id=913460> |
| 2. cvičení (harmonogram, persony, Lean Canvas) | <https://moodle.czu.cz/mod/resource/view.php?id=913467> |
| Lean Canvas – šablona (XLSX) | <https://moodle.czu.cz/mod/resource/view.php?id=913468> |
| Business Model Canvas | <https://moodle.czu.cz/mod/url/view.php?id=913469> |
| Řízení rizik (přednáška) | <https://moodle.czu.cz/mod/resource/view.php?id=913471> |
| 4. cvičení (Business Case, rizika, UC, User Journey) | <https://moodle.czu.cz/mod/resource/view.php?id=913481> |
| Business Case – inspirace (XLSX) | <https://moodle.czu.cz/mod/resource/view.php?id=913482> |
| Zadání hry | <https://moodle.czu.cz/mod/resource/view.php?id=913495> |
| Matice rizik pro hru (XLSX) | <https://moodle.czu.cz/mod/resource/view.php?id=913496> |
| User Stories pro hru (ZIP) | <https://moodle.czu.cz/mod/resource/view.php?id=913497> |
| Pravidla hry | <https://moodle.czu.cz/mod/resource/view.php?id=913498> |
| Zadání semestrálních projektů (DOCX) | <https://moodle.czu.cz/mod/resource/view.php?id=913503> |
| Odevzdání 1. části – lichý / sudý týden | <https://moodle.czu.cz/mod/assign/view.php?id=913476> / <https://moodle.czu.cz/mod/assign/view.php?id=913477> |
| Odevzdání 2. části – lichý / sudý týden | <https://moodle.czu.cz/mod/assign/view.php?id=913487> / <https://moodle.czu.cz/mod/assign/view.php?id=913488> |
| Odevzdání 3. části – lichý / sudý týden | <https://moodle.czu.cz/mod/assign/view.php?id=913500> / <https://moodle.czu.cz/mod/assign/view.php?id=913501> |

## Stav našeho projektu

| | |
|---|---|
| Tým | Jonáš Podzemský, Jan Brychnáč, Matyáš Kloubek, Miloslav Neuman, Alexander Vedernikov |
| Týden cvičení (lichý / sudý) | — |
| Téma projektu | Spolubyt (pracovní název) – matching spolubydlících + správa společné domácnosti |
| Hotové části | 1. část – obsah v [cast-1.md](cast-1.md), prezentace `spolubyt-cast-1.pptx`, Gantt `spolubyt-harmonogram.xlsx`; připraveno k odevzdání |
| 2. část | obsah v [cast-2.md](cast-2.md), prezentace `spolubyt-cast-2.pptx`, `spolubyt-business-case.xlsx`, `spolubyt-rizika.xlsx`, `spolubyt-use-case.drawio`; k revizi týmem |
| Diagramy | UML diagramy (Use Case, ERD…) černobíle podle normy v draw.io; vysvětlující schémata v prezentaci mohou být v barvách |
| Archiv | `puvodni/` – první verze 1. části; `new/` – revize od kolegy před opravou přetížení FE |
| Postup | obsah nejdřív v MD v této složce, PPTX a XLSX se z něj generují |
| Nástroj na harmonogram | Excel (MS Project není k dispozici) |

## Otevřené otázky

- Potvrdit lichý týden / středu (termín 2. části 24. 11.).
- Kam se odevzdává finální písemný dokument – složka v MS Teams, nebo Moodle.
- Obsah SharePoint tabulek (týmy, e-maily pro Jira) – vyžadují přihlášení Microsoft účtem.
- Text souboru „Zadání hry“ se nepodařilo extrahovat (pravděpodobně obrázky nebo textová pole).
