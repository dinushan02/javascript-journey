# 🟨 JavaScript Day 2 — Variables

## 📚 What I Learned

Today I learned about variables in JavaScript and how to use `let` and `const`.

A variable is a named reference used to store or work with a value in a program.

## 🧠 Key Concepts

### 1. Variables

Variables allow us to work with values by giving them meaningful names.

```js
const name = "Dinushan";
let currentSkill = "Python";
```

Here:

* `name` refers to the value `"Dinushan"`
* `currentSkill` refers to the value `"Python"`

### 2. `const`

`const` is used when a variable should not be reassigned.

```js
const name = "Dinushan";
```

This is not allowed:

```js
name = "Ram Kumar";
```

JavaScript will throw an error because a `const` variable cannot be reassigned.

### 3. `let`

`let` is used when a variable needs to be reassigned.

```js
let currentSkill = "Python";

currentSkill = "JavaScript";
```

The value of `currentSkill` can be reassigned.

## ⚖️ `let` vs `const`

| Keyword | Can be reassigned? | Use when                          |
| ------- | ------------------- | ---------------------------------- |
| `let`   | ✅ Yes               | The variable needs to be reassigned |
| `const` | ❌ No                | The variable should not be reassigned |

**Simple Rule:** Use `const` by default. Use `let` when reassignment is necessary.

## 🐍 Python vs JavaScript

In Python, variables can be reassigned directly:

```python
name = "Dinushan"
name = "Ram Kumar"
```

In JavaScript, we use `let` when reassignment is required:

```js
let name = "Dinushan";
name = "Ram Kumar";
```

With `const`, reassignment is not allowed:

```js
const name = "Dinushan";
name = "Ram Kumar"; // Error
```

## 📝 Naming Convention

JavaScript commonly uses **camelCase** for variable names.

Recommended:

```js
const learningTopic = "JavaScript";
```

Instead of:

```js
const learning_topic = "JavaScript";
```

## 💻 Practice

For my Day 2 practice, I created variables for:

* My name
* My profession
* My learning topic
* My current skill

I used `const` for values that did not need reassignment and `let` for a value that I wanted to change.

Example:

```js
const name = "Dinushan";
const profession = "Python Developer";
const learningTopic = "JavaScript";

let currentSkill = "Python";
currentSkill = "JavaScript";

console.log("Name:", name);
console.log("Profession:", profession);
console.log("Learning Topic:", learningTopic);
console.log("Current Skill:", currentSkill);
```

## 🎯 What I Understood

The important lesson from today is that choosing between `let` and `const` depends on whether the variable will be reassigned in the program.

* `const` → cannot be reassigned
* `let` → can be reassigned

I also learned that meaningful variable names and consistent naming conventions make code easier to understand.

## 🚀 Next Step

**Day 3 — JavaScript Data Types**

Topics coming next:

* Strings
* Numbers
* Booleans
* `undefined`
* `null`
* Checking data types with `typeof`

## ✅ Status

**Day 2 — Completed** 🚀