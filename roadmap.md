# Comprehension Stack Roadmap

This repository maintains the conceptual ecosystem map. Component implementation, release selection and integration qualification belong to the owning repositories and the [Open Control Stack hub](https://github.com/cogno-us/cognous-open-control-stack).

## Maintenance scope

| Work | Completion criterion |
| --- | --- |
| Keep the project map current | Project names and repository links resolve to the owning projects; responsibilities remain distinct. |
| Keep claims attributable | Each implementation or maturity claim points to a named source and its scope; missing evidence stays unknown. |
| Add bounded examples when useful | Examples label guidance, evidence, authority, execution and verification separately; conceptual examples are not presented as executed workflows. |
| Preserve independent adoption | Optional reasoning and sensemaking projects are not represented as prerequisites for the selected runtime chain. |
| Maintain historical context | Earlier architecture and roadmap decisions remain available through version history. |

## Component work and maturity

Use the [README project map](README.md#project-responsibilities) to reach each component's current documentation and issue queue. Do not infer that a component lacks a schema, tests or safety controls from this repository's earlier roadmap.

For runtime implementation, inspect the hub's [selected component lock](https://github.com/cogno-us/cognous-open-control-stack/blob/main/component-lock.json) and [support ledger](https://github.com/cogno-us/cognous-open-control-stack/blob/main/docs/release-status.md). A component merge, a selected version, an executed qualification and a deployment are separate milestones. This repository assigns no aggregate production-readiness label.

The [historical roadmap](https://github.com/cogno-us/comprehension-stack/blob/eec41d965d0f2cdb5c1e72db2204eb6c3320ae6f/roadmap.md) included labels such as “early stage,” “minimal implementation” and “hardened fork,” along with proposed component tasks. Those are historical planning statements, not the current component backlog or proof of hardening.

## Out of scope here

Runtime enforcement code, credential configuration, authority grants, component lock changes, duplicated compatibility contracts and deployment approval remain outside this conceptual repository. Cross-project examples should link to actual qualification evidence when available and state unexecuted or unsupported portions explicitly.
