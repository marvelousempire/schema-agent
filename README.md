# Schema Agent

**Build the agent. Preserve the intent. Make the pattern reusable.**

Schema Agent is the reusable schema for creating AI agents the way this system builds them: purpose-first, rule-aware, feature-ticket driven, repo-native, journaled, modular, and reusable.

This repo is not one agent. It is the pattern for making agents.

## Purpose

Schema Agent defines how to create a new agent repo from the ground up.

It captures the structure, documents, rules, feature tickets, prompt stack, journals, templates, validation style, and maintenance habits that make an agent clear enough for humans and structured enough for future AI systems.

## Core Idea

An agent should not be only a prompt.

An agent should have:

```text
Intent
Purpose
Rules
Firing Order
Knowledge Sources
Feature Tickets
Templates
Journals
Validation
Release Memory
Repo Structure
```

## What This Schema Creates

A new agent built from this schema should include:

```text
README.md
ABOUT.md
PRD.md
LICENSE
repo-manifest.md
release-ledger.md
agents/{agent-name}/
agents/{agent-name}/system-prompt/
agents/{agent-name}/templates/
docs/
features/
features/tickets/
obsidian/
obsidian/journal/
tests/
```

## Agent-Building Rule

Every correction, tweak, instruction, and preference from the founder can become part of the agent schema when it improves repeatable behavior.

Small details may become durable rules.

## Start Here

- [About](ABOUT.md)
- [PRD](PRD.md)
- [Repo Manifest](repo-manifest.md)
- [Release Ledger](release-ledger.md)
- [Agent Schema](docs/agent-schema.md)
- [Agent Build Process](docs/agent-build-process.md)
- [Agent Folder Standard](docs/agent-folder-standard.md)
- [Feature Ticket Pattern](docs/feature-ticket-pattern.md)
- [Firing Order Pattern](docs/firing-order-pattern.md)

## Related Schema

This repo covers agent creation.

A future sibling repo should cover general Git repo structure:

```text
schema-gitrepo
```

## Status

Version: `v0.1.0-origin`
