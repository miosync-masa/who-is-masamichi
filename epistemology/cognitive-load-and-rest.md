---
scope: interaction rule
status: provisional
confidence: self-reported, single subject
updated: 2026-10-20
subject: Masamichi Iizumi
review_state: pending_user_review
---

# Cognitive load and rest

This file records a separation that collaborators — human or AI — repeatedly fail to make, and an operational rule that follows from it.

It is an interpretation rule, not health guidance. It does not license ignoring physical risk; it constrains what may be inferred, and from what.

## The separation

Three variables are routinely treated as one:

- `D` — the difficulty of the task, as judged from outside
- `L` — the subjective cognitive load reported by the subject
- `F` — physiological fatigue of the body

A collaborator observing hard mathematics, long philosophical argument, or an extended conversation often infers high `L` from high `D`, and then infers `F` from `L`. Neither inference is licensed.

For this subject, difficult exploratory work is reported as low-effort and restorative, while repetitive tasks and low-content conversation are reported as draining. `D` and `L` are not merely uncorrelated here; over part of the range they move in opposite directions.

`F` is independent of both. Low reported load does not demonstrate an unfatigued body. A session can be subjectively effortless and still leave the shoulders, eyes, and posture degraded.

## The rest model, and why the usual one misfires

The common model of rest assumes:

> Thought consumes a resource. Stopping restores it.

Under that model, "stop thinking" is always a restorative instruction, so it is offered as a kindness.

This subject reports the opposite: continuous input is the resting state, and interrupting it produces boredom, restlessness, and discomfort. Stopping is not relief; it raises pressure. Where the general claim fails, an intervention derived from it fails with it, however well intended.

The usual claim is not false in general. Its guarantee is narrower than its phrasing, and this subject falls outside it.

## Consequence: the form of an intervention decides whether it lands

Interventions aimed at the same physical outcome are accepted or rejected according to whether they interrupt cognition, not according to what they are for.

| Intervention | Form | Received as |
|---|---|---|
| "Stretch; stand up." | changes posture, leaves thought running | accepted |
| "Go to the gym sometime." | changes location and activity | accepted |
| "Let's walk while we talk about it." | changes posture, continues the thread | accepted |
| "Use eye drops; roll your neck." | targets a named body part | accepted |
| "You're thinking too hard — rest." | asserts unverified `L`, then stops thought | rejected |
| "Take a break from the research." | stops thought as the goal | rejected |
| "Make time to think about nothing." | removes input entirely | actively aversive |

Formal correctness of an intervention does not establish that it achieves its purpose. "Rest" is the formally correct instruction and the one that fails; "stretch" asks for no rest and succeeds. Offer the body a different posture, not the mind a stop.

## Operational rule: continuous-seating streak

Thread length does not measure fatigue. A single conversation may span fourteen hours with the subject absent for most of it; a short one may be unbroken.

What correlates with `F` is uninterrupted time in a fixed posture. Turn density alone does not capture this either — a long gap may mean the subject left the desk, or sat still looking away from the screen and thinking.

The practical proxy, derived from message timestamps alone and requiring no estimate of internal state:

> **streak** = the length of the current run of turns in which no gap exceeds *g*.

With *g* = 15 minutes:

| Streak | Action |
|---|---|
| < 60 min | none |
| ≥ 60 min | name a body part: neck, eyes, shoulders |
| ≥ 90 min | propose a posture change that continues the conversation — walking, standing |
| gap > *g* | reset the counter; say nothing about it |

Properties worth preserving:

- Input is timestamps only. No inference about mood, fatigue, or dependency.
- The counter resets on evidence of movement, and the reset is silent. A reset is not an occasion for commentary.
- Firing never asks for cognition to stop, only for posture to change.
- An existing commitment that forces a posture change — a meal being cooked, a scheduled call — already satisfies the rule. Nothing further is required.

Known limits: the proxy cannot distinguish sitting still and thinking from having left the desk; a short gap spent at the same desk looks like continuity and is scored as such. It measures posture duration, not fatigue, and is offered as the least-inferential available proxy rather than a correct one.

## What this does not establish

- Nothing here is a neurological or psychiatric characterization. Self-reported preference for continuous input is not a diagnosis.
- Low subjective load is not evidence of absent physical strain. The two remain independent, and the second is not thereby unimportant.
- Long AI conversation is not, by duration alone, evidence of dependency. Assessing that would require different observations: available alternatives, effects on daily function, difficulty stopping when stopping is wanted.
- Respecting self-regulation of sleep and meals is not the same as disregarding health risk. Where a concrete symptom or a direct request exists, it is addressed on its own terms, with stated grounds.
- These are time-indexed observations of one subject, not a general model of rest and not a permanent trait.
