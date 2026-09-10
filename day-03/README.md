# 🟨 JavaScript Day 3 — Data Types

## 📚 What I Learned

Today I learned about **data types in JavaScript** and how different types of values are stored and identified.

A data type tells us **what kind of value** we are working with.

---

## 🧠 Key Concepts

### 1. String

A string represents text.

```javascript
const name = "Dinushan";
const profession = "Python Developer";
```

The values `"Dinushan"` and `"Python Developer"` are both `string` values.

---

### 2. Number

JavaScript uses the `number` type for numeric values.

```javascript
const age = 24;
const height = 170.65;
```

Both values are `number`.

Unlike Python, JavaScript's basic `number` type covers both integers and decimal numbers.

---

### 3. Boolean

A Boolean represents one of two values:

```javascript
true
false
```

Example:

```javascript
const isDeveloper = true;
```

The value `true` has the `boolean` data type.

---

### 4. Undefined

A variable that has been declared but has not been assigned a value has the value `undefined`.

```javascript
let currentProject;
```

Since no value was assigned to `currentProject`:

```javascript
console.log(currentProject);
```

outputs:

```text
undefined
```

---

### 5. Null

`null` represents an intentional absence of a value.

```javascript
const phoneNumber = null;
```

Here, the variable has deliberately been assigned `null`.

---

## 🔍 Using `typeof`

The `typeof` operator can be used to check the type of a value.

Example:

```javascript
const name = "Dinushan";

console.log(typeof name);
```

Output:

```text
string
```

Other examples:

```javascript
typeof 24        // "number"
typeof 170.65    // "number"
typeof true      // "boolean"
typeof undefined // "undefined"
```

### ⚠️ JavaScript `null` Quirk

An interesting behavior in JavaScript is:

```javascript
typeof null
```

which returns:

```text
object
```

This is a historical JavaScript behavior.

---

## 🐍 Python vs JavaScript

| Python  | JavaScript |
| ------- | ---------- |
| `str`   | `string`   |
| `int`   | `number`   |
| `float` | `number`   |
| `bool`  | `boolean`  |
| `None`  | `null`     |

One important difference is that Python has separate `int` and `float` types, while JavaScript uses `number` for ordinary numeric values.

---

## 💻 Practice

For today's practice, I created variables representing:

* My name
* My age
* My height
* Whether I am a developer
* A variable without an assigned value
* A variable intentionally assigned `null`

```javascript
const name = "Dinushan";

const age = 24;

const height = 170.65;

const isDeveloper = true;

let currentProject;

const phoneNumber = null;

console.log(typeof name);
console.log(typeof age);
console.log(typeof height);
console.log(typeof isDeveloper);
console.log(typeof currentProject);
console.log(typeof phoneNumber);
```

### Expected Output

```text
string
number
number
boolean
undefined
object
```

---

## 🎯 What I Understood

The main lesson from today is that JavaScript values have different data types.

I learned:

* `string` → text
* `number` → numeric values
* `boolean` → `true` or `false`
* `undefined` → no value has been assigned
* `null` → intentional absence of a value
* `typeof` → checks the type of a value

I also learned that JavaScript uses `number` for both integer and decimal numbers.

---

## 🚀 Next Step

**Day 4 — JavaScript Operators**

Topics coming next:

* Arithmetic operators
* Assignment operators
* Comparison operators
* Logical operators
* Increment and decrement
* Python vs JavaScript operator differences

## ✅ Status

**Day 3 — Completed 🚀**