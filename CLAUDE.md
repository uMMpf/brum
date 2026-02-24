# Košarka Brum Brum

## Architecture
- Single file app: everything in `index.html`
- React 18 + Babel + Tailwind CSS (all via CDN, no build step)
- Google Sheets backend via Apps Script, localStorage as fallback

## Rules
- Do NOT change the SCRIPT_URL value
- Do NOT expose real names in commit messages or PR descriptions
- Keep everything in a single index.html file
- Template literals must use backticks (Babel transpilation)
- Preserve mobile-friendly touch targets (min-h-12, w-5 h-5 checkboxes)
- UI language is Croatian
- Names are anonymized in storage — real names only live in NAME_MAP
