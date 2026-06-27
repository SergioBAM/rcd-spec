# WI-006 — Create Initial Project Planner Skill

## Status

Planned

## Purpose

Create the first AI Project Planner skill for RCD.

The skill should guide an AI agent to create RCD Plans and Work Items from a feature idea or implementation discussion.

## Problem

AI agents can produce inconsistent plans if they are not given a repeatable planning process.

RCD needs an initial skill that teaches an AI agent to act as a planning facilitator, not just a document generator.

## Output

Create:

```text
skills/project-planner/SKILL.md
```

## Scope

This Work Item includes:

- defining the purpose of the Project Planner skill
- requiring the agent to clarify the problem before creating files
- requiring the agent to define success and scope
- requiring the agent to create a Plan folder
- requiring the agent to create Work Item files
- reinforcing that plans start small and earn structure
- keeping the skill generic enough for multiple AI agents where possible

## Out of Scope

This Work Item does not include:

- implementation Work Item skill
- code review skill
- plan synchronization skill
- Zoho-specific integration
- Basecamp-specific integration
- GitHub automation

## Acceptance Criteria

- `skills/project-planner/SKILL.md` exists.
- The skill starts by helping the user clarify the problem, success definition, scope, and Work Items.
- The skill does not jump directly into generating documents.
- The skill treats the repository as the authoritative source of implementation knowledge.
- The skill creates lightweight plans by default.
- The skill avoids tool-specific assumptions where possible.

## Implementation Notes

The Project Planner skill should feel like an experienced technical lead helping shape work before execution.

It should not behave like a project manager, Scrum master, or ticket factory.
