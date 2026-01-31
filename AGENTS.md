# AGENTS.md

Guidance for agents working on the **black-swan-seeker** repo.

## Project Overview
This skill is a "mental model engine". It doesn't run code; it runs *logic frameworks* against information.

## Key Files
- `SKILL.md`: The primary directive. It instructs the agent to switch from "Helpful Assistant" mode to "Critical Analyst" mode.
- `references/analysis-frameworks.md`: The knowledge base of risk concepts. If you need to add a new mental model (e.g., "Game Theory"), add it here.

## Maintenance
- **Updating Frameworks:** If new risk theories emerge, update `references/analysis-frameworks.md`.
- **Tuning Triggers:** If the agent triggers too often on simple questions (e.g., "What is a swan?"), refine the triggers in `SKILL.md`.

## Testing
To test this skill, ask the agent to analyze a "safe" topic (e.g., "The US Treasury Bond market") and verify it can identify tail risks (e.g., "Sovereign debt crisis", "Hyperinflation").
