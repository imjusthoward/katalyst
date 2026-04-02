# Katalyst

Katalyst is the long-term internal systems platform for distributed tutoring and operations teams.

It stays separate from Pulse:

- Pulse = public-facing convention companion
- Katalyst = internal systems platform

## Current focus

- tutoring operations in Japan
- roughly 100 students and tutors
- coordination, scheduling, continuity, and execution support

## What is in this repo

This repo is intentionally a scaffold, not a full implementation.

Included here:

- architecture framing
- module map
- low-fidelity dashboard direction
- tutoring deployment requirements
- backlog and component inventory

## Start here

- [Architecture](./docs/architecture.md)
- [Module map](./docs/module-map.md)
- [Dashboard wireframe](./docs/dashboard-wireframe.md)
- [Tutoring deployment requirements](./docs/tutoring-deployment.md)
- [Component inventory](./docs/component-inventory.md)
- [Backlog](./docs/backlog.md)

## Product principles

- internal-first
- modular
- operational
- continuity-aware
- boring in a good way
- useful before elegant

## Suggested next build order

1. Auth and organization model
2. People directory and role membership
3. Resource and announcement layer
4. Project and task execution layer
5. Tutoring operations dashboard
6. Continuity notes and handover history
