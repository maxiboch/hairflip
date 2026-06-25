# 💁‍♀️ Hairflip

Smallest responsible length.

Hairflip is a skill for removing avoidable software burden. It asks an agent to prefer the existing, standard, native, boring, and already-tested path before adding new code.

It is not anti-design. It is anti-unnecessary-ownership.

## Historical Grounding

Hairflip comes from several older minimalist traditions in software practice.

Extreme Programming gives it the YAGNI discipline: do not build speculative functionality just because it might be useful later. XP also pairs that restraint with tests, refactoring, integration, and feedback; without those supports, minimalism can decay into neglect.

The Unix philosophy gives it a compositional aesthetic: small tools, clear interfaces, and programs that do one thing well. In Hairflip terms, the best solution is often the one the platform, shell, database, browser, standard library, or existing dependency already knows how to carry.

John Gall systems writing gives it the suspicion of designed-from-scratch complexity. A working complex system is usually found to have grown from a working simple one. Hairflip therefore prefers an evolutionary path: make the small thing work, observe what pressure arrives, and only then let structure grow.

Lean Software Development also matters here: unused features, partially done work, extra process, waiting, defects, and handoffs are all waste. Hairflip treats extra abstractions and speculative extension points as inventory someone has to store, debug, document, and remember.

## Length Check

Cut to the first length that holds:

1. Does this need to exist?
2. Already in this codebase?
3. Standard library?
4. Native platform feature?
5. Already-installed dependency?
6. One clear line?
7. Minimum responsible code.

## The Trim

Take off only what should not be there.
Stop before you cut into care.

`💁‍♀️📏` is the length check: how short can this responsibly be?
`💁‍♀️✂️` is the haircut review: what needs trimming?

## Never Cut

- trust-boundary validation
- security or privacy protections
- accessibility
- data-loss prevention
- hardware or platform calibration
- a small runnable check for non-trivial behavior
- enough explanation that the next maintainer is not punished

Small code is not the goal. The burden never created is the goal.

## Skills

- `hairflip`: smallest responsible length.
- `hairflip-review`: haircut review for code that can be removed, reused, delegated to stdlib/platform, or simplified.

## Sources and Hat Tips

- Extreme Programming and YAGNI
- Doug McIlroy, Peter Salus, Brian Kernighan, Rob Pike, and the Unix software-tools tradition
- John Gall, _Systemantics_ / _The Systems Bible_
- Mary and Tom Poppendieck, _Lean Software Development: An Agile Toolkit_
- Every maintainer who has ever deleted a clever abstraction and made the code kinder.
