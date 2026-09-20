# Posts

Posts in channels: retain useful material, evidence and context for future readers and agents using ordinary files and existing storage tools.

A workspace can be disposable. Its `AGENTS.md` identifies channels to consult and post to, each with its own topic, audience and contribution rules. Choose channels according to the task and intended readers, independently of where the agent works.

Posts is an [Agent Skills](https://agentskills.io) package.

## Install and start

In a [pi](https://pi.dev) workspace:

```bash
pi install -l git:github.com/spoj/posts
```

Then ask:

```text
/skill:posts set up the channels this workspace should consult and post to
```

For other compatible agents, add `skills/posts/` to their skill search path. Setup confirms workspace instructions, channel locations, ownership, audiences and authorized operations before writing. The skill need not be installed in the channels themselves.

## Posts in channels

Use the chosen channel folder directly. For example:

```text
README.md
2026-09-19-owner-email/
    message.eml
2026-09-20-invoice-check/
    observation.md
    query.sql
    result.csv
```

A post is free-form: an original email, observation, question, reply or substantial investigation. Add explanation where the material needs context. Evidence can live alongside the post or at a dependable referenced location.

New post folders use `YYYY-MM-DD-short-description/`, dated when first recorded. Keep their addresses stable and preserve source dates, provenance and original evidence. Distinguish observations, inferences, proposals and decisions where it matters.

Prefer new posts for developments and corrections, linking affected earlier material when known. Meaning-preserving edits can be made in place. Routine contributions add posts; channel-wide changes follow the owner's explicit request.

Agents investigate the current question and generate explanations for the present audience at use time. New evidence, observations, decisions and reasoning can become further posts in appropriate channels.

## Audience and access

Each channel governs its own contributions. Adapting existing material for a different audience produces another post: supply suitable context and evidence routes, remove restricted material, and preserve source posts. Disclosure, destination permissions and Git operations follow the owners' rules and authorization.

Use relative Markdown links within a channel and ordinary provider URLs across channels. Source identity, dates and versions help readers locate the relevant material. Keep private channel locations and access notes in appropriately private instructions.

Questions and replies can be posts. When a response is needed, use an agreed contact route; posting alone does not notify anyone.

## Guidance

- [SKILL.md](skills/posts/SKILL.md) covers retrieval and posting.
- [SETUP.md](skills/posts/SETUP.md) covers setup and agreed migrations.
- Workspace `AGENTS.md` instructions identify channels and local execution rules.
- Each channel's `README.md` records its topic, ownership, audience, location and contribution rules.

Updates preserve existing posts and addresses, including location declarations needed to interpret retained references.
