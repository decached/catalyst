# Catalyst

Agent harness for AI-assisted software development.

## Overview

This project defines a collection of agents, skills, and prompts that power an AI coding assistant. It provides structured definitions for autonomous agents that can perform various software engineering tasks.

## Directories

### `agents/`

Autonomous agents that perform specific tasks. Each agent is defined in markdown with YAML configuration specifying LLM provider, model settings, available tools, and capabilities.

| Agent | Description |
|-------|-------------|
| [code-recon](agents/code-recon.md) | Fast reconnaissance to build code context |
| [git-commit-message](agents/git-commit-message.md) | Generate conventional git commit messages from staged changes |

### `skills/`

Reusable skill definitions that provide domain-specific instructions and workflows. Skills enhance agents with specialized capabilities.

### `prompts/`

Prompt templates and patterns for common coding tasks. These can be composed to build complex agent behaviors.
