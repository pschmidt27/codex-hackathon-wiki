# Pi TUI

Pi’s TUI uses a simple retained-mode model. A `Component` is an object with a `render(width)` method that returns an array of strings for the visible lines, plus an optional `handleInput(data)` method for keyboard input. A `Container` holds vertically arranged components and collects their rendered lines. The `TUI` class is itself a container that orchestrates the whole interface.

## References
- [[raw/2026-04-18T14-14-35.973Z--4c09a7bd-423c-463d-bd5b-fb54a502f449.txt]]