# Split and Join String (Python)

This repository contains a Python program that splits a string using spaces and joins the words using a hyphen (`-`).

---

## 🧩 Problem Statement

Given a string of space-separated words, split the string on spaces and join the words using a hyphen.

---

## 🔢 Example

### Input
this is a string


### Output


this-is-a-string


---

## 💡 Approach

1. Use `split(" ")` to divide the string into words.
2. Use `"-".join()` to join the words with hyphens.

---

## 💻 Python Code

```python
def split_and_join(line):
    line = line.split(" ")
    line = "-".join(line)
    return line
