# Cocina Club — Spanish Cooking Game

A responsive, browser-based Spanish vocabulary arcade game. No installation or server required.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Your game progress is saved in that browser using local storage.

## Game modes
- **Kitchen Rush:** 10-question multiple-choice round with a 15-second timer per question.
- **Chef's Flashcards:** reveal meanings and mark words you know.
- **Pair the Plates:** match Spanish and English pairs.
- **Word Scramble:** unscramble Spanish words against a 30-second clock.
- **Cocina Quest:** a playable 2D side-scrolling platform game. Move with A/D or the arrow keys, jump with Space or Up, collect floating vocabulary ingredients, and reach the kitchen exit. Mobile on-screen controls are included. Each collected word shows its Spanish and English meaning and earns XP.

## Curated starter vocabulary
The starter pantry now contains 43 carefully selected beginner words focused on useful food, kitchen equipment and cooking verbs. The included CSV/TXT lists contain the same curated set, rather than the previous large mixed vocabulary dump. You can still add your own words whenever you want.

The game uses a new local-storage version for this cleaned-up starter pantry. This means the old saved word list is not loaded into the new version; the old browser data is left untouched.

## Add your own vocabulary
Click **Add words**. Paste one pair per line, for example:

    la manzana — the apple
    cocinar — to cook
    el cuchillo — the knife

Supported separators: em dash, en dash, hyphen surrounded by spaces, comma, semicolon, colon, pipe, tab, or two or more spaces. Duplicate Spanish entries are skipped.

You can also import TXT, CSV, TSV, DOCX or PDF files. DOCX/PDF reading libraries load from a CDN and require an internet connection the first time. Scanned PDFs need OCR, which is not included.

## Spanish A1 Academy
The website includes a 37-lesson A1 course roadmap based on the public lesson index at iEspanol.org. Each lesson opens its original page in a new tab. Tick the checkbox next to a lesson to track your progress locally. The game does not copy or host the course's lesson text, exercises or audio.

## Notes
- Vocabulary parsing and file reading happen in your browser; uploaded vocabulary is not sent to a server.
- Google Fonts are optional; the browser uses fallback fonts offline.


You can remove individual words from **My word pantry** using the ✕ button beside each entry. Deletions are saved locally, including when the pantry becomes empty.
