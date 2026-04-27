# NORTH-STAR.md

A career-level direction file. The big picture of where you're heading, separate from any single project. Sits at the root of your workspace and gets loaded when you need to make strategic decisions.

This is one of a family of five templates that customise AI for the way you actually work.

| Template | What it covers | When to do it |
|----------|----------------|---------------|
| **[CLAUDE.md](https://github.com/catrinmdonnelly/CLAUDE.md)** | Who you are, how you work, what's on your desk | First. Even if you do nothing else, this gets you 70% of the value |
| **[COPY.md](https://github.com/catrinmdonnelly/COPY.md)** | How things should sound. Voice + banned phrases | Second. Voice is the most-violated AI default |
| **[DESIGN.md](https://github.com/catrinmdonnelly/DESIGN.md)** | How things should look. Design tokens + banned aesthetics | Third. Only if you make visual things (websites, slides, social posts) |
| **[CONTEXT.md](https://github.com/catrinmdonnelly/CONTEXT.md)** | What each project is and where it's going | Per project, when you start working in a specific folder |
| **[NORTH-STAR.md](https://github.com/catrinmdonnelly/NORTH-STAR.md)** (this repo) | Career-level direction. The why behind the projects | Last, and only if you have multiple businesses or want to think strategically |

You don't have to do all five. The minimum useful set is **CLAUDE.md + COPY.md**. Add the others as you need them.

They reference each other. Your CLAUDE.md tells AI to read the others when the relevant work comes up, so you do not have to think about which file is needed when.

## Why this exists

If you have **one project**, you don't need a NORTH-STAR.md. Your CLAUDE.md priorities and your project's CONTEXT.md tell the whole story. Skip this template.

If you have **multiple projects, businesses, or directions**, you need a file that explains why those exist together. Without it, every cross-project decision happens in a vacuum:

- Should I take on a fourth business?
- Should I sunset one of these?
- Which client opportunity fits the long game?
- Why am I working on this and not that?

NORTH-STAR.md answers those questions. It's the umbrella the projects sit under.

## Built on the work of others

The "where am I heading" document isn't new. If anything in here is good, the credit goes to:

- **[Derek Sivers](https://nownownow.com)** for popularising the "now page" convention. The "Active projects" and "Review cadence" sections borrow from this thinking.
- **The phase-model concept**, which is common in business strategy, lean methodology, and personal finance planning. Naming the phases helps you see where you are and stops you trying to skip steps.
- **The personal-strategy literature broadly**: *On Writing Well* by William Zinsser, *The Effective Executive* by Peter Drucker, the manifesto genre. The principles section in particular owes a lot to this tradition.

What's mine is the integration with CLAUDE.md and CONTEXT.md as a coherent family, the "what I'm not building" section (the most-skipped, most-useful one), and the explicit "how I decide" rules for resolving hard choices.

## Who it's for

- **Solo founders running multiple ventures** (consulting + product + side project)
- **Consultants** with several brands or service lines
- **Anyone in a phase of career change** where the direction matters more than any single project
- **People with messy ambitions** who need to write them down to get clear

## What's in this repo

| File | What |
|------|------|
| `NORTH-STAR.md` | The template. Drop it at your workspace root, walk through with Claude, save the clean version. |

The template uses HTML comments throughout. Paste it into Claude, get walked through it section by section, end up with a clean file.

## How to use

### Conversational (the easy way)
1. Copy the contents of `NORTH-STAR.md` from this repo
2. Paste it into a Claude chat
3. Answer the questions, one at a time. Take your time. These are big questions.
4. Claude outputs a clean NORTH-STAR.md (no comments) ready to save at your workspace root

### Manual
1. Copy `NORTH-STAR.md` to your workspace root
2. Open it in any text editor
3. Read the HTML comments to understand each section
4. Fill in the bracketed bits, delete the comments
5. Save

### Wiring it up
Add this line to your `CLAUDE.md` "Other context files" section so Claude reads NORTH-STAR.md when strategic questions come up:

```
@NORTH-STAR.md for direction and big-picture decisions
```

## Sections in the template

| Section | What it captures |
|---------|------------------|
| **Where I'm heading** | One paragraph. The big picture in plain language. |
| **Why** | The reason behind it. The motivation that holds when things get hard. |
| **Phase model** | The roadmap in stages (Phase 1, 2, 3). Stops you trying to skip steps. |
| **Numbers** | Specific targets (revenue, customers, time). Not slogans, actual numbers. |
| **Principles** | The values you won't trade off. Decisions get easy when these are clear. |
| **What I'm not building** | Equally important. Defines what stays out of scope. |
| **How I decide** | The rules that resolve hard choices when two paths both look reasonable. |
| **Active projects (and how they fit)** | Each project mapped to the direction. If one doesn't fit, it's a sunset candidate. |
| **Review cadence** | When you'll come back. Yearly is fine. |

## How often to update it

This file changes **rarely**. Once or twice a year at most. The whole point is that it's stable enough to be a reference point when other things shift.

If you find yourself updating NORTH-STAR.md every month, either:
- The direction wasn't right to start with, OR
- You're confusing it with CLAUDE.md (which IS supposed to update monthly)

The test: a year from now, would the same person reading this file recognise it? If yes, you've written it right.

## License

MIT.

Made by Catrin Donnelly.
