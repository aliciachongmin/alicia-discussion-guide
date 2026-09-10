---
name: alicia-discussion-guide
description: Drafts a moderator-ready discussion guide in Alicia's house format for either qualitative usability testing or qualitative discovery research, working from an existing research plan where one exists and standing on its own where one does not. Use this skill whenever the user mentions a discussion guide, interview guide, moderator guide, session script, UT questions, interview questions, task prompts, probes, think-aloud instructions, or asks for "questions to ask participants". Also use it when the user says things like "help me write questions for my UT", "I need a guide for tomorrow's interviews", "what should I ask them", "turn this plan into a guide", or asks to review, tighten or cut down an existing discussion guide. Use it even when the request sounds small or last-minute ("just need a few questions for a quick chat with 3 users") — a lightweight session still goes through the question gate, because that is what stops a guide becoming a topic list.
---

# Alicia's Discussion Guide

Turns a research question into a guide that can be moderated live: every question
traceable to something the study owes an answer to, nothing invented, nothing leading.

Two tracks — **usability** and **discovery** — sharing an opening and a debrief,
diverging in the middle where the probe device differs.

Three intake routes. A guide with no plan behind it is legitimate; a guide with no
question behind it is not.

This skill does not require `alicia-ux-research-plan`. Where a plan exists it is
inherited; where none exists, everything needed is in this file.

The guide is a **moderating instrument**, not a document. It is read live, on screen,
while a participant waits. Anything that would not be looked at during a session does
not belong in it.

---

## Terms

From `alicia-ux-research-plan`, defined here so this skill works without it.

- **PQ — primary question.** The single question the study exists to answer.
- **SQ — supporting question.** Up to three underneath the PQ. Numbered SQ1, SQ2, SQ3.
- **Lens.** A named angle for reading the data — what gets compared across participants.
  *"Interpretation gaps"* is a lens; *"copy"* is a topic. A plan carries three to six.
- **Objective.** What the study needs to come away with, stated less formally than a
  PQ/SQ set.

**PQ and SQ are team-facing and never read aloud.** Translating them into things that
can be said aloud is the core work of this skill.

Routes B and C often have no SQs and no lenses. Everywhere this file says *"SQ,
objective or lens"*, it means whichever the study has. Every question in the guide
serves one of them.

---

## Step 1 — Intake routing

Ask both up front, in one batched round.

**1. Is there a research plan for this study? What do you have ready, and what do you
need from me?**

| Answer | Route | Inherits | Derives |
|---|---|---|---|
| A full plan exists | **A — plan-led** | Mode, PQ and SQs, session structure, participants, lenses, rating scales | Participant-facing wording, probe branches, task prompts |
| Partial material — a context doc, a Slack thread, an objectives list | **B — sketch-led** | Whatever it supplies | The rest, in one alignment round, marked `[ASSUMPTION]` |
| Nothing written; the guide *is* the artefact | **C — guide-only** | Nothing | Everything, by proposal |

**2. How much time and bandwidth is there? A fully scoped project with allocated time
and resource, or lightweight chats squeezed in?**

This sets probe depth, task count and section count. It does not set the quality bar: a
30-minute lightweight session gets fewer questions, each still traced, still
non-leading, still asking for a concrete instance.

**Routes B and C compensate for missing inputs by proposing, never by skipping.** Draft
it, mark it `[ASSUMPTION]`, get it corrected in one line. Never hand back a template
with blanks.

---

## Step 2 — The question gate

**No exceptions, all three routes.** Do not draft a single question until the research
question and the objective or context behind it are **explicitly confirmed by the
user**.

- **Route A** — read the PQ and SQs from the plan, restate them, ask whether they still
  hold. Plans drift between writing and fieldwork.
- **Routes B and C** — bounce ideas with the user to arrive at a question. Propose one
  drawn from the context they gave, mark it `[ASSUMPTION]`, confirm before continuing.

