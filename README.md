# American English File 1 — Interactive Elementary Companion

A responsive GitHub Pages course companion built from the uploaded **AEF1_Curso_Completo.html** source.

## Integrated source content

- All **12 units**, with their source titles, subtitles and themes.
- Student's Book and Workbook areas for every unit.
- Grammar Lab: source explanations, forms, bilingual examples, usage notes and common-error corrections.
- Vocabulary: 10 source entries per unit with Portuguese meanings and bilingual examples.
- Useful English chunks: 5 expressions per unit with meanings, use cases and examples.
- **144 source-based practice questions** (6 Student's Book + 6 Workbook per unit), with automatic feedback and retry.
- Unit-specific Conversation Lab prompts built from the unit's actual theme, grammar and expressions.
- Source lesson schedules for Student's Book and Workbook.
- **358 audio track guides** with section labels, focus and listening-stage prompts.
- **43 video guides** with titles, categories and guided viewing questions.
- iPhone/iPad responsive layout, light/dark theme, local progress, local notes and print-friendly lesson view.

## Media files: important distinction

The audio/video **catalogue and guided questions are integrated**, but the MP3/MP4 binary files are not yet stored in this repository. The original HTML is about 228 MB and the source archive is much larger; GitHub's normal file upload limit is 100 MB per file. The players point to these locations:

- `media/audio/<filename>`
- `media/video/<filename>`

Add only media you are authorized to redistribute. Once a file is uploaded at its matching path, its player can load it; missing files display a clear unavailable status. The app does not redirect to YouTube.

## Run / publish

1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select `main` and `/(root)`, then Save.
4. Wait for GitHub Pages to publish the site.

## Project structure

- `index.html` — responsive course app shell
- `styles.css` — layout, iOS/iPad responsiveness and themes
- `app.js` — unit rendering, practice correction, progress, notes and media players
- `data/units.json` — source-derived unit curriculum
- `data/media.json` — 358 audio and 43 video guides
- `media/audio/` and `media/video/` — locations for authorized media binaries

Progress and notes are stored locally in the current browser and do not synchronize between devices.
