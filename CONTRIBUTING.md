## Contributing to Tech Career Roadmaps

Thanks for taking the time to contribute!

This repository is a **documentation-first** project: most contributions are edits to Markdown files (roadmaps) and repository docs.

---

## Quick start

### Prerequisites
- **Git** installed
- A **GitHub account**
- A text editor (Cursor, VS Code, etc.)

### Fork + clone
1. Fork the repository on GitHub.
2. Clone your fork:

```bash
git clone https://github.com/<your-username>/career-roadmaps.git
cd career-roadmaps
```

3. Create a branch for your change:

```bash
git checkout -b my-change
```

---

## What you can contribute
- **Fix typos / grammar / broken Markdown formatting**
- **Improve a roadmap** (clarity, missing tools, better progression steps)
- **Add a new roadmap** for a career that isn’t covered yet
- **Standardize structure** across roadmaps (tables, headings, consistency)

If you’re brand new to open source, start with issues labeled **`good first issue`**.

---

## Repository structure (important)
- **Root**: `README.md` (project overview + list of careers), `LICENSE.txt`
- **One folder per career** (kebab-case): e.g. `software-developer/`
  - Each career folder contains a `README.md` roadmap.
  - Some folders also include `LICENSE.txt` (MIT).

---

## Editing an existing roadmap
1. Pick a career folder (example: `software-developer/`).
2. Edit its `README.md`.
3. Keep the section structure consistent:
   - Introduction
   - Key Skills
   - Educational Background
   - Technologies & Tools (table)
   - Career Roadmap (6 steps)
   - Tips for Advancement

### Content guidelines
- **Prefer concrete, actionable bullets** over generic advice.
- **Avoid vendor lock-in** where possible (mention alternatives).
- **Keep the “Career Roadmap” 6-step format** unless there’s a strong reason to change it.
- If you add links, prefer reputable sources (official docs, well-known communities).

---

## Adding a new career roadmap

1. Create a new folder at the repo root using **kebab-case**:
   - Example: `site-reliability-engineer/`

2. Add a `README.md` in that folder using the standard structure above.

3. Update the root `README.md`:
   - Add a row to the “Available Career Roadmaps” table with:
     - Career name
     - Folder name
     - Short description

4. (Optional) Add `LICENSE.txt` to the folder:
   - If you add it, it should match the root `LICENSE.txt` (MIT).

---

## Commit message guidance
Use clear, short commit messages. Examples:
- `Fix markdown fence in root README`
- `Improve ERP Consultant tools table`
- `Add roadmap for <Career Name>`

---

## Opening a Pull Request (PR)
1. Push your branch:

```bash
git push -u origin my-change
```

2. Open a PR on GitHub.

### PR checklist
- [ ] Your change is limited and focused (easy to review)
- [ ] Markdown renders correctly on GitHub
- [ ] If you added a career folder, you also updated the root table

---

## Code of Conduct
Be respectful and constructive in issues and PRs. (A dedicated `CODE_OF_CONDUCT.md` may be added later.)