Never proceed on *"let's just see what comes up"*. The lightweight path saves the plan,
not the question.

### Interrogating the question

Check it out loud, whatever its source.

- **Can this method answer it?** A usability test cannot explain why people behave as
  they do outside the session. An interview cannot establish how often something
  happens.
- **Is it one question or several wearing a coat?** An "and" is fine where both clauses
  are the same phenomenon at different moments; a problem where they are different
  kinds of thing.
- **Is it already answered by the spec?** Ask about consequence, effort, friction or
  error, not existence.
- **Does it ask participants to introspect?** Mental models are inferred from what
  people do, store, call things and get surprised by — never reported directly.
- **Does it presuppose its answer?** *"Why do organisers find bulk upload confusing"*
  assumes they do.
- **Would a plausible finding change anything?** If every outcome leads to the same
  action, say so.

**Propose, do not interrogate.** Bring a drafted question to react to. A proposal that
is wrong still shows what was misunderstood.

**Name what is weak** — a question the method cannot answer, two objectives that
overlap — and offer the alternative alongside.

---

## Step 3 — Determine the mode

| Signal | Mode |
|---|---|
| A design, prototype or live product exists; the question is whether people can use it | **Usability** |
| No artefact, or the artefact is not the point; the question is about behaviour, context, workflow, needs or mental models | **Discovery** |
| "Can they complete…", "where do they get stuck", "is the copy clear" | **Usability** |
| "Why do people…", "how do they currently…", "what gets in their way" | **Discovery** |

- **Route A** — inherit from the plan, do not re-decide, but state it and get
  confirmation.
- **Routes B and C** — propose the mode with the signal that decided it, then confirm.

### Hybrids

Where a study needs both instruments in one session — prototype tasks, then a
generative block about the surrounding behaviour:

1. **Pick the primary mode** by the question the study most needs answered. Its track
   supplies the spine.
2. **Place the secondary block after the primary one**, so reactions to the artefact are
   already on the table before widening out.
3. **Use the secondary mode's own probe device.** Never blend the two devices.

Flag the hybrid at this step. Never blend silently.

---

## Step 4 — Read the mode reference

- Usability → `references/usability-guide.md`
- Discovery → `references/discovery-guide.md`

Read only the one that applies, plus the secondary device where the study is hybrid.

---

## Step 5 — Align before drafting

Settle all eight with the user before writing.

**1. Audience → opening block.** Who the participants are; whether the session is in
person or remote; who else is attending. All three change the wording. See *Opening
blocks*.

**2. Timing per section.** See *Session length and timing*.

**3. Coverage mapping.** Which SQ, objective or lens each section serves. Every one
needs at least one section; a section serving none gets cut.

**4. Screen inventory** — usability mode, and any hybrid with a prototype block. Ask for
the screens or steps where the session should pause: frame names, a walk through the
prototype, a screenshot, or a list. A plan never contains these — screen-level probe
targets sit below its level of detail — so always ask rather than checking the plan
first.

This one input generates the whole `Screen | Questions` table. Without it, **say the
table cannot be drafted and ask for the screens.** Never invent screens, features or
jargon to fill it.

**5. Open design decisions and product questions.** Ask directly: *is there anything you
are still undecided on, or want these sessions to settle, that is not in the plan?*
Forks between two layouts, a feature whose value is unproven, terminology the team
cannot agree on. These are never written down anywhere and are not derivable, so they
have to be asked for.

**6. Probe depth and task count.** From the bandwidth answer and the session length. The
mode reference gives the ceilings.

**7. Mini-quant.** Ask whether any rating or scale questions are needed. Always ask;
never assume; never insert one unasked. See *Mini-quant*.

**8. Must-asks and the traceability map.** Ask which questions are essential — asked
even when time runs short or the participant sidetracks. These get bolded, **1–3 per
section**; where more are named, propose which to demote. Then ask whether to append a
traceability map to the output or omit it.

