# Data Types

## Overview

A data type defines the **kind of value** that a variable can store. Different data types allow programs to work with numbers, text, true or false values, collections of data, and more.

Choosing the correct data type helps programs use memory efficiently, perform the correct operations, and reduce errors.

Every programming language supports multiple data types, although their names and implementations may differ.

---

## Why It Matters

Data types are important because they:

- Define what kind of data can be stored
- Determine what operations can be performed
- Improve program reliability
- Help prevent programming errors
- Allow computers to manage memory efficiently

Understanding data types is essential for writing correct and efficient programs.

---

## Common Data Types

Most programming languages provide several basic data types.

Some of the most common are:

- Number
- String
- Boolean
- Null
- Undefined
- Object
- Array

These are the primary data types you'll work with in JavaScript.

---

## Number

The **Number** data type stores numeric values.

Examples:

```text
25

3.14

-100

0
```

Numbers are used for:

- Age
- Prices
- Scores
- Calculations
- Measurements

---

## String

A **String** stores text.

Strings are written inside quotation marks.

Examples:

```text
"Ali"

"Hello World"

"Software Engineering"
```

Strings are commonly used for:

- Names
- Messages
- Email addresses
- Passwords
- Website URLs

---

## Boolean

A **Boolean** stores only one of two possible values:

```text
true

false
```

Booleans are used when making decisions.

Example:

```text
isLoggedIn

↓

true
```

```text
isAdmin

↓

false
```

---

## Null

**Null** represents an intentional absence of a value.

Example:

```text
middleName

↓

null
```

This means the variable currently has **no assigned value on purpose**.

---

## Undefined

A variable is **undefined** when it has been created but has not yet been assigned a value.

Example:

```text
let age;
```

Since no value has been assigned yet:

```text
age

↓

undefined
```

---

## Object

An **Object** stores multiple related pieces of information together.

Example:

```text
Person

↓

Name: Ahmed

Age: 22

Country: Bahrain
```

Objects are useful for representing real-world entities.

---

## Array

An **Array** stores multiple values inside a single variable.

Example:

```text
["Apple", "Banana", "Orange"]
```

Arrays are used whenever multiple related values need to be stored.

---

## Choosing the Right Data Type

Different situations require different data types.

| Situation | Data Type |
|-----------|-----------|
| Age | Number |
| Name | String |
| Is Logged In | Boolean |
| No Value Yet | Null or Undefined |
| Student Information | Object |
| Shopping List | Array |

Choosing the correct data type makes programs easier to understand and maintain.

---

## Real-World Examples

### Banking App

- Account Balance → Number
- Customer Name → String
- Is Account Active → Boolean

---

### Online Store

- Product Name → String
- Price → Number
- Cart Items → Array

---

### Social Media

- Username → String
- Followers → Number
- Verified Account → Boolean
- User Profile → Object

---

### School System

- Student Name → String
- Marks → Number
- Subjects → Array

---

## Data Types in JavaScript

JavaScript includes several primitive data types:

- Number
- String
- Boolean
- Undefined
- Null
- BigInt
- Symbol

It also includes one non-primitive data type:

- Object

Arrays and functions are technically special types of objects in JavaScript.

---

## Common Mistakes Beginners Make

Beginners often:

- Confuse numbers with strings.

Example:

```text
25
```

is different from

```text
"25"
```

- Forget that Booleans only have two values.
- Confuse `null` and `undefined`.
- Store the wrong type of data in a variable.
- Assume every value is text.

Understanding data types helps prevent many common programming errors.

---

## Key Takeaways

- A data type defines what kind of value a variable stores.
- Common data types include Number, String, Boolean, Null, Undefined, Object, and Array.
- Different data types are used for different purposes.
- Choosing the correct data type improves code quality and efficiency.
- Understanding data types is fundamental to programming.

---

## Summary

Data types are one of the core building blocks of programming. They define the kinds of values that variables can store and determine how those values can be used within a program. From numbers and text to objects and arrays, each data type serves a specific purpose. Mastering data types allows programmers to write accurate, efficient, and reliable software across any programming language.
