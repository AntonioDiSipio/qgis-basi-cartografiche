# QGIS - Basi Cartografiche e Servizi Standard OGC

Raccolta di file di configurazione XML preimpostati per importare rapidamente connessioni a servizi cartografici standard (WMS, WMTS, WFS, XYZ Tiles) all'interno di **QGIS**.

Il repository include endpoint ufficiali per la consultazione e l'interrogazione vettoriale/raster di cartografia catastale, ortofoto, limiti amministrativi e dati territoriali.

---

## 📁 Contenuto del repository

| File | Protocollo | Descrizione principale |
| :--- | :--- | :--- |
| `basi_cartografiche_wfs-ogc-api_feature.xml` | **WFS / OGC API** | Servizi vettoriali interrogabili e scaricabili (es. Catasto Nazionale AdE via INSPIRE WFS). |
| `cartografia_di_base_wms.xml` | **WMS / WMTS** | Servizi raster a visualizzazione (ortofoto, CTR, carte topografiche, vincoli). |
| `xyz_tiles.xml` *(opzionale)* | **XYZ Tiles** | Basemap raster globali ad alte prestazioni (OSM, Google, ESRI, Bing). |

---

## 🚀 Istruzioni per l'importazione in QGIS

L'importazione si effettua direttamente tramite il pannello **Browser** (Navigatore) di QGIS:

### Importazione WFS / OGC API - Features
1. Apri QGIS.
2. Nel pannello **Browser**, individua la voce **WFS / OGC API - Features**.
3. Clicca con il tasto destro sulla voce e seleziona **Carica connessioni...** (*Load Connections...*).
4. Seleziona il file `basi_cartografiche_wfs-ogc-api_feature.xml`.
5. Seleziona le connessioni desiderate (oppure clicca su **Seleziona tutto**) e premi **Importa**.

### Importazione WMS / WMTS
1. Nel pannello **Browser**, individua la voce **WMS/WMTS**.
2. Clicca con il tasto destro e seleziona **Carica connessioni...** (*Load Connections...*).
3. Seleziona il file `cartografia_di_base_wms.xml` e conferma l'importazione.

---

## 🏛️ Servizi principali inclusi

- **Agenzia delle Entrate (AdE)**: Cartografia Catastale Nazionale (fogli, particelle, fabbricati) conforme agli standard INSPIRE WFS.
- **Geoportale Nazionale (MASE)**: Limiti amministrativi, ortofoto territoriali e vincoli.
- **ISPRA**: Banche dati geologiche e inventari ambientali (es. dissesto IFFI).
- **Regione Abruzzo**: Servizi territoriali, ortofotopiani e Carte Tecniche Regionali.

---

## 📄 Note e Licenze

I dati richiamati dai servizi rimangono di proprietà dei rispettivi enti erogatori e sono distribuiti secondo le rispettive licenze d'uso (IODL, Creative Commons, direttiva INSPIRE).
