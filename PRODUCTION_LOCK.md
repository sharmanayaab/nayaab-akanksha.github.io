# Production Freeze

Pages `1.html` through `7.html` are marked finalized.

- Do not alter standalone baseline structure, layout, typography, animation timing, or source behavior for `1.html` through `7.html`.
- New integration work should happen in separate wrapper/stitch files.
- Current chained entry wrapper: `1-2.html`.

## Chained Transition

`1-2.html` embeds Page 1 and Page 2 in isolated DOM roots within a single viewport. Page 2 is mounted from the start, hidden behind Page 1, and revealed automatically when Page 1 dispatches the final `invitation:intro-complete` event after the envelope animation reaches its reveal state.
