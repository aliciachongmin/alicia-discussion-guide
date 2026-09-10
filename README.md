# README.md

# What this skill does

This skill turns a research question into a **moderator-ready discussion guide** for
either **qualitative usability testing** or **qualitative discovery research**. It works
from an existing research plan where there is one, and stands on its own where there is
not.

The guide it produces is a **moderating instrument, not a document**. It is written to be
read live, on screen, while a participant waits — so it contains only what gets used in
the session, with space to type notes into as you go.

Three things hold the quality bar:

1. **The question gate.** Nothing is drafted until the research question and the
   objective behind it are confirmed. This applies to every route, including the
   lightweight one. A guide written without a question is a topic list.
2. **Traceability.** Every question maps to a supporting question, objective or analysis
   lens before it reaches you. Untraced questions get cut or demoted.
3. **A self-check.** The draft is audited before delivery — and again after your edits,
   which is what catches a cut that left something uncovered.

---

# Why this exists

Discussion guides get written at very different levels of preparation. Sometimes there
is a full research plan behind them; sometimes there are two days' notice and a rough
sense of what needs answering. The pressure in the second case is to reach for a generic
interview template, which produces a session that runs smoothly and generates nothing
anyone can act on.

This skill removes that trade-off. The **structure and the quality bar stay fixed** while
the amount of input required flexes. A 30-minute lightweight chat gets fewer questions
than a 90-minute usability test, but each one is still traced, still non-leading, and
still asks for a concrete instance rather than a general opinion.

It also does the translation work that is easy to skip: research questions are written
for the team and cannot be read aloud, and converting them into things a participant can
actually answer is where most of the thinking sits.

---

# What this skill covers

| In scope ✅ | Out of scope ❌ |
| --- | --- |
| Usability testing guides | Research plans (use `alicia-ux-research-plan`) |
| Discovery research guides | Screeners and recruitment messages |
| Sessions that need both, as a hybrid | Quantitative studies and surveys |
| Task prompts and screen-level probes | Synthesis, tagging and reporting |
| Probe banks and branch tables | Notetaking and capture systems |
| Small-scale rating questions | Consent policy — the boilerplate is fixed, not drafted |
| Revising or tightening an existing guide | — |

---

# How it works with the research plan skill

The two skills run **together or independently**.

- **Together** — write the plan, then hand it to this skill. It inherits the mode,
  questions, session structure, participants, lenses and rating scales, so there is
  almost nothing to ask you.
- **On its own** — no plan needed. The terms it borrows from the plan skill (PQ, SQ,
  lens) are defined inside its own files, so nothing breaks when there is no plan to
  inherit from.

**Even with a full plan, it will still ask you two things** — a last check before
drafting:

- **The screens** where a usability session should pause.
- **The open design decisions** you want these sessions to settle.

---

# How to use the skill

Say what the session is for. Attach the plan if there is one.

Examples:

> Here's my UT plan for the admin portal redesign — can you turn it into a discussion
> guide? Sessions are 90 minutes, in person.

> I need a guide for three quick chats with agency admins next week about why they still
> use paper forms. No plan, no time to write one.

What happens next:

1. **Intake routing.** It asks whether a plan exists, what you have ready, and how much
   time and bandwidth the research has. That sets **Route A** (plan-led), **B**
   (sketch-led) or **C** (guide-only).
2. **The question gate.** It confirms the research question — read from the plan on Route
   A, proposed and agreed with you on B and C. It will not skip this.
3. **Mode.** It picks usability or discovery and says which, flagging hybrids.
4. **Alignment.** Audience, timings, coverage, screens, open questions, probe depth,
   rating scales, must-asks, and whether you want a traceability map appended.
5. **Draft.** The full guide as plain text in the conversation, so it can be read and
   edited in place.
6. **File.** If you ask, it packages the agreed guide as a markdown file for Notion.

Anything assumed is marked `[ASSUMPTION]`; anything unknown is `[TBC]`. Both are meant to
be resolved, not left in.

---

# The three routes

