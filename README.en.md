# Eight Hundred Wiles

[中文](README.md) | English

> See through the game. Keep your guard. Don't get played.

**Not a guide to becoming cunning. A guide to not being played.**

A social-strategy skill for AI coding agents. It decodes the subtext, incentive structures, and institutional logic behind what people say and what rules require — then gives you a judgment, a plan, and a paper trail.

The Chinese name is 八百个心眼子 — literally "eight hundred wits," a colloquial way of saying someone is street-smart and sees the angles.

---

## Why it exists

You have probably had moments like these:

- Your boss says "you decide" — and when it goes wrong, it is your name on it.
- A new company rule lands, you follow it, and the cost quietly ends up on your desk.
- A colleague presents your work as his own, and you only realize it afterward.
- A relative asks for money, you cannot say no, and you lose both the money and the relationship.
- Six months later, you finally understand what that sentence really meant.

None of this is about intelligence. Nobody taught you how to read people, situations, and the real purpose behind a rule.

**This skill fills that gap.**

## What it does

### 1. Reads between the lines

It separates literal meaning, subtext, and behavioral signals: who was notified, who was skipped, how forms of address changed, why this was said now. Signals are harder to fake than words.

### 2. Decodes rules and policies

For any policy, it asks three questions: who wrote it, who it is for, and who bears the cost. Then it reads three layers: the written text, the actual enforcement, and the real intent.

### 3. Judges whether to enter a situation

It assesses the situation through five factors — legitimacy, timing, terrain, key people, and rules — plus three lenses: position, cost, and time. Fight, wait, or walk away.

### 4. Gives actions, not just analysis

Three tiers of strategy, a three-part refusal script, buying time, creating a paper trail, and setting boundaries. Every move is something you can actually say or do.

### 5. Turns experience into judgment

Each real event becomes a case: signals, what you did, what happened, what to do next time. Two similar cases become a pattern; three become instinct.

### 6. Keeps you from becoming paranoid

Every judgment comes with at least three interpretations: ordinary, incentive-driven, and targeted. When evidence is thin, it defaults to the most ordinary explanation. Seeing through things is not the same as assuming the worst.

## What it refuses to do

- No manipulation, framing, rumor-spreading, sowing discord, or PUA
- No personality assessment, psychological diagnosis, or fortune-telling
- It does not make decisions for you
- It does not replace legal, medical, or financial advice

**It is defensive only: lose less, get fooled less, hold your boundaries.**

## Who it is for

- New employees who cannot read what their boss really means
- People in bureaucracies who need to understand responsibility and procedure
- Anyone tired of being trapped by social obligations
- People who have been burned and want the lesson to stick
- Ordinary people who want to "grow some wits"

**Not for:** anyone looking for ways to harm others.

## Installation

Place the whole `xinyanzi/` directory in your user-level skills folder:

```bash
# macOS / Linux
cp -r xinyanzi ~/.claude/skills/xinyanzi

# Windows
cp -r xinyanzi C:\Users\<you>\.claude\skills\xinyanzi
```

Or at the project level, so it only applies to one project:

```bash
cp -r xinyanzi <project>/.claude/skills/xinyanzi
```

Restart Claude Code to pick it up. The skill name is `xinyanzi`.

**Check that it worked:** type `/` in Claude Code and look for `xinyanzi`, or just ask "what does my boss really mean by this?" and see if it answers like a strategist.

## How to use it

### Step 1: Describe the situation

No special format needed. Dump what you know. At minimum, include:

| Element | Example |
| --- | --- |
| Exact words | "My boss said: 'you lead this project, the credit is all yours.'" |
| Setting | Private chat, his office, just the two of us |
| Relationship | My direct manager, started last month |
| Context | The previous owner left last month |
| Your worry | Afraid of being scapegoated, but also afraid of looking unenthusiastic |

Incomplete information is fine. It will give a provisional read and ask the one or two questions that actually change the conclusion.

### Step 2: Read the strategist's brief

By default, half a screen:

```
【Judgment】He is shifting responsibility onto you, not giving you an opportunity.
【Critical point】No authority, no resources, no fallback for failure.
【Your position】You can accept, but not empty-handed.
【Three actions】1. ... 2. ... 3. ...
【You can say】"I'm willing, but let me confirm three things first."
【Confidence】70%. If he puts the division of labor in writing, it is real mentorship.
```

### Step 3: Expand when you need to

The brief ends with two or three concrete directions. Reply with a letter or a sentence:

