# „DataCo“ Tiekimo Grandinės Duomenų Rinkinio Analizė (Power BI)

<img width="1415" height="795" alt="image" src="https://github.com/user-attachments/assets/0c61937d-c339-429b-8cb1-0ac900d7c90d" />

## 📌 Projekto Apžvalga
Šis „Power BI“ projektas skirtas **„DataCo“ tiekimo grandinės (2015–2018 m.)** pardavimų, produktų, pristatymo procesų ir geografinių rodiklių analizei. Projekto tikslas – transformuoti didelį kiekį struktūrizuotų duomenų į interaktyvias, verslo sprendimams pritaikytas vizualizacijas, padedančias optimizuoti logistiką, padidinti pelno maržą ir identifikuoti pelningiausius rinkos segmentus.

### 📊 Pagrindiniai duomenų rinkinio rodikliai:
* **Įrašų skaičius:** 180,519 tūkst.
* **Kintamųjų skaičius:** 53 kintamieji
* **Nagrinėjamų šalių skaičius:** 164 šalys
* **Unikalių užsakymų skaičius:** 65,752 tūkst.

---

## 🖥️ Ataskaitos Puslapių Analizė ir Techninė Dokumentacija

### 0. Titulinis puslapis / Turinys (Main Dashboard Navigation)
<img width="800" height="446" alt="Navigacija" src="https://github.com/user-attachments/assets/9cef4f70-528e-40ed-8576-d8a23ec475d9" />


1. **Parodyti „Power BI“ įgūdžiai:**
   * Profesionalaus, vartotojui patogaus dizaino (UI/UX) kūrimas.
   * Navigacijos struktūros planavimas naudojant puslapių nuorodas (Page Navigation).
   * Aukšto lygio KPI kortelių (*KPI Cards*) panaudojimas bendram duomenų mastui įvertinti.
2. **Bendros įžvalgos / Prognozės:**
   * Matomas milžiniškas operacijų mastas (virš 180 tūkst. įrašų), apimantis globalią rinką (164 šalys). Tai indikuoja poreikį segmentuoti analizę pagal regionus ir produktų grupes, kad būtų išvengta duomenų triukšmo.
3. **Ką parodo vizualizacijos:**
   * **Viršutinis KPI blokas:** Parodo bendrą duomenų rinkinio apimtį, kintamuosius, geografinę aprėptį ir unikalių užsakymų skaičių.
   * **4 navigaciniai blokai:** Nukreipia vartotoją į specifines analitines sritis (Pardavimų apžvalga, Prekių analizė, Pristatymo ir užsakymų analizė, Geografinė analizė).

---

### 1. Pardavimų apžvalga (Sales Overview)
<img width="800" height="445" alt="Pardavimų apžvalga" src="https://github.com/user-attachments/assets/e667079d-2a4b-48c7-92c4-6394b47b9818" />


1. **Parodyti „Power BI“ įgūdžiai:**
   * Laiko eilučių analizė (*Time Series Analysis*) ir tendencijų vizualizavimas.
   * Skirtingų tipų vizualizacijų (linijinių grafika, žiedinių diagramų, stulpelinių grafikų) derinimas siekiant visapusiško konteksto.
   * Duomenų formatavimas (valiutos, procentai, tūkstančių/milijonų trumpiniai).
2. **Bendros įžvalgos / Prognozės:**
   * **Krizinis signalas:** Linijiniame grafike matomas staigus pajamų kritimas 2017 m. pabaigoje – 2018 m. pradžioje. Prognozuojama, kad nesiėmus skubių veiksmų (gali būti techninė duomenų trūkumo klaida arba reali verslo krizė), įmonė rizikuoja prarasti rinkos pozicijas.
   * Europos ir Lotynų Amerikos rinkos sugeneruoja daugiau nei 57% visų pajamų, todėl investicijos į rinkodarą šiose zonose atneš didžiausią grąžą.
