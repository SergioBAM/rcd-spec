# Repository-Centric Development (RCD)

Repository-Centric Development (RCD) is a lightweight software development methodology for small to medium software teams building focused business applications.

RCD is built on one simple principle:

> **The repository is the authoritative source of implementation knowledge.**

Communication tools capture discussion. Project management tools track progress. The repository stores the implementation plan, technical decisions, and executable work specifications that developers and AI agents use to build the software.

RCD is designed to improve planning consistency without creating documentation bloat.

## The Golden 5 Rules

1. Every meaningful feature starts with a plan.
2. Plans live beside the code.
3. Work Items are executable specifications.
4. Project management tools track execution; Git stores implementation knowledge.
5. Only document complexity that exists.

## Core Idea

A plan starts small and earns structure as complexity appears.

A small change may only need:

```text
docs/plans/change-password/
├── README.md
└── work-items/
    └── WI-001-update-password-validation.md
```

A larger feature may need:

```text
docs/plans/admin-authentication/
├── README.md
├── architecture.md
├── decisions.md
└── work-items/
    ├── WI-001-configure-entra-app-registration.md
    ├── WI-002-implement-login-flow.md
    └── WI-003-protect-admin-api.md
```

The amount of documentation should match the amount of uncertainty.

## Repository Structure

```text
spec/        The RCD methodology and standards
templates/   Reference templates for plans and work items
examples/    Small example implementations of the methodology
skills/      AI agent skills that apply RCD
```

## Start Here

Read these documents in order:

1. [Philosophy](spec/01-philosophy.md)
2. [Repository Layout](spec/02-repository-layout.md)
3. [Plans](spec/03-plans.md)
4. [Work Items](spec/04-work-items.md)

## Status

RCD is currently a draft methodology under active development.

The current focus is keeping the process simple enough to use on real-world business application projects while still being structured enough for repeatable human and AI-assisted development.
