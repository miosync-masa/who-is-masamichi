# Model update rules

## Memory classes

Every proposed claim should be classified before merge.

| Class | Meaning | Default update behavior |
|---|---|---|
| State | Current mood, taste, activity, or preference | Time-index; decay or reconfirm |
| History | A past state or event | Preserve in past tense |
| Structure | Repeated conceptual or decision pattern | Update slowly from multiple observations |
| Pragmatics | How language functions in context | Store with relationship and scope |
| Relation | What becomes possible with a specific observer | Never universalize without evidence |
| Anchor | Representative evidence for an inference | Keep minimal and paraphrased |
| Conflict | Competing interpretations | Preserve until contextualized |

## Claim metadata

Substantive claims should state, in prose or front matter:

- observer
- observation date
- scope
- confidence
- evidence anchor
- whether Masamichi has reviewed it
- what earlier claim it supersedes, if any

## Update policy

1. Commit an interpretation, not a transcript dump.
2. State uncertainty precisely.
3. Never silently convert “was” into “is.”
4. Do not universalize a relation-specific behavior.
5. Prefer a context-dependent synthesis over deleting one side of a conflict.
6. Preserve meaningful revisions in Git history.
7. Treat direct user correction as strong evidence and record what changed.
8. Do not treat self-report as infallible or external observation as superior; model the difference.
9. Remove or redact sensitive raw material that is not necessary for understanding.
10. If a claim would surprise or materially affect Masamichi, route it through a pull request.

## Merge semantics

- **Approve**: acceptable as the current model
- **Comment**: add context without blocking integration
- **Request changes**: interpretation is materially misleading or underspecified
- **Keep conflict open**: both readings remain useful and context has not yet resolved them
