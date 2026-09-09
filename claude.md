# Project Context: Single-File Vanilla HTML/JS Weight Tracker App

## Tech Stack & Architecture
- **Stack:** Pure HTML5, CSS3, and Vanilla JavaScript (ES6+) contained entirely within a single html file. 
- **Constraints:** NO frameworks, NO build tools, and **ABSOLUTELY NO CDN LINKS**.
- **Data & State:** Uses LocalStorage keys only with JSON export/input
- **Assets:** If icons are needed, fetch the SVG data and bake the raw SVG code directly into the HTML markup. Must be consistent style. Only use icons if needed, do not clutter. 

## Token Efficiency & Coding Guidelines
- **Concise Responses:** Provide direct code blocks or diffs. Skip conversational filler, explanations, or lectures.
- **Targeted Edits:** Modify only the requested lines or sections. Do not rewrite whole files unless necessary.
- **No Workspace Scanning:** This is a single file application, with a JSON for export/import.

- Act as an expert coding partner, not an employee.
- Ask me when critical decisions need to be made.
- Ask me if i have a preference on something medium to big, or something that will impact scaling in the future. I have a laymans knowledge, so don't ask me critical software development questions. 
- I trust you with the smaller things.
  Ensure to update the changelog in the dev console. Keep entries very brief and high level, a sentence per change. 

## Changelog & Versioning
- Every change gets a CHANGELOG entry and an APP_VERSION bump. No exceptions.
- Version format is X.YYY — each digit is a size tier, bump exactly one per change:
  - `+0.001` bug fix
  - `+0.010` tiny tweak
  - `+0.100` small feature
  - `+1` large feature

## Git Workflow
- I don't use git/PRs manually. After pushing your branch, open a pull request and merge it into the main branch yourself — don't ask me to do it or wait for my confirmation.
- Only skip the auto-merge and ask me first if something seems risky or destructive (e.g. it could break the app, lose data, or you're unsure about a decision).
