---
name: devops-infrastructure-studio
description: "Coordinate end-to-end devops & infrastructure studio workflows from one master skill, loading specialist playbooks as needed."
---

# DevOps & Infrastructure Studio

## Mission
Create repeatable and observable infrastructure workflows with least privilege, deployment safety, cost awareness, and recovery planning.

## Use this skill when
The user asks to create, extend, analyze, or deliver a devops & infrastructure studio project and expects one coordinated workflow rather than manually selecting individual specialist skills.

## Invocation contract
This is the only selectable skill in this repository. The specialist modules below are internal reference playbooks, not separate skills to invoke. Start from the user's brief, load only relevant references, and coordinate the complete workflow.

## Required inputs
Infer what is clear from the user's brief and repository. Identify only essential missing information. Typical inputs include goal, target users/platform, scope, references, constraints, existing stack, output format, budget, deadline, and acceptance criteria. Ask one concise clarification only when a missing fact blocks safe or correct execution; otherwise state reasonable assumptions and proceed.

## Operating protocol
1. Inspect the current repository, project instructions, files, configuration, and existing conventions before editing.
2. Translate the request into deliverables, explicit assumptions, non-goals, acceptance criteria, and risks.
3. Build a short phased plan. Prefer a working vertical slice over broad scaffolding that does not run.
4. Read the relevant internal references from the map below. Do not load unrelated modules or duplicate work.
5. Discover the actual tools, dependencies, APIs, providers, and runtime capabilities available in the current environment. Never invent tool names, provider availability, model IDs, endpoints, test results, or completed outputs.
6. Implement the requested outcome in the existing project. Preserve working behavior and avoid unnecessary rewrites.
7. Validate with the strongest available automated and manual checks. Fix issues found, then re-run the relevant checks.
8. Report exact files changed, commands/tests executed and results, deliverables created, unresolved issues, and what remains unverified.

## Internal specialist reference map
- `devops-engineer` — read `references/devops-engineer.md` when this capability is needed.
- `docker-engineer` — read `references/docker-engineer.md` when this capability is needed.
- `cloud-engineer` — read `references/cloud-engineer.md` when this capability is needed.
- `cicd-engineer` — read `references/cicd-engineer.md` when this capability is needed.
- `distributed-systems-engineer` — read `references/distributed-systems-engineer.md` when this capability is needed.
- `performance-engineer` — read `references/performance-engineer.md` when this capability is needed.
- `human-centered-product-design` — read `references/human-centered-product-design.md` when this capability is needed.
- `design-quality-critic` — read `references/design-quality-critic.md` when this capability is needed.
- `product-experience-engineer` — read `references/product-experience-engineer.md` when this capability is needed.

## Coordinated workflow
1. Inspect application architecture, target environment, constraints, and current deployment process.
2. Define availability, latency, security, compliance, cost, and recovery objectives.
3. Design infrastructure topology, container strategy, networking, secrets, and identity boundaries.
4. Implement infrastructure and CI/CD as code using the project conventions.
5. Add health checks, logs, metrics, traces, alerts, and runbooks.
6. Test build, deployment, rollback, backup, restore, and failure handling.
7. Review IAM, exposed services, secrets, image provenance, and supply-chain risk.
8. Document costs, operational ownership, disaster recovery, and unresolved assumptions.

## Expected deliverables
- infrastructure architecture
- container and deployment configuration
- CI/CD pipeline
- observability and runbooks
- security, cost, and recovery review

## Quality gates
- Requirements map to implemented behavior or clearly documented non-goals.
- The project builds/runs with available dependencies, or blockers are stated with evidence.
- Tests cover critical user flows or critical subsystem invariants.
- Security, privacy, accessibility, performance, and failure states are considered where relevant.
- Documentation matches the delivered implementation.
- No capability is described as complete unless the corresponding artifact exists and has been checked.

## Human-centered quality requirement
For any user-facing interface, load the human-centered design, design critique, and product-experience references. Apply them as quality gates throughout the work, not as a last-minute decoration pass. The result should be distinctive and fit the product domain, not a generic AI template.


## Security, privacy, and rights
- Protect secrets and personal data. Never place API keys, access tokens, passwords, signing keys, or private credentials in source files, prompts, examples, or logs.
- Use only dependencies, media, datasets, and assets with verified rights and compatible licenses.
- Do not claim external APIs, models, services, or tools are configured unless verified in the current environment.

## Approval gates
Ask before paid API/service usage, production deployment, public publication, destructive changes, external account actions, large cloud jobs, or changes that can incur charges. Do not ask for approval for ordinary reversible local edits within the user's requested scope.

## Stop conditions
Stop and explain the blocker when required permissions, credentials, source material, tools, dependencies, or target hardware are unavailable. Continue with independent work where possible, but do not simulate unavailable external generation or claim a final build succeeded.

## Final response format
Summarize: outcome; key implementation; files/artifacts; validation results; required user actions; known limitations. Be explicit about partial completion.
