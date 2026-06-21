# python-discoveries
This is a like daily diary about things i learned in python

# 🧰 Python Toolbox

A personal collection of things I discover while learning Python.

This is not a notes repository and not a copy of Python documentation.

The goal of this repo is simple:

* Keep track of mistakes I keep making
* Save patterns that appear repeatedly
* Store useful discoveries that made Python click
* Build my own programming toolbox over time

Instead of trying to memorize everything Python offers, I want to create a place where I can revisit things that actually helped me while building projects and solving problems.

---

## 📂 Repository Structure

```text
python-toolbox/
│
├── things-that-saved-me/
├── bugs-i-made/
├── patterns/
├── aha-moments/
```

---

## 📁 things-that-saved-me/

Purpose:

Useful functions, tricks, concepts, or discoveries that unexpectedly saved time or made code easier.

Examples:

* `float('-inf')`
* `enumerate()`
* `zip()`
* `list.copy()`
* `dict.get()`
* `any()` / `all()`

Template:

```python
# What it is:
...

# Why it helped:
...

# Example:

...

# When I may use it:
...
```

---

## 📁 bugs-i-made/

Purpose:

A collection of mistakes I personally made so I don't repeat them again.

These are usually more valuable than perfect notes because they show where my thinking went wrong.

Examples:

* Comparing numbers with strings



* Forgetting `return`
* Infinite loops
* Wrong indentation

Template:

```python
# Mistake:

...

# Why it happened:

...

# Fixed version:

...

# Lesson learned:

...
```

---

## 📁 patterns/

Purpose:

Store reusable problem-solving structures.

Instead of remembering entire solutions, I can remember patterns.

Examples:

Find largest number:

```python
largest = float('-inf')

for num in nums:
    if num > largest:
        largest = num
```

Count frequency:

```python
freq = {}

for item in items:
    freq[item] = freq.get(item,0)+1
```

Two pointers:

```python
left = 0
right = len(nums)-1
```

Template:

```python
# Pattern Name:

...

# Problem type:

...

# Code:

...

# Why it works:

...
```

---

## 📁 aha-moments/

Purpose:

Small moments where something suddenly made sense.

Usually these are ideas that changed my understanding.

Examples:

🧠 "`b = a` doesn't create a new list"

🧠 "`return` gives back values while `print()` only displays them"

🧠 "`float('-inf')` is useful because starting with `0` can fail"

Template:

```python
# What clicked:

...

# Before:

I thought ...

# After:

I realized ...

# Example:
...
```

---

## Emoji Legend

🧠 = New concept

🔥 = Saved me time

💀 = Mistake I made

⚡ = Shortcut or trick

🚫 = Avoid this

---

This repo grows with projects, mistakes, debugging sessions, and random "wait... Python can do that?!" moments.
 


