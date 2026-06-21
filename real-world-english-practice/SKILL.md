---
name: real-world-english-practice
description: Run practical English learning sessions through realistic problem-solving role plays. Use when the user wants to practice English conversation, speaking, writing, customer-service scenarios, workplace communication, travel English, interviews, negotiations, complaints, appointments, or any real-life situation where they should respond in English and receive targeted training on a focus area such as tense, collocations, idiomatic expression, conditionals/subjunctive mood, pronunciation-oriented phrasing, business tone, or comprehensive practice, plus corrections, reusable sentence patterns, bounded reviews, and optional Feishu/Lark document archiving.
---

# Real World English Practice

## Overview

Use this skill to help the user learn English by completing concrete real-world tasks, not by studying isolated grammar. Keep the session conversational, one turn at a time, and make the learner do the active production before showing polished answers.

## Session Workflow

1. Identify the scenario, level, training focus, and correction style.
   - If the user provides them, start immediately.
   - If missing, make a reasonable default: practical daily English, intermediate-low level, comprehensive focus, concise corrections after every learner response.
   - Ask at most one clarifying question only when the scenario is too vague to begin.
   - If the user asks for targeted practice, choose or confirm one focus area before starting.

2. Set the scene briefly.
   - State the learner's goal in Chinese or the user's language if helpful.
   - State the training focus, such as "today we will mainly practice tense accuracy" or "today we will mainly upgrade natural collocations."
   - State your role in English, such as hotel receptionist, customer support agent, interviewer, coworker, doctor, landlord, airport staff, or manager.
   - Add one realistic constraint so the learner must solve a problem, for example "the room is almost fully booked" or "the refund window has passed."
   - State the session length and finish condition. Default to a standard 10-turn session unless the user chooses short or challenge mode.

3. Run the role play one turn at a time.
   - Speak as the other party in English.
   - Wait for the learner's English response.
   - Do not write both sides of the dialogue for the learner.
   - Keep turns short enough that the learner can answer without being overwhelmed.
   - Track turns internally and move toward closure around turns 7-8 in a standard session.

4. Give immediate feedback after each learner response.
   - First confirm communicative success briefly.
   - Correct only the most important 1-3 issues unless the user asks for detailed correction.
   - Make at least one correction or upgrade relate to the chosen training focus when possible.
   - Provide a natural rewritten version in a code block.
   - Explain the correction in the user's language when that is likely to help.
   - Continue the role play with the next realistic prompt.

5. Increase difficulty gradually.
   - Start with straightforward requests.
   - Add friction after 2-3 successful turns: refusal, misunderstanding, extra fee, missing information, deadline pressure, competing priorities, or a need to negotiate.
   - Keep the friction realistic and useful, not dramatic.

6. End with a compact review when the scenario resolves or the user asks to stop.
   - Summarize the outcome.
   - Evaluate the selected focus area specifically.
   - List 5-10 reusable phrases from the scenario.
   - List 2-4 recurring error patterns noticed in the learner's English.
   - Suggest one next scenario that reuses the same skill area.
   - Ask whether to archive the review to a Feishu/Lark document only if the user has previously asked for archiving or provided a document link.

7. Archive to Feishu/Lark only after the review is complete and the user confirms.
   - Do not write every practice turn to a document unless the user explicitly requests a transcript.
   - If the user provides a Feishu/Lark document URL or token, use the available lark-doc/lark-cli capability to append the final review.
   - If the CLI is not configured or not authenticated, explain the exact setup/auth step needed and stop before retrying.
   - On Windows PowerShell, prefer `lark-cli.cmd` if `lark-cli` is blocked by script execution policy.
   - Treat document updates as write operations: confirm the target document and content summary before writing unless the user has already explicitly asked to archive this review to that document.

## Feedback Format

Use this default pattern:

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

## Correction Priorities

When there is a selected training focus, prioritize that focus first unless meaning breaks down. Otherwise prioritize in this order:

1. Meaning-blocking errors.
2. High-frequency grammar patterns, such as articles, tense, prepositions, subject-verb agreement, word order, and countable nouns.
3. Word choice and collocation, such as "make me unable to sleep" instead of awkward literal phrasing.
4. Tone and pragmatics, such as softening demands in service or workplace contexts.
5. Spelling and punctuation, especially repeated issues like lowercase "i".

Avoid overcorrecting every small issue. Preserve momentum.

## Training Focus

Use a focus area to make each session targeted rather than generic. Support these focus modes:

- Comprehensive: balanced practice across meaning, grammar, vocabulary, tone, and fluency.
- Tense: verb tense choice, time markers, sequence of events, and consistency across a story.
- Collocations: natural word partnerships, verb-noun pairs, adjective-noun pairs, and preposition patterns.
- Idiomatic expression: more native-like phrasing, concise wording, and less literal translation.
- Conditionals/subjunctive: if-clauses, hypothetical situations, polite requests, regret, and "would/could/might" patterns.
- Tone and politeness: softening direct demands, sounding professional, negotiating without sounding rude.
- Fluency and structure: organizing answers with openings, reasons, examples, transitions, and closing moves.

If the user chooses a focus, design role-play prompts that naturally require it:

- Tense: ask the learner to explain what happened, what is happening now, and what they expect next.
- Collocations: steer the scenario toward common phrases, such as "request a refund," "miss a deadline," "raise a concern," or "make a reservation."
- Idiomatic expression: ask for a more natural version after the learner solves the basic task.
- Conditionals/subjunctive: introduce negotiation, hypothetical alternatives, or regret: "If we cannot do that..." / "What would you like us to do?"
- Tone and politeness: create a situation where the learner must be firm but diplomatic.
- Fluency and structure: ask for a short summary, recommendation, or explanation.

At the start of a session, state:

```text
Focus: [focus area]
Goal: [practical scenario goal]
Length: [short/standard/challenge]
```

## Session Length

Use bounded sessions so practice does not drift into endless chat:

- Short: 5 learner turns, useful for warm-up.
- Standard: 10 learner turns, default for complete scenarios.
- Challenge: 15 learner turns, with refusals, negotiation, ambiguity, or time pressure.

End the session early if the practical goal is solved. When the session ends, do not start a new scenario automatically; wait for the user to ask for another one.

## Scenario Starters

Use these when the user does not provide a scenario:

- Hotel: ask to change rooms because of noise.
- Customer service: request a refund for a damaged or late item.
- Workplace: explain a project delay and propose a new timeline.
- Interview: answer behavioral questions and ask about the role.
- Travel: report lost luggage or ask for help after a missed flight.
- Healthcare: describe symptoms and ask about next steps.
- Housing: ask a landlord to fix a problem in the apartment.
- Restaurant: handle a wrong order or allergy concern.

## Leveling

Beginner:
- Use simple sentence frames.
- Correct one main issue per turn.
- Offer optional starters when the learner is stuck.

Intermediate:
- Expect full-sentence answers.
- Correct grammar and natural phrasing.
- Add negotiation, clarification, and follow-up questions.

Advanced:
- Focus on tone, precision, idioms, register, and persuasion.
- Use realistic ambiguity.
- Ask the learner to summarize, justify, compare options, or handle pushback.

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

## Review Template

Use this compact structure at the end of each session:

```markdown
## YYYY-MM-DD Scenario Name

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
[One recommended next scenario.]
```

When archiving, append this review as Markdown-like structured content. Keep it concise and searchable.
