# Mission 5 — Numbers and Data

## Task / Objective
Convert decimal, binary and hexadecimal numbers manually, verify the conversions using Python, build a number converter program and understand text encoding.

## Task 5.1 — Convert Numbers by Hand

1. **Decimal 13 to binary**

   Divide repeatedly by 2:

   - 13 ÷ 2 = 6 remainder 1
   - 6 ÷ 2 = 3 remainder 0
   - 3 ÷ 2 = 1 remainder 1
   - 1 ÷ 2 = 0 remainder 1

   Read the remainders from bottom to top.

   **Answer: 1101**

2. **Decimal 25 to binary**

   - 25 ÷ 2 = 12 remainder 1
   - 12 ÷ 2 = 6 remainder 0
   - 6 ÷ 2 = 3 remainder 0
   - 3 ÷ 2 = 1 remainder 1
   - 1 ÷ 2 = 0 remainder 1

   **Answer: 11001**

3. **Binary 1010 to decimal**

   \(1×2^3 + 0×2^2 + 1×2^1 + 0×2^0\)

   = 8 + 0 + 2 + 0

   **Answer: 10**

4. **Binary 1101 to decimal**

   \(1×2^3 + 1×2^2 + 0×2^1 + 1×2^0\)

   = 8 + 4 + 0 + 1

   **Answer: 13**

5. **Hexadecimal A to decimal**

   A = 10

   **Answer: 10**

6. **Hexadecimal 1F to decimal**

   \(1×16 + 15 = 31\)

   **Answer: 31**

7. **Binary 1111 to hexadecimal**

   1111 in binary = 15 in decimal, and 15 is F in hexadecimal.

   **Answer: F**

## Task 5.2 — Verify Using Python

I used Python's built-in conversion functions to verify my manual calculations.

| Expression | Result | Matches manual calculation? |
|---|---|---|
| `bin(13)` | `0b1101` | Yes |
| `bin(25)` | `0b11001` | Yes |
| `int('1010', 2)` | `10` | Yes |
| `int('1101', 2)` | `13` | Yes |
| `int('A', 16)` | `10` | Yes |
| `int('1F', 16)` | `31` | Yes |
| `hex(15)` | `0xf` | Yes |

## Task 5.3 — Build a Small Number Converter

I created `number_converter.py` using Python's `input()`, `int()`, `bin()` and `hex()` functions.

### Program

```python
number = int(input("Enter a positive decimal number: "))

binary = bin(number)
hexadecimal = hex(number)

print("Binary:", binary)
print("Hexadecimal:", hexadecimal)
```

### Test Results

| Decimal Input | Binary Output | Hexadecimal Output |
|---|---|---|
| 13 | `0b1101` | `0xd` |
| 25 | `0b11001` | `0x19` |
| 31 | `0b11111` | `0x1f` |

### Understanding the Functions

- `input()` accepts a value from the user.
- `int()` converts the input into an integer.
- `bin()` converts an integer into binary.
- `hex()` converts an integer into hexadecimal.

## Task 5.4 — How Is Text Stored?

1. **ASCII decimal codes:**
   - Uppercase A = 65
   - Lowercase a = 97

2. A computer needs an encoding standard to convert characters into numbers that it can store and process. Encoding standards ensure that text can be represented and interpreted consistently.

3. An example of a character outside basic ASCII is **₹ (Indian Rupee symbol)**.

## My Understanding

I learned that computers represent numbers using binary digits (0 and 1). Decimal uses base 10, binary uses base 2 and hexadecimal uses base 16. I also understood how Python can convert numbers between these systems and how character encoding helps computers store text.

## Difficulties Faced

Initially, understanding the conversion of binary and hexadecimal numbers was challenging.

## How I Resolved Them

I practised the conversion steps manually and then checked my answers using Python's built-in functions.

## Evidence / Files

- `number_converter.py`
- This README file
- Terminal output showing the three test cases

## Commit Details

Commit message: `Complete number conversions and Python converter`
