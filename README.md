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
templates/
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
- [Founder Tuning Loop](docs/founder-tuning-loop.md)
- [Validation Pattern](docs/validation-pattern.md)
- [Handoff Sheet Pattern](docs/handoff-sheet-pattern.md)
- [Schema Family Map](docs/schema-family-map.md)

## Build A New Agent

- [New Agent Checklist](docs/new-agent-checklist.md)
- [Build New Agent Prompt](docs/build-new-agent-prompt.md)
- [Minimum Viable Agent Repo](docs/agent-schema-minimum-viable-repo.md)
- [Schema Selection Guide](docs/schema-selection-guide.md)

## Example Agent

- [Example Agent](agents/example-agent/README.md)
- [Example Core System Prompt](agents/example-agent/system-prompt/00-core-system-prompt.md)
- [Example Firing Order](agents/example-agent/system-prompt/01-firing-order.md)

## Templates

- [README Template](templates/readme-template.md)
- [ABOUT Template](templates/about-template.md)
- [PRD Template](templates/prd-template.md)
- [Feature Ticket Template](templates/feature-ticket-template.md)
- [Journal Entry Template](templates/journal-entry-template.md)
- [Handoff Sheet Template](templates/handoff-sheet-template.md)

## Related Schema

```text
schema-agent      = how to build agents
schema-gitrepo    = how to structure Git repos
agent-housekeeper = first working reusable agent standard
motif             = working product repo using the repo and agent patterns
```

Read:

- [Schema Family Map](docs/schema-family-map.md)

## Status

Version: `v0.1.3-family-map`
