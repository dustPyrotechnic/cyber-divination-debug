# Cyber Divination Debug

A Kimi skill that turns a GitHub-issue quality gate into a short Yi-Jing / Mei-Hua style hexagram reading.

## Purpose

When someone reports a bug with insufficient evidence, this skill helps resist the urge to guess. Instead, it casts a symbolic hexagram from the time and scene, gives a short unverified conclusion, and asks for the missing diagnostic materials.

## Core Principle

- Evidence sufficient → analyze normally.
- Evidence insufficient → don't guess. Cast a short hexagram, describe the image, and ask for more materials.

## Trigger Phrases

- "Why the error?"
- "What's this bug?"
- "Clicked but no response"
- "Won't run"
- "Crashed"
- "Suddenly stopped working"
- "I didn't change anything"

## What It Does

1. Maps the question time to a trigram.
2. Builds a hexagram from time, scene, and error result.
3. Derives the 互卦 (mutual hexagram) and 体用 (body/function) relationship to enrich the divination frame.
4. Gives a two- to three-sentence "short divination" (短断) that is explicitly unverified.
5. Reviews the six-yao evidence map and lists the missing materials.
6. Asks the user to provide logs, screenshots, environment, version, reproduction steps, etc.

## What It Does NOT Do

- Predict root causes.
- Provide step-by-step fixes without evidence.
- Replace normal technical debugging.

## Installation

Copy the `cyber-divination-debug` directory into your project's skills folder or Kimi skills path.

## License

MIT
