# Inventor Lab Games

**A family-led experiment in human-centred AI, creative problem-solving and learning through play.**

## Why this project exists

Inventor Lab is a parent-led learning project built around a simple question: *How can a child use AI to turn an idea into something real, while developing the ability to think independently?*

The goal is not to teach a seven-year-old to write software. The goal is to nurture creativity, reading, writing, reasoning, decision-making and the habits of an inventor: imagine, make, test, investigate and improve.

The games are the tangible outcome. The important learning happens in the decisions, explanations and iterations that create them.

## Our approach: people lead, AI assists

Responsibilities are intentionally clear:

- **The child is the inventor.** He imagines the worlds, characters, rules and features, describes what he wants, tests the results and decides what to change.
- **The parent is the facilitator.** I guide the discussion, supervise AI interactions, challenge assumptions, help prioritise and handle practical setup and safety.
- **AI is the technical assistant.** It translates instructions into playable prototypes, proposes possible solutions and helps address defects. Its output is not assumed to be correct.

The child is encouraged to write and read his own instructions, with adult supervision. He does not need to understand the generated code to take ownership of the product decisions.

## The learning loop

1. **Imagine** — Express an idea and agree on the simplest useful version.
2. **Create** — Ask AI to make a playable prototype.
3. **Play** — Try it on a computer or iPad.
4. **Investigate** — Compare what happened with what was intended.
5. **Improve** — Describe one change clearly and test again.
6. **Reflect** — Identify what was learned and choose the next experiment.

This is deliberately iterative rather than prescriptive. AI can misunderstand a request, introduce a bug or overcomplicate a solution. Recognising and correcting those outcomes is part of the learning.

## Why this matters beyond the game

My professional background is in **strategy, operations and transformation**, not software development. This personal project applies principles that matter in any practical AI-enabled change initiative:

- **Human ownership and judgment:** Clear accountability for goals, choices and acceptance of results.
- **Strategy to execution:** Turning an idea into a working outcome through manageable steps.
- **Pragmatic adoption:** Using technology because it helps people achieve something, not because the technology is novel.
- **Experimentation and feedback:** Learning through observable results, adjusting quickly and retaining what works.
- **Capability building:** Helping someone become more confident and independent rather than making them dependent on a tool.
- **Responsible use:** Adult supervision, age-appropriate content, minimal personal data and no unnecessary commercial features.

This is a small family project, not a commercial product, a professional software engineering portfolio or a claim of educational research expertise. Its value lies in demonstrating a practical, human-centred way of working with AI.

## Games

### Marnep & Satjup — Planet Adventures

A browser-based platform adventure that begins on Marnep, a fictional planet inspired by Mars and Neptune, then unlocks Satjup as a longer, more challenging second level. The player moves, jumps, uses ladders, avoids moving obstacles and collects stars.

- **Current prototype:** v0.3
- **Game file:** [marnep/index.html](marnep/index.html)
- **Designed for:** Browser play on a computer and touch-friendly play on an iPad
- **Status:** Prototype; iPad behaviour still needs to be verified

The longer-term ambition includes additional planets and possibly two-player gameplay, guided by the child's choices.

### THEANIMALL — Animal Runner

A second game designed by a nine-year-old inventor. Players begin with a rabbit, cat or dog; run through animal-specific worlds; dodge approaching trains, monsters and rocks; and collect in-game coins to unlock more animals. Each playable animal has a different pursuer. Three hits end the run; the chase ends in a playful, non-graphic cartoon.

- **Current prototype:** v0.1
- **Latest playable game:** [theanimall/index.html](theanimall/index.html)
- **Preserved first release:** [theanimall/versions/v0.1/index.html](theanimall/versions/v0.1/index.html)
- **Designed for:** iPad Safari touch controls and desktop keyboards
- **Status:** First published prototype; real iPad playtesting needed
- **Language:** French, following the inventor's preference

## Release and publication process

Each playable update keeps a permanent URL for the newest stable game and a separate archive of previous versions.

For every accepted version:

1. Save a standalone, playable copy at `marnep/versions/vX.Y/index.html`.
2. Update `marnep/index.html` to the latest accepted game.
3. Update the library home page (`index.html`) with the new version's description where relevant. Its built-in JavaScript also reads the latest published game's version and the GitHub version folders to keep the displayed release and archive links in sync, even if the static fallback was not edited.
4. Verify the repository files and the GitHub Pages deployment. Test the game controls and gameplay separately, ideally on an iPad.
5. Report **created**, **tested** and **published** as three distinct statuses. A successful GitHub commit or Pages deployment is not proof of successful gameplay testing.

The homepage and latest-game URLs remain stable as new versions are released. The fallback HTML should still be updated alongside each release, and the runtime synchronisation protects visitors against an accidentally stale version label. The browser may cache a previously opened page until it is refreshed.

## Project principles

- Keep each game small and playable before adding complexity.
- Preserve working functionality when introducing changes.
- Explain problems in plain language; let the child make the creative decisions.
- Keep repository documentation in English. In-game language may vary as part of bilingual learning.
- Avoid advertising, purchases, public chat, personal profiles and unnecessary data collection.
- Treat AI-generated code as something to review and test, not as a guarantee.

---

*Built together as a family learning experience. The child leads the imagination; the parent provides guidance; AI helps make the ideas playable.*
