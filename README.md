# Thinking Partner

A deterministic thinking partner that challenges assumptions and applies 150+ mental models to sharpen decisions, solve problems, and think more clearly.

Built on the open [Agent Skills](https://agentskills.io) standard. Works with Claude Code, Cursor, Windsurf, Cline, GitHub Copilot, and any AI agent that supports the standard.

## Install

```bash
npx skills add mattnowdev/thinking-partner
```

## What It Does

Not a lecture — a sparring session. Turns your AI agent into a thinking partner that:

- **Challenges assumptions** — Surfaces hidden beliefs you're treating as facts
- **Applies mental models** — Selects and deploys the right frameworks for your situation (150+ models across 17 disciplines)
- **Detects orientation capture** — Notices when your thinking serves comfort instead of truth
- **Maintains productive tension** — Holds complexity open long enough to find real insight

## When It Triggers

- "Help me think through X"
- "Challenge my thinking"
- "What am I missing?"
- "Play devil's advocate"
- "Stress test this idea"
- "Help me decide between X and Y"
- Any named mental model: SWOT, first principles, inversion, pre-mortem, 5 Whys, etc.

## What Makes It Different

| Feature | This Skill | Others |
|---|---|---|
| **Orientation Detection** | Diagnoses 6 thinking states (GT0-GT5) with targeted interventions | Generic questioning |
| **150+ Mental Models** | Full catalog organized by discipline with key questions | Handful of models |
| **Cognitive Operations** | 7 complementary operation pairs (Decouple/Re-couple, Hold/Resolve, etc.) | None |
| **Structured Workflow** | 6-step deterministic process from diagnosis to synthesis | Freeform |
| **Anti-Patterns** | Explicit guidance on what NOT to do | None |

## Mental Models Included

Organized across 17 disciplines:

- **General Thinking**: First Principles, Inversion, Second-Order Thinking, Chesterton's Fence, Entropy, and more
- **Decision-Making**: Pre-Mortem, Regret Minimization, SWOT, Asymmetric Risk, Preserving Optionality
- **Problem-Solving**: 5 Whys, Fishbone, MECE Decomposition, Bright Spots Analysis, Local vs Global Optima
- **Systems & Complexity**: Feedback Loops, Stocks & Flows, Tipping Points, Antifragility, Path Dependence
- **Economics & Strategy**: Incentives, Network Effects, Tragedy of the Commons, Lindy Effect, Power Laws
- **Statistics & Probability**: Bayesian Updating, Correlation vs Causation, Selection Bias, Gambler's Fallacy
- **Psychology & Biases**: Confirmation Bias, Planning Fallacy, Halo Effect, Curse of Knowledge, Peak-End Rule
- **Physics & Engineering**: Inertia, Activation Energy, Resonance, Half-Life, Margin of Safety
- **Biology & Evolution**: Natural Selection, Red Queen Effect, Coevolution, Niche Construction
- **Communication & Persuasion**: Steel Manning, Reciprocity, Narrative/Storytelling, Pyramid Principle
- **Creativity & Innovation**: SCAMPER, Design Thinking, Oblique Strategies, Minimum Viable Experiment
- **Learning & Development**: Feynman Technique, Spaced Repetition, Zone of Proximal Development
- **Time & Resource Management**: Eisenhower Matrix, Pareto Principle, Maker's vs Manager's Schedule
- **Game Theory**: Prisoner's Dilemma, Schelling Point, Tit for Tat, Signaling, Moral Hazard
- **Negotiation**: BATNA, ZOPA, Logrolling
- **Resilience & Antifragility**: Barbell Strategy, Skin in the Game, Via Negativa, Hormesis
- **Ethics & Responsibility**: Veil of Ignorance

See the full catalog in [`skills/thinking-partner/references/model-catalog.md`](skills/thinking-partner/references/model-catalog.md).

## Alternative Install

<details>
<summary>Manual install per agent</summary>

**Claude Code (Plugin)**
```bash
/plugin marketplace add mattnowdev/thinking-partner
/plugin install thinking-partner@mattnowdev-thinking-partner
```

**Claude Code (Manual)**
```bash
cp -r skills/thinking-partner ~/.claude/skills/thinking-partner
```

**Cursor**
Copy `skills/thinking-partner/SKILL.md` and the `references/` directory into `.cursor/rules/`.

**Windsurf**
Copy `skills/thinking-partner/SKILL.md` and the `references/` directory into `.windsurfrules/`.

**Other Agents**
Copy the skill files into your agent's custom instructions or rules directory.

</details>

## License

MIT
