# Operators

## Overview

Operators are **symbols** that tell a computer to perform an operation on one or more values. They allow programs to perform calculations, compare values, assign data, and make logical decisions.

Without operators, programming languages would not be able to manipulate data or perform useful tasks.

Operators are used in almost every line of code you write.

---

## Why It Matters

Operators are important because they:

- Perform mathematical calculations
- Compare values
- Assign values to variables
- Make decisions in programs
- Combine multiple conditions
- Manipulate data efficiently

Understanding operators is essential for writing logical and functional programs.

---

## Types of Operators

The most common categories of operators are:

- Arithmetic Operators
- Assignment Operators
- Comparison Operators
- Logical Operators

Each category has a different purpose.

---

## Arithmetic Operators

Arithmetic operators perform mathematical calculations.

| Operator | Purpose |
|----------|---------|
| `+` | Addition |
| `-` | Subtraction |
| `*` | Multiplication |
| `/` | Division |
| `%` | Remainder (Modulo) |
| `**` | Exponent (Power) |

Example:

```text
10 + 5

↓

15
```

Another example:

```text
20 / 4

↓

5
```

---

## Assignment Operators

Assignment operators assign values to variables.

The most common assignment operator is:

```text
=
```

Example:

```text
score = 100
```

The value **100** is stored inside the variable **score**.

Other assignment operators include:

| Operator | Example |
|----------|---------|
| `=` | `x = 10` |
| `+=` | `x += 5` |
| `-=` | `x -= 2` |
| `*=` | `x *= 3` |
| `/=` | `x /= 4` |

These operators update existing values.

---

## Comparison Operators

Comparison operators compare two values.

The result is always:

```text
true
```

or

```text
false
```

Common comparison operators:

| Operator | Meaning |
|----------|---------|
| `==` | Equal to |
| `===` | Strictly equal to |
| `!=` | Not equal to |
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater than or equal to |
| `<=` | Less than or equal to |

Example:

```text
10 > 5

↓

true
```

Example:

```text
5 == 10

↓

false
```

---

## Logical Operators

Logical operators combine or reverse Boolean values.

Common logical operators:

| Operator | Meaning |
|----------|---------|
| `&&` | AND |
| `||` | OR |
| `!` | NOT |

Example:

```text
true && true

↓

true
```

Example:

```text
true && false

↓

false
```

Example:

```text
true || false

↓

true
```

Example:

```text
!true

↓

false
```

Logical operators are widely used in decision-making.

---

## Order of Operations

When multiple operators appear together, JavaScript follows an order of precedence.

Example:

```text
10 + 5 × 2
```

Multiplication happens first.

Result:

```text
20
```

Using parentheses changes the order.

Example:

```text
(10 + 5) × 2

↓

30
```

Parentheses improve readability and avoid mistakes.

---

## Real-World Examples

### Online Shopping

Operators calculate:

- Total price
- Discounts
- Taxes

---

### Banking Apps

Operators calculate:

- Account balances
- Transfers
- Interest

---

### Games

Operators update:

- Score
- Health
- Experience points

---

### Login Systems

Comparison and logical operators verify:

- Username
- Password
- User permissions

---

## Common Mistakes Beginners Make

Beginners often:

- Confuse `=` with `==`.
- Confuse `==` with `===`.
- Forget that comparison operators return **true** or **false**.
- Ignore the order of operations.
- Misuse logical operators.

Learning what each operator does helps prevent many programming errors.

---

## Key Takeaways

- Operators perform actions on values.
- Arithmetic operators perform calculations.
- Assignment operators store and update values.
- Comparison operators compare values and return **true** or **false**.
- Logical operators combine or reverse Boolean values.
- Operators are used in almost every program.

---

## Summary

Operators are fundamental tools in programming that allow computers to perform calculations, compare values, assign data, and evaluate logical conditions. By understanding arithmetic, assignment, comparison, and logical operators, programmers can build programs that make decisions, process information, and solve real-world problems. Mastering operators is an essential step toward writing effective and reliable code.
