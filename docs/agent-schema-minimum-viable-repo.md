# Agent Schema Minimum Viable Repo

## Purpose

This document defines the smallest safe agent repo that still follows Schema Agent.

## Minimum Root Files

```text
README.md
ABOUT.md
PRD.md
repo-manifest.md
release-ledger.md
```

## Minimum Agent Files

```text
agents/{agent-name}/README.md
agents/{agent-name}/system-prompt/00-core-system-prompt.md
agents/{agent-name}/system-prompt/01-firing-order.md
agents/{agent-name}/validation.md
```

## Minimum Tracking Files

```text
features/ledger.md
tests/README.md
```

## Minimum Memory Files

```text
obsidian/README.md
obsidian/journal/Journal Update - Origin.md
```

## Rule

A minimum repo may be small, but it still needs a front door, purpose, firing order, ledger, and validation path.
