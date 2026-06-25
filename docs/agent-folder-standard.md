# Agent Folder Standard

## Purpose

This document defines the standard folder pattern for an agent.

## Required Path

Each agent should live at:

```text
agents/{agent-name}/
```

## Required Files

```text
agents/{agent-name}/README.md
agents/{agent-name}/persona.md
agents/{agent-name}/operating-manual.md
agents/{agent-name}/knowledge-sources.md
agents/{agent-name}/validation.md
```

## Required Folders

```text
agents/{agent-name}/system-prompt/
agents/{agent-name}/templates/
```

## System Prompt Folder

The system prompt folder stores ordered instruction files.

## Templates Folder

The templates folder stores reusable outputs.

## Rule

The agent folder should explain how the agent thinks, what it reads, what it does, and how it validates work.
