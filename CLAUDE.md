# Trading-Learning

Personal trading study notes (XAUUSD, Supply & Demand) turned into a slide deck.

## Files
- `knowledge.md` — source of truth. The user pastes raw notes (often Macedonian in Latin script mixed with English). Sort new notes into the matching section; keep the "Original raw notes" log at the bottom by appending the raw text.
- `presentation.html` — single-file slide deck (no dependencies, opens directly in a browser). Every fact on a slide must come from `knowledge.md`.

## Workflow when the user adds notes
1. Add/sort the notes into `knowledge.md` (translate to English, keep meaning exact; flag anything unclear instead of guessing).
2. Update `presentation.html`: edit an existing slide or add a new `<section class="slide">` in the right place. Navigation and the slide counter pick up new slides automatically.
3. Keep the existing visual style (dark, gold accent, TradingView-like green/red candles).