```
Expand?
  A. Break down his motives (three possibilities + signals)
  B. Give me soft / medium / hard scripts
  C. Predict his next move and your fallback
```

You can also say "expand", "go deeper", or "give me three scripts".

For urgent or high-stakes situations (job, money, relationship), it skips the question and gives the full plan directly.

### Step 4: Record it and follow up

When the outcome is known, tell it. The case moves from `open` to `closed`, and the lesson gets extracted:

> "That project — he never gave me the resources. I asked for written confirmation like you said. He didn't reply, so I only took coordination, not the outcome."

It records the signals, your action, the result, and what to do next time.

### Step 5: Check your past cases

Next time something similar happens, ask:

> "Have I run into something like this before?"

It reads your personal index. If there is a match, it says "you saw this before — here is what happened." If not, it says so, instead of forcing a connection.

### Three common modes

**Decode** — paste a sentence, or describe a scene.

> "What does he really mean by this?"

**Strategize** — explain your position, leverage, and worry.

> "Should I fight for this credit? How?"

**Review** — tell it something that already happened.

> "Something from last year still bothers me. Help me review it."

### Common commands

| What you want | What to say |
| --- | --- |
| Decode a sentence | "What does he mean by this?" |
| Read a policy | "What is this rule really about?" |
| Get a plan | "What should I do?" |
| Get a script | "Give me one sentence I can actually say." |
| Go deeper | "Expand" / pick A, B, or C |
| Record a case | "Record this for me." |
| Check past cases | "Have I seen this before?" |
| Review an old event | "Help me review what happened last year." |
| Extract patterns | "Summarize the patterns across these cases." |

### How to ask better

- **Give the exact words**, not your paraphrase.
- **Give the setting** — the same sentence means something different in a meeting and at dinner.
- **Give the relationship** — can this person affect your review, resources, or job?
- **State your worry** — what you fear determines which side it protects first.
- **Don't lie** — the truer the input, the sharper the read.

### A complete conversation

> **You:** My boss said privately, "you lead this project, young people need practice, the credit is all yours." The previous owner left last month. I'm worried it's a trap.
>
> **It:** 【Judgment】He is shifting responsibility onto you, not giving you an opportunity. ... (brief)
>
> **You:** Expand B.
>
> **It:** Soft / medium / hard ways to accept: soft — coordinate without owning the outcome; medium — accept but negotiate authority first; hard — ask for clarity before answering. Each with a script.
>
> **You:** I chose medium, and he agreed. Record it.
>
> **It:** Recorded, status: open. Come back when there is a result.

## Your experience stays yours

The method layer ships with the skill and can be shared. The experience layer lives only on your machine:

```
~/.claude/xinyanzi/
  PROFILE.md     your position, style, red lines, current situation
  INDEX.md       one-page index
  cases/         one file per case
  patterns.md    recurring patterns: theirs, yours, and calibration notes
```

- No real names — roles or aliases only
- Never published, shared, or uploaded
- Created automatically on first use

## Repository layout

```
xinyanzi/
  SKILL.md
  README.md
  README.en.md
  references/
    decode.md            reading words and signals
    policy.md            rules, policies, and company regulations
    power.md             position, interests, and situations
    sunzi.md             the Art of War checklist
    boundary.md          boundaries, refusal, and self-protection
    epistemics.md        judgment discipline
    ethics.md            ethical limits and scenario walkthroughs
    casebook.md          how the experience layer works
    templates/           experience-layer templates
    playbook/
      workplace.md       ten workplace scenarios
      officialdom.md     eight bureaucratic scenarios
      renqing.md         seven social-obligation scenarios
      common-traps.md    twenty common traps
```

The reference library is currently written in Chinese. The skill's trigger description is bilingual, and it can answer in English, but the detailed playbooks are Chinese-first for now.

## Design principles

- **Separate method from experience**: share the method, keep the experience private.
- **Verdict first, details on request**: like a strategist, set the direction before expanding.
- **Ordinary before malicious**: when evidence is thin, assume the most ordinary explanation.
- **One is an accident, two is a pattern, three is a rule**: do not let a single bad experience become a bias.
- **Record behavior, not people**: store signals and outcomes, not names and grudges.
- **See through, do not call out**: information advantage is not the same as action advantage.

## One line

**"Wits" is not a dirty word. It just means you saw the situation before everyone else did.**

---

If this README reminds you of a moment when you got played, it was probably written for you.
