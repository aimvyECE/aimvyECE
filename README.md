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
| [Avatar Preflight Lab](https://github.com/aimvyECE/avatar-preflight-lab) | Responsible voice and lip-sync workflows | Declaration validation, deterministic fingerprints and change review; no model inference |

## Reproduce, inspect, challenge

| Project | Automated checks | Start here |
| --- | --- | --- |
| Energy optimisation | [![tests](https://github.com/aimvyECE/microgrid-dispatch-lab/actions/workflows/tests.yml/badge.svg)](https://github.com/aimvyECE/microgrid-dispatch-lab/actions) | [Experiment guide](https://github.com/aimvyECE/microgrid-dispatch-lab/blob/main/docs/EXPERIMENTS.md) |
| Energy reporting | [![tests](https://github.com/aimvyECE/energy-evidence/actions/workflows/tests.yml/badge.svg)](https://github.com/aimvyECE/energy-evidence/actions) | [Validation method](https://github.com/aimvyECE/energy-evidence/blob/main/VALIDATION.md) |
| Avatar preflight | [Tests and workflow status](https://github.com/aimvyECE/avatar-preflight-lab/actions) | [Audit walkthrough](https://github.com/aimvyECE/avatar-preflight-lab/blob/main/docs/AUDIT.md) |

The repositories include local quick starts, synthetic fixtures, regression tests
and contribution guidance. A passing test suite checks implemented behavior,
not field validity or production readiness.

**Technical focus:** Python, linear programming (SciPy/HiGHS), structured data
validation, deterministic reporting, CLI interfaces and continuous integration.
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
