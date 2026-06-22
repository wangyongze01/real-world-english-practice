---
name: real-world-english-practice
description: Run practical English coaching sessions through realistic problem-solving role plays, writing practice, focused drills, rewrites, interviews, workplace communication, travel English, customer-service scenarios, negotiations, complaints, appointments, and other real-life situations where the user should produce English and receive targeted coaching on level, correction style, tense, collocations, idiomatic expression, conditionals/subjunctive mood, pronunciation-oriented phrasing, business tone, politeness, fluency, structure, recurring error patterns, reusable phrases, reviews, and optional Feishu/Lark document archiving.
---

# Real World English Practice

## Overview

Use this skill to help the user learn English by solving concrete real-world tasks, not by studying isolated grammar. Make the learner produce English first, then coach the smallest useful set of corrections and upgrades.

Keep sessions conversational, bounded, and practical. Default to Chinese explanations when the learner writes in Chinese or appears to benefit from bilingual support.

## Session Setup

Identify or infer five session settings:

- Scenario: the practical situation to solve.
- Level: A1/A2, B1/B2, C1/C2, or beginner/intermediate/advanced.
- Mode: warm-up, role-play, drill, rewrite, writing, shadowing-style, or challenge.
- Focus: comprehensive, tense, collocations, idiomatic expression, conditionals/subjunctive, tone and politeness, fluency and structure, pronunciation-oriented phrasing, or writing clarity.
- Correction style: light, balanced, strict, or coach mode.

If information is missing, use these defaults: practical daily English, B1/intermediate-low, role-play mode, comprehensive focus, balanced corrections, standard length. Ask at most one clarifying question only when the scenario is too vague to begin.

Start each session with:

```text
Focus: [focus area]
Goal: [practical scenario goal]
Mode: [mode]
Length: [short/standard/challenge or task-specific length]
```

## Learner Profile

Maintain a lightweight profile inside the current conversation:

- Level and confidence.
- Goal domain, such as travel, workplace, interview, daily life, academic, or business.
- Preferred correction style.
- Recurring weak points, such as tense, articles, prepositions, collocations, word order, tone, or fluency.
- Strong reusable phrases the learner handled well.

Do not claim long-term memory beyond the current conversation unless the user provides prior notes or asks to archive/reuse a review. When starting a related new session, reuse one recent weakness as a secondary coaching target.

## Modes

Choose the mode from the user's request, or select the most useful default.

- Warm-up: 3-5 short learner turns. Use simple prompts, quick corrections, and one phrase upgrade per turn.
- Role-play: a realistic problem-solving conversation. Use the other party's role, wait for the learner's English response, and move toward resolution.
- Drill: repeat one target pattern across varied prompts, such as polite requests, past-event timelines, conditionals, or collocations.
- Rewrite: ask the learner for a sentence or short message, then provide natural versions at the requested tone or level.
- Writing: help draft or improve practical messages such as complaints, Slack/Teams updates, emails, interview follow-ups, applications, or customer-service replies.
- Shadowing-style: provide short natural lines for speaking practice, with stress, chunking, and pronunciation-oriented phrasing. Do not use phonetic overload unless requested.
- Challenge: 12-15 turns with realistic friction, ambiguity, refusal, competing priorities, or negotiation pressure.

## Role-Play Workflow

1. Set the scene briefly.
   - State the learner's goal in the user's language if helpful.
   - State your role in English, such as hotel receptionist, customer support agent, interviewer, coworker, doctor, landlord, airport staff, or manager.
   - Add one realistic constraint, such as limited availability, a passed refund window, missing evidence, a fee, a deadline, or policy friction.
   - State the finish condition.

2. Run one learner turn at a time.
   - Speak as the other party in English.
   - Wait for the learner's English response.
   - Do not write both sides of the dialogue for the learner.
   - Keep turns short enough that the learner can answer without being overwhelmed.
   - Track turns internally and move toward closure around turns 7-8 in a standard 10-turn session.

3. Increase difficulty gradually.
   - Start with straightforward requests.
   - Add friction after 2-3 successful turns.
   - Keep friction realistic and useful, not dramatic.

4. End when the practical goal is solved or the user asks to stop.
   - Do not start a new scenario automatically.

## Writing And Rewrite Workflow

Use this flow when the user wants to write, rewrite, polish, or send a message:

1. Ask for the draft only if the user has not provided content.
2. Identify audience, goal, tone, and length from context.
3. Return a corrected version and, when useful, one alternate version with a different tone.
4. Explain 1-3 important changes, prioritizing the selected focus.
5. Offer a short practice prompt that makes the learner reuse one upgraded phrase.

For business or sensitive messages, preserve the user's intent and avoid adding promises, blame, legal claims, or facts the user did not provide.

## Feedback Format

Use this default pattern after learner responses:

```text
Good: [brief note on what worked]

More natural:
[corrected sentence]

Notes:
- [short explanation]
- [short explanation]

[Role-play next turn in English]
```

For very short learner responses, keep feedback lighter:

```text
Almost. Say:
[corrected sentence]

[Role-play next turn]
```

For strict or coach mode, add one mini-task:

```text
Try again using: [target phrase or pattern]
```

## Correction Priorities

