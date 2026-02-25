# Bruksanvisningar – Project Instructions

## Language Rules

- **Always extract and use only the Swedish section** from multilingual manuals/PDFs.
- If Swedish is not present, fall back to **English only**.
- Never include content in other languages (Danish, Norwegian, Finnish, etc.) in the generated guides.

## Project Structure

- `index.html` – GitHub Pages landing page listing all guides
- `*-guide.html` – Individual interactive HTML guides per product
- `*.pdf` – Source manuals (not committed to git)

## Guide Creation

- Each guide is a single self-contained HTML file with Swedish content
- Follow the style of existing guides (advancedtacker-guide.html, poolvarmepump-guide.html)
- After creating a guide, update `index.html` and `README.md`
- Create a PR to GitHub after each new guide

## Workflow

1. Extract Swedish content from PDF
2. Create `<productname>-guide.html`
3. Update `index.html` with new card
4. Update `README.md`
5. Commit and push on a feature branch
6. Create PR to master
