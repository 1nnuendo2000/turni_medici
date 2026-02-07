# 🏥 Sistema Turni Medici - Versione Modulare

Sistema completo per la gestione dei turni medici con validazione delle disponibilità.

## 📁 Struttura del Progetto

```
turni-medici/
├── index.html              # Pagina principale
├── css/
│   ├── variables.css       # Variabili CSS (colori, dimensioni)
│   ├── components.css      # Stili componenti (bottoni, tabelle)
│   └── layout.css          # Layout e struttura pagina
├── js/
│   ├── config.js           # Configurazioni e costanti
│   ├── validators.js       # Validazioni disponibilità
│   ├── renderer.js         # Rendering tabella turni
│   ├── storage.js          # Gestione localStorage
│   ├── history.js          # Undo/Redo
│   ├── dragdrop.js         # Drag & drop
│   └── app.js              # Coordinatore principale
├── data/
│   └── disponibilita.json  # File disponibilità medici
└── README.md               # Questa guida
```

## 🚀 GUIDA PASSO-PASSO PER PUBBLICARE SU GITHUB

### STEP 1: Prepara i file sul tuo computer

1. Crea una cartella chiamata `turni-medici`
2. Dentro crea le sottocartelle: `css`, `js`, `data`
3. Scarica tutti i file che ti fornirò e mettili nelle cartelle giuste

### STEP 2: Crea account GitHub (se non ce l'hai)

1. Vai su https://github.com
2. Clicca "Sign up" in alto a destra
3. Scegli username, email e password
4. Verifica l'email

### STEP 3: Crea un nuovo repository

1. Clicca il "+" in alto a destra → "New repository"
2. Nome repository: `turni-medici`
3. Descrizione: "Sistema gestione turni medici"
4. Seleziona "Public" (o "Private" se vuoi)
5. ✅ Spunta "Add a README file"
6. Clicca "Create repository"

### STEP 4: Carica i file (METODO FACILE - Via browser)

1. Nel tuo repository, clicca "Add file" → "Upload files"
2. Trascina TUTTA la cartella `turni-medici` (o seleziona i file)
3. Scrivi un messaggio tipo: "Prima versione del sistema turni"
4. Clicca "Commit changes"

### STEP 5: Attiva GitHub Pages (per pubblicare online)

1. Nel repository, clicca "Settings" (in alto)
2. Nel menu a sinistra, clicca "Pages"
3. Sotto "Source", seleziona "main" dal menu a tendina
4. Clicca "Save"
5. Aspetta 1-2 minuti
6. Ricarica la pagina: vedrai il link tipo `https://TUO-USERNAME.github.io/turni-medici/`

### STEP 6: Testa il sito

1. Apri il link che hai ottenuto
2. Verifica che tutto funzioni
3. Se c'è qualche errore, controlla la console (F12 → Console)

---

## 🔧 METODO ALTERNATIVO: Usa GitHub Desktop (più professionale)

### Installazione

1. Scarica GitHub Desktop: https://desktop.github.com
2. Installalo e fai login con il tuo account GitHub

### Pubblicazione

1. Apri GitHub Desktop
2. Clicca "File" → "Add Local Repository"
3. Seleziona la cartella `turni-medici`
4. Scrivi un messaggio nel campo "Summary" (es: "Prima versione")
5. Clicca "Commit to main"
6. Clicca "Publish repository" in alto
7. Conferma e aspetta il caricamento

---

## 📝 Come aggiornare il sito dopo modifiche

### Via Browser:
1. Vai nel repository su GitHub
2. Clicca sul file da modificare
3. Clicca l'icona della matita (Edit)
4. Fai le modifiche
5. Scorri in basso, scrivi cosa hai cambiato
6. Clicca "Commit changes"

### Via GitHub Desktop:
1. Modifica i file sul tuo computer
2. Apri GitHub Desktop
3. Vedrai le modifiche nella colonna sinistra
4. Scrivi cosa hai cambiato in "Summary"
5. Clicca "Commit to main"
6. Clicca "Push origin" in alto

---

## 🎯 Funzionalità del Sistema

- ✅ Gestione turni medici con drag & drop
- ✅ Validazione automatica disponibilità
- ✅ Import/Export JSON
- ✅ Calcolo automatico carichi lavoro
- ✅ Undo/Redo (Ctrl+Z / Ctrl+Y)
- ✅ Autosave locale
- ✅ Scrollbar custom
- ✅ Context menu
- ✅ Keyboard shortcuts

## 🔑 Shortcut da Tastiera

- `Ctrl + Z` - Annulla
- `Ctrl + Y` - Ripristina
- `Ctrl + S` - Salva manualmente
- `Ctrl + E` - Esporta JSON

## 📊 Come funziona la validazione

Il sistema legge i file di disponibilità da `data/disponibilita.json` e valida:

1. **Turni Fissi (◆)**: Obbligatori ricorrenti settimanali
2. **Veti (⛔)**: Giorni specifici non disponibili
3. **Congedi (🏖️)**: Ferie/permessi
4. **Target Alpi**: Range min-max turni mensili

## 🐛 Risoluzione Problemi

### Il sito non si carica
- Controlla che `index.html` sia nella root del repository
- Verifica che GitHub Pages sia attivo in Settings → Pages

### Errori JavaScript
- Apri la Console (F12)
- Controlla che tutti i file .js siano caricati
- Verifica i percorsi relativi nei tag `<script>`

### Modifiche non visibili
- Fai "hard refresh": Ctrl+Shift+R (Windows) o Cmd+Shift+R (Mac)
- Svuota cache del browser

## 📞 Supporto

Per problemi o domande:
1. Apri una "Issue" nel repository GitHub
2. Descrivi il problema con screenshot se possibile

---

**Creato con ❤️ per semplificare la gestione turni medici**
