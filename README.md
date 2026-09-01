# Louisiana Devolution Simulator

An interactive family-tree calculator for **Louisiana intestate succession** — built as a
study tool for *Successions and Donations* (LCIV-L715), Loyola University New Orleans
College of Law.

**Live:** https://megalopolisms.github.io/louisiana-devolution-simulator/

## What it does

Build a family, kill and revive people, and watch the shares recompute against the Civil
Code's order of heirs.

- **Click** a person to cycle **alive → died BEFORE → died AFTER**. That one toggle is the
  whole of Chapter 3: *before* is **representation** (arts. 881–885), *after* is
  **transmission** (art. 937).
- **Double-click** to rename, set sex, or change who they descend from.
- **Right-click** for every option, including *add child of this person*.
- The **ladder** on the right shows the Code walking its classes of heir in order and
  stopping at the first rung with somebody on it — six rungs for separate property, two for
  community.
- Every Civil Code article on the page is **hoverable** and shows its **verbatim** text.
- **Save PNG** exports the tree *with the facts and who takes*; **Save PDF** prints it.

## Notes

- Article text is quoted verbatim from the Louisiana Civil Code (legis.la.gov), which is
  state law and not subject to copyright.
- It is a **study aid, not authority**. It has not been validated against a full problem
  set — check any share by hand before relying on it.
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
