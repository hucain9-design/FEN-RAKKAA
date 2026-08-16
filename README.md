# Fen Rakkaa — Assignment Defence Portal

PTMT9002 Strategic Project Development · Hussain Shaany S2610358

A single-page portal holding the FINAL strategic project proposal, the defence
companion, the 8-slide defence presentation (with speaker notes) and the
downloadable deliverables, plus an AI defence examiner.

## Structure
- `index.html` — the portal (Overview · Proposal · Defence Companion · Presentation · Ask AI · Downloads)
- `presentation.html` — the standalone slide deck (arrow keys to navigate, toolbar to print to PDF)
- `downloads/` — the submitted PDF, PPTX and DOCX
- `_ds/` — the Modernist design system stylesheet
- `support.js`, `deck-stage.js` — runtime for the page and the deck

## Publish with GitHub Pages
1. Repo → Settings → Pages
2. Source: "Deploy from a branch", Branch: `main`, Folder: `/ (root)` → Save
3. The site appears at `https://hucain9-design.github.io/FEN-RAKKAA/`

## Note on the AI examiner
The "Ask AI" tab uses an AI service provided by the design environment the site
was built in. On GitHub Pages that service is not present, so the chat shows a
polite error there. Everything else — proposal, companion, presentation and
downloads — works fully as a static site.
