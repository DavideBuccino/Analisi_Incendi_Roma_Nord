*Read this in other languages: [🇮🇹 Italiano](#-italiano) | [🇬🇧 English](#-english)*

---

# 🇮🇹 Italiano

# 🌲 Analisi Spaziale e Multitemporale degli Incendi a Roma Nord (2020-2024)

![QGIS](https://img.shields.io/badge/QGIS-3.x-589632?style=for-the-badge&logo=qgis&logoColor=white)
![Sentinel-2](https://img.shields.io/badge/Copernicus-Sentinel--2-0033A0?style=for-the-badge)
![Remote Sensing](https://img.shields.io/badge/Remote_Sensing-Spectral_Analysis-F37021?style=for-the-badge)

## 📌 Panoramica del Progetto
Vivere in prima persona l'emergenza degli incendi che hanno colpito Roma Nord nel luglio 2020 e, di nuovo, nel luglio 2024 mi ha spinto ad analizzare l'accaduto con una rigorosa metodologia geospaziale in ambiente **QGIS**.

Ho sviluppato questo report tecnico indipendente per misurare scientificamente l'impatto di questi disastri sul Parco di Monte Ciocci e sulla Riserva Naturale di Monte Mario. I dati estratti confermano la perdita di numerosi ettari di prezioso verde urbano: **3,47 ettari** a Monte Ciocci e **6,69 ettari** a Monte Mario.

Un aspetto fondamentale di questo studio è la **validazione dei risultati**: le perimetrazioni ottenute tramite questa analisi (basata su dati Sentinel-2) sono coerenti e in linea con i risultati ufficiali ottenuti con PlanetScope e pubblicati da **ISPRA** nel report istituzionale *“Ecosistemi terrestri ed incendi boschivi in Italia: Anno 2024”*.

### 📄 Consultazione del Report Completo
*(Trascina e rilascia qui il file "Report Incendi Roma Nord.pdf" o inserisci un'immagine di anteprima della mappa)*

---

## 🛠️ Strumenti e Tecnologie
* **Software:** QGIS (Desktop GIS)
* **Dati Satellitari:** ESA Copernicus Sentinel-2 (Risoluzione 10m)
* **Bande Analizzate:** Banda 4 (Red - Rosso Visibile) e Banda 8 (NIR - Infrarosso Vicino)

---

## 🔬 Workflow Tecnico e Indici Spettrali

Il flusso di lavoro di Remote Sensing (Telerilevamento) mi ha permesso di estrarre tre livelli di informazione cruciali:

1. **Mappatura dei Perimetri (BAI):** * Attraverso l'elaborazione dell'indice spettrale **BAI (Burn Area Index)**, che sfrutta la riflettanza delle bande Red e NIR, ho isolato il segnale radiometrico del suolo carbonizzato, tracciando con precisione i confini definitivi delle aree percorse dal fuoco per entrambi gli eventi.

2. **Analisi di Severità del Danno (dBAI):**
   * Calcolando il **Delta BAI (dBAI)** tramite la sottrazione dei valori raster pre e post-incendio, ho quantificato il livello di severità del danno sul suolo, identificando le zone dove la combustione della biomassa è stata più distruttiva.

3. **Resilienza Ecologica e Recupero (NDVI / dNDVI):**
   * Per valutare il tasso di recupero vegetativo, ho effettuato un confronto multitemporale calcolando l'indice **NDVI (Normalized Difference Vegetation Index)**. Il confronto (Delta NDVI) tra il 2020 e il 2026 ha permesso di misurare matematicamente la resilienza dell'ecosistema.

---

## 💡 Conclusioni Principali
Le mappe restituiscono una duplice verità: la natura sta rapidamente ricolonizzando gli spazi grazie alle specie pioniere, ma le "cicatrici ecologiche" sono ancora ben visibili laddove la foresta d'alto fusto non ha ancora recuperato la densità originale. 
Questo studio è l'ulteriore conferma di quanto il Remote Sensing e i sistemi GIS siano alleati scientifici imprescindibili per monitorare, comprendere e tutelare il patrimonio naturale delle nostre città.

<br><br>

---

# 🇬🇧 English

# 🌲 Spatial and Multitemporal Analysis of Wildfires in North Rome (2020-2024)

## 📌 Project Overview
Experiencing firsthand the wildfire emergencies that struck North Rome in July 2020 and again in July 2024 drove me to analyze the events using a rigorous geospatial methodology in **QGIS**.

I developed this independent technical report to scientifically measure the impact of these disasters on the Monte Ciocci Park and the Monte Mario Nature Reserve. The extracted data confirms the loss of several hectares of precious urban greenery: **3.47 hectares** at Monte Ciocci and **6.69 hectares** at Monte Mario.

A critical aspect of this study is the **validation of the results**: the burn perimeters obtained through this analysis (based on Sentinel-2 data) are consistent and aligned with the official results derived from PlanetScope imagery, published by **ISPRA** (the Italian Institute for Environmental Protection and Research) in their institutional report.

### 📄 Full Report Consultation
*(Drag and drop your "Report Incendi Roma Nord.pdf" file here, or insert a map preview image)*

---

## 🛠️ Tools & Technologies
* **Software:** QGIS (Desktop GIS)
* **Satellite Data:** ESA Copernicus Sentinel-2 (10m Resolution)
* **Analyzed Bands:** Band 4 (Red) and Band 8 (NIR - Near Infrared)

---

## 🔬 Technical Workflow & Spectral Indices

The Remote Sensing workflow allowed me to extract three crucial layers of information:

1. **Burn Perimeter Mapping (BAI):** * By processing the **BAI (Burn Area Index)**, which leverages the reflectance of the Red and NIR bands, I isolated the radiometric signal of the charred soil, precisely tracing the definitive boundaries of the areas affected by the fire for both events.

2. **Damage Severity Analysis (dBAI):**
   * By calculating the **Delta BAI (dBAI)** through the subtraction of pre- and post-fire raster values, I quantified the severity of the soil damage, identifying the zones where biomass combustion was most destructive.

3. **Ecological Resilience and Recovery (NDVI / dNDVI):**
   * To evaluate the vegetative recovery rate, I performed a multitemporal comparison by calculating the **NDVI (Normalized Difference Vegetation Index)**. The comparison (Delta NDVI) between 2020 and 2026 allowed for the mathematical measurement of the ecosystem's resilience.

---

## 💡 Key Takeaways
The maps reveal a dual truth: nature is rapidly recolonizing the spaces thanks to pioneer species, but the "ecological scars" are still clearly visible where the high-canopy forest has not yet recovered its original density. 
This study is further confirmation of how Remote Sensing and GIS are indispensable scientific allies for monitoring, understanding, and protecting the natural heritage of our cities.
