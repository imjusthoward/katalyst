# Katalyst

Internal systems platform for distributed tutoring and operations teams.

- **Pulse** = public-facing convention companion
- **Katalyst** = internal operations and coordination platform

## Scope

- Tutoring operations across Japan (~100 students and tutors)
- Scheduling, coordination, continuity, and execution support
- Modular — each domain (people, resources, tasks, tutoring) ships independently

## Documentation

- [Architecture](./docs/architecture.md)
- [Module map](./docs/module-map.md)
- [Dashboard wireframe](./docs/dashboard-wireframe.md)
- [Tutoring deployment requirements](./docs/tutoring-deployment.md)
- [Component inventory](./docs/component-inventory.md)
- [Backlog](./docs/backlog.md)

## Build order

1. Auth and organisation model
2. People directory and role membership
3. Resource and announcement layer
4. Project and task execution layer
5. Tutoring operations dashboard
6. Continuity notes and handover history

## Principles

Operational before elegant. Each module ships when useful, not when complete.