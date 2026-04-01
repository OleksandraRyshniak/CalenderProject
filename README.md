# :card_index_dividers: MSProject juhendid

> Veebisait, kus selgitatakse samm-sammult, kuidas kasutada **Microsoft Project / ProjectLibre** peamisi funktsioone: kalendrite loomist, arvutusvälja lisamist ja diagrammide kasutamist.

---

## :books: Sisukord

- [Sait](#globe_with_meridians-sait)
- [Mida tehti](#wrench-mida-tehti)
- [Muudetud failid](#file_folder-muudetud-failid)
- [Lehed](#page_facing_up-lehed)
- [Sisu ülevaade](#clipboard-sisu-ülevaade)
- [Tehtud tööd](#white_check_mark-tehtud-tööd)
- [Tehnoloogiad](#hammer_and_wrench-tehnoloogiad)
- [Autor](#bust_in_silhouette-autor)

---

## :globe_with_meridians: Sait

<a href="https://oleksandraryshniak.github.io/CalenderProject/index.html">Ava veebileht</a>

---

## :wrench: Mida tehti

Selles projektis loodi õpetlik veebileht **Microsoft Project / ProjectLibre** kasutamiseks. Lisati kolm juhendit:

- Kohandatud **tööajakalendri** loomine (`index.html`)
- **Arvutusvälja** lisamine valemiga (`valem.html`)
- **Diagrammide** (Cash Flow, Gantt) kasutamine (`diagram.html`)

---

## :file_folder: Muudetud failid

| Fail | Muudatus |
|------|----------|
| `index.html` | Kalendri loomise juhend — 7 sammu, pildid |
| `valem.html` | Arvutusvälja juhend — Custom Fields, valem `[Cost]*[% Complete]/100` |
| `diagram.html` | Diagrammide juhend — Cash Flow aruanne, tabel kuludega |
| `style.css` | Kujundus ja paigutus |
| `README.md` | :new: Loodud |

---

## :page_facing_up: Lehed

| Leht | Fail | Kirjeldus |
|------|------|-----------|
| :calendar: Kalender | `index.html` | Kuidas luua kohandatud tööajakalender |
| :1234: Arvutusväli | `valem.html` | Kuidas lisada valemiga arvutusväli |
| :bar_chart: Diagrammid | `diagram.html` | Kuidas luua Cash Flow aruanne |

**Kuidas luua kohandatud tööajakalender lehe**
<img width="810" height="933" alt="{6C9B7506-D3D0-4778-91F9-BBEB3D65EAA5}" src="https://github.com/user-attachments/assets/53f0888e-63a0-48e7-9868-67d46e4ed83e" />

**Kuidas luua ja kasutada diagramme lehe**
<img width="820" height="947" alt="{41EC118E-4F60-4B2C-815F-72C8C21A3EB8}" src="https://github.com/user-attachments/assets/62f42148-e660-4998-845c-ef00115da717" />

**Kuidas lisada valemiga arvutusväli lehe**
<img width="796" height="921" alt="{B8BCF6B2-3339-46FC-B842-842665F11DE7}" src="https://github.com/user-attachments/assets/c4c8be46-6b74-4d16-a897-57996bd48da8" />

**Navigatsioonimenüü**
<img width="1010" height="188" alt="{7D207E00-E3DE-40E6-BF00-7F800CE1DD9C}" src="https://github.com/user-attachments/assets/f3fd833d-1777-4b73-94b7-638c6be0b788" />


---

## :clipboard: Sisu ülevaade

### :calendar: Kalender (index.html)

Juhend selgitab 7 sammuga, kuidas:

1. Avada **Change Working Time** aken
2. Vaadata olemasolevat kalendrit
3. Luua uus baasikalender (nt `newCalendar`)
4. Lisada erand konkreetsele kuupäevale
5. Seadistada kohandatud tööajad väljadega **From / To**
6. Vaadata tulemust kalendris
7. Määrata kalender ülesandele läbi **Task Information → Advanced**

### :1234: Arvutusväli (valem.html)

Juhend selgitab 4 sammuga, kuidas:

1. Avada **Custom Fields** aken menüüst **Project**
2. Valida välja tüübiks **Number** ja anda nimi (nt `Cost Complete "€"`)
3. Lisada valem: `[Cost]*[% Complete]/100`
4. Vaadata tulemust Gantti tabelis uues veerus

### :bar_chart: Diagrammid (diagram.html)

Juhend selgitab 4 sammuga, kuidas:

1. Avada vahekaart **Report**
2. Valida **Costs → Cash Flow**
3. Lugeda Cash Flow aruannet (Actual Cost, Baseline Cost, Remaining Cost, Cost Variance)
4. Vaadata kulude tabelit aruande allosas

---

## :white_check_mark: Tehtud tööd

- [x] `index.html` loodud: kalendri loomise juhend 7 sammuga
- [x] `valem.html` loodud: arvutusvälja juhend valemiga
- [x] `diagram.html` loodud: Cash Flow diagrammi juhend
- [x] Navigatsioonimenüü lisatud kõigile lehtedele
- [x] `images/` kaust loodud ja pildid üles laaditud
- [x] `style.css` loodud
- [x] GitHub Pages seadistatud
- [x] `README.md` loodud

---


> [!NOTE]
> Kõik kolm lehte kasutavad ühist `style.css` faili kujunduse jaoks.

> [!TIP]
> GitHub Pages uueneb automaatselt iga kord, kui teed commit'i harusse `projectLibre`.

---

## :hammer_and_wrench: Tehnoloogiad

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat&logo=github&logoColor=white)

- **HTML5** — lehtede struktuur
- **CSS3** — kujundus ja paigutus (`style.css`)
- **GitHub Pages** — automaatne avaldamine harust `projectLibre`

---

## :bust_in_silhouette: Autor

**Oleksandra Ryshniak**
© 2026 · Tallinn :estonia:

---

[^1]: Microsoft Project ja ProjectLibre on projektihalduse tööriistad Gantt-diagrammide ja ressursside haldamiseks.
[^2]: GitHub Pages võimaldab avaldada staatilisi veebilehti otse repositooriumist tasuta.