3. **Ką parodo vizualizacijos:**
   * **KPI kortelės:** Bendros pajamos ($36,78 mln.), Bendras pelnas ($3,97 mln.), Parduotų prekių kiekis (384 tūkst. vnt.), Vidutinė pelno marža per užsakymą (12,06 %).
   * **Pajamų ir pelno dydis kiekvieną mėnesį (Linijinis grafikas):** Atvaizduoja pajamų ir pelno dinamiką laike. Pelno linija išlieka stabili, tačiau pajamos patiria drastišką nuosmukį periodo pabaigoje.
   * **Pajamos pagal rinką (Žiedinė diagrama / Donut Chart):** Parodo rinkų pasiskirstymą. Lyderiauja *Europe* ($10,87 mln.) ir *Latin America* ($10,28 mln.).
   * **Pajamos pagal 8 pelningiausias prekių kategorijas (Horiz. stulpelinis grafikas):** Išryškina „Fishing“ (žvejybos) ir „Cleats“ (sportinių batelių) kategorijų dominavimą.
   * **Pajamos pagal pristatymo būdą (Vertikalus stulpelinis grafikas):** Parodo, kad „Standard Class“ yra populiariausias ir daugiausiai pajamų generuojantis pristatymo metodas.

---

### 2. Parduodamų prekių analizė (Product Analysis)
<img width="800" height="443" alt="Prekių analizė" src="https://github.com/user-attachments/assets/d4144a73-bf59-4c0b-ad18-1179bcc2d6dd" />


1. **Parodyti „Power BI“ įgūdžiai:**
   * Sklaidos diagramų (*Scatter chart*) su tendencijos linijomis (*Trend lines*) kūrimas koreliacijų paieškai.
   * Pažangus lentelių formatavimas naudojant duomenų juostas (*Data bars*) vizualiam palyginimui.
   * Kategorijų filtravimo (*Slicers*) integracija ataskaitos viršuje.
2. **Bendros įžvalgos / Prognozės:**
   * **Neigiama koreliacija:** Sklaidos grafikas aiškiai parodo, kad didėjant vidutinei prekės kainai, pelno marža procentiškai linkusi mažėti (neigiama tendencijos linija). Prognozė: brangių prekių kainodara turi būti peržiūrėta, nes jos neuždirba proporcingai didesnės maržos.
   * Pardavimų kiekis periodo pabaigoje (2018 m.) šovė į viršų, kas rodo išaugusią paklausą, nors bendros pajamos (iš 1 puslapio) krito – tai reiškia, kad buvo parduota daug pigių prekių.
3. **Ką parodo vizualizacijos:**
   * **KPI kortelės:** Vidutinė prekės kaina ($141,23), Vidutinė nuolaida ($20,66), Vidutinis prekių kiekis krepšelyje (2,13 vnt.), Vidutinis pelnas per prekės vienetą ($21,97).
   * **Prekių kainų įtaka pelno maržai (Sklaidos diagrama):** Kiekvienas taškas yra produktas. Parodo ryšį tarp prekės kainos vidurkio ir maržos.
   * **Užsakymų skaičius fiksuotu laikotarpiu per mėnesį (Linijinis grafikas):** Atskleidžia užsakymų kiekio šuolį 2017 m. pabaigoje (virš 2,100 vnt.).
   * **TOP 5 prekės pagal pelno maržą (Horiz. stulpelinis grafikas):** Identifikuoja produktus-lyderius pagal efektyvumą (pvz., *Polar FT4 Heart Rate Monitor*).
   * **5 pelningiausi produktai (Matrica/Lentelė su Data Bars):** Detalizuoja top prekių pajamas, pelną ir kiekius. Matome, kad *Field & Stream Sportsman 16 Gun Fire Safe* atnešė net $43,65 tūkst. pelno.

---

### 3. Pristatymo ir užsakymų analizė (Delivery & Order Analysis)
<img width="800" height="445" alt="Pristatymai ir užsakymai" src="https://github.com/user-attachments/assets/f8f2f34a-f136-4f92-bd2c-a4b96d4f4a70" />


1. **Parodyti „Power BI“ įgūdžiai:**
   * Grupuotų ir sukauptų stulpelinių grafikų (*Stacked bar charts*) kūrimas kelių dimensijų analizei vienu metu.
   * Procentinio dalių pasiskirstymo vizualizavimas.
   * Anomalijų ir rizikų valdymas per atšauktų užsakymų tendencijų sekimą.
2. **Bendros įžvalgos / Prognozės:**
   * **Logistikos efektyvumas:** Faktinis pristatymo laikas (3,50 d.) vidutiniškai viršija numatytąjį (2,93 d.). Tai sisteminė problema. Jei logistikos procesai nebus optimizuoti, klientų pasitenkinimas kris, o atšauktų užsakymų skaičius (kuris dabar siekia 1,367 tūkst.) augs.
   * Beveik pusė užsakymų (45,02%) vis dar yra „Vykdoma“ būsenoje, kas gali signalizuoti apie „butelio kakliuką“ (*bottleneck*) sandėliuose ar logistikoje.
