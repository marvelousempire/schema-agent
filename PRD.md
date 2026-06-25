# Product Requirements Document - Schema Agent

## Product Name

Schema Agent

## Purpose

Schema Agent is a reusable schema for designing, documenting, and maintaining AI agent repos.

## Problem

Agents are often created as loose prompts.

Loose prompts are hard to maintain because they do not preserve structure, decisions, versions, feature requests, validation rules, or founder intent.

## Solution

Create a reusable agent-building schema that tells an AI or developer how to build a complete agent repo.

## Target Users

- Founders
- Builders
- AI operators
- Developers
- Prompt engineers
- Teams building many agents

## Core Requirements

1. Define the required repo files for an agent.
2. Define the required agent folder structure.
3. Define the system prompt firing order.
4. Define how rules are created and updated.
5. Define how feature tickets are created.
6. Define how journals preserve decisions.
7. Define how templates are used.
8. Define how validation works.
9. Define how release memory is tracked.
10. Define how another AI can use the schema.

## Required Root Files

```text
README.md
ABOUT.md
PRD.md
LICENSE
repo-manifest.md
release-ledger.md
```

## Required Folders

```text
agents/
docs/
features/
features/tickets/
obsidian/
obsidian/journal/
tests/
```

## Agent Folder Requirement

Each agent should live in:

```text
agents/{agent-name}/
```

Required subfolders:

```text
agents/{agent-name}/system-prompt/
agents/{agent-name}/templates/
```

## Success Criteria

Schema Agent is successful when a new AI can read this repo and build a new agent using the same structure and logic.

## First Reference Implementation

```text
agent-housekeeper
```
