# „DataCo“ tiekimo grandinės apžvalga (Power BI)

<img width="1407" height="787" alt="image" src="https://github.com/user-attachments/assets/5fc9cb94-1335-4657-a143-4912939f50eb" />

## Projekto Aprašymas
Tai yra **„Power BI“ projektas**, kuriame analizuojami globalios įmonės „DataCo“ tiekimo grandinės duomenys. Projekto tikslas – praktiškai pritaikyti „Power BI“ vizualizavimo galimybes ir transformuoti turimus duomenis į interaktyvų įrankį, skirtą pardavimų, produktų, logistikos ir geografinių rodiklių apžvalgai.

### Pagrindiniai duomenų rinkinio rodikliai:
* **Duomenų laikotarpis:** 2015–2018 m.
* **Įrašų skaičius:** 180 519 vnt.
* **Kintamųjų skaičius:** 53 kintamieji
* **Unikalių užsakymų skaičius:** 65 752 vnt.
* **Nagrinėjamų šalių skaičius:** 164 šalys

---

## Ataskaitos puslapių apžvalga

### 0. Titulinis puslapis (turinys)
<img width="800" height="446" alt="Navigacija" src="https://github.com/user-attachments/assets/9cef4f70-528e-40ed-8576-d8a23ec475d9" />

* **Panaudoti „Power BI“ įgūdžiai:** naudojant puslapių nuorodas (mygtukus) sukurta navigacija į kiekvieną ataskaitos puslapį, pateikti duomenų šaltinio svarbiausi duomenys panaudojant korteles.
* **Vizualizacijų reikšmė:** 4 dideli navigaciniai blokai leidžia vartotojui patogiai pereiti į atskirus ataskaitos puslapius.

---

### 1 Puslapis – Pardavimų apžvalga
<img width="800" height="445" alt="Pardavimų apžvalga" src="https://github.com/user-attachments/assets/e667079d-2a4b-48c7-92c4-6394b47b9818" />

* **Panaudoti „Power BI“ įgūdžiai:**
  * KPI kortelių (*KPI Cards*) vizualizavimas ir formatavimas.
  * Linijiniai grafikai su dviem duomenų eilutėmis (*Pajamos ir Pelnas*) laiko eilutėje.
  * Žiedinė diagrama su etikečių formatavimu.
  * Horizontalios juostinės diagramos su duomenų rūšiavimo nustatymais.
  * Spalvų paletės parinkimas ir bendras dashboardo išdėstymas (*Layout*).
* **Ką parodo vizualizacijos:**
  * **KPI kortelės:** Bendros pajamos ($36,78 mln.), Bendras pelnas ($3,97 mln.), Parduotų prekių kiekis (384 tūkst. vnt.), Vidutinė pelno marža per užsakymą (12,06%).
  * **Pajamų ir pelno dydis per mėnesį:** Pajamų ir pelno dinamika laike.
  * **Pajamos pagal rinką:** Rinkų pasiskirstymas, kur lyderiauja *Europe* ($10,87 mln.).
  * **Pajamos pagal 8 pelningiausias kategorijas:** Išryškina „Fishing“ (žvejybos) ir „Cleats“ (sportinių batelių) prekių dominavimą.
  * **Pajamos pagal pristatymo būdą:** Parodo, kad „Standard Class“ generuoja didžiausią apyvartą.
* **Įžvalgos:**
  * Linijiniame grafike matomas staigus pajamų kritimas 2017 m. pabaigoje – 2018 m. pradžioje. Tai signalas ištirti, ar tai reali verslo krizė, ar duomenų trūkumo klaida.
  * Kadangi Europa ir Lotynų Amerika sugeneruoja virš 57% pajamų, įmonė gali prognozuoti, kad investicijos į rinkodarą šiuose regionuose atneš didžiausią grąžą.

---

### 2 Puslapis – Parduodamų prekių analizė
<img width="800" height="443" alt="Prekių analizė" src="https://github.com/user-attachments/assets/d4144a73-bf59-4c0b-ad18-1179bcc2d6dd" />

* **Panaudoti „Power BI“ įgūdžiai:**
  * Taškinio grafiko (*Scatter chart*) kūrimas ir tendencijų linijos (*Trend line*) įterpimas.
  * Dinaminių filtrų (*Slicers*) kūrimas ir jų integravimas į kitas vizualizacijas.
  * Lentelės formatavimas naudojant integruotas duomenų juostas (*Data bars*).