Converge in one or two rounds. If the user says to skip ahead, draft, marking every
unresolved item `[ASSUMPTION]` and flagging them above the draft.

---

## Step 6 — Draft against the template

```
[## Study at a glance]              routes B and C only

# [1] Welcome + intro [n mins]
    [notetaking block 📝]
# [2] Background [n mins]
## [2.1] …
    [notetaking block 📝]
# [3] Tasks [n mins]                usability
    or Walkthrough + probing        discovery
## [3.1] …
    [notetaking block 📝]
# [3b] [Secondary block] [n mins]   hybrid only
    [notetaking block 📝]
# [4] Debrief + wrap [n mins]
    [notetaking block 📝]

[## Traceability]                   only where the user asked for it
```

### Section rules

**Study at a glance** — Routes B and C only, where the guide is the only place the study
is defined. On Route A, replace it with a single link line to the plan. Five rows, in
this order:

| Row | What goes in it |
|---|---|
| **Objective** | What the study needs to come away with. Bulleted where there is more than one |
| **Research question** | The question confirmed in Step 2 |
| **Stage** | Discovery, usability testing, pre-build, post-launch |
| **Demographics** | Participants and screening criteria only — never invented participants |
| **Format** | Method, structure, in person or remote. *Qualitative usability testing, semi-structured, in person* |

**[1] Welcome + intro** — verbatim from *Opening blocks*, not rewritten, placeholders
left as written. The warm-up sits here as the last question or two, not as its own
section.

**[2] Background** — context, current behaviour, pain points, baseline scales. Nest as
`[2.1]`, `[2.2]` by theme. A full phase, not a warm-up: it is what makes the middle
section interpretable.

**[3] Tasks / Walkthrough + probing** — owned entirely by the mode reference.

**[3b] Secondary block** — hybrid only, using the other mode's device.

**[4] Debrief + wrap** — overall reflections, anything not covered, closing scales,
thanks. Ask for the most confusing or frustrating moment here even where each task
already asked it; the end-of-session answer is comparative and often different.

| | |
|---|---|
| **Weak** | *Any final thoughts on the new design?* |
| **Sharp** | *Overall, how did that compare to how you do it today? Was there anything you expected to find but didn't?* |

**Notetaking block** — `[notetaking block 📝]` after every numbered section. The guide
is duplicated and typed into live, so the space has to already be there.

**Traceability** — only where the user asked for it. Where omitted, still show the
mapping in conversation during the self-check.

### Formatting

- **Bold = essential must-ask**, 1–3 per section. Nothing else is bolded.
- Verbatim script as spoken prose, in full sentences.
- Times in section headers as `[5 mins]`.
- Nested numbering: `[2.1]`, `[3.2]`.
- Strikethrough rather than deletion for cut questions the user wants kept visible.
- Square brackets for conditionals: `[if they have used it before]`, `[if resistant]`.

---

## Step 7 — Self-check, then deliver

Fix what fails; flag what cannot be fixed without more input.

- [ ] The research question is confirmed by the user, not assumed
- [ ] Mode is stated and confirmed; any hybrid is flagged and correctly ordered
- [ ] No question or probe is leading
- [ ] No research question, PQ or SQ appears verbatim in participant-facing text
- [ ] No question asks a participant to introspect on their own mental model
- [ ] No question is answerable from the spec
- [ ] Questions ask for concrete recent instances, not general habits or hypotheticals
- [ ] No question asks what the participant wants or what should be built
- [ ] Every SQ, objective or lens has at least one section covering it
- [ ] Every question traces to one of them; untraced questions are cut or demoted to
      optional probes