| Route | When | What it needs from you |
| --- | --- | --- |
| **A — plan-led** | A full research plan exists | The plan, the screens, and any open design questions |
| **B — sketch-led** | Partial material: a context doc, a Slack thread, an objectives list | Whatever material exists, and a confirmed research question |
| **C — guide-only** | Nothing written; the guide is the artefact | The decision it informs, who you're talking to, how long the session is, and one confirmed question |

Route C compensates for missing inputs by **proposing, never by skipping**. It drafts,
marks it `[ASSUMPTION]`, and you correct it in a line — you never get handed a template
with blanks.

---

# The two tracks

Both share an opening and a debrief, and diverge in the middle where the probe device
differs.

| | Usability | Discovery |
| --- | --- | --- |
| **Middle section** | Tasks | Walkthrough + probing |
| **Probe device** | `Screen \| Questions` — fires at a moment | `Anticipated answer \| Follow-ups` — fires on a branch |
| **Verbatim blocks** | Think-aloud instruction, prototype caveat, task prompts | Walkthrough openers |
| **Session length** | 45–60 mins by default | 30–60 mins by default |
| **Time split** | 5 / 25 / 55 / 10 | 5 / 10 / 70 / 10 |

**Hybrids.** Where a session genuinely needs both — prototype tasks, then a generative
block about the surrounding behaviour — the primary mode supplies the spine and the
secondary block goes afterwards, using its own device. The two are never blended.

---

# What the guide contains

```
[Study at a glance]        routes B and C only
[1] Welcome + intro        verbatim, from fixed boilerplate
[2] Background
[3] Tasks / Walkthrough + probing
[3b] Secondary block       hybrid only
[4] Debrief + wrap
[Traceability]             only if you ask for it
```

A **notetaking block** follows every numbered section, since the guide gets duplicated
and typed into during the session.

**Bold means essential must-ask** — the questions asked even when time runs short or the
participant sidetracks. Capped at 1–3 per section, because the marking only works if it
is scarce. Nothing else is bolded.

**Opening blocks are fixed boilerplate**, not drafted. There are two — one for members of
the public, with the consent form; one for public officers and internal participants,
with verbal consent. Placeholders are left intact for you to fill in.

---

# Two things worth knowing about the output

**It goes broad on purpose.** You are meant to cut. Questions arrive in two tiers — core
questions that something depends on, and optional probes you can drop freely — and the
self-check runs again after your edits to catch anything a cut left uncovered. Breadth
comes from alternative phrasings and probe branches on ground that is already traced,
never from new topics.

**Rating questions are situational.** The skill always asks whether you want any, and
before adding one it asks what you want the number to tell you and what you will use it
for. If neither has an answer, the scale is decoration and gets dropped. Small-n scales
are read alongside the *why* that produced them — never on their own, and never as
representative of a wider population.

---

# Files

```
alicia-discussion-guide/
├── SKILL.md                        the workflow, template, guardrails and standards
├── references/
│   ├── usability-guide.md          tasks, screen probes, prototype handling
│   └── discovery-guide.md          walkthroughs, branch tables, recall handling
└── README.md                       this document
```

- **SKILL.md** → the routes, the question gate, the shared template, and the rules that
  apply in both modes
- **references/usability-guide.md** → what changes when the machinery is applied to a
  session with an artefact under test
- **references/discovery-guide.md** → what changes when it is applied to a session about
  behaviour and context

The reference files are read by the skill, not by you — one at a time, depending on mode.
Keeping them separate is what stops a discovery guide arriving with task prompts
attached.

---

# Refining it

The parts most likely to need adjusting after real use:

- **The volume ceilings** — core question counts and task counts per session length.
  These are starting points and should be tuned to how sessions actually run.
- **The standard probe banks** in both reference files, which are the fastest lever on
  how natural the questions sound.
- **The example pairs** throughout `SKILL.md`. Adding a paired weak and sharp example to
  a section is usually more effective than adding another rule.
- **The time splits**, which are inherited from the research plan skill and may want
  different proportions for shorter sessions.

Changes go in `SKILL.md` for anything shared, or the relevant reference file for anything
mode-specific.
