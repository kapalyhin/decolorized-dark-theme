# Change Log

All notable changes to the "Decolorized Dark Theme" project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

## [0.0.1] - 2025-10-17

### Added

-   Initial release of the **Decolorized Dark Theme**.
-   Set base editor background to very dark grey (`#212121`).

### Changed

-   **Focus Palette:** Implemented the core philosophy of the theme, distinguishing declarations from usage:
    -   **Classes:** Highlighted with Pale Red (`#F07178`).
    -   **Functions/Methods:** Highlighted with Pale Yellow (`#FFCB6B`).
    -   **Variable/Parameter Declarations:** Highlighted with Pale Blue (`#89DDFF`).
-   **Decolorization:** Aggressively made usage of variables, function calls, method calls, imports, and all punctuation white (`#eeffff`) to minimize visual noise.
-   Fixes for correct scope targeting in TypeScript (e.g., ensuring `variable.other.constant.ts` is colored Blue only when declared, and white when used as an object property).
