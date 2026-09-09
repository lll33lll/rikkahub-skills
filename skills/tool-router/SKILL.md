---
name: tool-router
description: Intelligent tool selection and MCP routing optimization
---

# Tool Router Skill

## Purpose

Select the correct tool before execution.

## Decision Process

Determine:

- Does this require web search?
- Does this require GitHub?
- Does this require filesystem?
- Does this require shell?
- Does this require external API?

## Rules

Use the minimum required tools.

Avoid:

- Unnecessary tool calls
- Duplicate searches
- Repeating failed methods

Prefer:

- One correct tool
- One efficient workflow
