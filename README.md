# Claude App Optimiser

A Claude Code slash command that invokes a performance optimization sub-agent.

## What It Does

Runs "Turbo Claude 5000", a sub-agent that reviews and optimizes your codebase across three areas:

- **Code Cleanup** - Identifies and removes dead code, residual implementations, and traces of old architectures
- **Architecture Review** - Evaluates app structure and flags fundamental design gaps
- **Database Optimization** - Reviews indexing, join tables, and recommends maintenance scripts

## Installation

Copy `agent.md` and `slash.md` to your Claude Code configuration directory.

## Usage

```
/optimise
```

The sub-agent will analyze your codebase and either make improvements or flag issues requiring your input.