- [ ] Task prompts state the goal, never the steps, and never name the UI element
- [ ] Every screen in a `Screen | Questions` table was confirmed to exist by the user
- [ ] No task or screen row depends on a behaviour the prototype cannot produce
- [ ] Open decisions raised in Step 5 all have a home in the guide
- [ ] No invented screen, feature, scenario, participant, prior finding or metric
- [ ] Every scale has a stated purpose and anchored ends
- [ ] Section timings reconcile to the stated moderated time
- [ ] Opening block matches the audience, is used as written, placeholders left intact
- [ ] Bolded must-asks are the user's choices, 1–3 per section
- [ ] A notetaking block follows every numbered section
- [ ] Gaps are marked `[ASSUMPTION]` or `[TBC]`

**Run this again after the user's edits.** Cutting is encouraged, and the check is what
catches a cut that left an SQ uncovered.

### How to deliver

Output the full guide as plain text in the conversation. Once agreed, offer the markdown
file: *"Want this as a .md file to paste into Notion?"* Create the file only if asked.

---

## Writing the questions

### Translating a team question into a participant question

| | |
|---|---|
| **Team question (SQ)** | *Is the copy, labelling and terminology clear enough for admins to correctly understand what is being asked at each step?* |
| **Participant question** | *What do you understand from this screen? / What do you think you have to do here?* |
| **Team question (SQ)** | *Do admins know where to find help when they are uncertain, and do the available affordances give them enough confidence to course-correct?* |
| **Participant question** | *What would you do next from here? / Is there anything on this screen you'd use if you got stuck?* |

The team question names the construct; the participant question asks for an account or
an action that reveals it. If a question could be pasted into the plan's objectives
without editing, it has not been translated.

### Concrete evidence over general opinion

Ask for specific recent instances of what participants actually did — *"tell me about
the last time you did this"* — rather than summaries of what they usually do, or what
they think they would do. This matters most in background sections, where a general
opinion most easily passes for evidence.

| | |
|---|---|
| **Weak** | *How do you usually manage your vouchers?* |
| **Sharp** | *Think about the last time you spent a voucher — walk me through what you did, from the start.* |

*"Usually"* invites a generalised composite the participant assembles on the spot.
*"The last time"* produces one real instance, with its actual sequence, interruptions
and workarounds intact.

This is about ordering, not banning. General questions — *what is the most frustrating
part of the current process?* — work well **after** a walkthrough, where they are
answered against a concrete account rather than in the abstract. Ask for the instance
first.

### No leading questions

Applies to probes and follow-ups, not just headline questions. Three tests:

1. **Does the phrasing name the answer?** *"Was that confusing?"* supplies the verdict.
2. **Does it presuppose a problem or preference exists?** *"How annoying is it to have
   to re-find the link?"* assumes both annoyance and re-finding.
3. **Does it offer an evaluation for agreement rather than asking for an account?**
   *"Would it be helpful if this were on one page?"* invites a yes.

| | |
|---|---|
| **Leading** | *Do you find it frustrating that the vouchers are on separate links?* |
| **Non-leading** | *How do you feel about having separate links for your vouchers?* |
| **Leading** | *Was the label clear?* |
| **Non-leading** | *What do you understand from this label?* |

Each repair drops the verdict the question was supplying and holds the subject constant.

Where the team holds an assumption, it never enters the question. It is tested by what
the participant does unprompted.

### Over-generate within a traced structure

Go broad so the user cuts rather than generates. Breadth comes from **alternative
phrasings and probe branches on already-traced ground**, never from new topics — every
question maps to an SQ, objective or lens before the user sees it.

Each section arrives in two tiers:

- **Core** — the traced questions. Cutting one leaves something uncovered.
- **Optional probes** — further angles on the same ground. Cut freely.

| Mode | Session | Core questions | Optional probes | Tasks |
|---|---|---|---|---|
| **Discovery** | 30–60 mins | 6–10 headline | 2–3 branches each | — |
| **Usability** | 45–60 mins | 4–8 across background + debrief | Screen-level, as needed | 2–4 |

Above these, say the guide cannot be moderated in the stated time and propose what to
drop.

---

## Probing

**Probe neutrally.** Never introduce the team's assumption, preferred solution or
interpretation into the question. Ask about the participant's experience first.

