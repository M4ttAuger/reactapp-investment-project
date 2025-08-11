# React Investment Calculator

Questo progetto è una semplice applicazione web sviluppata con React che permette di simulare investimenti nel tempo. L'utente può inserire i dati principali dell'investimento e visualizzare i risultati in tempo reale.

## Funzionalità principali

- **Inserimento dati investimento**: L'utente può inserire l'investimento iniziale, l'investimento annuale, il rendimento atteso e la durata.
- **Visualizzazione risultati**: I risultati vengono calcolati e mostrati dinamicamente in base ai dati inseriti.
- **Interfaccia intuitiva**: Layout semplice e chiaro, con logo e intestazione personalizzati.

## Funzionalità React utilizzate

- **Componenti funzionali**: Tutte le parti dell'app sono suddivise in componenti React riutilizzabili (`Header`, `UserInput`, `Results`).
- **Stato locale con useState**: I dati inseriti dall'utente sono gestiti tramite lo stato locale con lo hook `useState`.
- **Props**: I dati e le funzioni vengono passati tra i componenti tramite le props, favorendo la modularità.
- **Gestione eventi**: Gli input dell'utente sono gestiti tramite eventi React (`onChange`).

## Avvio del progetto

1. Installa le dipendenze:
   ```bash
   npm install
   ```
2. Avvia il server di sviluppo:
   ```bash
   npm run dev
   ```
3. Apri il browser su `http://localhost:5173` per vedere l'app in funzione.

## Struttura del progetto

```
reactapp-investment-project/
├── public/
├── src/
│   ├── components/
│   ├── assets/
│   ├── styles/
│   ├── util/
│   ├── App.jsx
│   ├── index.jsx
│   └── index.css
├── package.json
├── vite.config.js
└── README.md
```

## Autore

Creato da M4ttAuger.
