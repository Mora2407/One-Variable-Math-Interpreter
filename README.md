A simple math interpreter designed to solve basic linear equations with one variable.

## Syntax

### Addition
* **Example:** `1 + 1`
* **Commutative:** `1 + 2 = 2 + 1`
* **Associative:** `(1 + 2) + 3 = 1 + (2 + 3)`
* **Variable Addition:** `x + x = 2x`

### Subtraction
* **Example:** `2 - 1`
* **Non-Commutative:** `2 - 1 != 1 - 2`
* **Variable Subtraction:** `2x - x = x`

### Multiplication
* **Example:** `2 * 3`
* **Commutative:** `2 * 3 = 3 * 2`
* **Distributive:** `2 * (x + 3) = 2x + 6`
* **Implicit Multiplication:** `10x`

### Division
* **Example:** `10 / 2`
* **Variable Division:** `4x / 2 = 2x`
* **Complex Division:** `(x + 1) / (x + 2)`

### Unary Operators & Parentheses
* **Unary Minus:** `-5`, `--5 = 5`
* **Nested Parentheses:** `((1 + 2) * 3)`

## Equations

### Solving for X
* `x + 1 = 5` → **x = 4**
* `2x = 10` → **x = 5**

### Errors & Edge Cases
* **Multi-variable:** `x + y = 10` → **Error: Multiple variables not supported**
* **Non-linear:** `x * x = 4` → **Error: Nonlinear equations not supported**
* **Infinite Solutions:** `x + 1 = x + 1` → **Infinite Solutions**
* **No Solution:** `x + 1 = x + 2` → **No Solution**

## Benchmark
<img width="465" height="161" alt="image" src="https://github.com/user-attachments/assets/8e3919fb-1b3f-4537-8aba-0920b51bcd8c" />
