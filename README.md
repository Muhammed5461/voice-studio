# Sükûn Voice Studio

Ruhige KI-Voice-overs auf **Deutsch und Türkisch** für Motion-Graphics-Videos – mit der Gemini-Stimme **Charon**.

## Nutzung
1. App öffnen → **Einstellungen** → Gemini-Schlüssel aus [Google AI Studio](https://aistudio.google.com) einfügen → **Prüfen & Modelle laden**.
2. **Skript** → Text einfügen (Absatz = Szene) oder per KI erstellen → bei Bedarf DE ↔ TR übersetzen.
3. **Szenen** → **Alle vertonen** → anhören, einzelne Szenen neu vertonen, Klang anpassen.
4. **Export** → MP3/WAV + SRT-Untertitel (z. B. für CapCut).

## Datenschutz
Der Schlüssel, die Projekte und die Aufnahmen bleiben im Browser des Geräts. Texte gehen nur direkt an die Gemini-API von Google.

## Technik
Eine einzige `index.html` ohne Build-Schritt. MP3-Kodierung mit [LAME/lamejs](https://lame.sourceforge.net) (LGPL, `vendor/lame.min.js` unverändert), ZIP mit JSZip (MIT).
