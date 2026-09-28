# skillbox

My toolbox of skills for coding agents

Side project, maintained when I have time.

## What it does

- Each skill is a folder with a single SKILL.md
- YAML frontmatter: name + when-to-use description
- Versioned like code: review changes in PRs
- Concrete instructions, output formats and examples
- Drop-in compatible with ~/.claude/skills

## Install

```bash
git clone <this repo>
cp -r skills/* ~/.claude/skills/
```

## Examples

```bash
# skills trigger automatically on matching tasks
# or invoke directly: /code-review
```

## Project structure

```text
├── .github/
│   └── dependabot.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── skills/
│   ├── code-review/
│   │   └── SKILL.md
│   ├── commit-message/
│   │   └── SKILL.md
│   ├── refactor-plan/
│   │   └── SKILL.md
│   └── test-writer/
│       └── SKILL.md
├── .gitignore
├── CHANGELOG.md
└── CONTRIBUTING.md
```