3. **Ką parodo vizualizacijos:**
   * **KPI kortelės:** Užsakymų skaičius (65,752 tūkst.), Atšauktų užsakymų skaičius (1,367 tūkst.), Numatytas vid. pristatymo laikas (2,93 d.), Faktinis vid. pristatymo laikas (3,50 d.).
   * **Užsakymų skaičius pagal pristatymo būdą ir statusą (Sukauptas stulpelinis grafikas):** Parodo, kad daugiausiai vėluojančių ar įtariamų sukčiavimu užsakymų yra „Standard Class“ pristatymo tipe.
   * **Užsakymų pasiskirstymas pagal statusą (Žiedinė diagrama):** Parodo procentinę užsakymų būseną (Vykdoma – 45,02%, Įvykdyta – 44,05% ir t.t.).
   * **Atšauktų ir peržiūrimų užsakymų tendencija (Laiko eilutės grafikas):** Žymi „Atšaukta“ ir „Įtariamas sukčiavimas“ dinamiką mėnesiais. Matomas reguliarus svyravimas (piksuoja rizikos bangas kas kelis mėnesius).

---

### 4. Geografinė analizė (Geographical Analysis)
<img width="800" height="442" alt="Geografinė analizė" src="https://github.com/user-attachments/assets/a27861f9-3459-462d-9bf3-305d5e12e41c" />


1. **Parodyti „Power BI“ įgūdžiai:**
   * GIS / Žemėlapių vizualizacijų (*Map integration*) integravimas naudojant burbulų dydžius (*Bubble size*) apyvartai atvaizduoti.
   * Geografinių hierarchijų valdymas (Regionas -> Šalis -> Miestas).
   * Geriausiai pasirodančių lokacijų identifikavimas per TOP filtrus.
2. **Bendros įžvalgos / Prognozės:**
   * Vakarų Europa (*Western Europe*) yra pats pelningiausias regionas įmonei ($625,446.08 pelno). Strateginė prognozė: tikslinga plėsti sandėlių tinklą būtent Vakarų Europoje, kad būtų sumažintas pristatymo laikas (išspręsta 3 puslapio problema) šiame kritiniame regione.
   * Didžiausia užsakymų koncentracija telkiasi pakrantėse ir didžiuosiuose megamiestuose (kaip matoma žemėlapyje).
3. **Ką parodo vizualizacijos:**
   * **KPI kortelės & Filtrai:** Šalių skaičius (164), Unikalių miestų skaičius (3,597 tūkst.), Pelningiausio regiono kortelė (*Western Europe*).
   * **5 pelningiausi miestai (Horiz. stulpelinis grafikas):** Parodo miestus, generuojančius didžiausią grynąjį pelną: lyderis – *Santo Domingo*, toliau seka *New York City*, *Tegucigalpa*, *Los Angeles*, *Managua*.
   * **Pelnas pagal rinką (Žiedinė diagrama):** Geografinis pelno pasiskirstymas procentais (Europe – 29,48%, Latin America – 28,32%).
   * **Didžiausios apyvartos šalys (Pasaulio žemėlapis):** Vizualiai identifikuoja karštuosius pardavimų taškus visame pasaulyje. Burbulo dydis reprezentuoja apyvartos dydį.

---

## 🛠️ Technologijų stakas
* **Įrankis:** Power BI Desktop / Power BI Service
* **Duomenų šaltinis:** DataCo Supply Chain Dataset (Kaggle)
* **Duomenų transformacija:** Power Query (ETL procesas, duomenų tipų keitimas, stulpelių valymas).
* **Analitika:** DAX (skaičiuojami matavimai vidutiniam pristatymo laikui, maržoms, unikalių užsakymų skaičiavimui).

## 🚀 Kaip peržiūrėti projektą?
1. Atsisiųskite `.pbix` failą iš šios repozitorijos.
2. Atsidarykite jį naudodami [Power BI Desktop](https://powerbi.microsoft.com/).
3. Jei norite interaktyviai naršyti, naudokite titulinio puslapio navigacinius mygtukus arba filtrus ataskaitų viršuje.
