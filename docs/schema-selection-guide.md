# Schema Selection Guide

## Purpose

This guide explains when to use Schema Agent and when to use a future Git repo schema.

## Use Schema Agent When

Use this repo when the main goal is to create an AI agent.

Examples:

- Housekeeper Agent
- Research Agent
- Coding Agent
- Legal Drafting Agent
- Repo Auditor Agent
- Content Agent
- Vision Agent

## Future Use Schema Gitrepo When

Use a future `schema-gitrepo` repo when the main goal is general repo structure, not agent behavior.

Examples:

- Product repo
- Plugin repo
- Documentation repo
- Dataset repo
- Design system repo
- Knowledge base repo

## Relationship

```text
schema-agent   = how to build agents
schema-gitrepo = how to structure repos
```

## Rule

If the repo contains an agent with behavior, use Schema Agent.

If the repo is only a project structure, use Schema Gitrepo.
