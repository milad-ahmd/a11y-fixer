> [!NOTE]
> **This skill now lives in the main collection: [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills/tree/main/skills/a11y-fixer)**. Please ⭐ star it there; that's where updates land first.
> Docs: **https://milad-ahmd.github.io/agent-skills/skills/a11y-fixer/** · Claude Code: `/plugin install all-skills --marketplace milad-ahmd/agent-skills`

<div align="center">

# ♿ a11y-fixer

**WCAG 2.2 AA audit that fixes accessibility issues in your code. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/a11y-fixer)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/a11y-fixer?style=social)](https://github.com/milad-ahmd/a11y-fixer)
![Category](https://img.shields.io/badge/category-Frontend-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/a11y-fixer/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- a11y-fixer
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/a11y-fixer /tmp/a11y-fixer
mkdir -p ~/.claude/skills && cp -r /tmp/a11y-fixer/skills/a11y-fixer ~/.claude/skills/
```

**Per project:** copy `skills/a11y-fixer` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/a11y-fixer/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Audit this app for accessibility and fix the issues
Make the signup form screen-reader friendly
```

The full workflow, rules and output format are in [`SKILL.md`](skills/a11y-fixer/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
