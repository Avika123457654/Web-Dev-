## ⚙️ Module 01: Engine & Execution Context



### Key Learnings:
* **The V8 Pipeline:** Code ➔ Parser (AST) ➔ Interpreter (Ignition) ➔ Compiler (TurboFan).
* **Execution Context Phases:** 1. **Memory Phase:** Variable declarations are scanned; `var` is initialized as `undefined`.
    2. **Execution Phase:** Line-by-line code execution and value assignment.
* **Hoisting Logic:** Understanding why calling a function before its declaration works, while doing the same for a variable might result in `undefined` or a `ReferenceError`.
