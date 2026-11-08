<div align="center">

<img src="https://raw.githubusercontent.com/levencode-labs/.github/main/assets/levencode-mark.png" width="112" alt="Levencode Labs logo" />

# Levencode Labs

**Thoughtful tools for working with code.**

Built with AI. Refined through engineering, testing, and review.

</div>

---

We build practical tools for developers and coding agents. The aim is simple: make complex code changes easier to understand, safer to carry out, and clearer to verify.

## Deploom

<img align="right" src="https://raw.githubusercontent.com/levencode-labs/.github/main/assets/deploom-mark.png" width="104" alt="Deploom logo" />

**Dependency upgrades with a clear plan.**

Deploom helps developers and coding agents plan dependency updates for JavaScript and TypeScript projects. It brings version choices, compatibility constraints, permitted changes, and unresolved evidence into one inspectable workflow.

- **Plan within boundaries.** Choose which dependencies may change and which version lines are acceptable.
- **Understand decisions.** See conflicts, blockers, and the reasons behind proposed versions.
- **Check the result.** Keep planning, installation, and runtime verification separate.

**[Get started](https://github.com/levencode-labs/deploom-mcp/blob/main/USERGUIDE.md)** · [Руководство на русском](https://github.com/levencode-labs/deploom-mcp/blob/main/USERGUIDE.ru.md) · [Latest release](https://github.com/levencode-labs/deploom-mcp/releases/latest)

### Projects

| Repository | What it does |
| :-- | :-- |
| <img src="https://raw.githubusercontent.com/levencode-labs/.github/main/assets/deploom-core-mark.png" width="28" height="28" alt="" /> [**Deploom Core**](https://github.com/levencode-labs/deploom-core) | Planning engine for dependency-version decisions, compatibility constraints, and explicit evidence. |
| <img src="https://raw.githubusercontent.com/levencode-labs/.github/main/assets/deploom-mcp-mark.png" width="28" height="28" alt="" /> [**Deploom MCP**](https://github.com/levencode-labs/deploom-mcp) | Agent-facing MCP server, structured upgrade plans, verification boundaries, and the optional `deploom-upgrade` Skill. |

<sub>Deploom is under active development. An upgrade plan is not an installed or runtime-verified migration; acceptance requires checks against the actual result.</sub>

---

## SelfReview

<img align="right" src="https://raw.githubusercontent.com/levencode-labs/.github/main/assets/selfreview-mark.png" width="104" alt="SelfReview logo" />

**Project conventions you can trace, approve, and check before code review.**

SelfReview is a local toolkit for JavaScript, TypeScript, and React/TSX. It turns project-specific review expectations into explicit, reusable checks: collect rule candidates from source code, agreements, and merge-request feedback; review and approve them; then apply supported rules through AST analysis, the CLI, and an ESLint adapter.

- **Respect project scopes.** Keep conventions separate for each codebase or share them across a team.
- **Approve deliberately.** Discovered patterns and review comments are rule candidates, not automatic policy.
- **Review before the review.** Check changed code and export conventions for agents and developers.

**[Get started](https://github.com/levencode-labs/selfreview/blob/main/USERGUIDE.md)** · [Руководство на русском](https://github.com/levencode-labs/selfreview/blob/main/USERGUIDE.ru.md) · [Repository](https://github.com/levencode-labs/selfreview)

<sub>SelfReview complements human code review. Unsupported or ambiguous conventions stay visible for manual review; AST checks do not replace project tests or runtime verification.</sub>
