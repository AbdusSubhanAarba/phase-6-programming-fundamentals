# Loops

## Overview

A loop is a programming structure that allows a block of code to **repeat multiple times** until a certain condition is met.

Instead of writing the same code over and over, a loop performs the repetition automatically, making programs shorter, cleaner, and more efficient.

Loops are commonly used whenever a task needs to be repeated.

---

## Why It Matters

Loops are important because they:

- Reduce repetitive code
- Save development time
- Make programs easier to maintain
- Process large amounts of data efficiently
- Automate repetitive tasks

Without loops, many programs would require thousands of repeated lines of code.

---

## How Loops Work

A loop follows three basic steps:

1. Start.
2. Check a condition.
3. If the condition is true, execute the code and repeat.
4. If the condition is false, stop.

Example:

```text
Start

↓

Check Condition

↓

True?

↓

Yes → Execute Code → Repeat

No → End
```

---

## Why We Use Loops

Imagine you want to display:

```text
Hello
```

five times.

Without a loop:

```text
Hello

Hello

Hello

Hello

Hello
```

You would repeat the same instruction five times.

With a loop, you simply tell the computer:

```text
Repeat 5 times.
```

The computer handles the repetition automatically.

---

## Types of Loops

Most programming languages provide several kinds of loops.

The most common are:

- `for` loop
- `while` loop
- `do...while` loop

Each is useful in different situations.

---

## The `for` Loop

A `for` loop is used when you know **how many times** something should repeat.

Example:

```text
Repeat 10 times

↓

Print "Welcome"
```

The loop automatically counts each repetition until it reaches the limit.

---

## The `while` Loop

A `while` loop repeats **as long as a condition remains true**.

Example:

```text
Battery Level > 20%

↓

Keep Playing Music
```

Once the battery drops below the condition, the loop stops.

---

## The `do...while` Loop

A `do...while` loop is similar to a `while` loop.

The difference is that the code executes **at least once** before checking the condition.

Example:

```text
Open Menu

↓

Check if User Wants to Continue

↓

Repeat if Yes
```

Even if the condition is false, the menu appears once.

---

## Loop Control

Loops continue until their stopping condition is reached.

Example:

```text
Count

1

↓

2

↓

3

↓

4

↓

5

↓

Stop
```

Every loop needs a condition that eventually becomes false.

---

## Infinite Loops

An **infinite loop** happens when the stopping condition is never reached.

Example:

```text
Condition = Always True

↓

Repeat Forever
```

Infinite loops can cause programs to freeze or crash.

Every loop should have a way to stop.

---

## Real-World Examples

### Online Shopping

Loop through every product in the shopping cart.

---

### Social Media

Display every post in a user's feed.

---

### Email App

Read every email in the inbox.

---

### Video Games

Update the player's position every frame while the game is running.

---

### Attendance System

Check every student's attendance record.

---

## Common Mistakes Beginners Make

Beginners often:

- Forget to update the loop condition.
- Create infinite loops accidentally.
- Use the wrong type of loop.
- Repeat code manually instead of using a loop.
- Stop the loop too early or too late.

Understanding when the loop starts and stops is the key to using loops correctly.

---

## Key Takeaways

- Loops repeat a block of code.
- They reduce repetitive code and improve efficiency.
- The main loop types are `for`, `while`, and `do...while`.
- Every loop needs a stopping condition.
- Infinite loops occur when a loop never stops.
- Loops are used in almost every software application.

---

## Summary

Loops are one of the most powerful tools in programming because they allow tasks to be repeated automatically. Instead of writing the same instructions multiple times, programmers use loops to process data efficiently, automate repetitive work, and simplify code. Understanding `for`, `while`, and `do...while` loops is essential for building scalable and efficient software.
