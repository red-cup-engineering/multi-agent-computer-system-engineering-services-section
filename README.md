# Multi-Agent Computer System Engineering Services Section

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

**Engineering computer systems whose behavior involves multiple agents.**
This repository groups domain material and specialized component repositories
for composing agents into a system. It does not itself run a swarm, provide a
hosted agent service, or expose a root application.

## Where to begin

The actual root contains `content/` and `lib/` for this section's material,
plus a `services/` composition. Its current submodule is
[multi-agent computer platform engineering](services/multi-agent-computer-platform-engineering-services-section).
Follow that component's own README, package exports, and tests for
implementation-specific instructions and readiness claims.

For the **faculty packages that agents compose**, begin instead with the
[Agent Organization Engine](https://github.com/red-cup-engineering/agent-organization-engine).
The broader [Agent Computer System Engineering Services Section](https://github.com/red-cup-engineering/agent-computer-system-engineering-services-section)
explains the single-agent and multi-agent engineering boundaries.

## What exists today

This repository has **no tracked top-level `apps/` directory**. An earlier
introduction listed `apps/playing`, `apps/computing`,
`apps/socializing`, and `apps/organizing` as applications here; that was
an obsolete path inventory, not a working installation guide. The corresponding
faculty source must be located and verified in its actual owning repository.

The current submodule is a source composition. A checked-in pointer does not
establish that the child is deployed, that multiple agents are operational,
or that a proposed interaction has passed an independent conformance test.
Consult the owner's current Issues, pull requests, development branches,
and test evidence for those claims.

## Scope and boundaries

A multi-agent **computer system** specifies and composes the behavior of
several agents. The hosting/runtime **platform** and the behavior of each
single **agent computer system** are separately owned engineering subjects.
Do not treat this section's inventory as an API, a running platform, or an
authority grant to the agents it describes.
