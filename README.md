# Decolorized Dark Theme

A highly customized, high-contrast dark theme for Visual Studio Code, optimized for TypeScript and JavaScript development. This theme focuses on reducing visual noise by carefully controlling the color of syntax elements, making the code's structure and core logic stand out.

**Goal:** Clean, focused coding. We de-emphasize elements like variable usage, method calls, and punctuation, while giving strong contrast to declarations and key components.

## ✨ Key Features

### 1. Focus on Declarations (Blue, Yellow, Red)

The theme employs a minimal color palette to ensure that the most important parts of your code—the definitions—are instantly recognizable.

| Element | Color | Purpose |
| :--- | :--- | :--- |
| **Class Names** | Pale Red (`#F07178`) | Highlights main structural components. |
| **Function/Method Names** | Pale Yellow (`#FFCB6B`) | Clearly marks executable logic. |
| **Variable/Parameter Declarations** | Pale Blue (`#89DDFF`) | Emphasizes where data is created or defined. |

### 2. Reduced Visual Noise (White)

To minimize distraction and maximize focus, several common elements are stripped of color and rendered in a subtle, pale white (`#eeffff`). This is the **Decolorization** effect:

* **Variable Usage:** When you read or use a variable within a method or function (e.g., as an argument or in an expression), it is rendered white.
* **Method/Function Calls:** Names of methods or functions when they are being executed (e.g., `myObject.call()`) are white.
* **Punctuation:** All commas, and dots (`.`) are rendered in white.
* **Imports:** The names of imported objects (e.g., `React` in `import React from 'react'`) are white.

### 3. High Contrast Palette

Other essential elements are styled for maximum readability against the very dark background (`#212121`):

* **Keywords/Control Flow (`const`, `if`, `return`):** White
* **Strings & Numbers:** Pale Green (`#C3E88D`)
* **Comments:** Pale Violet (`#C792EA`)

## 💻 Installation

1.  Open **Extensions** sidebar in VS Code. (`Ctrl+Shift+X` or `Cmd+Shift+X`)
2.  Search for **Decolorized Dark Theme**.
3.  Click **Install**.
4.  Go to **File** > **Preferences** > **Color Theme** (or **Code** > **Settings** on Mac) and select **Decolorized Dark Theme**.
