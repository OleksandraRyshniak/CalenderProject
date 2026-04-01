# :card_index_dividers: ProjectLibre juhendid

> Veebisait, kus selgitatakse samm-sammult, kuidas kasutada **ProjectLibre** peamisi funktsioone: isiklike töökalendrite loomist ja erinevate diagrammide kasutamist.

---

## :books: Sisukord

- [Sait](#globe_with_meridians-sait)
- [Mida tehti](#wrench-mida-tehti)
- [Muudetud failid](#file_folder-muudetud-failid)
- [Lehed](#page_facing_up-lehed)
- [Sisu ülevaade](#clipboard-sisu-ülevaade)
- [Tehtud tööd](#white_check_mark-tehtud-tööd)
- [Koodinäited](#computer-koodinäited)
- [Tehnoloogiad](#hammer_and_wrench-tehnoloogiad)
- [Autor](#bust_in_silhouette-autor)

---

## :globe_with_meridians: Sait

<a href="https://oleksandraryshniak.github.io/CalenderProject/index.html">Ava veebileht</a>

---

## :wrench: Mida tehti

Selles projektis loodi õpetlik veebileht **ProjectLibre** kasutamiseks. Lisati kaks juhendit:

- Kohandatud **tööajakalendri** loomine
- **Diagrammide** (Gantt, võrgudiagramm) kasutamine

Eemaldati fail `valem.html` ning uuendati navigatsioonimenüüd kõigil lehtedel.

---

## :file_folder: Muudetud failid

| Fail | Muudatus |
|------|----------|
| `index.html` | Uuendatud sisu, lisatud pildid, parandatud tekstid |
| `diagram.html` | Kirjutatud ümber — lisatud Gantt ja võrgudiagrammi juhend |
| `style.css` | Uuendatud kujundus pastelltoonides |
| `valem.html` | :x: Eemaldatud projektist |
| `README.md` | :new: Loodud |

---

## :page_facing_up: Lehed

| Leht | Fail | Kirjeldus |
|------|------|-----------|
| :calendar: Kalender | `index.html` | Kuidas luua kohandatud tööajakalender ProjectLibre'is |
| :bar_chart: Diagrammid | `diagram.html` | Kuidas luua ja kasutada diagramme ProjectLibre'is |

**Kuidas luua kohandatud tööajakalender ProjectLibre'is lehe**
<img width="945" height="914" alt="{EAC7F1A4-9ABF-49FD-A97F-B745E4EB5659}" src="https://github.com/user-attachments/assets/b81aad3c-e68e-4b24-86e0-a10cd21a54d7" />

**Kuidas luua ja kasutada diagramme ProjectLibre'is lehe**
<img width="944" height="902" alt="{52FEC4CF-3989-4AFD-91B9-F2AB011A45D1}" src="https://github.com/user-attachments/assets/1143b048-963f-4ab7-8d94-4e1689115513" />

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

### :bar_chart: Diagrammid (diagram.html)

Juhend tutvustab kahte peamist vaadet:

1. **Võrgudiagramm (Network)** — ülesannete sõltuvused ja järjestus graafiliselt
2. **Gantt ressurssidega** — ressursid ja koormusprotsendid ajajoonel (27.apr–18.mai 2026)

---

## :white_check_mark: Tehtud tööd

- [x] Loodud haru `projectLibre`
- [x] `index.html` uuendatud: uus sisu ja pildid
- [x] `diagram.html` ümber kirjutatud: Gantt ja võrgudiagrammi juhend
- [x] Navigatsioonimenüü uuendatud kõigil lehtedel
- [x] `valem.html` eemaldatud projektist
- [x] `images/` kaust loodud ja pildid üles laaditud
- [x] `style.css` uuendatud pastellkujundusega
- [x] GitHub Pages seadistatud harust `projectLibre`
- [x] Issues loodud ja Kanban tahvlil hallataud
- [x] `README.md` loodud

---

> [!NOTE]
> Kõik muudatused tehti harus **projectLibre**, mitte `main` harus.

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

[^1]: ProjectLibre on tasuta avatud lähtekoodiga projektihalduse tarkvara — alternatiiv Microsoft Project'ile.
[^2]: GitHub Pages võimaldab avaldada staatilisi veebilehti otse repositooriumist.
