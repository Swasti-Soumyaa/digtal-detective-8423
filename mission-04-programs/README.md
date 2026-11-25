# Mission 4 — How Programs Run

## 1. Mission Title
How Programs Run

## 2. Task / Objective
Understand how Python programs execute and compare how compilers and interpreters translate or execute programs.

## 3. Work Completed

### Task 4.1 — Create and Run a Python Program

Created a Python file named `hello.py` containing:

```python
print("Hello from Python")
```

Executed the program using Python 3 in Terminal.

Command used:

`python3 mission-04-programs/hello.py`

Expected output:

`Hello from Python`

### Task 4.2 — Compiler vs Interpreter

| Point | Compiler | Interpreter |
|---|---|---|
| When translation / execution happens | Translates the source code before the program runs | Reads and executes instructions at runtime |
| Typical output | Translated code, often machine code | Usually executes instructions without producing a separate executable |
| One example | C compiler | Python interpreter |
| One advantage | Compiled programs can execute efficiently | Makes testing and executing code convenient |

**Explanation:**

A compiler translates the source code into another form before the program runs. An interpreter executes instructions at runtime. Compilers can produce machine code that runs efficiently, while interpreters make it convenient to test and execute programs. Some programming language implementations use a combination of both approaches.

## 4. Commands / Tools Used
- `python3 --version` – Checks the installed Python version.
- `python3 mission-04-programs/hello.py` – Executes the Python program.
- VS Code – Used