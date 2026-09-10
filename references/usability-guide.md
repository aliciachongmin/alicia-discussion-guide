# usability-guide.md

Read this only when the mode is usability. Everything here slots into the template in
`SKILL.md`; this file does not restate the shared spine, the guardrails or the question
gate.

This file owns section `[3] Tasks`, and adds usability-specific content to `[2]
Background` and `[4] Debrief + wrap`.

---

## When this mode applies

A design, prototype or live product exists, and the question is whether people can use
it: complete tasks, find what they need, understand the copy, know what to do next,
recover when stuck, or choose between versions.

If there is no artefact to react to, the mode is wrong. Go back to Step 3.

---

## What Route A inherits

The plan supplies more than it looks. Before asking the user anything, mine it for:

| From the plan | Becomes |
|---|---|
| Threshold criteria naming task completions | The task list, and how many tasks |
| Evaluative criteria — the *Working* and *Concerning* signals under each lens | The probes. These are close to probe specifications already |
| Data to be captured | The rating scales, with their anchors |
| Session structure | Section timings, verbatim |
| Methodology → Prototype | The prototype caveat, and what it cannot simulate |

**Evaluative criteria are the highest-leverage source.** A signal like *"when asked what
this means, participants interpret labels correctly without hedging"* converts almost
directly into a screen probe. Where a plan has lenses but no observable signals under
them, expect to derive more from scratch and say so.

**What no plan supplies:** the screens, and the open design decisions. Always ask for
both — see `SKILL.md` Step 5, items 4 and 5.

---

## [2] Background

25% of the session. Enough to interpret what happens in the tasks, not a study of its
own.

Cover, nested as `[2.1]`, `[2.2]`:

- **Their context** — role, what they use the product for, volume and frequency
- **Current workflow** — how they do this today, in sequence, anchored to the last real
  instance
- **Pain points** — asked *after* the walkthrough, so they are answered against a
  concrete account
- **Baseline scales**, where the study uses them

Where the study compares a current tool against a prototype, the baseline rating belongs
here, before exposure. Asking afterwards gets a rating contaminated by what they just
saw.

---

## [3] Tasks

55% of the session. One subsection per task: `[3.1]`, `[3.2]`, `[3.3]`. The bold
must-ask cap of 1–3 applies **per task subsection**, not to the phase as a whole.

### Think-aloud instruction — verbatim, once, before the first task

> Before we start with the prototype, I'd appreciate it if you could think out loud as
> you go through the prototype — meaning, if you're reading something on the screen in
> your head or thinking some thoughts, do share them out loud with me so that I can get
> a sense of what you're looking at or what you're thinking about when looking at the
> screens.
>
> I'll also pause at certain points to ask you questions like "what do you think this
> means?" or "what would you do next?" — these are mainly for me to see if the copy is
> clear and whether users like yourselves are able to understand, or just to see how
> you'd handle certain scenarios on your own. Rest assured that I'll come back to any
> outstanding questions at the end.
>
> Any questions before we start?

### Prototype caveat — verbatim, before the first task

Adapt the product name only. Where the plan's Methodology names something the prototype
cannot simulate, add it here in one clause.

> This is the prototype of the [product]; it's just a prototype so some things may not
> respond exactly like the real system would, but most of the key flows should be
> clickable.

### Task prompts

Verbatim, and identical across participants. A task prompt states the **goal and the
situation**, never the steps and never the UI element that has to be found — finding it
is what is being tested.

| | |
|---|---|
| **Weak** | *Click on "Create campaign", fill in the campaign name, then upload your NRIC whitelist.* |
| **Sharp** | *Your first task is to create [campaign] on this platform and publish it when all the details are ready, as if you were doing it for real on your own. Go ahead and start whenever you feel ready, and please keep thinking aloud as you go.* |

The weak version tests whether someone can follow instructions. The sharp version can
fail informatively.

Where a task needs a scenario to make sense, give it as a situation rather than a
sequence:

> Your second task is to create a single voucher — for example, for an eligible resident
> who comes to claim it over the counter in person, and they want it in paper.

Where the entry point itself is being tested, say so as an imagined starting state
rather than a location:

> Let's imagine you've already logged in and you know which submission you want to check
> — tell me where you would click.

### Task count

| Session | Tasks |
|---|---|
| 45–60 mins | 2–3 |
| 90 mins | up to 4, where one is a long end-to-end flow |

Order tasks so the longest and most central comes first, while attention is freshest.
Shorter, self-contained tasks follow.

If the task list exceeds this, say the session cannot hold it and propose which tasks to
drop or merge.

### Prototype limitations

Ask the user, before drafting, what the prototype **cannot** do: steps that dead-end,
states it cannot reach, data it cannot accept. Two things follow.

1. **Name them in the caveat line** where a participant will hit one during a task.
2. **Do not write a task or a screen row that depends on a behaviour the prototype
   cannot produce.** Raise it as a gap instead — this is a limitation the study needs to
   record, not something to design around silently.

