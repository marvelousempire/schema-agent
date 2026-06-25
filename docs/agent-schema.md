# Agent Schema

## Purpose

The Agent Schema defines the reusable structure for building AI agents.

## Core Definition

An agent is not only a prompt.

An agent is a structured system made of:

- Purpose
- Intent
- Rules
- Knowledge sources
- Firing order
- Templates
- Feature tickets
- Journals
- Validation
- Release memory

## Required Root Files

```text
README.md
ABOUT.md
PRD.md
LICENSE
repo-manifest.md
release-ledger.md
```

## Required Agent Folder

```text
agents/{agent-name}/
```

## Required Agent Subfolders

```text
agents/{agent-name}/system-prompt/
agents/{agent-name}/templates/
```

## Required Project Folders

```text
docs/
features/
features/tickets/
obsidian/
obsidian/journal/
tests/
```

## Schema Rule

Every agent should be small enough to understand, structured enough to maintain, and documented enough to reuse.
