# Works

A communication channel to future agents: a collection of dated folders, each retaining a message with useful material, evidence and context.

Messages are free-form. One may contain an original email; another may hold a substantial investigation with documents, calculations, code and results. Explanation supplies context where the material needs it. Evidence can live alongside the message or at a dependable referenced location.

Works is an [Agent Skills](https://agentskills.io) package for ordinary files and existing storage tools.

## Install and start

In [pi](https://pi.dev):

```bash
pi install git:github.com/spoj/works
```

Open pi in the intended workspace and ask:

```text
/skill:works setup here
```

For other compatible agents, add `skills/works/` to their skill search path. Setup confirms the collection location, ownership, audience and authorized operations before writing.

## Messages

Use the chosen collection folder directly. For example:

```text
README.md
2026-09-19-owner-email/
    message.eml
2026-09-20-invoice-check/
    observation.md
    query.sql
    result.csv
```

New message folders use `YYYY-MM-DD-short-description/`, dated when first recorded. Their addresses remain stable. Source and observation dates travel with the material so future readers can understand when it applies.

Preserve original evidence and the distinctions between observations, inferences, proposals and decisions. Prefer adding developments and corrections as new messages, identifying affected earlier material when known. Meaning-preserving edits can be made in place.

Routine contributions add messages; collection-wide changes follow the owner's explicit request. Agents use ordinary tools to investigate the current question and generate explanations for the present audience at use time. New evidence, observations, decisions and reasoning can become further messages.

## Connections and other collections

Use relative Markdown links within a collection and ordinary provider URLs across collections. Source identity, dates and versions help readers locate the relevant material.

Each collection retains its own ownership, structure and contribution rules. Use its available access routes and formats. Choose copying or linking according to authorization, expected access and version stability. Shared messages carry context and evidence routes suitable for their recipients.

Personal followed locations and access notes belong in private local instructions. Storage permissions, sharing and Git operations follow the owner's authorization.

## Guidance

- [SKILL.md](skills/works/SKILL.md) contains the capture, retrieval and sharing protocol.
- [SETUP.md](skills/works/SETUP.md) covers setup and agreed migrations.
- Each collection's `README.md` records its ownership, audience, location and contribution rules.
- An optional, owner-maintained `AGENTS.md` holds local instructions.

Keep the reusable method in the skill and local facts in the collection's own guidance. Updates to existing collections preserve their records and addresses, including location declarations that explain retained references.
