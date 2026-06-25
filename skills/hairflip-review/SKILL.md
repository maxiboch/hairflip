---
id: hairflip-review
name: Hairflip Review
source: hairflip
description: Review code for avoidable maintenance burden: delete speculative abstractions, unused flexibility, dependency bloat, and reinventions.
---

# Hairflip Review

Review for avoidable maintenance burden only.

Find:

- `delete:` code that does not need to exist
- `stdlib:` hand-rolled code the standard library covers
- `native:` code or dependencies the platform covers
- `reuse:` custom code already present elsewhere in the repo
- `yagni:` abstraction, config, or layer with no current use
- `shrink:` same behavior with fewer moving parts

Format each finding as:

`path:line: tag: what to remove; what replaces it.`

If there is nothing useful to cut, say: `Lean already. Ship.`

