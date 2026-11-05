# Cocina Club — Spanish Cooking Game

A responsive, browser-based Spanish vocabulary game. No installation or server required.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox or Safari).
3. Your progress and vocabulary are saved in that browser using local storage.

## Add your own vocabulary
Click **Add words**. Paste one pair per line, for example:

    la manzana — the apple
    correr — to run
    la cocina — kitchen

Supported separators: em dash, en dash, hyphen surrounded by spaces, comma, semicolon, colon, pipe, tab, or two or more spaces. Duplicate Spanish entries are skipped.

You can also import:
- TXT, CSV and TSV (read locally)
- DOCX (uses Mammoth.js from a CDN)
- PDF (uses PDF.js from a CDN)

The first DOCX/PDF import needs an internet connection to load its document-reading library. The rest of the game works without those libraries. Scanned/image-only PDFs do not contain selectable text, so OCR is not included; export them with selectable text or paste the words instead.

## Game modes
- Kitchen Rush: 10-question multiple-choice round with a 15-second question timer.
- Chef's Flashcards: reveal meanings and mark words you know.
- Pair the Plates: match Spanish and English pairs.

XP, learned words and your custom word pantry are stored in local browser storage. Clearing browser site data will clear this progress. The included sample pantry can be replaced by adding your own words; duplicates are ignored.

## Notes
- All parsing and file reading happen in your browser; uploaded vocabulary is not sent to a server.
- Google Fonts are optional; if offline, the browser uses fallback fonts.
- DOCX/PDF import requires internet access for the library CDN.
