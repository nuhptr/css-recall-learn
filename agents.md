# Repository Guidelines (`agents.md`)

## Project Overview

`css-recall-learn` is a hands-on CSS study repository following Future Fullstack's **CSS Full Course Tutorial for Beginners** (Part 1 & Part 2: 12 modules, 64 lessons) using plain HTML5 and CSS3 with no build tooling. It pairs with `html-recall-learn` and builds toward the **Quill** multi-page marketing website.

## Directory & Naming Conventions

- **Flat Alphabetical Modules**: All 12 modules live directly under `app/` using descriptive, prefix-free kebab-case names whose natural alphabetical order matches the course sequence:
  1. `applying-css`
  2. `formatting-text`
  3. `handling-selectors`
  4. `learning-the-box-model`
  5. `measuring-with-units`
  6. `native-css-functions`
  7. `organizing-with-flexbox`
  8. `page-grid-layouts`
  9. `responsive-design`
  10. `stacking-and-positioning`
  11. `transitions-and-shadows`
  12. `using-css-frameworks`
- **Lesson Folders**: Use lowercase kebab-case mirroring the chapter titles. Each lesson folder contains `index.html` and `style.css` (plus optional reference screenshots/assets). Do **not** add `.gitkeep` placeholder files.
- **README Synchronization**: Keep `README.md` (Table of Contents, Learning Roadmap, Curriculum, and Project Structure) in sync when adding, renaming, or completing lessons. Do **not** add video timestamps or a Resources section to `README.md`.

## Formatting & Code Style

- Follow `.prettierrc` (`tabWidth: 4`, `printWidth: 100`, `singleQuote: false`, `jsxSingleQuote: false`, `semi: false`, `htmlWhitespaceSensitivity: "ignore"`, `bracketSameLine: true`) and `.prettierignore` (`*.md`).
- After editing HTML, CSS, or JSON files, verify formatting with:
  ```bash
  npx -y prettier --check .
  ```
- Keep exercises vanilla HTML5 and CSS3; external CSS frameworks (Bootstrap, Tailwind CSS) are scoped only to `app/using-css-frameworks/`.

## Git & Release Workflow

- **Conventional Commits v1.0.0**: Use `<type>[optional scope]: <description>` (imperative, lowercase, no trailing period) and include:
  ```text
  Co-authored-by: Gemini <gemini@google.com>
  ```
- **Simplified Git-Flow**:
  - `main` is the only long-lived branch and must remain clean and release-ready. Do not create a `dev` or `develop` branch.
  - Use short-lived kebab-case branches from `main` (`feature/*`, `fix/*`, `hotfix/*`, `docs/*`, `chore/*`, `release/*`) and merge via Pull Request with a structured description (Summary / Context, Key Changes, Verification / Test Plan, Notes / Risks).
  - Do **not** automatically delete merged branches (local or remote).
- **Releases & Push Policy**:
  - Tag releases on `main` using SemVer (`vMAJOR.MINOR.PATCH`), keeping both Git tag names and GitHub Release titles strictly to the version number only (e.g., `v1.0.0`).
  - Only run `git push` when the user explicitly requests it.
