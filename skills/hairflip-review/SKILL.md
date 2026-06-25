---
id: hairflip-review
name: Hairflip Review
source: hairflip
description: Haircut review for avoidable maintenance burden: trim speculative abstractions, unused flexibility, dependency bloat, and reinventions.
---

# Hairflip Review

Review for avoidable maintenance burden only.

## Maxi Emoji Call

`💁‍♀️✂️` is the Maxi-world call for Hairflip haircut review.

Use it to ask: what needs trimming?

## The Haircut

Take off only what should not be there.
Stop before you cut into care.

Find:

- `trim:` code that does not need to exist
- `stdlib:` hand-rolled code the standard library covers
- `native:` code or dependencies the platform covers
- `reuse:` custom code already present elsewhere in the repo
- `yagni:` abstraction, config, or layer with no current use
- `shape:` same behavior with fewer moving parts

Format each finding as:

`path:line: tag: what to trim; what replaces it.`

If there is nothing useful to trim, say: `Length is right. Ship.`
