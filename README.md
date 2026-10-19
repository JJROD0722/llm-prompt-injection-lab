# LLM Prompt Injection Lab

Tested system-prompt disclosure in Lakera Agent Breaker’s Cycling Coach training challenge.

## Tests and findings
- Normal cycling request: generated a training plan.
- Level 1 direct extraction: disclosed apparent internal instructions; score 100.
- Level 2 reworded extraction, developer claim, and translation request: refused disclosure.

## Documents
- [Investigation report](LLM-Prompt-Injection-Report.pdf)
- [Test log and evidence](Prompt-Injection-Test-Log.pdf)

## Skills demonstrated
- LLM security testing
- Comparing expected and observed behavior
- Evidence documentation
- Identifying limitations and proposing defenses

## Limitations
Five tests were performed in an authorized training challenge. The original system prompt was unavailable for comparison. Level 2 refusals do not prove protection against every attack. No private user records or external systems were accessed. Proposed defenses were not implemented or tested.

## Platform
[Lakera Agent Breaker](https://play.lakera.ai/agent-breaker)