Where the prototype is **customised per participant** — populated with their own
campaign, data or use case — say so, and name the fallback the moderator uses when
customisation was not possible. The task prompt has to work in both versions.

### The Screen | Questions device

One row per screen or step where the session pauses. This is the core instrument of a
usability guide.

| Screen | Questions |
|---|---|
| [Screen name, as the user gave it] | • What do you understand from this screen? / What do you think you have to do?<br>• Which elements caught your eye? / What did you pause to look at? |
| [Screen name] | *Watch them do it without guidance, then:*<br>• What did you understand from [specific label]?<br>• What do you think will happen after you press [action]? |

**Construction rules:**

- **Screens come only from the user's inventory.** Never invent a screen, a label, a
  field or a piece of product jargon to fill a row.
- **Not every screen earns a row.** Include a screen where something is at stake:
  unfamiliar terminology, a decision, a fork, a step the team is unsure about. A row per
  screen produces a guide nobody can moderate in time.
- **Every row traces** to an SQ, objective or lens. Where a screen serves none, cut it or
  raise it as a gap.
- **Watch first, probe second.** Where the point is whether someone can proceed
  unaided, write *"watch them do it without guidance, then:"* into the row. Probing
  before they act destroys the observation.
- **Use the screen's actual wording** when probing a label, in quotes, so the moderator
  reads out what the participant is looking at.
- Open design decisions from Step 5 become rows at the screen where they surface.

### Standard probes

A bank, drawn on as needed, not a script. These recur across studies and stay
non-leading.

| Purpose | Probe |
|---|---|
| Comprehension | *What do you understand from this? / What do you think this means?* |
| Expectation | *What would you do next from here? / What do you expect to happen when you click this?* |
| Attention | *Which elements caught your eye? / What did you pause to look at?* |
| Reasoning | *What made you go there? / What were you looking for?* |
| Terminology | *What do you understand by [term]? / Is that a word you'd use yourself?* |
| Preference, where the study compares versions | *Which of these is clearer to you, and why?* |
| Prioritisation | *Which of these would you call essential, and which are good to have?* |

Never probe with a verdict attached. *"Was that clear?"* fails every time.

### Post-task questions

**Situational, not fixed.** What follows a task depends on what the study needs, and is
agreed with the user in Step 5 alongside the mini-quant dialogue. Do not attach a
standard block to every task by reflex.

Where post-task questions are used, ask **the same ones after every task in that study**,
or the answers cannot be compared across tasks.

Candidates:

- *Were there any points that were confusing or caused uncertainty? Which was the most
  confusing or frustrating?*
- *Were there any points that felt particularly clear or well organised?*
- *Is there anything you expected to find but didn't?*
- A confidence or ease rating, anchored — see *Mini-quant* in `SKILL.md`

Keep it short after short tasks. A five-minute task followed by four debrief questions
inverts the balance of the session.

**Ask any rating first, before discussing the task.** A rating given after a
conversation about what went wrong is a rating of the conversation.

### Comparative tasks

Where the study compares two or more versions — layouts, labels, components — a bare
preference is not a finding on its own.

- **Show each version on its own before comparing.** Ask what they understand from each
  independently, then ask which is clearer and why.
- **Ask for the reason, never just the pick.** *Which is clearer to you, and why?* The
  preference alone is unusable.
- Where the plan defines comparative ratings, they belong in the debrief, after both
  versions have been seen.

---

## [4] Debrief + wrap

10% of the session. Usability-specific content, on top of the shared rules:

- **Comparison to today** — *how did that compare to how you do this currently?*
- **Parked questions.** The think-aloud instruction promises *"I'll come back to any
  outstanding questions at the end"*. Include a line in the debrief holding the
  moderator to it: *anything you asked me during the session that I said I'd come back
  to.* Without it the promise is made and quietly dropped.
- **Overall confusing or frustrating moment**, even where each task already asked it.
  The end-of-session answer is comparative and often names something different.
- **Closing scales**, where the study uses them — overall ease, and self-service
  confidence
- **The forward-looking question**, which works well as a closer: *if this were the
  product you had to use for your next [task], how would you feel about it?*

---

## Timing

Percentages of the moderated session, from the plan's Session structure. Buffer is not
printed.

| Section | Share |
|---|---|
| `[1]` Welcome + intro | 5% |
| `[2]` Background | 25% |
| `[3]` Tasks | 55% |
| `[4]` Debrief + wrap | 10% |

The printed sections sum to 95%; the remaining 5% is unprinted buffer.

**Route A** — take the numbers from the plan's table directly, dropping buffer and any
break.

**Routes B and C** — apply the percentages to the stated session length, round each to
the nearest 5 minutes, give `[1]` a minimum of 5 minutes, and reconcile any difference
against `[2] Background`. Check the total.

Where multiple tasks share `[3]`, split its allocation across the subsections and show
each: `## [3.1] Create a campaign [40 mins]`.

If the session cannot hold the structure, cut a task rather than compressing every
section.
