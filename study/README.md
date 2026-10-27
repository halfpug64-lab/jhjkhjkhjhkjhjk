# Studyhall

A free Quizlet-style study site in one HTML file. Upload notes, a PDF or a Word doc, and an AI builds:

- **Flashcards**: flip, shuffle, mark "know it" / "still learning", definition-first mode
- **Practice tests**: AI-written multiple choice and true/false, plus questions built from your cards (multiple choice, true/false, written answers with typo tolerance)
- **Match**: timed term-to-definition game that saves your best time
- **Categories**: sort items into the right groups (tap or drag)

## Running it

Open `study/index.html` in a browser. It also works on GitHub Pages or any static host.

## AI (free)

Click **AI settings** and paste a free API key from one of these:

- Google Gemini: https://aistudio.google.com (default model `gemini-flash-latest`)
- Groq: https://console.groq.com (default model `llama-3.3-70b-versatile`)

The key stays in your browser's local storage and is sent only to that provider. Free tiers have rate limits. Groq's are tighter, so long documents get cut short there.

## Without AI

Type one term per line, like `Mitochondria - makes ATP` (a colon, tab or `=` works too), and click **Make cards without AI**. Lines like `# Organelles` or `Organelles:` start a category group.

## Notes

- Sets are saved in your browser. Use **Export** / **Import set** to back them up or share them.
- Scanned PDFs (photos of pages) have no text layer, so they can't be read.

## claude.ai version

`claude-artifact.html` is the version published as a claude.ai artifact: https://claude.ai/artifact/1aufUWkpnQcGbFwmZwq6MX

It runs on your Claude account instead of an API key and saves sets to your account so they show up on any device. It only works when opened on claude.ai.
