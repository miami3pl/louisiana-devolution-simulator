# The Beautiful Haley Simulator

An interactive family-tree calculator for **Louisiana intestate succession** — built as a
study tool for *Successions and Donations* (LCIV-L715), Prof. Milton "MJ" Hernandez,
Loyola University New Orleans College of Law.

**Live:** https://miami3pl.github.io/louisiana-devolution-simulator/

It opens on **Prof. Hernandez's own chart** — the family he draws on the board in Classes
2–4, from Ducky and Joann down to Sweet Baby Milo — with Arthur as the decedent. The generic
family and the Quiz 2 fact pattern are one click away on the tabs.

## What it does

Build a family, kill and revive people, and watch the shares recompute against the Civil
Code's order of heirs.

- **Click** a person to cycle **alive → died BEFORE → died AFTER**. That one toggle is the
  whole of Chapter 3: *before* is **representation** (arts. 881–885), *after* is
  **transmission** (art. 937).
- **Double-click** to rename, set sex, or change who they descend from.
- **Right-click** for every option, including *make this person the decedent* — the tree
  re-roots and every relationship and degree is recomputed from the new center.
- Representation runs **ad infinitum** in the direct line (art. 882): a grandchild who
  predeceased is himself represented, and art. 885 partitions **by roots at every level**.
- The **ladder** on the right shows the Code walking its classes of heir in order and
  stopping at the first rung with somebody on it — six rungs for separate property, two for
  community.
- The **Affidavit of Death and Heirship** panel narrates the facts as they now stand, in the
  form the notaries use.
- Every person carries an **icon** — a baby for Sweet Baby Milo, a ring for a spouse, a
  seedling for an adopted child, **◐ for half-blood** (the fact art. 893 turns on). Icons are
  inferred from who the person is and can be changed per person in the editor. They are a
  reading aid only: the arithmetic never consults one.
- Every Civil Code article on the page is **hoverable** and shows its **verbatim** text.
- **Save PNG** exports the tree *with the facts and who takes*; **Save PDF** prints it.

## Notes

- Article text is quoted verbatim from the Louisiana Civil Code (legis.la.gov), which is
  state law and not subject to copyright.
- Single self-contained HTML file. No build step, no network calls, no dependencies.
  Download it and it works offline.

## Educational use only

This is a **study aid built by a student for a law-school course**. It is **not legal advice
and not authority**. It has not been validated against a full problem set and it may be wrong —
verify every share against the Louisiana Civil Code and the Revision Comments before relying on
any result. Nothing here creates an attorney–client relationship.

Article text is quoted verbatim from the Louisiana Civil Code as published by the Louisiana
State Legislature; state law is not subject to copyright. No copyrighted casebook, commercial
database, or course material is reproduced in this repository.

## License

Code: MIT (see LICENSE). Civil Code article text is public domain.