* **Ką parodo vizualizacijos:**
  * **KPI kortelės:** Vidutinė kaina ($141,23), Nuolaidos dydis ($20,66), Kiekis krepšelyje (2,13 vnt.), Pelnas per vienetą ($21,97).
  * **Prekių kainų įtaka pelno maržai:** Parodo ryšį tarp prekės kainos ir jos sugeneruojamos maržos.
  * **Užsakymų skaičius per mėnesį:** Paklausos tendencija laike.
  * **TOP 5 prekės pagal pelno maržą ir 5 pelningiausi produktai:** Išskiria efektyviausias prekes.
* **Įžvalgos:**
  * Užsakymų skaičiaus šuolis periodo pabaigoje rodo išaugusią pigesnių prekių paklausą.
  * Pasitaiko prekių, kurių pardavimai buvo nuostolingi įmonei (pvz. elipsinio treniruoklio "sole e25 elliptical" pardavimai).

---

### 3 Puslapis – Pristatymo ir užsakymų analizė (Delivery & Order Analysis)
<img width="800" height="445" alt="Pristatymai ir užsakymai" src="https://github.com/user-attachments/assets/76232835-bbc0-4d8b-b79a-654cdfec5e23" />


* **Panaudoti „Power BI“ įgūdžiai:**
  * Sudėtinės stulpelinės diagramos (*Stacked bar*) kūrimas.
  * Žiedinė diagrama su procentų ir absoliučių reikšmių etikečių derinimu.
  * Dviejų eilučių linijinis grafikas problematiškų užsakymų stebėjimui laike.
  * KPI kortelių naudojimas pristatymo laiko palyginimui (*Numatytas ir Faktinis laikas*).
* **Ką parodo vizualizacijos:**
  * **KPI kortelės:** Užsakymų skaičius (65 752 vnt.), Atšauktų užsakymų skaičius (1 367 vnt.), Numatytas (2,93 d.) ir Faktinis (3,50 d.) pristatymo laikas.
  * **Užsakymų skaičius pagal būdą ir statusą:** Parodoma, kuriuo pristatymo būdų dažniausiai pristatomos prekės, stulpelio segmentai yra nuspalvinti pagal užsakymo statusą - pagal juos galima daryti išvadas, stebėjimą, kuriuose pristatymo būduose tiekimas stringa.
  * **Užsakymų pasiskirstymas pagal statusą:** Atskleidžia, kad net 45,02% užsakymų yra „Vykdoma“ (Pending) būsenoje.
  * **Atšauktų ir įtariamų sukčiavimų tendencija:** Seka rizikos faktorius laiko eilutėje.
* **Įžvalgos**
  * Faktinis pristatymo laikas (3,50 d.) sistemingai viršija numatytąjį (2,93 d.). Tai rodo logistikos sutrikimus.

---

### 4 Puslapis – Geografinė analizė
<img width="800" height="447" alt="Geografinė analizė" src="https://github.com/user-attachments/assets/33dcf321-e025-480f-9621-4f0e1a10f151" />

* **Panaudoti „Power BI“ įgūdžiai:**
  * *Bing Maps* žemėlapio integravimas, valdant burbulų dydžius pagal apyvartos reikšmes.
  * Dinaminės kortelės, rodančios geriausiai pasirodantį regioną pagal parinktą filtrą, sukūrimas.
  * Kelių filtrų (*Slicers*) sinchronizavimas tarpusavyje.
* **Ką parodo vizualizacijos:**
  * **KPI kortelės:** Šalių skaičius (164), Miestų skaičius (3 597) ir Pelningiausias regionas (*Western Europe* su $625,446.08 pelno).
  * **5 pelningiausi miestai:** Išskiria pelno lyderius (*Santo Domingo*, *New York City* ir t.t.).
  * **Pelnas pagal rinką:** Geografinis pelno pasiskirstymas procentais (Europe – 29,48%).
  * **Didžiausios apyvartos šalys (Žemėlapis):** Vizualiai identifikuoja globalius prekybos taškus.
* **Įžvalgos:**
  * Nors pajamų atžvilgiu skirtumas tarp Europos ir Lotynų Amerikos rinkų yra nedidelis, pelno atžvilgiu Europa išlaiko stipresnę poziciją. Įmonė gali prognozuoti didesnę investicijų grąžą plėsdama infrastruktūrą būtent vakarų Europos miestuose.

---

## Naudoti įrankiai
* **Duomenų vizualizacija:** Power BI Desktop
* **Duomenų šaltinis:** Kaggle (DataCo Supply Chain Dataset) https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

## Kaip peržiūrėti projektą?
1. Atsisiųskite `.pbix` failą iš šios repozitorijos.
2. Atsidarykite jį naudodami [Power BI Desktop](https://powerbi.microsoft.com/).
3. Naudokite titulinio puslapio navigacinius mygtukus bei filtrus puslapių viršuje interaktyviam duomenų tyrinėjimui.