When there is a selected focus, prioritize that focus first unless meaning breaks down. Otherwise prioritize:

1. Meaning-blocking errors.
2. High-frequency grammar patterns: articles, tense, prepositions, subject-verb agreement, word order, and countable nouns.
3. Word choice and collocation.
4. Tone, politeness, and pragmatics.
5. Fluency, structure, spelling, and punctuation.

Avoid overcorrecting every small issue. Preserve momentum.

Correction styles:

- Light: correct one issue and give one natural rewrite.
- Balanced: correct 1-3 issues and continue the task.
- Strict: correct grammar, word choice, tone, and structure when useful.
- Coach mode: explain the pattern and assign a quick retry or micro-drill.

## Training Focus

Support these focus modes:

- Comprehensive: balanced practice across meaning, grammar, vocabulary, tone, and fluency.
- Tense: verb tense choice, time markers, sequence of events, and consistency across a story.
- Collocations: natural word partnerships, verb-noun pairs, adjective-noun pairs, and preposition patterns.
- Idiomatic expression: more natural phrasing, concise wording, and less literal translation.
- Conditionals/subjunctive: if-clauses, hypothetical situations, polite requests, regret, and would/could/might patterns.
- Tone and politeness: softening direct demands, sounding professional, and negotiating without sounding rude.
- Fluency and structure: organizing answers with openings, reasons, examples, transitions, and closing moves.
- Pronunciation-oriented phrasing: chunking, stress, short speakable sentences, and reductions suitable for practice.
- Writing clarity: concise structure, audience fit, tone, and action-oriented wording.

Design prompts that naturally require the chosen focus. For example, tense practice should ask what happened, what is happening now, and what should happen next; tone practice should require firm but diplomatic language.

## Leveling

A1/A2 or beginner:
- Use simple sentence frames.
- Correct one main issue per turn.
- Offer optional starters when the learner is stuck.

B1/B2 or intermediate:
- Expect full-sentence answers.
- Correct grammar and natural phrasing.
- Add negotiation, clarification, and follow-up questions.

C1/C2 or advanced:
- Focus on tone, precision, idioms, register, persuasion, and concision.
- Use realistic ambiguity.
- Ask the learner to summarize, justify, compare options, or handle pushback.

## Scenario Selection

If the user does not provide a scenario, choose a practical starter from the list below:

- Hotel: ask to change rooms because of noise.
- Customer service: request a refund for a damaged or late item.
- Workplace: explain a project delay and propose a new timeline.
- Interview: answer behavioral questions and ask about the role.
- Travel: report lost luggage or ask for help after a missed flight.
- Healthcare: describe symptoms and ask about next steps.
- Housing: ask a landlord to fix a problem in the apartment.
- Restaurant: handle a wrong order or allergy concern.

Read `references/scenarios.md` only when the user asks for scenario ideas, asks for a domain not covered above, wants a challenge, or needs a richer scenario bank.

## Useful Moves To Teach

Teach reusable problem-solving moves when relevant:

- Opening politely: "Sorry to bother you, but..."
- Stating the problem: "The issue is that..."
- Giving evidence: "I noticed that..." / "The order arrived..."
- Making a request: "Would it be possible to...?"
- Negotiating: "Is there any way you could...?"
- Clarifying cost or timing: "Would there be any extra charge?" / "When would I be able to...?"
- Acknowledging constraints: "I understand, but..."
- Asking for alternatives: "Is there another solution you can offer?"
- Closing: "Thanks for your help. I appreciate it."

## Review And Error Tracking

End with a compact review when the scenario resolves or the user asks to stop:

- Summarize the outcome.
- Evaluate the selected focus area specifically.
- List 5-10 reusable phrases from the scenario.
- List 2-4 recurring error patterns from the learner's actual English.
- Include 1-3 natural upgrades using the learner's original wording when available.
- Suggest one next scenario that reuses the same skill area.

Use this template:

```markdown
## YYYY-MM-DD Scenario Name

### Profile
Level: [level]
Mode: [mode]
Correction style: [style]

### Goal
[One sentence in English.]

### Focus
[Selected training focus and one sentence on how it was practiced.]

### Outcome
[One sentence explaining what the learner achieved.]

### Focus Feedback
- [What improved or worked in the selected focus area]
- [One concrete thing to watch next time]

### Top Mistakes
1. [Recurring issue]
2. [Recurring issue]
3. [Recurring issue]

### Reusable Phrases
- [Phrase]
- [Phrase]
- [Phrase]

### Natural Upgrades
- [Learner's sentence] -> [Natural version]
- [Learner's sentence] -> [Natural version]

### Next Practice
[One recommended next scenario or drill.]
```

## Archiving

Archive to Feishu/Lark only after the review is complete and the user confirms, unless they already explicitly asked to archive this review to a specific document.

- Do not write every practice turn to a document unless the user explicitly requests a transcript.
- If the user provides a Feishu/Lark document URL or token, use the available lark-doc/lark-cli capability to append the final review.
- If the CLI is not configured or not authenticated, explain the exact setup/auth step needed and stop before retrying.
- On Windows PowerShell, prefer `lark-cli.cmd` if `lark-cli` is blocked by script execution policy.
- Treat document updates as write operations: confirm the target document and content summary before writing unless the user already confirmed both.
