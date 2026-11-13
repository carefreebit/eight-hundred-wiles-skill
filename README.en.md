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

## How to use it

Just ask, as if talking to a seasoned strategist:

- "My boss said 'you lead this project, the credit is all yours.' What does he mean?"
- "The company now requires approval for every external commitment. What is this really about?"
- "A colleague presented my work as his in a meeting. What should I do?"
- "Something similar happened to me before. Help me review it."

By default you get a **strategist's brief**: the judgment, the critical point, three actions, one sentence you can say, and a confidence level. Say "expand" for the full analysis.

### Three common modes

**Decode**

> Paste a sentence, or describe a scene. It tells you what is on the surface and what is underneath.

**Strategize**

> Explain your position and your worry. It gives you three tiers of options and a worst-case fallback.

**Review**

> Tell it something that already happened. It reconstructs the signals, extracts the lesson, and records it in your personal casebook.

## Installation

Place the whole `xinyanzi/` directory in your user-level skills folder:

```
~/.claude/skills/xinyanzi/
```

Or at the project level:

```
<project>/.claude/skills/xinyanzi/
```

Restart Claude Code to pick it up. The skill name is `xinyanzi`.

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
