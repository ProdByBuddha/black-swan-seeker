# Black Swan Event Seeker

An AI agent skill specialized in **Red Teaming**, **Risk Analysis**, and identifying **High-Impact Outliers**.

## What is this?
This skill allows your AI agent to act as a specialized risk analyst. It uses a set of mental models (Taleb, Sornette, Systems Theory) to "stress test" any subject matter—be it a codebase, a financial strategy, a geopolitical situation, or a business plan.

It specifically hunts for:
- **Black Swans:** Unpredictable, extreme outliers.
- **Grey Rhinos:** Obvious but ignored dangers.
- **Fragilities:** Structural weaknesses that hate volatility.

## Usage

**Trigger the skill with phrases like:**
- "Play devil's advocate on [Project X]."
- "Find black swan events for [Bitcoin/AI/Supply Chains]."
- "What are the systemic risks of this architecture?"

**The agent will:**
1.  Establish the "Consensus View" (The White Swan).
2.  Perform an "Inversion Search" for contrarian data and historical failure modes.
3.  Analyze the system using frameworks like *The Turkey Problem* and *Tight Coupling*.
4.  Produce a **Risk Dossier** outlining scenarios and their potential impacts.

## Installation

### Generic (Gemini CLI / Codex / Claude Code)
Place the `black-swan-seeker` folder in your agent's skills directory.

```bash
# Example for Gemini CLI
cp -R black-swan-seeker ~/.gemini/skills/

# Example for Claude Code
cp -R black-swan-seeker ~/.claude/skills/
```

### Usage Example
> **User:** "Here is my deployment plan for the new payment gateway. Analyze it for black swan risks."
>
> **Agent:** *Activates black-swan-seeker...*
> "I will analyze the deployment plan.
> **Consensus:** You expect a smooth rollout with standard rollback procedures.
> **Potential Black Swans:**
> 1. **Provider Insolvency:** The underlying merchant of record freezes funds during launch (Confidence: Low, Impact: Critical).
> 2. **False Positive Storm:** Fraud AI bans 50% of legitimate users on Day 1 due to lack of history (Confidence: Medium, Impact: High).
> ..."

## License
MIT
