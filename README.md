# Nova IDE (Web Version)

Nova IDE is a **browser-based development environment** for the **Nova programming language**.  
It allows you to **write, run, and see your Nova code execute directly in the browser**, no installation required.

---

## Features

- **Editor Area**: Type your Nova code with a clean, monospace interface.
- **Run Button**: Execute your code instantly.
- **Terminal Output**: Displays program output, errors, and prompts.
- **Beginner-Friendly Commands**:
  - `say` → Print messages or variable values
  - `ask` → Ask user for input
  - `define` / `run` → Functions
  - `loop(n)` / `loop` → Loops
  - `check` / `otherwise` → Conditionals
  - `wait(n)` → Pause execution (demo-safe)
- **Safe Math Parser**: Handles expressions like `x is 5 plus 3 times 2`.

---

## Usage

1. Open `index.html` in your web browser.
2. Type your Nova code in the **editor area**.
3. Click the **Run** button.
4. See the output in the **terminal area**.

---

## Example

```nova
define greet:
    name is ask'What is your name?'
    say'Hello, ' plus name

run greet

loop(3):
    say'Loop iteration!'
