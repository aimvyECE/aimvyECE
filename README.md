# aimvyECE

### Exploring energy systems, reproducible analysis and responsible AI tooling

I build small, inspectable software experiments at the intersection of energy,
data and creative technology. My aim is to turn ambitious questions into working
prototypes with explicit assumptions, tests and documented limits.

## Current engineering portfolio

| Project | Focus | What works today |
| --- | --- | --- |
| [Microgrid Dispatch Lab](https://github.com/aimvyECE/microgrid-dispatch-lab) | Energy systems and optimisation | Linear optimisation and battery sensitivity sweeps; matched baselines and reproducible CSV/JSON experiments |
| [Energy Evidence](https://github.com/aimvyECE/energy-evidence) | Traceable energy reporting | Reporting calendars, coverage and missing-month checks, factor provenance, HTML/JSON reports |
| [Creative Vault Map](https://github.com/aimvyECE/creative-vault-map) | Creative archives and local-first tooling | Read-only Markdown/Obsidian link maps, isolated notes, exact duplicates and unresolved references; offline, synthetic examples |
| [Avatar Preflight Lab](https://github.com/aimvyECE/avatar-preflight-lab) | Responsible voice and lip-sync workflows | Declaration validation, deterministic fingerprints and change review; no model inference |
| [Context Budget Lab](https://github.com/aimvyECE/context-budget-lab) | Provider-neutral evidence retrieval | Local cited context bundles, excerpt budgets, duplicate suppression and stale-source checks; no language model inference |
| [Agent Change Ledger](https://github.com/aimvyECE/agent-change-ledger) | Human-supervised agent edits | Hash-checked proposals, diff preview and journaled undo; optional Ollama adapter not tested with real inference |
| [Identity Studio](https://github.com/aimvyECE/identity-studio) | Consent-aware fashion visualization | Local references, edit briefs, result comparison and human review; optional Qwen adapter tested with doubles, not real images |
| [Routine OS Local](https://github.com/aimvyECE/routine-os-local) | Local-first organisation | Editable daily lists, microsteps, notes and JSON export; public v0.2 has no automatic recurring routines or AI engine |

## Reproduce, inspect, challenge

| Project | Automated checks | Start here |
| --- | --- | --- |
| Energy optimisation | [![tests](https://github.com/aimvyECE/microgrid-dispatch-lab/actions/workflows/tests.yml/badge.svg)](https://github.com/aimvyECE/microgrid-dispatch-lab/actions) | [Experiment guide](https://github.com/aimvyECE/microgrid-dispatch-lab/blob/main/docs/EXPERIMENTS.md) |
| Energy reporting | [![tests](https://github.com/aimvyECE/energy-evidence/actions/workflows/tests.yml/badge.svg)](https://github.com/aimvyECE/energy-evidence/actions) | [Validation method](https://github.com/aimvyECE/energy-evidence/blob/main/VALIDATION.md) |
| Creative archives | [Tests and workflow status](https://github.com/aimvyECE/creative-vault-map/actions) | [Quick start and limitations](https://github.com/aimvyECE/creative-vault-map#try-the-synthetic-example) |
| Avatar preflight | [Tests and workflow status](https://github.com/aimvyECE/avatar-preflight-lab/actions) | [Audit walkthrough](https://github.com/aimvyECE/avatar-preflight-lab/blob/main/docs/AUDIT.md) |
| Context tooling | [Tests and workflow status](https://github.com/aimvyECE/context-budget-lab/actions) | [Synthetic benchmark and limits](https://github.com/aimvyECE/context-budget-lab#a-small-honest-benchmark) |
| Agent edit boundary | [Tests and workflow status](https://github.com/aimvyECE/agent-change-ledger/actions) | [Local quick start](https://github.com/aimvyECE/agent-change-ledger#try-it-without-a-model) |
| Identity workbench | [Tests and workflow status](https://github.com/aimvyECE/identity-studio/actions) | [Verification limits](https://github.com/aimvyECE/identity-studio/blob/main/docs/VERIFICATION.md) |
| Organisation toolbox | [Tests and workflow status](https://github.com/aimvyECE/routine-os-local/actions) | [Public-version scope](https://github.com/aimvyECE/routine-os-local#not-implemented--not-claimed) |

The repositories include local quick starts, synthetic fixtures, regression tests
and contribution guidance. A passing test suite checks implemented behavior,
not field validity or production readiness.

### Work in review and upstream exploration

[Energy Evidence PR #1](https://github.com/aimvyECE/energy-evidence/pull/1)
adds year comparisons over matching calendar months, with missing periods kept
explicit. It is currently a draft proposal, not a feature merged into `main`;
matching months does not establish weather-normalized or verified savings.

My public account also contains unmodified forks of upstream Crafting Apps.
Those applications are the work of their original authors, not portfolio projects
created here. A fork is a reference copy, not evidence of a contribution or of a
collaborating community. Upstream code, asset and branding licences still apply.

**Technical focus:** Python, linear programming (SciPy/HiGHS), structured data
validation, deterministic reporting, CLI interfaces and continuous integration, and browser-side JavaScript.
These are technologies exercised in this portfolio, not a claim of expert-level
experience with every related system.

## Questions I want to investigate

- How can energy decisions balance cost, emissions and operational constraints?
- How can data tools make assumptions and anomalies visible rather than hide them?
- What makes an AI-assisted workflow reproducible, useful and safe enough to extend?
- How can technical tools support creative exploration without losing provenance?

## Working principles

- Start with a reproducible baseline, then add complexity only when it earns its place.
- Distinguish synthetic demonstrations from field evidence and production systems.
- Credit upstream projects and review code, model and dataset licences separately.
- Keep private information and credentials out of public repositories.
- Document AI assistance, limitations and unfinished work.

These are early prototypes, not claims of deployed customer systems or established
community adoption. Contributions that improve correctness, tests, accessibility
or documentation are welcome.
