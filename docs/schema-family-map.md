# Schema Family Map

## Purpose

This file explains how the related schema and working repos fit together.

## Family Roles

```text
schema-agent      = how to build agents
schema-gitrepo    = how to structure Git repos
agent-housekeeper = first working reusable agent standard
motif             = working product repo using the repo and agent patterns
```

## Relationship

Schema Agent defines the agent-building pattern.

Schema Gitrepo defines the general repo-structure pattern.

Agent Housekeeper is a real agent that follows Schema Agent.

Motif is a real product repo that follows Schema Gitrepo and uses Agent Housekeeper as a submodule standard.

## Use Schema Agent When

Use Schema Agent when creating an AI agent with:

- Role
- Persona
- Rules
- Prompt stack
- Firing order
- Knowledge sources
- Validation behavior
- Templates

## Use Schema Gitrepo When

Use Schema Gitrepo when creating a general project repo with:

- README
- ABOUT
- PRD
- Repo manifest
- Release ledger
- Docs
- Feature tickets
- Journal
- Templates
- Tests

## Working Examples

| Repo | Role |
| --- | --- |
| schema-agent | Agent-building schema |
| schema-gitrepo | Git repo structure schema |
| agent-housekeeper | Reusable agent built from the agent schema style |
| motif | Product repo using the repo schema and Housekeeper standard |

## Rule

When a working repo produces a reusable pattern, move that pattern back into the correct schema repo.
