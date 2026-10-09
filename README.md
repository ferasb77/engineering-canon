# Engineering Canon

Shared, version-controlled engineering standards for AI-assisted development across projects.

## Canon

- [Current master: AI Engineering Canon](AI_ENGINEERING_CANON.md)
- [Preserved baseline: v1.1](versions/AI_ENGINEERING_CANON_v1.1.md)

**Current version:** 1.1 (proposed)  
**Status:** Draft for pilot adoption, not yet enforced by project repositories.  
**First pilot candidate:** CapabilityOS.

## Purpose

Set consistent expectations for planning, bounded implementation, testing, independent verification, security, permissions, approvals, agent orchestration, and durable engineering knowledge. The principles apply regardless of whether a project uses OpenAI Codex, Google Antigravity, or another coding agent.

## Adoption

1. Audit each project's existing architecture, `AGENTS.md`, rules, skills, tests, and deployment controls.
2. Identify gaps and conflicts with the canon before editing project instructions.
3. Pilot in one repository using a bounded, reversible task.
4. Record evidence and receive owner approval before declaring any practice adopted.
5. Keep tool-specific adapters minimal; do not copy the entire canon into every project's agent context.

## Change control

- The root `AI_ENGINEERING_CANON.md` is the working master.
- The `versions/` folder preserves approved historical versions and baselines.
- Proposed improvements should describe the reason, risk, validation plan, and affected projects.
- Updating this repository does **not** automatically update instructions or permissions in other repositories.
- Agents may propose changes but must not silently revise governing standards.

## Security

Never store credentials, tokens, private customer data, or production secrets in this repository. Review proposed changes before publishing: **this repository is public**.
