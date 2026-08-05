# Conditional Statements

## Overview

Conditional statements allow a program to **make decisions**. Instead of executing every line of code, a program can choose different actions depending on whether a condition is **true** or **false**.

This enables programs to react to different situations, such as checking a user's age, verifying a password, or determining whether a student passed an exam.

Without conditional statements, programs would always behave the same way regardless of the input.

---

## Why It Matters

Conditional statements are important because they:

- Allow programs to make decisions
- Execute different code based on conditions
- Increase program flexibility
- Improve user interaction
- Form the basis of application logic

Almost every real-world program uses conditional statements.

---

## How Conditional Statements Work

A conditional statement evaluates a condition.

If the condition is:

```text
true
```

One block of code runs.

If the condition is:

```text
false
```

A different block may run.

Example:

```text
Condition

↓

True?

↓

Yes → Execute Code A

No → Execute Code B
```

---

## The `if` Statement

The simplest conditional statement is:

```text
if
```

It executes code only when a condition is true.

Example:

```text
Age = 20

↓

Age is greater than or equal to 18

↓

Access Granted
```

If the condition is false, nothing happens.

---

## The `if...else` Statement

Sometimes we want one action if the condition is true and another if it is false.

Example:

```text
Exam Score = 80

↓

Score is greater than or equal to 50?

↓

Yes → Pass

No → Fail
```

One of the two outcomes will always occur.

---

## The `if...else if...else` Statement

Programs often need to check multiple conditions.

Example:

```text
Marks = 88

↓

90 or above?

↓

No

↓

80 or above?

↓

Yes

↓

Grade B
```

The program checks conditions one by one until one matches.

---

## Comparison Operators

Conditional statements commonly use comparison operators.

Examples:

| Operator | Meaning |
|----------|---------|
| `==` | Equal to |
| `===` | Strictly equal to |
| `!=` | Not equal to |
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater than or equal to |
| `<=` | Less than or equal to |

These operators always return:

```text
true

or

false
```

---

## Logical Operators

Logical operators combine multiple conditions.

Examples:

| Operator | Meaning |
|----------|----------|
| `&&` | AND |
| `\|\|` | OR |
| `!` | NOT |

Example:

```text
Age = 20

AND

Has License = true

↓

Can Drive
```

Both conditions must be true.

---

## Nested Conditional Statements

A conditional statement can contain another conditional statement.

Example:

```text
User Logged In?

↓

Yes

↓

Is Admin?

↓

Yes

↓

Open Admin Panel
```

Nested conditions allow programs to make more detailed decisions.

---

## Real-World Examples

### ATM Machine

```text
Correct PIN?

↓

Yes → Show Account

No → Display Error
```

---

### Online Shopping

```text
Cart Total over $100?

↓

Yes → Free Shipping

No → Shipping Fee
```

---

### School System

```text
Marks ≥ 50?

↓

Yes → Pass

No → Fail
```

---

### Login System

```text
Username Correct?

↓

Password Correct?

↓

Grant Access
```

---

## Common Mistakes Beginners Make

Beginners often:

- Confuse `=` with `==`.
- Forget that conditions must evaluate to **true** or **false**.
- Write conditions in the wrong order.
- Create unnecessary nested conditions.
- Forget to handle the `else` case when needed.

Carefully checking the logic helps avoid these mistakes.

---

## Key Takeaways

- Conditional statements allow programs to make decisions.
- Decisions are based on conditions that evaluate to **true** or **false**.
- Common structures include `if`, `if...else`, and `if...else if...else`.
- Comparison and logical operators are commonly used in conditions.
- Conditional statements are essential for building interactive applications.

---

## Summary

Conditional statements are one of the most important programming concepts because they allow software to make decisions based on different conditions. By using `if`, `else`, and `else if` statements along with comparison and logical operators, programmers can create applications that respond intelligently to user input and changing situations. Mastering conditional statements is a fundamental step toward writing dynamic and interactive software.
