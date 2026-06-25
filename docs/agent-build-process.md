# Agent Build Process

## Purpose

This document explains how to build an agent using Schema Agent.

## Process

```text
Intent
→ Purpose
→ Agent Role
→ Repo Structure
→ System Prompt Stack
→ Rules
→ Feature Tickets
→ Templates
→ Journal
→ Validation
→ Release Memory
```

## Step 1 - Capture Intent

Define why the agent should exist.

## Step 2 - Define Purpose

Write the agent purpose in plain language.

## Step 3 - Define Role

Explain what the agent is responsible for.

## Step 4 - Create Repo Structure

Add the required root files and folders.

## Step 5 - Create System Prompt Stack

Add ordered prompt files under:

```text
agents/{agent-name}/system-prompt/
```

## Step 6 - Capture Rules

Turn repeated instructions and founder corrections into durable rules.

## Step 7 - Create Feature Tickets

Turn buildable ideas into small Markdown tickets.

## Step 8 - Add Templates

When a repeated output appears, create a template.

## Step 9 - Add Journal

When a decision matters, add a journal entry.

## Step 10 - Validate

Check that the agent has purpose, rules, docs, tickets, templates, and a clear starting point.
