# Basi Cartografiche QGIS - Regione Abruzzo e Catasto Nazionale

File di configurazione XML preimpostato per importare con un solo clic le connessioni ai servizi standard **WMS/WMTS** ufficiali in **QGIS**.

---

## 🗺️ Servizi Inclusi

| Servizio | Ente Erogatore | Contenuti Principali |
| :--- | :--- | :--- |
| **Regione Abruzzo - Rete Geodetica** | Regione Abruzzo | Punti di raccordo rete geodetica e stazioni permanenti GNSS |
| **Regione Abruzzo - Geocatalogo Raster** | Regione Abruzzo | Ortofoto aeree multi-temporali, CTR raster (1:5.000, 1:10.000, 1:25.000), DTM e Hillshade |
| **Regione Abruzzo - SeaGIS 106** | Regione Abruzzo | Pianificazione territoriale, vincoli paesaggistici e ambientali |
| **Cartografia Catastale Nazionale** | Agenzia delle Entrate | Fogli catastali, particelle e fabbricati (Direttiva INSPIRE) |

---

## 🚀 Istruzioni di Importazione in QGIS

1. Scarica il file [`basi_cartografiche.xml`](basi_cartografiche.xml) da questo repository (clicca su **Raw** e poi **Salva con nome...**).
2. Apri **QGIS**.
3. Individua il pannello laterale **Browser** (se non visibile: menu *Visualizza* > *Pannelli* > spunta *Browser*).
4. Clicca con il **tasto destro** sulla voce **WMS/WMTS**.
5. Seleziona l'opzione **Carica connessioni...** (o *Load Connections...*).
6. Seleziona il file `basi_cartografiche.xml` scaricato.
7. Spunta i servizi che desideri aggiungere e premi **Importa**.

I servizi saranno immediatamente visibili nell'albero WMS/WMTS, pronti per essere trascinati nella finestra mappa.

---

## ⚖️ Licenza e Note Legali

- **File di configurazione XML:** Rilasciato sotto licenza [MIT](LICENSE). Libero utilizzo, modifica e condivisione.
- **Dati Cartografici e Servizi WMS:** La titolarità, i diritti e le condizioni d'uso dei dati cartografici consultati appartengono esclusivamente ai rispettivi enti erogatori:
  - Dati regionali: soggetti alle condizioni d'uso e copyright della **Regione Abruzzo** (Open Data / IODL).
  - Dati catastali: soggetti alle condizioni di servizio dell'**Agenzia delle Entrate** in attuazione della direttiva europea INSPIRE (consultazione cartografica).