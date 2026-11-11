# Raza7x Security Skills

A collection of five security skills for AI coding agents — practical, workflow-driven guidance for finding, fixing, and responding to security issues.

## Skills

- **bug-bounty-hunting** — Hunt vulnerabilities on authorized bug bounty programs and write reports that survive triage.
- **secret-management** — Manage the full lifecycle of secrets, from detection and storage to rotation and leaked-secret response.
- **incident-response** — Run a security or production incident end to end, from declaration to blameless postmortem.
- **api-security-audit** — Audit and test REST, GraphQL, and webhook APIs for security flaws, with reproducible proof-of-concept requests.
- **supply-chain-security** — Secure the software supply chain from dependency to deployed artifact, including SBOMs and build provenance.

## Install

```bash
npx skills add devilking7x/raza7x-security-skills
```

## How to use

1. Install the skills with the command above (or copy the `skills/` directory into your agent's skills folder).
2. When your task matches a skill — starting a bounty hunt, adding a credential, responding to an incident, auditing an API, or adding a dependency — invoke that skill and follow its workflow.
3. Each skill lives at `skills/<skill-name>/SKILL.md` with YAML frontmatter (`name`, `description`) and sections for Overview, When to Use, Process, Common Rationalizations, Red Flags, and Verification.
4. Validate the collection any time with `python3 scripts/validate-skills.py` (Python standard library only, no dependencies).

## About

This is original work by **Mohd Raja (Raza7x)** — the five security skills in this repository were written by him for AI-assisted security work. Licensed under the MIT License; see [LICENSE](LICENSE).
