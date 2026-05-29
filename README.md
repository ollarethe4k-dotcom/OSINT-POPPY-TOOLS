<div align="center">

# POPPY

[![Project Status: Alpha](https://img.shields.io/badge/Project_Status-In_Development/Alpha-red?style=for-the-badge)]()
[![Target OS](https://img.shields.io/badge/Target_OS-Windows%20%7C%20Linux-0078D6?style=for-the-badge&logo=windows&logoColor=white)]()
[![Python](https://img.shields.io/badge/Python-3.7+-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge&logo=opensourceinitiative&logoColor=white)]()
![Last Commit](https://img.shields.io/github/last-commit/ollarethe4k-dotcom/OSINT-POPPY-TOOLS?style=flat-square&color=blue)

<p align="center">
  A lightweight, multi-threaded OSINT tool written in Python to perform deep target investigations, aggregate search engine data, filter leaks, and automatically extract emails.
</p>

---

</div>

> [!WARNING]
> **Stato del progetto:** Lo strumento è attualmente in fase di sviluppo attivo. Al momento è rilasciata una **versione base** dell'applicativo; nuove funzionalità e ottimizzazioni d'architettura verranno integrate regolarmente.

---

## 📌 Features Attuali (Versione Base)

* **Architettura Multi-Thread:** Esegue interrogazioni rapide e concorrenti per massimizzare l'efficienza ed evitare blocchi[span_0](start_span)[span_0](end_span).

* **Categorizzazione Intelligente:** Suddivide e raggruppa automaticamente i risultati in base alla tipologia (es. *Social Media, Code/Data/Leaks, News, Blog*)[span_1](start_span)[span_1](end_span).

* **Email Harvester Automatico:** Analizza gli snippet dei risultati in tempo reale per estrarre gli indirizzi email associati al target[span_2](start_span)[span_2](end_span).

* **Deep Dorking Query:** Rotazione di query prefigurate mirate a profili di intelligence pubblici e leak dump[span_3](start_span)[span_3](end_span).

* **Interfaccia CLI Pulita:** Visualizzazione da terminale intuitiva con spinner di caricamento e log colorati tramite codici ANSI[span_4](start_span)[span_4](end_span).

---

## 🔮 Future Features (In Arrivo)

Stiamo lavorando per espandere le capacità dello strumento. 

Ecco la roadmap dei prossimi moduli in via di sviluppo:

- [ ] **Integrazione API Esterne:** Supporto nativo a servizi di intelligence come Shodan, Hunter.io e VirusTotal.

- [ ] **Esportazione dei Report:** Possibilità di salvare i risultati della scansione in formati strutturati come `JSON`, `CSV` o report grafici in `PDF`.

- [ ] **Scansione Target Avanzata:** Modulo specifico per l'esecuzione di reverse lookup tramite numeri di telefono, indirizzi IP e username (Social Media Cross-Hunting).

- [ ] **Web Scraping Diretto:
** Analisi approfondita ed estrazione del testo direttamente dalle pagine web individuate, superando il limite dei soli snippet dei motori di ricerca.

---

📝 License
Distribuito sotto Licenza MIT. 

Vedi il file LICENSE all'interno della repository per ulteriori informazioni.


