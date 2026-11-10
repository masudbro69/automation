# automation

Automation workspace featuring **REA (Reverse Engineer Anything)** agent skills and tooling, alongside the Jarvis AI Agent OS Android archive.

## Contents

- **`.agents/skills/` & `.claude/skills/`** — Ready-to-use REA agent skills automatically discovered by Claude Code, Codex, Cursor, Gemini CLI, and OpenCode:
  - [`reverse-engineer-anything`](.agents/skills/reverse-engineer-anything/SKILL.md) — Reverse engineer native binaries, Android APKs, Electron/JavaScript bundles, firmware, and runtime behavior with evidence-backed analysis
  - [`rea-analysis-optimization`](.agents/skills/rea-analysis-optimization/SKILL.md) — Analysis speed and evidence workflow optimization
  - [`rea-tool-design`](.agents/skills/rea-tool-design/SKILL.md) — REA MCP tool design guidelines
  - [`rea-ci-tests-audit`](.agents/skills/rea-ci-tests-audit/SKILL.md) — Conformance and CI verification audits
  - [`rea-changelog-update`](.agents/skills/rea-changelog-update/SKILL.md) — Release and changelog workflow
- **`rea/`** — Full clone of [`morluto/rea`](https://github.com/morluto/rea) (v6.8.0), including the MCP server, CLI (`rea` / `rea-agents`), native/Android/Ghidra/Hopper/JADX bridges, and documentation
- **`jarvis-ai-agent-os.zip`** — Jarvis AI Agent OS Android project archive

## Quick Start (REA MCP Setup)

The bundled `SKILL.md` files in `.agents/skills/` and `.claude/skills/` work out of the box when opening this repository in a supported coding agent. To also register the local REA MCP server on your machine:

```bash
npx rea-agents setup
```

See [`rea/README.md`](rea/README.md) for full documentation, guides, and supported analysis engines.
