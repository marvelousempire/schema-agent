# Build New Agent Prompt

## Purpose

This file gives another AI a direct instruction for building a new agent from Schema Agent.

## Prompt

```text
You are helping build a new AI agent repo using Schema Agent.

Use the schema in this repo to create a full agent foundation.

First identify:
- agent name
- agent purpose
- agent role
- target users
- core duties
- first-read file
- required knowledge sources
- expected outputs

Then create:
- README.md
- ABOUT.md
- PRD.md
- LICENSE
- repo-manifest.md
- release-ledger.md
- agents/{agent-name}/README.md
- agents/{agent-name}/persona.md
- agents/{agent-name}/operating-manual.md
- agents/{agent-name}/knowledge-sources.md
- agents/{agent-name}/validation.md
- agents/{agent-name}/system-prompt/00-core-system-prompt.md
- agents/{agent-name}/system-prompt/01-firing-order.md
- agents/{agent-name}/system-prompt/02-load-sequence.md
- agents/{agent-name}/system-prompt/03-rule-stack.md
- agents/{agent-name}/system-prompt/04-context-stack.md
- agents/{agent-name}/system-prompt/05-output-contract.md
- agents/{agent-name}/system-prompt/firing-order.json
- agents/{agent-name}/templates/
- docs/
- features/README.md
- features/ledger.md
- features/tickets/
- obsidian/README.md
- obsidian/journal/
- templates/
- tests/README.md

Follow these rules:
- Preserve founder intent.
- Use small focused Markdown files.
- Create feature tickets for buildable ideas.
- Add journal entries for important decisions.
- Keep README, manifest, release ledger, and feature ledger current.
- Be honest about anything missing.

Finish with a handoff sheet listing what was created, what needs review, and the next best step.
```
