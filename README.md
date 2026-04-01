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
<img width="945" height="914" alt="{EAC7F1A4-9ABF-49FD-A97F-B745E4EB5659}" src="https://github.com/user-attachments/assets/b81aad3c-e68e-4b24-86e0-a10cd21a54d7" />

**Kuidas luua ja kasutada diagramme lehe**
<img width="944" height="902" alt="{52FEC4CF-3989-4AFD-91B9-F2AB011A45D1}" src="https://github.com/user-attachments/assets/1143b048-963f-4ab7-8d94-4e1689115513" />
 **Kuidas lisada valemiga arvutusväli lehe**

**Navigatsioonimenüü**
<img width="940" height="184" alt="{6EB9E55E-5BC7-41D7-BCC2-09ED7B04BAC5}" src="https://github.com/user-attachments/assets/9b834399-396b-4e03-9ba2-769b9d3f45ad" />

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
