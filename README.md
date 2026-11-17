# American English File 1 — Interactive Elementary Companion

Responsive GitHub Pages project for a 12-unit Elementary course companion.

## Included in this first publication
- Mobile-first layout for iPhone, iPad and desktop.
- Light/dark theme switch.
- 12-unit navigation and search.
- Student's Book / Workbook study areas.
- Lesson completion tracking, saved locally in the browser.
- Notes per unit, print-friendly study view.
- Interactive practice engine with instant feedback and retry.
- Conversation practice area for every unit.
- Media library with local audio/video players, playback speed control and clear missing-file states.

## Important content and media status
The original uploaded HTML is approximately 228 MB and contains embedded media. GitHub rejects individual files over 100 MB, and GitHub Pages has a 1 GB published-site limit. The original full archive is larger still. This repository therefore does **not** pretend that the original 358 audio tracks, 42 videos, worksheets, or complete textbook lesson content have been uploaded.

The original source describes 12 units and 24 lesson sections (Student's Book + Workbook), 358 audio tracks, 42 videos and 12 practice worksheets. The actual media files and licensed source material must be added as appropriately sized, authorized files before the media player can play them.

## Add media
Place authorized files under:
- `media/audio/` — MP3, M4A or OGG
- `media/video/` — MP4 or WebM

Then update `data/media.json` with each file's relative path, title and unit. Do not upload copyrighted course materials publicly unless you have permission to redistribute them.

## Publish with GitHub Pages
1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main**, folder **/(root)**, then Save.
4. Wait for GitHub Pages to publish. The public URL will appear in the same section.

## Files
- `index.html` — app shell
- `styles.css` — responsive design and themes
- `app.js` — navigation, progress, notes, quiz and media controls
- `data/units.json` — 12-unit structure and original conversation prompts
- `data/media.json` — media manifest (initially empty)
