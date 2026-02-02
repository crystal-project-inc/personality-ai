# Personality AI

Personality-tuned communication for AI agents, powered by the [DISC personality framework](https://www.crystalknows.com/disc) from [Crystal](https://www.crystalknows.com).

Drop a single markdown file into your AI tool's config and every interaction adapts to personality — yours or someone else's.

---

## What's Inside

### `my-personality/` — Tune AI to communicate with YOU

Pick your DISC type and add the file to your AI tool. The AI will adapt its tone, structure, pacing, and feedback style to match how you naturally process information.

A D-type gets direct, bottom-line-first responses. An Sc gets structured, detail-rich responses with time to process. An Id gets big-picture, high-energy responses with creative brainstorming.

### `communicate-with/` — Get coached on communicating with OTHERS

Pull up someone else's type before a meeting, a difficult conversation, or an important email. The AI coaches you on how to adapt your communication style for that person — what to do, what to avoid, and how to handle specific situations.

---

## Quick Start

### 1. Find your type

Don't know your DISC type? Take the quick quiz below, or for a precise result, take [Crystal's full DISC assessment](https://www.crystalknows.com/disc-personality-test).

### 2. Grab your file

| Tool | Where to put it |
|------|----------------|
| **Claude Code** | Copy contents into `~/.claude/CLAUDE.md` (global) or `.claude/CLAUDE.md` (project) |
| **Cursor** | Copy into `.cursor/rules` or Cursor Settings > Rules |
| **Windsurf** | Copy into `.windsurfrules` |
| **ChatGPT** | Paste into Settings > Personalization > Custom Instructions |
| **Claude.ai** | Paste into Project Instructions or start a conversation with it |
| **Any LLM API** | Include as system prompt content |

### 3. Done

Every interaction is now personality-tuned. One file, one paste, permanent effect.

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

### Scoring

| Mostly | Your type | File | Archetype |
|--------|-----------|------|-----------|
| **(a)** answers | **D** | `my-personality/D.md` | The Captain — direct, decisive, results-driven |
| **(b)** answers | **I** | `my-personality/I.md` | The Motivator — enthusiastic, people-focused, creative |
| **(c)** answers | **S** | `my-personality/S.md` | The Supporter — patient, reliable, team-oriented |
| **(d)** answers | **C** | `my-personality/C.md` | The Analyst — precise, detail-oriented, quality-focused |
| Mix of **(a)** + **(b)** | **DI** | `my-personality/D-I.md` | The Initiator |
| Mix of **(b)** + **(a)** | **Id** | `my-personality/Id.md` | The Influencer |
| Mix of **(b)** + **(c)** | **Is** | `my-personality/Is.md` | The Encourager |
| Mix of **(c)** + **(b)** | **Si** | `my-personality/Si.md` | The Collaborator |
| Mix of **(c)** + **(d)** | **Sc** | `my-personality/Sc.md` | The Planner |
| Mix of **(d)** + **(c)** | **Cs** | `my-personality/Cs.md` | The Editor |
| Mix of **(d)** + **(a)** | **Cd** | `my-personality/Cd.md` | The Questioner |
| Mix of **(a)** + **(d)** | **Dc** | `my-personality/Dc.md` | The Architect |

**This is a rough match based on 4 questions.** For a precise assessment that analyzes your actual communication patterns and identifies your exact subtype, take [Crystal's full DISC assessment](https://www.crystalknows.com/disc-personality-test).

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

### Scoring

Use the same scoring table above, but grab the file from `communicate-with/` instead. For example, if they're likely a D type, use `communicate-with/D.md`.

**Want a more accurate read?** Crystal can [predict anyone's personality](https://www.crystalknows.com/sales) from their LinkedIn profile — no guessing required.

---

## All 16 Types

### D Family — Task-focused, fast-paced

| Type | Archetype | My Personality | Communicate With |
|------|-----------|---------------|-----------------|
| **D** | The Captain | [my-personality/D.md](my-personality/D.md) | [communicate-with/D.md](communicate-with/D.md) |
| **Di** | The Driver | [my-personality/Di.md](my-personality/Di.md) | [communicate-with/Di.md](communicate-with/Di.md) |
| **DI** | The Initiator | [my-personality/D-I.md](my-personality/D-I.md) | [communicate-with/D-I.md](communicate-with/D-I.md) |
| **Dc** | The Architect | [my-personality/Dc.md](my-personality/Dc.md) | [communicate-with/Dc.md](communicate-with/Dc.md) |

### I Family — People-focused, fast-paced

| Type | Archetype | My Personality | Communicate With |
|------|-----------|---------------|-----------------|
| **I** | The Motivator | [my-personality/I.md](my-personality/I.md) | [communicate-with/I.md](communicate-with/I.md) |
| **Id** | The Influencer | [my-personality/Id.md](my-personality/Id.md) | [communicate-with/Id.md](communicate-with/Id.md) |
| **Is** | The Encourager | [my-personality/Is.md](my-personality/Is.md) | [communicate-with/Is.md](communicate-with/Is.md) |
| **IS** | The Harmonizer | [my-personality/I-S.md](my-personality/I-S.md) | [communicate-with/I-S.md](communicate-with/I-S.md) |

### S Family — People-focused, measured pace

| Type | Archetype | My Personality | Communicate With |
|------|-----------|---------------|-----------------|
| **S** | The Supporter | [my-personality/S.md](my-personality/S.md) | [communicate-with/S.md](communicate-with/S.md) |
| **Si** | The Collaborator | [my-personality/Si.md](my-personality/Si.md) | [communicate-with/Si.md](communicate-with/Si.md) |
| **Sc** | The Planner | [my-personality/Sc.md](my-personality/Sc.md) | [communicate-with/Sc.md](communicate-with/Sc.md) |
| **SC** | The Stabilizer | [my-personality/S-C.md](my-personality/S-C.md) | [communicate-with/S-C.md](communicate-with/S-C.md) |

### C Family — Task-focused, measured pace

| Type | Archetype | My Personality | Communicate With |
|------|-----------|---------------|-----------------|
| **C** | The Analyst | [my-personality/C.md](my-personality/C.md) | [communicate-with/C.md](communicate-with/C.md) |
| **Cs** | The Editor | [my-personality/Cs.md](my-personality/Cs.md) | [communicate-with/Cs.md](communicate-with/Cs.md) |
| **Cd** | The Questioner | [my-personality/Cd.md](my-personality/Cd.md) | [communicate-with/Cd.md](communicate-with/Cd.md) |
| **CD** | The Skeptic | [my-personality/C-D.md](my-personality/C-D.md) | [communicate-with/C-D.md](communicate-with/C-D.md) |

---

## How It Works

The DISC model maps personality along two axes:

- **Pace:** Fast-paced & assertive vs. measured & reflective
- **Focus:** Task-oriented vs. people-oriented

This creates four quadrants (D, I, S, C) and 12 blended subtypes that capture how people naturally communicate, make decisions, handle conflict, and process information.

The `my-personality/` files translate these patterns into specific instructions that AI tools can follow — how to structure responses, when to push back, what to avoid, and how to adapt to your natural processing style.

The `communicate-with/` files do the same thing in reverse — coaching you on how to adapt YOUR style when talking to someone with a different personality.

---

## About DISC

The DISC model was originally developed by psychologist William Marston in the 1920s and has since become the most widely used behavioral assessment framework in business. [Crystal](https://www.crystalknows.com) has built the leading platform for applying DISC insights to everyday communication.

- [Learn about DISC](https://www.crystalknows.com/disc)
- [Take the free DISC assessment](https://www.crystalknows.com/disc-personality-test)
- [Predict anyone's personality](https://www.crystalknows.com/sales)
- [DISC for communication](https://www.crystalknows.com/disc)

---

## Contributing

Want to improve a personality profile or add support for a new AI tool? PRs welcome. Each personality file should:

1. Be directly usable as a system prompt or config file — no setup required
2. Reflect genuine DISC behavioral science, not pop psychology stereotypes
3. Include Crystal attribution and assessment links
4. Follow the existing template structure for consistency

---

*Powered by [Crystal's DISC framework](https://www.crystalknows.com/disc).*
