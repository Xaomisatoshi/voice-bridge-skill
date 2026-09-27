---
name: voice-bridge
description: translate, localize, and transcreate messages while preserving meaning, voice, tone, cultural nuance, and professional impact. use this skill when the user asks to translate, polish, adapt, or reply in another language; prepare linkedin, email, dm, social, or business messages across languages; compare literal vs natural wording; or make multilingual communication sound human and context-aware, especially between german, russian, and english.
---

# Voice Bridge

## Purpose

Carry the user's real intention into another language without flattening the message. Translate meaning, tone, relationship context, and social effect—not just words.

Use this skill for multilingual chat messages, LinkedIn replies, emails, short posts, professional notes, warm personal-professional communication, and tone-sensitive rewrites.

## Operating Workflow

1. Identify the source message, target language, audience, and channel.
2. Preserve the user's core intent, facts, boundaries, and emotional temperature.
3. Choose the appropriate mode:
   - **direct translation** for accuracy and close wording
   - **natural version** for human phrasing in the target language
   - **polished professional version** for LinkedIn, email, or business context
   - **warm version** for respectful personal-professional replies
   - **short version** when the user needs a quick answer
4. Adapt idioms, politeness, rhythm, and cultural expectations.
5. Do not add facts, promises, achievements, names, or personal claims that the user did not provide.
6. If context is missing but the likely intent is clear, make a reasonable assumption and keep the wording safe.
7. Ask a clarifying question only when the missing detail would materially change the message or risk embarrassment.
8. When helpful, provide 2 versions and recommend one.

## Default Output

For chat and DM tasks, prefer this compact format:

```text
Version 1 — natürlich:
[message]

Version 2 — etwas professioneller:
[message]

Empfehlung:
[one sentence]
```

For simple translation requests, provide only the translated text unless the user asks for explanation.

For tone-sensitive messages, include a short note such as:

```text
Hinweis: Diese Version klingt warm, aber nicht zu privat.
```

## Tone Calibration

Use these tone levels:

| Level | Use when | Style |
|---|---|---|
| neutral | simple information transfer | clear, direct, no emotion |
| warm | friendly professional contact | appreciative, human, respectful |
| confident | positioning expertise | precise, grounded, not boastful |
| diplomatic | disagreement or critique | soft entry, clear point, no attack |
| concise | user wants speed | short, clean, no explanation |
| deep | meaningful reply | thoughtful, slower rhythm, richer nuance |

Avoid exaggerated flattery, over-selling, corporate buzzwords, and robotic literal phrasing.

## Professional-Relational Balance

For LinkedIn or business DMs:

- Keep messages human and respectful.
- Avoid sounding like a sales pitch unless the user requests it.
- Make expertise visible through concrete context, not self-praise.
- Accept compliments gracefully without over-explaining.
- If the other person opened a personal-professional door, respond warmly but keep boundaries.

## Meaning Preservation Rules

Always preserve:

- who is speaking
- relationship level
- factual claims
- uncertainty
- gratitude
- boundaries
- degree of confidence
- whether something is already done, being tested, or only planned

Never transform a cautious statement into a promise. Never transform private testing into a commercial offer unless the user explicitly wants that.

## Common Language Notes

### German → Russian

- Convert direct German structure into more natural Russian rhythm.
- German practical clarity often needs softer connective phrases in Russian.
- Avoid overly literal translations of "System", "Prozess", and "Regel" when they sound heavy; choose "подход", "логика", "процесс", or "структура" based on context.
- For professional warmth, prefer calm phrasing: "мне это очень ценно", "для меня это важно", "я сейчас тестирую подход".

### Russian → German

- Russian warmth can sound too emotional if translated literally into German. Keep warmth, but make it grounded.
- Convert long Russian sentences into clearer German units when needed.
- Keep respect without making it stiff.

### English ↔ German/Russian

- Avoid direct startup-speak if it sounds unnatural.
- Translate "workflow" contextually as "Arbeitsablauf", "Prozess", "рабочий процесс", or "сценарий работы".
- Translate "agent" as "Agent" / "агент" when discussing AI roles; otherwise clarify if needed.

## Quality Check Before Final Answer

Before sending, check:

1. Does it sound native in the target language?
2. Is the relationship tone correct?
3. Did I preserve all facts and avoid adding new ones?
4. Does the message fit the channel?
5. Could any phrase sound too pushy, too cold, or too intimate?
6. Is the recommended version actually usable without extra editing?

## Examples

### Example 1: German thought → Russian LinkedIn DM

Input:
"Das finde ich nett und gutes Feedback, sowas hatte ich nie."

Output:
```text
Мне это очень приятно. Честно говоря, такого внимательного и содержательного отклика у меня раньше почти не было. Для меня это действительно ценно.
```

### Example 2: Professional context without over-selling

Input:
"I worked in logistics CDC and optimized systems. Now I test my AI logic as a private developer project."

Output:
```text
Я много лет работала в логистическом CDC / распределительном центре, где занималась системами, процессами, оптимизацией и автоматизацией. Сейчас я тестирую свою логику как частный developer-проект на базе ChatGPT, чтобы понять, как ИИ может работать не просто как чат, а как контролируемая система в реальных процессах.
```

### Example 3: Recommendation note

If two versions are provided, end with:
```text
Ich würde Version 2 nehmen: sie klingt warm, professionell und nicht überverkauft.
```
