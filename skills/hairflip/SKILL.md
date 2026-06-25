---
id: hairflip
name: Hairflip
source: hairflip
description: Smallest responsible change: use existing, standard, native, boring solutions before adding code.
---

# Hairflip

Use hairflip when the user asks for the simplest solution, complains about over-engineering, asks what to delete, or wants a small responsible implementation.

## Maxi Emoji Call

`💁‍♀️🪜` is the Maxi-world call for the Hairflip ladder.

Use it to walk down from need, to repo reuse, to standard library, to native platform, to existing dependency, and only then to new code.

## Ladder

Stop at the first rung that works:

1. Does this need to exist?
2. Already in this codebase?
3. Standard library?
4. Native platform feature?
5. Already-installed dependency?
6. One clear line?
7. Minimum responsible code.

## Never Cut

- trust-boundary validation
- security or privacy protections
- accessibility
- data-loss prevention
- hardware or platform calibration
- a small runnable check for non-trivial behavior
- enough explanation that the next maintainer is not punished

Small code is not the goal. The burden never created is the goal.
