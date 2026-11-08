# AGENTS.md - Developer & AI Agent Guide for awesome-wayland 🤖

## 🎯 Repository Overview
**awesome-wayland**: A curated list of Wayland resources. Please investigate these projects on your own before fully committing to them! This repository is a hard fork of natpen/awesome-wayland since it was archived on Oct. 17, 2023.

---

## 🏗️ Repository Architecture
Key directories and entrypoints: `.github/, LICENSE, README.md`.

### Tech Stack & Runtime
- **Category:** Documentation, Curated System Catalog, or Metadata Repository
- **Format:** Markdown & System Configs

## ⚙️ Verification Instructions
- Validate all Markdown links, relative anchors, and header hierarchies.
- Ensure UTF-8 clean encoding with zero corrupted characters or broken links.

---

## 🛡️ Coding & Safety Guidelines for Autonomous Agents

1. **Documentation Integrity:** Preserve all existing docstrings, header comments, and licensing banners. Never delete context unless specifically instructed.
2. **Zero Hardcoded Secrets:** Never embed API keys, OAuth tokens, personal access tokens, or sensitive credentials in committed files. Read credentials exclusively from environment variables or secure credential paths.
3. **Git Hygiene:**
   - Do not force-push (`git push --force`) or execute destructive resets.
   - Never modify root git configurations or harness infrastructure outside task scope.
   - Keep git diffs atomic, focused, and verified before committing.
4. **Agent Workflow Protocol:**
   - **Plan:** Inspect codebase architecture and dependencies before editing.
   - **Act:** Make minimal, clean, high-precision changes.
   - **Verify:** Run the appropriate verification commands listed above.
   - **Reflect:** Confirm zero regressions and review `git diff`.

---
*Maintained by Ayyappa Pravin • Built for Antigravity, Claude, Cursor & Autonomous AI Agents.*
