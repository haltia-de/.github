# AGENTS.md

Guidance for coding agents (Claude Code, Codex and others) working in
**haltia-de/.github**, the organization's profile repository. `CLAUDE.md`
only includes this file.

## What this is

- `profile/README.md` is the page GitHub shows at
  [github.com/haltia-de](https://github.com/haltia-de): the story of Haltia,
  the programs, how to install them, screenshots. Russian first, with short
  English paragraphs in italics. Pictures live beside it (`haltia.svg`,
  `haltia-splash.png`, `screens/`).
- `brand/` is the brand: the sign of Haltia and its sizes, the signs of the
  Pertin Haltia images, the organization avatar, the boot splash of the
  B8000-H and one icon per program (`brand/icons/`). `brand/README.md`
  (Russian) says what each file is for and where it is used.

There is no code, no package and no release here. A push to `main` shows on
the organization page at once.

## Rules

- Decisions, plans and the registry of repositories live in
  [haltia-de/haltia](https://github.com/haltia-de/haltia); link there
  instead of repeating them. Shared rules:
  [docs/conventions.md](https://github.com/haltia-de/haltia/blob/main/docs/conventions.md).
- Program icons here are the source; a program repository keeps its own
  copy under `data/`. Change both together.
- Screenshots must not show personal data (chats, accounts, names): this
  repository is public.
- Issues are turned off here: work on this repository is tracked in
  haltia-de/haltia.