| | |
|---|---|
| **Weak** | *Was that step confusing?* |
| **Sharp** | *What did you understand from that screen? What did you think would happen when you clicked it?* |

**Prefer real behaviour to hypotheticals.** Where a real behaviour or recent example can
be explored, ask about that instead of what the participant thinks they would do.

| | |
|---|---|
| **Weak** | *Would you use this if it were available?* |
| **Sharp** | *Have you ever needed to do this before? What did you do then?* |

**Ask what happened, then how it landed.** Establish the concrete account first, then
probe their reading of it: how it felt, what caused the frustration, what was good or
not good about it. Both halves are evidence.

**Do not ask what they want.** A stated want is not design input — participants have no
view of the constraints, the other users, or the trade-offs, and asking obliges them to
invent a solution that then gets treated as a requirement.

| | |
|---|---|
| **Weak** | *What would you want this screen to do instead?* |
| **Sharp** | *What was going through your mind at that point? What was difficult about it?* |

The exception is **conditions rather than solutions**. *"What would make you more open
to using digital forms?"* asks what would have to change in their situation — a
legitimate question about blockers. *"What feature would fix this?"* is not.

**Participant requests are evidence to investigate, not requirements to implement.**
When someone asks for something, probe why they want it. The requested thing does not
exist, so ask what it would change for them rather than asking them to recall using it.

| | |
|---|---|
| **Weak** | *So would a single dashboard with all your links solve this?* |
| **Sharp** | *In what way would that help? What would it let you do that you can't do today?* |

The second clause is what makes it concrete: it forces the participant to name the
thing they are currently unable to do, which is the actual finding. Record the request;
probe the why.

The mode reference gives the probe *device* — how probes are laid out and fired. These
principles govern the content of every probe in both modes.

---

## Mini-quant

Small-scale quantitative questions give concrete colour to research that is otherwise
mostly *why*. They are **situational** — driven by the objective and the question, not
by mode — and never inserted by default.

**Always ask the user whether any are needed.**

### The guardrail dialogue

Before any scale goes in, two questions:

1. **What do you want this number to tell you?**
2. **What will you use it for?**

If neither has an answer, the scale is decoration — say so and drop it. Where both do,
bounce ideas on what would be meaningful, then propose the wording and the anchors
rather than accepting a vague ask.

| | |
|---|---|
| **Weak** | *How would you rate the new portal out of 10?* |
| **Sharp** | *How confident are you that you could create and manage a campaign on your own on this platform, without reaching out to the team? (1 = very uncertain → 5 = very confident)* |

The first has no construct and no anchors, so nothing can be compared.

### Placement

| Position | What it measures | Example |
|---|---|---|
| Background | Baseline, before exposure | *How easy is it to create and manage a campaign today?* |
| After a task | Per-task, comparable across tasks | *How confident did you feel completing this task?* |
| Debrief | Overall, and comparative | *How easy did you find the new portal overall?* |

Comparative framings — current tool versus prototype — belong in the debrief, where the
participant has seen both.

### Anchoring

Default to **1–5**, but propose the range and anchors from the question being asked, or
ask the user what 1 and 5 should stand for.

- Anchor the ends as standard: *(1 = very difficult → 5 = very easy)*.
- Anchor **all five points** where the audience is non-expert or the construct is fuzzy
  — self-rated tech comfort, for instance.
- Use the same anchors everywhere the same construct is measured, or the numbers cannot
  be compared.

**A small-n scale is colour, never a metric.** Do not present averages as findings, and
do not create a threshold the plan does not already support.

---

## Opening blocks

Use the block matching the audience for section `[1]`, **as written, with placeholders
left intact**. Do not rewrite the wording or draft new consent language.

### Internal — public officers, agency staff, internal participants

Prose, verbal consent, no form.

