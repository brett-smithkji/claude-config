# claude-config

Agent instruction configs I sync across projects

Started as a weekend hack, grew on me.

## Features

- Kept short: agents read every token every time
- Per-archetype CLAUDE.md templates (api / cli / lib)
- Global coding-style rules in rules/
- Review checklist baked into instructions

## Installation

```bash
# pick a template
cp templates/CLAUDE.api.md your-project/CLAUDE.md
```

## How to use

```bash
# Claude Code reads CLAUDE.md from the repo root automatically
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── rules/
│   ├── review.md
│   └── style.md
├── templates/
│   ├── CLAUDE.api.md
│   └── CLAUDE.cli.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
└── SECURITY.md
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas
