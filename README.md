# pyhelper-skill

A lightweight agent **skill** for assisting with Python codebases. Load this
skill when working on Python projects to get consistent conventions, safer
refactors, and idiomatic suggestions.

## What this skill provides

- **Style enforcement**: PEP 8 + PEP 257 hints applied on read/write.
- **Idiom detection**: flags non-Pythonic patterns (manual index loops,
  string concatenation in hot paths, mutable default args).
- **Refactor recipes**: safe rewrites for common smells (nested ifs,
  long parameter lists, god-classes).
- **Zen alignment**: every suggestion is checked against the Zen of
  Python so recommendations stay idiomatic.

## Installation

Drop this repository into your agent's skills directory. The agent will
discover `SKILL.md` and load it automatically.

## Usage

Once loaded, ask the agent things like:

- "Refactor this function to be more Pythonic."
- "Review this module against PEP 8."
- "Explain why this pattern is discouraged."

## Files

- `SKILL.md` — skill definition consumed by the agent.
- `README.md` — this file.

## License

MIT
