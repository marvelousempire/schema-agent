# Schema Agent To Agent Housekeeper Map

## Purpose

This file maps the abstract Schema Agent pattern to the first working example: Agent Housekeeper.

## Relationship

```text
schema-agent = agent-building schema
agent-housekeeper = first working agent built from this style
```

## Mapping

| Schema Agent Concept | Agent Housekeeper Example |
| --- | --- |
| Agent schema | Housekeeper standard |
| System prompt stack | agents/housekeeper/system-prompt/ |
| Firing order | firing-order.json |
| Feature tickets | features/tickets/ |
| Feature ledger | features/ledger.md |
| Journal layer | obsidian/journal/ |
| Wiki layer | obsidian/ |
| Handoff pattern | handoff sheet template |
| Validation pattern | agents/housekeeper/validation.md |

## Rule

When a working agent creates a reusable pattern, move that pattern back into Schema Agent.
