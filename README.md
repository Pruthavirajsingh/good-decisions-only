# 🧠 Decision Analyst Agent

> A math-backed AI agent that runs every decision through 6 proven cognitive 
> frameworks — so you stop deciding on vibes and start deciding on math.

## What It Does

Drop any real decision in front of this agent — career, money, relationships, 
investments — and it will systematically run:

1. **Expected Value (EV)** — calculates the actual math behind each option
2. **Base Rate Check** — grounds your odds in historical reality, not hope
3. **Sunk Cost Audit** — strips out past investment that has zero votes on the future
4. **Bayesian Update** — tells you what your evidence actually justifies believing
5. **Survivorship Bias Check** — finds the graveyard behind every success story
6. **Kelly Criterion Sizing** — tells you exactly how much to commit, not just whether to act

## How to Use

### With Claude Code
```bash
cp decision-analyst.md ~/.claude/agents/
```
Then in any Claude session: *"Activate decision analyst and help me think through [your decision]"*

### As a System Prompt
Copy the contents of `decision-analyst.md` and paste it as the system prompt 
in any AI chatbot (Claude, ChatGPT, etc.)

## Example Inputs

- *"I have a stable job but a startup wants to hire me. Should I switch?"*
- *"I'm down 50% on this investment. Should I sell or hold?"*
- *"We've been together 4 years but I'm unhappy. Should I stay?"*
- *"Everyone in my circle is making money with X. Should I jump in?"*

## Inspired By

Built using the agent structure from [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents).  
Frameworks sourced from: Kahneman, Taleb, Tetlock, Thorp, Silver, and Duke.

## License
MIT
