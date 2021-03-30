---

title: "Good practices in Python."
type: slide
slideOptions:
  theme: cern3
  transition: none

---

---

## Python Good Practices

5/2/2019

---

1. Naming variables and functions
2. PEP8
3. Exceptions
4. Logging
5. Testing your code

---

### Naming

Intention of the variabls and functions should be clear from their names.

---

### PEP8
- Python Enhancement Proposals
(https://www.python.org/dev/peps/)
    - code formatting
    - comments
    - naming conventions

---

### PEP8

- Rules to keep consistent style in your code:
  - cleaner, more comfortable to read and to be understood.
- Collaboration with other people is easier.
- It is an essential requirement for code. 
- Bad formatting may be the source of many code problems.

---

### PEP8

Usually, we use auto-formatters.

---

### Exceptions
 
Two types of errors:
- Syntax Errors
- Runtime Errors, called Exceptions

---

### Exceptions

- Trying to open a file that does not exist (FileNotFoundError)
- Dividing a number by zero (ZeroDivisionError)
- Import is not found (ImportError)
- etc...

---

### Logging
- Tracking events during software excution.
- Very handful for debugging and post-failure analysis.
[Python Docs](https://docs.python.org/3/howto/logging.html)


---

### Logging
And why can't we just use print?

- Logs have more context (severity, timestamp, where they come from etc).
- More configurable (save in file, send over http etc).
- Debugging is easier.

---

### Code Testing
 Testing is one of the fundementals of coding and maybe the most important
 tool a coder has.

---

### Code Testing

- We test one thing per test.
- Each test must be independent.
- Use descriptive names for your test functions.
- Tests have to be simple and easy to explain.

Reitz, Kenneth, and Tanya Schlusser. The Hitchhiker's Guide to Python: Best Practices for Development. O'Reilly, 2016.

---

### Virtual Environments

- V.E. keep dependencies of different projects seperate.

---



