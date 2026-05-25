```markdown
# Apps

A curated collection of automation projects built with AI assistance.
Each project lives as an independent repository, organized here through Git submodules.

> Every project was developed with AI unless explicitly marked otherwise.

---

## Projects

| # | Project | Description | AI | Stack |
|:-:|---------|-------------|:--:|-------|
| 1 | [notepad-autocli](https://github.com/GustavoNaldoni1/notepad-autocli) | CLI automation for Windows 11 Notepad — save, open, page setup, tab detection, and popup handling via pyautogui | Yes | Python · pyautogui · PowerShell · ctypes |

---

## Structure

```text
apps/
├── README.md
├── .gitmodules
└── notepad-autocli/
    └── Notepad Automation CLI
```

Each directory is a standalone repository linked as a Git submodule, maintaining its own history, dependencies, and license.

---

## Submodules

| Submodule | Repository | Status |
|------------|------------|:------:|
| notepad-autocli | [GustavoNaldoni1/notepad-autocli](https://github.com/GustavoNaldoni1/notepad-autocli) | Active |

---

## Clone with Submodules

```bash
git clone --recurse-submodules https://github.com/GustavoNaldoni1/lab-automations.git
```

---

## Adding a New Automation

```bash
cd lab-automations
git submodule add https://github.com/GustavoNaldoni1/your-automation.git
git commit -m "Add your-automation submodule"
git push
```

---

## Convention

- All projects must be added as Git submodules pointing to their own repositories
- Projects not built with AI are marked with `No` in the `AI` column
- Each submodule maintains its own `README.md` and `LICENSE`
- Automations should target a specific Windows/Linux/macOS tool or workflow

---

## License

Each submodule has its own license.
This repository serves as an organizational index only.
```