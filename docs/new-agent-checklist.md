# New Agent Checklist

## Purpose

This checklist helps a builder create a new agent using Schema Agent.

## Required Root Files

- [ ] README.md
- [ ] ABOUT.md
- [ ] PRD.md
- [ ] LICENSE
- [ ] repo-manifest.md
- [ ] release-ledger.md

## Required Folders

- [ ] agents/{agent-name}/
- [ ] agents/{agent-name}/system-prompt/
- [ ] agents/{agent-name}/templates/
- [ ] docs/
- [ ] features/
- [ ] features/tickets/
- [ ] obsidian/
- [ ] obsidian/journal/
- [ ] templates/
- [ ] tests/

## Required Agent Files

- [ ] agents/{agent-name}/README.md
- [ ] agents/{agent-name}/persona.md
- [ ] agents/{agent-name}/operating-manual.md
- [ ] agents/{agent-name}/knowledge-sources.md
- [ ] agents/{agent-name}/validation.md

## Required Prompt Stack

- [ ] 00-core-system-prompt.md
- [ ] 01-firing-order.md
- [ ] 02-load-sequence.md
- [ ] 03-rule-stack.md
- [ ] 04-context-stack.md
- [ ] 05-output-contract.md
- [ ] firing-order.json

## Required Ledgers

- [ ] features/ledger.md
- [ ] release-ledger.md

## Required Memory

- [ ] obsidian/README.md
- [ ] obsidian/journal/initial-journal-entry.md

## Validation

- [ ] Agent purpose is clear.
- [ ] Agent start file is clear.
- [ ] Firing order exists.
- [ ] Feature ledger exists.
- [ ] Templates exist.
- [ ] Journal exists.
- [ ] Validation file exists.

## Rule

A new agent is not ready until another AI can read the repo and know where to begin.
