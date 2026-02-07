# 🚀 GUIDA RAPIDA - Per Cerebrolesi 😊

## ✅ Cosa hai adesso

Hai una web app divisa in file separati (non più un unico file da 3700 righe!):

```
📁 turni-medici/
├── 📄 index.html              ← Pagina principale
├── 📄 README.md               ← Guida completa (in inglese)
├── 📁 css/
│   ├── variables.css          ← Colori e impostazioni
│   ├── components.css         ← Bottoni, tabelle, etc
│   └── layout.css             ← Struttura pagina
├── 📁 js/
│   ├── config.js              ← Configurazioni
│   ├── validators.js          ← Validazione disponibilità
│   ├── storage.js             ← Salvataggio dati
│   ├── history.js             ← Undo/Redo
│   ├── renderer.js            ← Disegna la tabella
│   ├── dragdrop.js            ← Drag & drop
│   └── app.js                 ← Coordinatore principale
└── 📁 data/
    └── disponibilita.json     ← Disponibilità medici
```

---

## 📤 PUBBLICARE SU GITHUB - 3 PASSI

### PASSO 1: Scarica tutto
1. Vai alla fine di questa chat
2. Clicca sui file che ti ho creato
3. Scaricali TUTTI sul tuo computer
4. Crea una cartella `turni-medici`
5. Metti i file nelle cartelle giuste (come sopra)

### PASSO 2: Crea repository GitHub
1. Vai su https://github.com
2. Fai login (o crea account)
3. Clicca il "+" in alto a destra → "New repository"
4. Nome: `turni-medici`
5. Descrizione: "Sistema gestione turni medici"
6. Spunta "Add README"
7. Clicca "Create repository"

### PASSO 3: Carica i file
**METODO FACILE (Browser):**
1. Nel tuo repository, clicca "Add file" → "Upload files"
2. Trascina TUTTA la cartella `turni-medici`
3. Scrivi: "Prima versione sistema turni"
4. Clicca "Commit changes"

**ATTIVA IL SITO:**
1. Vai in "Settings" del repository
2. Clicca "Pages" nel menu a sinistra
3. Sotto "Source" seleziona "main"
4. Clicca "Save"
5. Aspetta 1 minuto
6. Ricarica la pagina → vedrai il link del sito! 🎉

---

## 🎮 COME USARE L'APP

### Prima volta:
1. Apri `disponibilita.json` nella cartella `data`
2. Modifica con i dati dei tuoi medici
3. Salva
4. Apri `index.html` nel browser

### Uso normale:
- **Trascina** i nomi dei medici sulle celle
- **Click** su una cella per assegnarla al medico
- **Tasto destro** per menu rapido
- **Ctrl+Z** per annullare
- **Ctrl+S** per salvare

### Importare disponibilità:
Il sistema legge automaticamente da `data/disponibilita.json`.

Per modificare le disponibilità:
1. Vai su https://1nnuendo2000.github.io/desiderata/
2. Compila i dati di un medico
3. Clicca "GENERA CODICE"
4. Copia il codice JSON
5. Incollalo in `disponibilita.json`

---

## 🔧 PERSONALIZZARE

### Cambiare colori:
Apri `css/variables.css` e modifica i colori in alto.

### Aggiungere medici:
Apri `js/config.js` e modifica l'array `MEDICI`.

### Attivare/disattivare funzioni:
Apri `js/config.js` e modifica `FEATURES`.

---

## 🆘 PROBLEMI COMUNI

### Il sito non si carica
- Controlla che `index.html` sia nella root
- Apri Console (F12) e guarda se ci sono errori rossi

### I file .js non si caricano
- Controlla che i percorsi siano giusti (es: `js/config.js`)
- Assicurati che le cartelle `js`, `css`, `data` esistano

### Le modifiche non si vedono
- Fai "hard refresh": Ctrl+Shift+R (Windows) o Cmd+Shift+R (Mac)
- Svuota la cache del browser

### Errori JavaScript
- Apri Console (F12)
- Leggi il messaggio d'errore
- Controlla che tutti i file .js siano caricati

---

## 📞 HELP

Se hai problemi:
1. Apri la Console (F12 nel browser)
2. Controlla errori rossi
3. Copia il messaggio d'errore
4. Cerca su Google o chiedi a ChatGPT/Claude

---

## 🎯 PROSSIMI PASSI

1. ✅ Pubblica su GitHub
2. ✅ Testa che funzioni online
3. ✅ Modifica `disponibilita.json` con dati reali
4. ✅ Usa il sistema per i turni!

---

**Creato con ❤️ per semplificare la vita** 

P.S. Se qualcosa non funziona, non è colpa tua - è colpa mia che ho spiegato male! 😊
