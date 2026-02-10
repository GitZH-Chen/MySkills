# MySkills

## Quick Update / Install

Use `update-skill.sh` to install or update skills from GitHub quickly.

Typical usage:

```bash
# Default: install/update ai-paper-writing from GitZH-Chen/MySkills (main)
./update-skill.sh

# Specify repo/path/ref
./update-skill.sh --repo GitZH-Chen/MySkills --path ai-paper-writing --ref main
```

It installs when missing, and backs up then updates when already installed.

Personal Codex skills for high-quality AI research.

## `ai-paper-writing`

Writing assistant for AI top-tier conference/journal papers in LaTeX.

- Drafting and polishing
- Grammar check
- BibTeX cleanup (`bib check`)
- Rebuttal

Path: `ai-paper-writing/`

### Usage

```md
Use $ai-paper-writing.
...
```

### File Conventions

As defined in `ai-paper-writing/agents/openai.yaml`:

- `./Aux`: manuscript support materials
- `./Aux/Rebuttal`: rebuttal materials
- `./Aux/Rebuttal/{venue}-Reviews.md`: review file (for example `ICLR26-Reviews.md`)
- `preamble.tex`: predefined LaTeX macros
- `xx.bib`: bibliography source (`\bibliography{xx.bib}`)
- `Aux/Guidelines.pdf`: optional formatting guideline
