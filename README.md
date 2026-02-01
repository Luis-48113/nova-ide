# Nova IDE (Web Version)

Nova IDE is a **browser-based development environment** for the **Nova programming language**.  
It allows you to **write, run, and see your Nova code execute directly in the browser**, no installation required.

---

## Features

- **Editor Area**: Type your Nova code with a clean, monospace interface and auto-indentation.
- **Run Button**: Execute your code instantly.
- **Terminal Output**: Displays program output, errors, and prompts.
- **Canvas**: For pixel-based graphics.
- **Strict Syntax**: Requires proper syntax like ':' after define, loop, if.
- **Import System**: Import built-in modules like time and random.
- **Hundreds of Commands**: Math functions, string operations, random numbers, timing, etc.
- **Beginner-Friendly Commands**:
  - `say` / `print` → Print messages or variable values
  - `ask` → Ask user for input
  - `define` / `run` → Functions
  - `loop(n):` / `if cond:` / `else:` → Control flow
  - `import module` → Load modules
  - `pixel x,y,color` → Draw pixels
  - Math: `add a,b,result`, `sqrt num`, `sin angle`, etc.
  - Strings: `upper var`, `lower var`, `concat a,b,result`
  - Random: `random_int min,max,var`, `random_float var`
  - Time: `time_now var`, `wait ms`
- **Safe Math Parser**: Handles expressions with variables and operators.

---

## Usage

1. Open `index.html` in your web browser.
2. Type your Nova code in the **editor area**.
3. Click the **Run** button or press Ctrl+Enter.
4. See the output in the **terminal area** and canvas.

---

## Examples

### Basic Function
```nova
define hello:
    loop(100):
        say 'hello'
run hello
```

### If/Else with Random
```nova
random_int 1,10,num
if num > 5:
    say "Big number"
else:
    say "Small number"
```

### Pixel Drawing
```nova
pixel 50,50,"red"
pixel 51,50,"red"
pixel 52,50,"red"
```

### Math and Strings
```nova
num is 16
sqrt num
say "Square root: "
say num

text is "hello"
upper text
say text
```
