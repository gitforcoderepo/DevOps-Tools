````markdown
# Python Scripting Notes

**Instructor:** Sandeep  
**Email:** omtech@gmail.com  
**Date:** 23 April 2026  

---

## Python Basics

- Python is a **programming language**.
- It is widely used for:
  - Scripting
  - Automation
  - DevOps
  - Data Science

> **Note:**  
> We (DevOps engineers) focus more on scripting and automation rather than full-scale application development. However, Python is still a programming language.

---

## Shebang Line

The first line of a Python script can be a **shebang line**, similar to shell scripting.

### Example:
```bash
#!/usr/bin/python
````

### Recommended (Portable Version):

```bash
#!/usr/bin/env python3
```

---

## Commenting in Python

### Single-line Comments

Use `#`

```python
# Comment 1
# Comment 2
# Comment 3
```

---

### Multi-line Comments

Python does not officially support multi-line comments.
We use multi-line strings instead:

```python
"""
This is comment line 1
This is comment line 2
This is comment line 3
"""
```

> ⚠️ These are technically strings, not actual comments.

---

## Variables

### Defining a Variable

```python
var1 = 10
```

### Accessing a Variable

```python
var1
```

---

## Printing Variables

### Python 2

```python
print var1
```

### Python 3 (Recommended)

```python
print(var1)
```

---

## Installation

1. Go to: [https://www.python.org](https://www.python.org)
2. Download Python for Windows
3. Install it

---

## Checking Installation

```bash
python --version
```

or

```bash
python3 --version
```

---

## First Python Script

```python
#!/usr/bin/env python3

# Comment section

"""
This is line 1 comment section
This is line 2 comment section
This is line 3 comment section
"""

# Defining variables
var1 = 10

# Printing variable
print(var1)
```

---

## Summary

* Python is both a **programming** and **scripting** language
* Use `#` for single-line comments
* Use `""" """` for multi-line descriptions/docstrings
* Always prefer **Python 3**
* Use `#!/usr/bin/env python3` for better portability

```

---

If you want, I can next:
- Add **GitHub badges & styling**
- Convert this into a **README.md with sections + TOC**
- Or make it look like **professional DevOps documentation**
```
