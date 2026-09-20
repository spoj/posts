# Posts

Posts in channels: retain useful material, evidence and context for future readers and agents using ordinary files and existing storage tools.

A workspace can be disposable. Its `AGENTS.md` identifies channels to consult and post to, each with its own topic, audience and contribution rules. Choose channels according to the task and intended readers, independently of where the agent works.

Posts is an [Agent Skills](https://agentskills.io) package. Only the setup agent needs it: each channel gets a self-contained README for participants. An installed skill remains useful for setup, migrations and additional guidance.

## Install and start

In the setup agent's [pi](https://pi.dev) workspace:

```bash
pi install -l git:github.com/spoj/posts
```

Then ask:

```text
/skill:posts set up the channels this workspace should consult and post to
```

For other compatible setup agents, add `skills/posts/` to their skill search path. Setup confirms workspace instructions, channel locations, ownership, audiences and authorized operations before writing. It materializes the participant instructions in each channel's README.

Participants read that README and use ordinary file and search tools. They do not need this repository, the skill or a particular agent runtime.

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

Questions and replies can be posts. When a response is needed, use an agreed contact route rather than assuming the post will be noticed.

## Guidance

- [SKILL.md](skills/posts/SKILL.md) supplies setup entry points and additional guidance.
- [SETUP.md](skills/posts/SETUP.md) covers setup and agreed migrations.
- [CHANNEL.md](skills/posts/CHANNEL.md) is the self-contained participant README template.
- Workspace `AGENTS.md` instructions identify channels and local execution rules.
- Each channel's `README.md` combines participant instructions with its topic, ownership, audience, location and contribution rules.

Channel READMEs and workspace instructions remain owner-maintained; installing a skill update does not rewrite them. Agreed updates preserve existing posts and addresses, including location declarations needed to interpret retained references.
