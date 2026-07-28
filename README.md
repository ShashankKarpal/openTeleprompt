<h1 align="center">OpenTeleprompter (Fork)</h1>

<p align="center"><b>A personal fork of OpenTeleprompter, currently tracking upstream with no code changes.</b></p>

<p align="center">
  <img alt="Fork" src="https://img.shields.io/badge/fork%20of-ArunNGun%2FopenTeleprompt-1C1B1D?style=flat-square">
  <img alt="Status" src="https://img.shields.io/badge/status-tracking%20upstream-1C1B1D?style=flat-square">
  <img alt="Changes" src="https://img.shields.io/badge/own%20changes-CI%20sync%20only-1C1B1D?style=flat-square">
  <img alt="Stack" src="https://img.shields.io/badge/built%20with-Tauri%20%C2%B7%20JS-1C1B1D?style=flat-square">
</p>

## Attribution

Forked from [ArunNGun/openTeleprompt](https://github.com/ArunNGun/openTeleprompt). Full credit to [Arun Kumar](https://github.com/ArunNGun) for building it. A local, private, voice-activated teleprompter with no subscription and no cloud dependency is worth exploring, and this fork exists to test it against a real workflow. Anything worth sharing goes back upstream as a pull request rather than staying here.

For features, documentation, and release downloads, see the [original project](https://github.com/ArunNGun/openTeleprompt).

## What this fork adds

- A daily GitHub Actions job that fast-forwards this fork from upstream.
- Nothing else yet. No code changes have been made.

## Use cases being evaluated

- Presentations and demos with structured talking points rather than word-for-word scripts.
- Panel discussions where bullet prompts work better than paragraphs.
- Recordings and calls where staying on message matters.
- Situations needing key points visible while speaking naturally.

## Build

Requires: Rust and Cargo, Node.js 18 or later. Same as upstream.

```bash
git clone https://github.com/ShashankKarpal/openTeleprompt.git
cd openTeleprompt
npm install
npm run build
```

## Roadmap

Every version must prove one behavior changed, not that a feature shipped. No version starts until the previous one is validated.

| Version | Behavior to prove | Completion criterion | Status |
|---|---|---|---|
| v0.1 | Entry: script to presenting in under 60 seconds | Used for one real presentation, friction documented | In progress |
| v0.2 | Return: reached for before every call | Used voluntarily 3 or more times over two weeks | Planned |
| v0.3 | Action: content is prepared differently because the tool exists | Prep workflow has visibly changed | Planned |
| v1.0 | Habit: not presenting without it | Part of the standard toolkit | Planned |

Directions under consideration after the v0.1 audit, none committed: file import for `.txt` and `.md`, named script slots, content modes (full script, bullets, FAQ pairs), section markers with keyboard shortcuts, font and contrast controls.

## License

**Upstream publishes no licence.** The [original project](https://github.com/ArunNGun/openTeleprompt) ships no `LICENSE` file and declares no licence field, which means the code is all rights reserved by its author. This fork adds no licence of its own and grants no rights it does not hold. Treat it as viewable source, not open source.

If you want to use this, ask the upstream author.

## Author

Fork maintained by Shashank Karpal. Upstream by Arun Kumar.
