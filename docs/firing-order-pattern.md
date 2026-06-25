# Firing Order Pattern

## Purpose

The Firing Order Pattern defines how an agent knows what to read first.

## Required Folder

```text
agents/{agent-name}/system-prompt/
```

## Suggested Files

```text
00-core-system-prompt.md
01-firing-order.md
02-load-sequence.md
03-rule-stack.md
04-context-stack.md
05-output-contract.md
```

## Rule

The agent should not guess its own operating order.

The order should be written down.

## Machine-Readable Order

Add:

```text
firing-order.json
```

This lets tools and future interfaces reorder or load the prompt stack safely.
