# DimaService CRM — Electron App

## Come creare l'installer .exe

### Requisiti
- Node.js 18+ (https://nodejs.org)
- npm (incluso con Node.js)

### Passaggi

1. **Estrai** questa cartella sul tuo PC Windows

2. **Apri il terminale** (cmd o PowerShell) nella cartella estratta

3. **Installa le dipendenze:**
   ```
   npm install
   ```

4. **Crea l'installer .exe:**
   ```
   npm run build
   ```

5. Il file `.exe` sarà nella cartella `dist/`
   - Esempio: `dist/DimaService CRM Setup 6.5.0.exe`

6. **Distribuisci** il file `.exe` — al primo avvio installa l'app sul PC

### Note
- Icona personalizzata: sostituisci `icon.ico` e `icon.png` con la tua icona
- L'app si apre come finestra desktop senza barra del browser
- I dati rimangono salvati in localStorage come sempre
