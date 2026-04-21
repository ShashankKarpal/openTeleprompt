# OpenTeleprompter (Fork)

Forked from [ArunNGun/openTeleprompt](https://github.com/ArunNGun/openTeleprompt), full credit to [Arun Kumar](https://github.com/ArunNGun) for building this.

---

## Why this fork exists

Came across this project and liked the idea immediately. A local, private, voice-activated teleprompter with no subscriptions or cloud dependency is exactly the kind of tool worth exploring. This fork is my personal workspace for testing and adapting it to my own workflow. Any improvements worth sharing will go back upstream as PRs.

---

## Use cases I am exploring

- Presentations and demos with structured talking points, not word-for-word scripts
- Panel discussions where bullet-point prompts work better than full paragraphs
- Recordings and calls where staying on message matters
- Situations where key points need to be visible while speaking naturally

---

## Development approach

This fork follows a behavior-first framework. Each version proves one user behavior has changed, not just that a feature was shipped. No version starts until the previous one is validated.

| Version | Behavior to prove | Completion criterion | Status |
|---------|-------------------|----------------------|--------|
| v0.1 | **Entry:** I can go from having a script to presenting in under 60 seconds | Used for one real presentation, friction points documented | In progress |
| v0.2 | **Return:** I reach for this tool before every call without hesitation | Used voluntarily 3+ times over two weeks | Not started |
| v0.3 | **Action:** I prepare content differently because I know I will use this tool | Prep workflow has visibly changed | Not started |
| v1.0 | **Habit:** I do not present without this tool | It is part of my standard toolkit without thinking about it | Not started |

---

## Current status

- Built from source on Apple Silicon (M4 Pro, macOS)
- App bundled and installed via `npm run build`
- No code changes yet, still in the v0.1 audit phase

---

## What is next

After the v0.1 audit, planned exploration areas include:

- File import (.txt, .md) to replace paste-only input
- Named script slots for quick switching between scripts
- Content modes (full script vs. bullet points vs. FAQ pairs)
- Section markers with keyboard shortcuts for jumping between segments
- Font and contrast controls for different display environments

These are directions, not commitments. Scope will be determined by what the v0.1 audit reveals.

---

## Contributing back

If any changes made here are useful to the broader project, they will be submitted as PRs to [ArunNGun/openTeleprompt](https://github.com/ArunNGun/openTeleprompt). This fork exists to experiment freely, not to fragment the project.

---

## Build instructions

Same as upstream. Requires Rust + Cargo and Node.js 18+.
npm install
npm run build

For full documentation, features, and release downloads, see the [original project](https://github.com/ArunNGun/openTeleprompt).
