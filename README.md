# 🧮 Scientific Calculator (Python)

A smart command-line scientific calculator built with **Python** that supports everyday arithmetic, scientific functions, intelligent input parsing, calculation history, and much more.

## ✨ Features

### ➕ Basic Arithmetic

Perform standard mathematical operations with ease.

* Addition (`+`)
* Subtraction (`-`)
* Multiplication (`*`)
* Division (`/`)

---

### 🔢 Flexible Multiplication Input

The calculator recognizes multiple multiplication symbols, allowing you to type expressions naturally.

**Supported formats:**

```text
5*3
5x3
5X3
5×3
```

---

### 📐 Trigonometric Functions

Evaluate common trigonometric functions by simply entering the function name followed by the angle.

**Supported functions:**

* `sin`
* `cos`
* `tan`
* `sec`
* `cosec`
* `cot`

**Example**

```text
sin30
cos60
tan45
```

Angles entered without parentheses are automatically interpreted in **degrees** and converted to **radians** internally.

---

### 🧠 Smart Expression Parsing

The calculator automatically understands common mathematical shorthand.

#### Implicit Multiplication

```text
3(2+3)
```

Automatically becomes:

```text
3*(2+3)
```

#### Trigonometric Input

```text
sin30
```

Automatically converts the angle from degrees to radians before evaluation.

---

### 📊 Mathematical Functions

Supported functions include:

* `sqrt()` or `sqrt16`
* `log10()`

**Examples**

```text
sqrt16
sqrt(25)
log10(100)
```

---

### 🔁 Previous Answer (`Ans`)

Reuse the result of your last calculation without typing it again.

**Example**

```text
5 + 5
Ans * 2
```

Output:

```text
10
20
```

---

### 📜 Calculation History

View every calculation performed during the current session.

**Command**

```text
history
```

Example:

```text
5+5 = 10
sqrt16 = 4
sin30 = 0.5
```

---

### 🧹 Clear History

Remove all stored calculations.

**Command**

```text
clear
```

---

### 🚪 Exit the Calculator

Close the program safely.

**Command**

```text
exit
```

---

### ⚠️ Error Handling

The calculator gracefully handles invalid input and common errors, including:

* Invalid expressions
* Unsupported operations
* Division by zero
* Incorrect function usage

Instead of crashing, it displays a clear and user-friendly error message.

---

# 💻 Example Session

```text
> 5x3
15

> sin30
0.5

> sqrt16
4

> Ans + 6
10

> history
5x3 = 15
sin30 = 0.5
sqrt16 = 4
Ans + 6 = 10

> clear
History cleared.

> exit
Goodbye!
```

## 🚀 Highlights

* Clean command-line interface
* Scientific calculator functionality
* Smart expression parsing
* Flexible multiplication symbols
* Automatic degree-to-radian conversion
* Previous answer support (`Ans`)
* Calculation history
* Friendly error handling
* Lightweight and easy to use
