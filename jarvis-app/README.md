# J.A.R.V.I.S. — KI Voice Assistant

Voice-only KI-Assistent mit Arc-Reactor-UI, powered by Groq (Llama 3.3 70B).

## Setup

1. **Groq API Key holen** (kostenlos): https://console.groq.com
2. `.env` Datei erstellen:
   ```
   cp .env.example .env
   ```
   Dann die Keys eintragen.

3. **Starten:**
   ```bash
   npm install
   npm start
   ```

4. Öffne `http://localhost:3000` im Browser.

## iPhone App

1. Öffne die URL in Safari
2. Teilen → "Zum Home-Bildschirm"
3. Fertig

## Features

- Sprachsteuerung (Tippe den Reaktor)
- Echte KI-Antworten via Groq/Llama
- Sprachausgabe auf Deutsch
- Multi-Key-Rotation (bis zu 20 Keys)
- Konversations-Gedächtnis pro Session
