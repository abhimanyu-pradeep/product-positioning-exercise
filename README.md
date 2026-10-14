# Product Positioning Exercise

A Claude skill that runs an interactive product positioning exercise based on April Dunford's *Obviously Awesome* framework.

Instead of filling out a template, you work through 10 steps in conversation with Claude acting as a **critical positioning consultant** — pushing back on vague answers, challenging assumptions, and helping you arrive at positioning that is specific, defensible, and differentiated.

## What you get

A **one-page positioning canvas** you can share with your leadership team — covering your market category, competitive alternatives, unique attributes, value themes, target customer, and positioning statement.

## Two modes

| Mode | Best for | What you bring |
|------|----------|----------------|
| **Data-driven** | Teams with 20+ customers | Customer/account list with revenue, engagement, retention data |
| **Founder knowledge** | Early-stage or pre-launch | Your knowledge of your best customers and the market |

## The 10 steps

| Step | What happens |
|------|-------------|
| 0. Context | Understand your product, stage, and why you're doing this |
| 1. Best-fit customers | Find the pattern in your happiest, most successful customers |
| 2. Competitive alternatives | What customers do if you don't exist (not just competitors) |
| 3. Unique attributes | What you have that alternatives genuinely don't |
| 4. Value themes | "So what?" — translate attributes into business outcomes |
| 5. Target characteristics | Situational traits + purchase triggers that make someone ready |
| 6. Market category | Pick your category and positioning style (Head to Head / Big Fish Small Pond / New Game) |
| 7. Trend (optional) | A market tailwind that makes your positioning urgent |
| 8. Positioning statement | Synthesize and pressure-test against 4 criteria |
| 9. Positioning canvas | One-page shareable artifact for your team |
| 10. What's next | Sales story, messaging, website — suggested path forward |

## Install

### Option 1: Copy the skill file

Copy `.claude/skills/product-positioning-exercise/SKILL.md` into your own project's `.claude/skills/product-positioning-exercise/` directory.

### Option 2: Global install

Copy it to `~/.claude/skills/product-positioning-exercise/SKILL.md` to make it available across all your projects.

### Option 3: Install as a plugin

```bash
/plugin marketplace add abhimanyupradeep/product-positioning-exercise
```

## Usage

In Claude Code or the Claude desktop app:

```
/product-positioning-exercise
```

Or just tell Claude: *"I want to run a positioning exercise for my product"* — it will pick up the skill automatically.

## What makes this different from a template

Templates ask you to fill in boxes. This skill runs a **conversation** where Claude:

- Pushes back when answers are too vague ("We're for everyone" → "Who succeeds the most?")
- Challenges boilerplate ("Better UX" → "What specifically can they do that they can't with alternatives?")
- Names trade-offs at every decision point
- Pressure-tests the final positioning against 4 criteria
- Iterates on the canvas until it's right for your team

The process matters more than the document. The canvas is the artifact — the conversation is the value.

## Example output

The positioning canvas is generated as an HTML artifact — clean, professional, printable as PDF. It includes:

- Positioning statement
- Market category and positioning style
- Competitive alternatives
- Unique attributes table with competitive comparison
- 3-5 revenue-anchored value themes
- Target customer characteristics and purchase triggers
- Market trend (if applicable)

## Credits

Framework based on April Dunford's [*Obviously Awesome*](https://www.aprildunford.com/obviously-awesome) (2019).

Interactive adaptation designed by [Abhimanyu Pradeep](https://www.linkedin.com/in/abhimanyupradeep/) ([Happilee](https://happilee.io)).

## License

MIT
