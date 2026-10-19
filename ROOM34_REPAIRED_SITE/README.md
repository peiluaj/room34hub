# ROOM 34 POETS SOCIETY — Student website

## Open in VS Code
1. Unzip this package. Open the **ROOM34_POETS_SOCIETY_SITE** folder in VS Code.
2. Open `index.html` with Live Server (recommended), or double-click `index.html` in your browser. No installation or build step required.
3. Files: `index.html` (layout), `style.css` (visual design), `script.js` (interactive features), `lessons.js` (all lesson data), `images/lessons/` and `images/readings/` (artwork).

## Content status
- Lessons **1–5** include real, differentiated reading passages, spelling activities, multiple-choice questions, written responses, poetry writing and reflection.
- Lessons **6–40** have the complete lesson titles and schedule, but their content is **not yet written**. They are explicitly labelled *coming soon*, not represented as finished.
- Images supplied for Lessons 1–3 are included as compressed WebP. The 40-lesson image plan is in `IMAGE_MANIFEST.csv`.
- Missing images show a graceful placeholder. Add the correctly named `.webp` files into the paths in the manifest and refresh.

## Important
- Work is stored in `localStorage` on the same browser/device, not in an online account. Clearing browser data can delete it.
- CSV export includes the student's name entered at download time, group, answers, poem, reflection and multiple-choice auto-mark values.
- All lessons are **visible**; future content is not falsely represented as complete.
- No teacher answer keys or exemplars are included in the student-facing app.
- No reading-level labels are shown to students.
- The styling draws inspiration from the supplied HistoryFlix layout; no HistoryFlix copyrighted image assets or source code have been copied.
- For GitHub Pages: upload the **contents of this folder** to your repository root and enable Pages from the main branch root.

## Interactive spelling activities (updated)
Each spelling challenge has its own workspace. Matching tasks use clickable word and definition tiles with connecting lines; use Check matches for feedback and Clear lines to retry. Recall-and-spell activities include individual word inputs, a hide/show word button and spelling checks. Other tasks include dedicated response boxes. All answers save automatically in browser localStorage and are included as separate spelling rows in the exported CSV. Matching lines are recalculated when the window resizes. These workspaces are available in the authored Lessons 1–5 for all five groups.


## Week 2 — Lessons 6–10
All five groups have original reading passages, 10-word vocabulary banks, four interactive spelling activities, multiple-choice and written comprehension, differentiated writing tasks, and reflections. The images are deliberately placeholders. Add images to `images/lessons/lesson06-cover.webp` through `lesson10-cover.webp` and `images/readings/lesson06-pioneers.webp` etc. The student site automatically shows the image when the file is present. The teacher answer keys and exemplars are stored in `lessons.js` (not shown to students).

## Vocab Arena (new)
Lessons 6–10 now have a five-game Vocab Arena: Match Attack, Word Hunter, Sentence Builder, Speed Round, and Word Master. The arena uses each group's own lesson vocabulary. Scores and responses save in browser localStorage and are included as `vocab_arena` rows in the CSV export. Future lessons 11–40 will automatically receive the same arena when approved vocabulary and lesson content are added. Lesson 1–5 activities are unchanged.

Files added: `vocab-arena.js`; changes in `index.html`, `script.js`, and `style.css`. When updating an existing project, copy all these files together, preserving your own extra images.
