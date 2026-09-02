# Beta Notes

## Round 1 — full-flow review

**Result:** The demo was fully playable with no broken interactions or browser errors. The atmosphere, visual identity, flow, and inline feedback were received positively.

### Findings

1. The opening disclosed the seven-minute answer before the first puzzle.
2. The cipher explained its complete method before the player attempted it.
3. ORBIT and Mara's original suspect card made the final choice too obvious.
4. The progress indicator needed a spoken “Step N of 4” state.
5. Muted secondary text and hint contrast warranted improvement.
6. The ending needed a concise clue-chain recap.

### Changes shipped

- Removed the seven-minute spoiler from the opening.
- Made the cipher method available only after one unsuccessful attempt.
- Added an independent telescope tracking ledger and rewrote suspect accounts around a contradiction.
- Added visible and screen-reader-announced step labels.
- Increased muted-text contrast.
- Added the ending recap: clocks → seven minutes → ORBIT → Mara.
- Re-ran full desktop and 390 px mobile QA before production deployment.
