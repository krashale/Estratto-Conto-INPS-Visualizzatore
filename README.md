# Estratto Conto INPS Visualizer

> Visualizzatore moderno, locale e privacy-friendly per gli estratti conto previdenziali INPS in formato XML.

## 📋 Descrizione

**Estratto Conto INPS Visualizer** è una semplice applicazione web che permette di aprire e visualizzare in modo chiaro e leggibile i file XML dell'estratto conto previdenziale INPS.

L'obiettivo è trasformare un documento tecnico e poco intuitivo in un report facilmente consultabile e stampabile.

Tutto avviene direttamente nel browser:

* ✅ Nessun server
* ✅ Nessun upload online
* ✅ Nessuna registrazione
* ✅ Nessuna installazione
---

## ✨ Funzionalità

### 📂 Caricamento XML
* Drag & Drop del file XML
* Selezione tramite file picker
* Validazione automatica del file

### 👤 Anagrafica
Visualizzazione delle informazioni personali:
* Nome e Cognome
* Codice Fiscale
* Data di nascita
* Luogo di nascita
* Sesso
* Indirizzo

### 🏢 Regime Generale
Visualizzazione dei contributi da lavoro dipendente:
* Periodo contributivo
* Tipo contribuzione
* Tipo contributo
* Settimane utili al diritto
* Settimane utili al calcolo
* Retribuzione imponibile
* Azienda / Datore di lavoro

### 📋 Gestione Separata
Visualizzazione dei contributi parasubordinati:
* Anno
* Reddito imponibile
* Committente
* Tipo attività
* Contributi versati
* Aliquota contributiva

### 📈 Montante Contributivo
Visualizzazione del montante accumulato:
* Reddito imponibile
* Contributi annui
* Rivalutazioni
* Montante progressivo

### 🏛 Gestione Pubblica
Supporto ai contributi provenienti da:
* Enti Locali
* Pubblica Amministrazione
* Fondi pubblici
con dettaglio dei periodi e delle retribuzioni.

### ⚠ Segnalazioni e Avvertenze
Evidenzia automaticamente:
* Segnalazioni personalizzate INPS
* Avvertenze
* Note informative

### 🖨 Stampa PDF
Layout ottimizzato per:
* Stampa cartacea
* Salvataggio in PDF
* Archiviazione personale
---

## 🔒 Privacy
Questo progetto è stato progettato con il principio **Privacy First**.

### I tuoi dati non lasciano mai il computer
Il file XML viene:
1. Caricato nel browser
2. Elaborato localmente tramite JavaScript
3. Visualizzato a schermo

Non vengono effettuate:
* chiamate API
* upload verso server
* invii a terze parti
* tracking
Il progetto funziona completamente offline.
---

## 📄 Formato supportato

Attualmente supporta i file XML dell'estratto conto previdenziale INPS contenenti sezioni come:

```xml
<DatiAnagrafici>
<RegimeGenerale>
<RegimeParasubordinati>
<GestionePubblica>
```

Le sezioni non presenti nel file vengono automaticamente ignorate.
---

## 🛠 Tecnologie utilizzate
* HTML5
* CSS3
* JavaScript Vanilla
* DOMParser API
* FileReader API

Nessuna dipendenza esterna.

Nessun framework.

Nessuna libreria di terze parti.


## 📦 Struttura del progetto

```text
.
├── estratto_conto_inps.html
├── README.md
└── LICENSE
```

---

## 🎯 Roadmap

Possibili evoluzioni future:

* [ ] Timeline contributiva interattiva
* [ ] Grafici annuali
* [ ] Analisi buchi contributivi
* [ ] Stima pensionistica indicativa
* [ ] Esportazione Excel
* [ ] Tema scuro
* [ ] Supporto ad ulteriori gestioni previdenziali
* [ ] PWA installabile offline

---

## ⚠ Disclaimer

Questo progetto:
* non è affiliato all'INPS
* non sostituisce i servizi ufficiali INPS
* non fornisce consulenza previdenziale
* non garantisce la correttezza dei dati contenuti nei file XML

L'utente è responsabile della verifica delle informazioni riportate.
---

## 🤝 Contributi
Segnalazioni, bug report e pull request sono benvenuti.

Se trovi un problema:
1. Apri una Issue
2. Descrivi il comportamento riscontrato
3. Allega (se possibile) un XML anonimizzato
---

## 📜 Licenza
Distribuito sotto licenza MIT.
Vedi il file `LICENSE` per maggiori dettagli.

---

## ⭐ Supporta il progetto
Se questo strumento ti è stato utile:
* lascia una ⭐ su GitHub
* condividilo con altri utenti INPS
* contribuisci con idee e miglioramenti

---

**Estratto Conto INPS Visualizer**
*Leggi il tuo estratto conto previdenziale in modo semplice, chiaro e sicuro.* 🔒📊📄

![Built with Claude](https://img.shields.io/badge/Built%20with-Claude-purple)
![Reviewed with ChatGPT](https://img.shields.io/badge/Reviewed%20with-ChatGPT-green)