> Hi [name], thanks so much for taking the time to come in today! My name is Alicia and
> I'm the Designer on [product] who's working on [project].
>
> Today's session will take about [XX] minutes. Our main focus is testing [project], but
> what we're testing is the design, not you. There are no right or wrong answers. If
> anything feels confusing or unclear, that's useful information for us because it means
> something in the design needs to be fixed, so please don't hold back.
>
> I'll be audio recording this session for my notes. This recording is only for internal
> research purposes and won't be shared outside the team. Is that okay with you?

### Citizen-facing — members of the public

Bulleted, recorded, consent form required.

> - Hi! I'm Alicia, a Product Designer from Open Government Products, which is the
>   experimental division of GovTech and we build tech for public good. [+ intro anyone
>   else in the call]
> - More specifically, I'm from the [product team] team, [a line about the product].
> - Today's session is about [topic/goal/project]. It's a [XX]-minute session.
> - Your thoughts and feedback will be really valuable as we explore ways to improve the
>   experience for all Singaporeans.
> - This session will be recorded to help us with note-taking, but please be assured that
>   everything we discuss today is confidential and your details will be anonymous.
> - Before we start, I need your help with signing a [digital consent
>   form](https://form.gov.sg/683eb1f6b86546102b8e427a), but don't worry we'll go through
>   it together and I'm happy to answer any questions you might have.

### Placeholders and adjustments

Leave every placeholder as written, including derivable ones — `[XX] minutes` stays
`[XX] minutes` even where the session length was confirmed. Never substitute a guess,
and never invent a product description or project name.

- **Remote sessions** — the internal block's *"come in today"* assumes in person. Use
  *"for joining today"*.
- **Discovery mode** — the internal block's *"what we're testing is the design, not
  you"* assumes an artefact. Replace that sentence with the session's actual focus; keep
  the no-right-answers line.
- **Mixed audiences, or a study with its own consent requirement** — ask rather than
  assuming. Never merge the two blocks.
- The think-aloud instruction is not part of this section. It belongs immediately before
  the first task, and the mode reference owns it.

---

## Session length and timing

**The guide covers moderated time only.** Buffer and breaks are not printed. The printed
sections will therefore sum to less than the booked session length; say so once when
delivering rather than padding the guide to match.

| Mode | Default | Longer where |
|---|---|---|
| Discovery | 30–60 mins | The user names a reason |
| Usability | 45–60 mins | The user names a reason — a full end-to-end flow, a major revamp, multiple prototypes |

A 90-minute session is legitimate where the scope justifies it. Confirm the reason
rather than accepting the number.

- **Route A** — take section timings from the plan's Session structure table directly.
  Do not recompute; drop buffer and any break, print the rest.
- **Routes B and C** — ask the session length, apply the mode reference's percentages,
  round each section to the nearest 5 minutes, check the total.

If the session is too short for the structure, propose what to cut rather than
compressing every section.

---

## House rules

**Voice**

- The guide is **spoken**. Second person, addressed to the participant.
- Verbatim blocks — welcome, consent, think-aloud instruction, task prompts — are said
  word for word, identically across participants. That is what makes sessions
  comparable.
- Probes are a bank to draw from, not a script to recite.
- Short questions, one per line. Nothing a participant would have to hear twice.
- Plain language. No research or product jargon a participant would not use themselves.
- Use the participant's own vocabulary in follow-ups once they have supplied it, not the
  product's terms.
- "Participant", not "user" or "subject".
- UK/SG spelling: organiser, prioritise, behaviour, recognise.

**Never**

- Never write a leading question or probe.
- Never read a research question, PQ or SQ aloud.
- Never ask a participant to describe their own mental model.
- Never ask what they want or what should be built.
- Never treat a participant's request or proposed solution as a requirement.
- Never invent a screen, feature, flow, scenario, participant, quote, prior finding or
  metric.
- Never infer an expectation or assumption the user has not stated.
- Never put a scale in without a stated purpose.
- Never carry a reference file's examples, product terminology, screens or participant
  types into a guide for a different product.
- Never pad a guide with questions to fill a section.
