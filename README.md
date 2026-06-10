<h1 align="center">dzylab</h1>

<p align="center">
  <b>Open-source discipline tools for AI-assisted development.</b><br>
  <i>Verify artifacts, not declarations.</i>
</p>

---

AI agents — and people — are optimistic. They mark work "done" before it is: a plan gets skipped,
tests never run, docs go stale, a secret slips into a commit. I build small, dependency-free tools
that make that impossible. Completion becomes **evidence**, not a declaration.

## Projects

### 🛡️ [KRONOS](https://github.com/dzylab/kronos)

A workflow engine for [Claude Code](https://claude.com/claude-code). Every task runs
**PLAN → CODE → TEST → DOCS → COMMIT**, and a git commit-gate hook verifies the *facts*, not the
checkboxes — you can't fake your way past it.

[![stars](https://img.shields.io/github/stars/dzylab/kronos?style=flat&color=00b0ff)](https://github.com/dzylab/kronos)
![license](https://img.shields.io/github/license/dzylab/kronos?color=blue)

### 🚦 [KRONOS CI](https://github.com/dzylab/kronos-ci)

A pull-request discipline gate for CI — and any editor. It **runs your tests itself** (instead of
trusting a log), scans for leaked secrets, and guards your main branch. Ten checks, zero dependencies,
works on GitHub / GitLab / locally / Cursor / Windsurf — anywhere git lives.

[![stars](https://img.shields.io/github/stars/dzylab/kronos-ci?style=flat&color=00b0ff)](https://github.com/dzylab/kronos-ci)
![license](https://img.shields.io/github/license/dzylab/kronos-ci?color=blue)

## Principles

- **Verify, don't trust.** Completion is evidence: a real test run, a real diff, a real artifact.
- **Zero dependencies.** Python standard library and git — nothing to `pip install`.
- **Honest scope.** A discipline gate, not a security boundary — each tool states exactly what it does and does not do.
- **Open forever.** GPL-3.0 — use it, fork it, improve it.

---

<p align="center"><i>No roadmap, no guarantees — shared because it might be useful to others too.</i></p>
