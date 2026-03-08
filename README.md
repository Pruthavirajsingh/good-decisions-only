<div align="center">

# 🧠 good-decisions-only

### Stop deciding on vibes. Start deciding on math.

A specialized AI agent that runs every real decision through 6 battle-tested  
cognitive frameworks — and delivers a clear, structured recommendation.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code Compatible](https://img.shields.io/badge/Claude%20Code-Compatible-blue?logo=anthropic)](https://docs.anthropic.com/en/docs/claude-code/sub-agents)
[![Agent Type](https://img.shields.io/badge/Agent%20Type-Decision%20Analysis-indigo)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Pruthavirajsingh/good-decisions-only/pulls)

</div>

---

## 🤔 Why This Exists

You make roughly **35,000 decisions a day.**

For small stuff — what to eat, which show to watch — gut instinct is fine.

But for the decisions that actually shape your life? Career moves, investments,
relationships, health? Vibes are a disaster.

The problem isn't intelligence. It's that the human brain is wired to:
- Feel losses **2x more** than equivalent gains *(loss aversion)*
- Ignore base rates and chase inspiring anecdotes *(base rate neglect)*
- Let past investment contaminate forward decisions *(sunk cost fallacy)*
- Only see the winners and miss the graveyard *(survivorship bias)*
- Either ignore new evidence or wildly overreact to it *(bad Bayesian updating)*
- Go all-in or nothing, when the math says something in between *(Kelly violations)*

This agent fixes all of that. Not with motivation. With math.

---

## ⚙️ The 6-Framework Engine

Every decision gets run through all 6. No shortcuts.
```
┌─────────────────────────────────────────────────────────────┐
│                    YOUR DECISION INPUT                       │
└─────────────────────┬───────────────────────────────────────┘
                      │
          ┌───────────▼───────────┐
          │   1. REFRAME FIRST    │  Strip emotion & sunk costs.
          │                       │  What are you ACTUALLY deciding?
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │  2. EXPECTED VALUE    │  EV = Σ(probability × payoff)
          │                       │  Show the math. Make it visible.
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │   3. BASE RATE CHECK  │  What's the historical success rate
          │                       │  for this category of decision?
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │  4. SUNK COST AUDIT   │  Past investment = zero votes.
          │                       │  Only the future counts.
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │  5. BAYESIAN UPDATE   │  What does your evidence actually
          │                       │  justify believing? Update proportionally.
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │ 6. SURVIVORSHIP CHECK │  Find the graveyard.
          │                       │  Who tried this and failed silently?
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │  7. KELLY SIZING      │  How much to commit? Quarter-Kelly
          │                       │  to Half-Kelly for real humans.
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │   CLEAR RECOMMENDATION│  A verdict. Not a list of considerations.
          └───────────────────────┘
```

---

## 🚀 How to Use

### Option 1 — With Claude Code (Recommended)
```bash
# Clone and install
git clone https://github.com/Pruthavirajsingh/good-decisions-only.git
cp good-decisions-only/decision-analyst.md ~/.claude/agents/
```

Then in any Claude Code session:
```
"Activate decision analyst — I need to think through [your decision]"
```

### Option 2 — As a System Prompt (Claude, ChatGPT, Gemini, etc.)

1. Open `decision-analyst.md`
2. Copy the entire contents
3. Paste it as the **system prompt** in any AI chatbot
4. Describe your decision and let it run the full framework

---

## 💡 Example Decisions It Handles

| Decision Type | Example Input |
|---|---|
| 💼 Career | *"Stable $120K job vs. startup offer with equity. Switch?"* |
| 💰 Investment | *"Down 50% on this stock. Sell or hold?"* |
| ❤️ Relationship | *"Together 6 years but unhappy. Stay or leave?"* |
| 🚀 Opportunity | *"Everyone I know is making money in X. Should I jump in?"* |
| 🎓 Education | *"Drop out to build my startup or finish the degree?"* |
| 🏠 Life | *"Move to a new city for a job I'm not sure about?"* |

---

## 📊 Real Example Output

**Input:** *"I have a stable $120K job. A startup offered me $90K base + equity. Should I switch?"*

**Agent Output (condensed):**

> **Reframe:** This is a forward-only EV question. Your tenure at your current job is a sunk cost — it doesn't vote.
>
> **EV Calculation:**
> - Option A (Stay): EV = $120K (certain)
> - Option B (Startup): 60% success → $250K total comp | 40% failure → $70K
>   EV = (0.60 × $250K) + (0.40 × $70K) = **$178K**
>
> **Base Rate:** Startup success rate ~20-30%. Equity actually vesting: ~40% of that.
> Adjusted EV drops to ~$145K — still higher than staying.
>
> **Sunk Cost flagged:** "I've invested 4 years here" — removed from calculation.
>
> **Survivorship Bias:** You're hearing about startup wins on LinkedIn. The failures
> don't post. Denominator matters.
>
> **Kelly Sizing:** Don't quit cold. Negotiate a 3-month notice. Build runway.
> That's your quarter-Kelly move.
>
> **Verdict:** The math favors the switch IF you have 6+ months of savings as runway.
> If you don't — build it first, then switch. The opportunity isn't going anywhere.

---

## 📚 The Intellectual Foundation

These 6 frameworks aren't invented here — they're sourced from the best thinkers in decision science:

| Framework | Source |
|---|---|
| Expected Value | Standard probability theory |
| Base Rate Neglect | Daniel Kahneman — *Thinking, Fast and Slow* |
| Sunk Cost Fallacy | Richard Thaler — Behavioral Economics |
| Bayesian Updating | Thomas Bayes + Philip Tetlock — *Superforecasting* |
| Survivorship Bias | Nassim Taleb — *Fooled by Randomness* |
| Kelly Criterion | John Kelly + William Poundstone — *Fortune's Formula* |

**Recommended reading if you want to go deeper:**
- *Thinking, Fast and Slow* — Daniel Kahneman
- *Superforecasting* — Philip Tetlock
- *Fooled by Randomness* — Nassim Taleb
- *Fortune's Formula* — William Poundstone
- *Thinking in Bets* — Annie Duke
- *The Signal and the Noise* — Nate Silver

---

## 🗂️ Repo Structure
```
good-decisions-only/
├── decision-analyst.md   ← The full agent prompt (paste this as system prompt)
├── README.md             ← You are here
├── CHANGELOG.md          ← Version history
└── LICENSE               ← MIT
```

---

## 🤝 Contributing

Found a framework that should be added? A bias that's missing? PRs are welcome.

1. Fork the repo
2. Create a branch: `git checkout -b improve-framework`
3. Make your changes
4. Submit a PR with a clear explanation of what you added and why

---

## 🏗️ Built With

Agent structure inspired by [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents).
Frameworks sourced from Kahneman, Taleb, Tetlock, Thorp, Silver, and Duke.

---

## 📜 License

MIT — use freely, commercially or personally.

---

<div align="center">
<i>The fact that you're reading a README about decision frameworks already puts you ahead.<br>
Most people just go with their gut and wonder why they're stuck.</i>
</div>
