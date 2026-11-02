# Ladderbox

A PLC learning environment that runs entirely in the browser.

- Ladder logic using the Allen-Bradley instruction set (contacts, coils, timers, counters, compare, math, move)
- A Structured C view that stays in sync with the ladder, both ways
- Tag table with Allen-Bradley data types (BOOL, SINT, INT, DINT, REAL, TIMER, COUNTER, arrays)
- HMI, process simulations (transmission cell, sorter), and a 3D world, all driven by the PLC
- Lab exercises with automatic checks, and an interactive book
- Export to Studio 5000 (L5X) and to Arduino sketches; L5X import

Everything is in `index.html`. Pushing to `main` deploys it to GitHub Pages through the workflow in `.github/workflows/pages.yml`.

© Jesse Roberts. Allen-Bradley, Studio 5000 and Arduino are trademarks of their respective owners; Ladderbox is not affiliated with them.
