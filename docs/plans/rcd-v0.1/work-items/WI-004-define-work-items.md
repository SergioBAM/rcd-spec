# WI-004 — Define Work Items

## Status

Planned

## Purpose

Define what a Work Item is in RCD.

A Work Item is the smallest independently useful implementation specification in a Plan.

## Problem

Project management tickets are often too thin to guide implementation. They track work, but they do not reliably preserve the implementation context needed to complete that work.

RCD needs Work Items to be useful to both humans and AI agents. A developer should be able to read a Work Item and understand what needs to be done, why it matters, what is out of scope, and how completion will be verified.

## Output

Create `spec/04-work-items.md`.

## Scope

This Work Item includes:

- defining a Work Item
- explaining how Work Items differ from tickets
- defining the expected structure of a Work Item
- explaining what makes a Work Item too large or too small
- explaining when to split a Work Item
- defining acceptance criteria expectations
- explaining how Work Items relate to project management tools

## Out of Scope

This Work Item does not include:

- project management workflow
- status board configuration
- estimation
- story points
- sprint planning
- Git branching strategy

## Acceptance Criteria

- `spec/04-work-items.md` exists.
- The document defines a Work Item as an executable implementation specification.
- The document explains that Work Items are more detailed than simple project management tickets.
- The document explains that external tools may track Work Items but do not own their implementation knowledge.
- The document defines the minimum useful Work Item sections.
- The document explains when a Work Item should be split.
- The document avoids Scrum-specific terminology unless used for contrast.

## Implementation Notes

This is one of the most important parts of RCD.

Keep it direct. The goal is not to create large mini-PRDs for every task. The goal is to define enough context that work can be completed without hunting through chat, memory, and ticket comments.
