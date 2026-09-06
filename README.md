# Basi Cartografiche QGIS - Regione Abruzzo e Catasto Nazionale

Raccolta di risorse pronte all'uso per caricare rapidamente in **QGIS** i servizi standard **WMS/WMTS** ufficiali della Regione Abruzzo e dell'Agenzia delle Entrate.

Nel repository sono disponibili due modalità di utilizzo:
1. **File GeoPackage (`basi_cartografiche.gpkg`)**: progetto QGIS completo preconfigurato e pronto da aprire.
2. **File XML (`basi_cartografiche.xml`)**: elenco di connessioni WMS da importare nel Browser di QGIS.

---

## 🗺️ Servizi Inclusi

| Servizio | Ente Erogatore | Contenuti Principali |
| :--- | :--- | :--- |
| **Regione Abruzzo - Rete Geodetica** | Regione Abruzzo | Punti di raccordo rete geodetica e stazioni permanenti GNSS |
| **Regione Abruzzo - Geocatalogo Raster** | Regione Abruzzo | Ortofoto aeree multi-temporali, CTR raster (1:5.000, 1:10.000, 1:25.000), DTM e Hillshade |
| **Regione Abruzzo - SeaGIS 106** | Regione Abruzzo | Pianificazione territoriale, vincoli paesaggistici e ambientali |
| **Cartografia Catastale Nazionale** | Agenzia delle Entrate | Fogli catastali, particelle e fabbricati (Direttiva INSPIRE) |

---

## 📦 Modalità 1: Apertura Rapida con GeoPackage (`.gpkg`)

Il file [`basi_cartografiche.gpkg`](basi_cartografiche.gpkg) contiene al suo interno il progetto QGIS già impostato con i layer WMS organizzati.

1. Scarica il file **`basi_cartografiche.gpkg`** da questo repository.
2. Apri **QGIS**.
3. Dal pannello **Browser**, naviga fino alla cartella in cui hai scaricato il file ed espandi la voce `basi_cartografiche.gpkg`.
4. Fai doppio clic sul progetto contenuto all'interno (oppure trascina il file `.gpkg` direttamente nella finestra di QGIS e seleziona il progetto).

---

## ⚙️ Modalità 2: Importazione Connessioni XML (`.xml`)

Se vuoi aggiungere i servizi all'elenco generale di QGIS per usarli in qualsiasi altro tuo progetto:

1. Scarica il file [`basi_cartografiche.xml`](basi_cartografiche.xml) da questo repository (clicca su **Raw** e poi **Salva con nome...**).
2. Apri **QGIS**.
3. Individua il pannello laterale **Browser** (se non visibile: menu *Visualizza* > *Pannelli* > spunta *Browser*).
4. Clicca con il **tasto destro** sulla voce **WMS/WMTS**.
5. Seleziona **Carica connessioni...** (o *Load Connections...*).
6. Seleziona il file `basi_cartografiche.xml`.
7. Seleziona i servizi desiderati e premi **Importa**.

---

## ⚖️ Licenza e Note Legali

- **File di configurazione e progetto:** Rilasciati sotto licenza [MIT](LICENSE). Libero utilizzo, modifica e condivisione.
- **Dati Cartografici e Servizi WMS:** La titolarità, i diritti e le condizioni d'uso dei dati cartografici consultati appartengono esclusivamente ai rispettivi enti erogatori:
  - Dati regionali: soggetti alle condizioni d'uso e copyright della **Regione Abruzzo** (Open Data / IODL).
  - Dati catastali: soggetti alle condizioni di servizio dell'**Agenzia delle Entrate** in attuazione della direttiva europea INSPIRE (consultazione cartografica).
