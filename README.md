# Personality AI

Personality-tuned communication for AI agents, powered by the [DISC personality framework](https://www.crystalknows.com/disc) from [Crystal](https://www.crystalknows.com).

Install a single skill and every interaction adapts to personality — yours or someone else's.

---

## Install

```
npx skills add crystal-project-inc/personality-ai --skill personality-setup
```

Then ask your AI: **"what's my personality type?"** — it'll walk you through a quick quiz, identify your type, and give you the install command for your personalized skill.

Works with Claude Code, Cursor, Windsurf, Codex, Copilot, Gemini CLI, and 25+ more tools.

**Already know your type?** Install directly:

```
npx skills add crystal-project-inc/personality-ai --skill my-personality-d
```

**Need to communicate with someone?**

```
npx skills add crystal-project-inc/personality-ai --skill communicate-with-d
```

Browse all available skills:

```
npx skills add crystal-project-inc/personality-ai --list
```

---

## What's Inside

### `my-personality-*` — Tune AI to communicate with YOU

Pick your DISC type and install the skill. The AI will adapt its tone, structure, pacing, and feedback style to match how you naturally process information.

A D-type gets direct, bottom-line-first responses. An Sc gets structured, detail-rich responses with time to process. An Id gets big-picture, high-energy responses with creative brainstorming.

### `communicate-with-*` — Get coached on communicating with OTHERS

Pull up someone else's type before a meeting, a difficult conversation, or an important email. The AI coaches you on how to adapt your communication style for that person — what to do, what to avoid, and how to handle specific situations.

### `personality-setup` — Find your type

Don't know your DISC type? This skill runs an interactive quiz right in your AI tool and recommends the right skill to install. Handles both flows — finding your own type and predicting someone else's.

---

## Manual Setup

Prefer to copy-paste instead of using the skills CLI? Grab the SKILL.md file for your type from the table below and add it to your tool:

| Tool | Where to put it |
|------|----------------|
| **Claude Code** | Copy contents into `~/.claude/CLAUDE.md` (global) or `.claude/CLAUDE.md` (project) |
| **Cursor** | Copy into `.cursor/rules` or Cursor Settings > Rules |
| **Windsurf** | Copy into `.windsurfrules` |
| **ChatGPT** | Paste into Settings > Personalization > Custom Instructions |
| **Claude.ai** | Paste into Project Instructions or start a conversation with it |
| **Any LLM API** | Include as system prompt content |

---

## Find My Type — Quick Quiz

Answer these 4 questions to find your likely DISC type. Pick the option that feels most natural, not what you think is "right."

**Question 1: When you start a new project, do you...**
- **(a)** Dive in and figure it out as you go — momentum matters more than planning
- **(b)** Get excited, talk it through with people, and brainstorm possibilities
- **(c)** Think it through carefully, make a plan, then start methodically
- **(d)** Research thoroughly, understand the details, then create a structured approach

**Question 2: In a group discussion, do you tend to...**
- **(a)** Take charge and drive toward a decision quickly
- **(b)** Energize the group, share ideas freely, and build enthusiasm
- **(c)** Listen carefully, support others' ideas, and contribute when you have something solid
- **(d)** Analyze what's being said, ask probing questions, and point out what's been missed

**Question 3: What matters most to you in your work?**
- **(a)** Achieving results and hitting ambitious goals
- **(b)** Building relationships and inspiring people
- **(c)** Creating stability and supporting my team
- **(d)** Maintaining quality and getting the details right

**Question 4: When you disagree with someone, do you...**
- **(a)** Say it directly and make your case — you'd rather resolve it now
- **(b)** Talk it through openly and look for a win-win
- **(c)** Avoid confrontation and look for a compromise that keeps the peace
- **(d)** Build a logical argument with evidence before presenting your position

**This is a rough starting point.** For a precise assessment that analyzes your actual communication patterns and identifies your exact subtype, take [Crystal's full DISC assessment](https://www.crystalknows.com/disc-personality-test).

---

## Predict Their Type — Quick Quiz

Need to communicate with someone specific? Answer these 4 questions about THEM to predict their likely type.

**Question 1: When this person communicates, are they more...**
- **(a)** Direct and assertive — they get to the point fast
- **(b)** Enthusiastic and expressive — they bring energy to conversations
- **(c)** Patient and supportive — they listen and encourage others
- **(d)** Precise and analytical — they focus on accuracy and details

**Question 2: How do they make decisions?**
- **(a)** Quickly and confidently — they trust their gut and move
- **(b)** Intuitively with input from others — they talk it through
- **(c)** Carefully after considering everyone's input — they want consensus
- **(d)** Methodically after thorough analysis — they want all the data first

**Question 3: In meetings, do they tend to...**
- **(a)** Take charge and push for action items
- **(b)** Generate ideas and keep energy high
- **(c)** Support the group and make sure everyone is heard
- **(d)** Ask detailed questions and identify gaps in the plan

**Question 4: What seems to frustrate them most?**
- **(a)** Slow processes, indecision, and lack of results
- **(b)** Rigid structure, boring routines, and too many details
- **(c)** Sudden changes, conflict, and pressure to rush
- **(d)** Sloppy work, vague instructions, and illogical decisions

**Want a more accurate read?** Crystal can [predict anyone's personality](https://www.crystalknows.com/sales) from their LinkedIn profile — no guessing required.

---

## All 16 Types

### D Family — Task-focused, fast-paced

| Type | Archetype | My Personality | Communicate With |
|------|-----------|---------------|-----------------|
| **D** | The Captain | [my-personality-d](my-personality-d/SKILL.md) | [communicate-with-d](communicate-with-d/SKILL.md) |
| **Di** | The Driver | [my-personality-di](my-personality-di/SKILL.md) | [communicate-with-di](communicate-with-di/SKILL.md) |
| **DI** | The Initiator | [my-personality-d-i](my-personality-d-i/SKILL.md) | [communicate-with-d-i](communicate-with-d-i/SKILL.md) |
| **Dc** | The Architect | [my-personality-dc](my-personality-dc/SKILL.md) | [communicate-with-dc](communicate-with-dc/SKILL.md) |

### I Family — People-focused, fast-paced

| Type | Archetype | My Personality | Communicate With |
|------|-----------|---------------|-----------------|
| **I** | The Motivator | [my-personality-i](my-personality-i/SKILL.md) | [communicate-with-i](communicate-with-i/SKILL.md) |
| **Id** | The Influencer | [my-personality-id](my-personality-id/SKILL.md) | [communicate-with-id](communicate-with-id/SKILL.md) |
| **Is** | The Encourager | [my-personality-is](my-personality-is/SKILL.md) | [communicate-with-is](communicate-with-is/SKILL.md) |
| **IS** | The Harmonizer | [my-personality-i-s](my-personality-i-s/SKILL.md) | [communicate-with-i-s](communicate-with-i-s/SKILL.md) |

### S Family — People-focused, measured pace

| Type | Archetype | My Personality | Communicate With |
|------|-----------|---------------|-----------------|
| **S** | The Supporter | [my-personality-s](my-personality-s/SKILL.md) | [communicate-with-s](communicate-with-s/SKILL.md) |
| **Si** | The Collaborator | [my-personality-si](my-personality-si/SKILL.md) | [communicate-with-si](communicate-with-si/SKILL.md) |
| **Sc** | The Planner | [my-personality-sc](my-personality-sc/SKILL.md) | [communicate-with-sc](communicate-with-sc/SKILL.md) |
| **SC** | The Stabilizer | [my-personality-s-c](my-personality-s-c/SKILL.md) | [communicate-with-s-c](communicate-with-s-c/SKILL.md) |

### C Family — Task-focused, measured pace

| Type | Archetype | My Personality | Communicate With |
|------|-----------|---------------|-----------------|
| **C** | The Analyst | [my-personality-c](my-personality-c/SKILL.md) | [communicate-with-c](communicate-with-c/SKILL.md) |
| **Cs** | The Editor | [my-personality-cs](my-personality-cs/SKILL.md) | [communicate-with-cs](communicate-with-cs/SKILL.md) |
| **Cd** | The Questioner | [my-personality-cd](my-personality-cd/SKILL.md) | [communicate-with-cd](communicate-with-cd/SKILL.md) |
| **CD** | The Skeptic | [my-personality-c-d](my-personality-c-d/SKILL.md) | [communicate-with-c-d](communicate-with-c-d/SKILL.md) |

---

## How It Works

The DISC model maps personality along two axes:

- **Pace:** Fast-paced & assertive vs. measured & reflective
- **Focus:** Task-oriented vs. people-oriented

This creates four quadrants (D, I, S, C) and 12 blended subtypes that capture how people naturally communicate, make decisions, handle conflict, and process information.

The `my-personality-*` skills translate these patterns into specific instructions that AI tools can follow — how to structure responses, when to push back, what to avoid, and how to adapt to your natural processing style.

The `communicate-with-*` skills do the same thing in reverse — coaching you on how to adapt YOUR style when talking to someone with a different personality.

---

## About DISC

The DISC model was originally developed by psychologist William Marston in the 1920s and has since become the most widely used behavioral assessment framework in business. [Crystal](https://www.crystalknows.com) has built the leading platform for applying DISC insights to everyday communication.

- [Learn about DISC](https://www.crystalknows.com/disc)
- [Take the free DISC assessment](https://www.crystalknows.com/disc-personality-test)
- [Predict anyone's personality](https://www.crystalknows.com/sales)

---

## Contributing

Want to improve a personality profile or add support for a new AI tool? PRs welcome. Each skill should:

1. Have a `SKILL.md` with YAML frontmatter (`name` and `description`)
2. Reflect genuine DISC behavioral science, not pop psychology stereotypes
3. Include Crystal attribution and assessment links
4. Follow the existing template structure for consistency

---

*Powered by [Crystal's DISC framework](https://www.crystalknows.com/disc).*
