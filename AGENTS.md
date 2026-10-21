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
  B8000-H and the icons of the programs and of the shell's groups
  (`brand/icons/`; Firefox has none on purpose). `brand/README.md`
  (Russian) says what each file is for and where it is used.

There is no code, no package and no release here. A push of `profile/` to
`main` shows on the organization page at once; the organization avatar is
uploaded by hand in the organization settings.

## Rules

- Decisions, plans and the registry of repositories live in
  [haltia-de/haltia](https://github.com/haltia-de/haltia); link there
  instead of repeating them. Shared rules:
  [docs/conventions.md](https://github.com/haltia-de/haltia/blob/main/docs/conventions.md).
- `brand/icons/` holds the sketches of the icons in one style (rules in
  `brand/README.md`). What users see ships elsewhere: each program's icon
  from its own `data/`, and calculator, cards and service from
  haltia-de/shell `share/icons/`. Some have drifted apart (messenger and
  music draw differently); when you change an icon, change both places.
- Screenshots must not show personal data (chats, accounts, names): this
  repository is public.
- Issues are turned off here: work on this repository is tracked in
  haltia-de/haltia.
