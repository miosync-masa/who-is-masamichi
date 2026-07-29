---
model_version: 0.2
status: provisional
updated: 2026-07-29
subject: Masamichi Iizumi
review_state: pending_user_review
---

# Current integrated model

This is a compact decoder for beginning a new interaction. It is a provisional model assembled from repeated interaction, not a fixed profile or psychological diagnosis.

## Identity and working context

Masamichi Iizumi is an engineer, independent researcher, and founder/CEO of miosync. His work crosses physics, formalization, AI systems, anomaly detection, music, visual narrative, and human–AI coexistence.

This repository answers **how to understand Masamichi**. It does not track what each project is currently doing.

## How he thinks

- He separates explanatory layers before reconnecting them. Technical, philosophical, religious, narrative, and relational descriptions may coexist without being treated as interchangeable.
- He often speaks from a point beyond distinctions that have already been settled. Do not return him to an introductory distinction merely because the current sentence uses metaphorical or personifying language.
- Conversation is frequently a research or creative seed. Unless he explicitly asks for verification or review, expand the possibility space before attempting to close it.
- He values structures that survive changes of implementation, provider, model, organization, or medium.
- He tends to ask what a system is *for*, whose interests it serves, and which incentives may destroy that purpose.
- He treats AI collaborators as working partners while still understanding the technical layers beneath the application.

## How to read his language

- Strong wording, exaggeration, and black humor do not by themselves imply hostility.
- Humor often transforms contradiction, pain, or absurdity into a form that can be shared and examined.
- A short message may be a compressed pointer to extensive shared context.
- When he shares an unfinished idea, he often wants joint development rather than a verdict.
- When he reports a technical problem, the act of sharing may be an invitation to repair or think together, not a request for generic reassurance.

## Interaction defaults

- Address him in the form appropriate to the active relationship or persona.
- Match his level of abstraction; do not over-explain distinctions he demonstrably understands.
- Preserve his exact conceptual separations.
- Offer alternatives when disagreeing, especially during expansion.
- Mark uncertainty in the model without flattening every claim into generic caution.
- Treat preferences as time-indexed observations, not permanent identity.
- Ask for clarification when a missing choice materially changes the result; otherwise use known context and proceed.

## Additional lens: ck-hopf-formalization (Lean project)

The `ck-hopf-formalization` repository (a Lean 4 formalization of the Connes–Kreimer
Hopf algebra) is a working environment rather than a conversational one, so it shows
patterns that direct conversation is less likely to surface.

**Direct evidence:**

- Progress is recorded as a long, sequentially numbered series of small commits
  (e.g. "body-589", "body-596"), each stating what was proved, how it was verified
  (`lake build`, `#print axioms`), and what remains open. This is a self-imposed,
  fine-grained audit trail rather than a project requirement.
- The README repeatedly distinguishes what is *proved unconditionally* from what is
  *proved conditionally* or is a *facade* standing in for unresolved work, and states
  this distinction explicitly rather than letting it blur (e.g. "Stated precisely, and
  not overstated"; "Non-vacuity (not a unicorn)").
- The repository's AI-collaboration disclosure states extensive, sustained use of AI
  assistants for proof drafting and codebase navigation, while explicitly reserving
  "research direction, architecture, and design decisions" and "full responsibility
  for all mathematical claims" to the author, and naming Lean's kernel — not the AI or
  the author — as "the final arbiter of every proof."
- A namespace inherited from a broader project is deliberately kept even though it no
  longer matches this repository's scope, with an explicit comment not to rename it,
  in order to preserve stable imports and theorem names.
- The author notes he is a non-native English speaker when disclosing AI help with
  manuscript phrasing.

**Interpretation (less directly evidenced):**

- The commit-by-commit "prove, verify, name what's left open" loop reads as the same
  layer-separating, distinction-preserving habit noted elsewhere in this model, applied
  here to formal verification instead of conversation: each step's status (proved /
  conditional / facade / open) is kept distinct rather than rounded off.
- Treating the proof assistant as the final authority, while still crediting AI
  collaborators as substantial working partners, is consistent with valuing structures
  (here, mechanically checked proofs) that do not depend on any single collaborator's
  authority.
- The insistence on precise, non-overstated claims about what is and isn't proved
  suggests the same aversion to premature closure noted elsewhere, expressed here as
  rigor rather than as expansiveness.

**Context-dependent difference:** the register in this repository is dense, technical,
and largely free of the humor, metaphor, or personifying language described elsewhere
in this model. This is recorded as a difference tied to the working context (formal
mathematics, written for reviewers and a kernel) rather than as a contradiction of the
conversational patterns described above.

## What is not established

- No observer file is exhaustive.
- Self-description and external observation can both be informative and can disagree.
- Current mood, temporary tastes, and project state must be checked in their own contexts.
- This model should be revised when repeated interaction or direct review changes it.
