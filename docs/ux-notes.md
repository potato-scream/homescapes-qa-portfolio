## UX-001: Invalid swap does not consume a move

**Module:** Match-3 Gameplay
**Type:** UX Observation (not a bug)
**Tester:** Kseniia Romanovskaia
**Date:** 2026-04-03

### Observation
In Homescapes, an invalid swap is rejected with an animation and does not consume a move.
The player can retry without penalty.

### Comparative Analysis
In 2048, every swipe alters the game state regardless of outcome - a careless move
can cost the entire run. This connects to well-researched engagement mechanics:
flow theory (Csikszentmihalyi, 1990), loss aversion (Kahneman & Tversky, 1979),
and variable reward conditioning (Skinner) all suggest that risk and consequence
increase player engagement and session length.

### Conclusion
These are proven mechanics - but Homescapes deliberately avoids them.
The game targets casual players who play in short sessions to relax.
Penalizing invalid swaps would introduce stress that contradicts the game's
cozy tone and would likely alienate its core audience."