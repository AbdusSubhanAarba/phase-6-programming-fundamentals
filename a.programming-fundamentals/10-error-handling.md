# Error Handling

## Overview

Error handling is the process of **detecting, managing, and responding to errors** that occur while a program is running. Instead of allowing a program to crash unexpectedly, error handling enables it to respond gracefully and continue running whenever possible.

Every programmer encounters errors. The goal is not to avoid them completely, but to handle them properly.

---

## Why It Matters

Error handling is important because it:

- Prevents programs from crashing
- Improves user experience
- Makes software more reliable
- Helps identify problems quickly
- Allows programs to recover from unexpected situations

Good software is not software without errors—it is software that handles errors well.

---

## What Is an Error?

An error is a problem that prevents a program from working correctly.

Errors can happen for many reasons, including:

- Invalid user input
- Missing files
- Network problems
- Incorrect calculations
- Programming mistakes

Programs should be prepared to deal with these situations.

---

## Types of Errors

There are three common categories of programming errors.

### Syntax Errors

Syntax errors happen when the code does not follow the rules of the programming language.

Example:

- Missing quotation marks
- Missing brackets
- Missing semicolons (where required)

The program usually cannot start until these errors are fixed.

---

### Runtime Errors

Runtime errors occur **while the program is running**.

Examples:

- Dividing by zero
- Opening a file that does not exist
- Losing an internet connection

The program starts successfully but encounters a problem during execution.

---

### Logic Errors

Logic errors happen when the program runs without crashing but produces the wrong result.

Example:

A shopping cart should calculate:

```text
100 + 20

↓

120
```

Instead, it returns:

```text
100
```

The program runs, but the logic is incorrect.

---

## How Error Handling Works

A program performs an operation.

↓

If no error occurs:

Continue normally.

↓

If an error occurs:

Detect the problem.

↓

Respond appropriately.

↓

Continue or stop safely.

---

## Error Handling in JavaScript

JavaScript provides a mechanism called:

```text
try...catch
```

Its purpose is simple:

- **try** → Run the code.
- **catch** → Handle any error that occurs.

This prevents unexpected crashes and allows the program to respond gracefully.

(You'll learn the exact syntax later when writing JavaScript.)

---

## Why Error Handling Is Important

Imagine an online banking application.

Without error handling:

```text
Network Error

↓

Application Crashes
```

With error handling:

```text
Network Error

↓

Display

"Connection lost. Please try again."
```

The second experience is much better for the user.

---

## Real-World Examples

### ATM Machine

If there is no cash available:

```text
Display

"Unable to complete transaction."
```

instead of freezing.

---

### Online Shopping

If a payment fails:

```text
Display

"Payment unsuccessful. Please try again."
```

---

### Login System

If the password is incorrect:

```text
Display

"Incorrect username or password."
```

---

### File Download

If the internet disconnects:

```text
Display

"Download failed. Please reconnect and try again."
```

---

### Mobile App

If the server cannot be reached:

```text
Display

"Unable to connect to the server."
```

instead of closing the application.

---

## Best Practices

Good programmers:

- Expect errors to happen.
- Display helpful error messages.
- Avoid exposing technical details to users.
- Handle only the errors they can recover from.
- Test programs using invalid inputs.

Planning for failures makes software more reliable.

---

## Common Mistakes Beginners Make

Beginners often:

- Ignore possible errors.
- Assume users will always enter valid information.
- Display confusing technical error messages.
- Stop the entire program because of a small error.
- Forget to test unusual situations.

Every program should be prepared for unexpected events.

---

## Key Takeaways

- Error handling manages problems that occur while a program runs.
- The three main types of errors are syntax errors, runtime errors, and logic errors.
- JavaScript uses `try...catch` for handling runtime errors.
- Good error handling improves reliability and user experience.
- Every professional application includes error handling.

---

## Summary

Error handling is an essential part of programming that allows software to respond safely when problems occur. Instead of crashing, well-designed programs detect errors, inform the user appropriately, and recover whenever possible. By understanding syntax errors, runtime errors, logic errors, and the basics of JavaScript's `try...catch` mechanism, programmers can build applications that are more reliable, user-friendly, and professional.
