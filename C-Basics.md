# C Programming Language Basics

## 1. Data Types

| Data Type | Description |
| :--- | :--- |
| `int` | Stores whole numbers (integers) without decimals. Typically 4 bytes. |
| `float` | Stores fractional numbers with single-precision floating point. |
| `double` | Stores fractional numbers with double-precision floating point. |
| `char` | Stores a single character/letter or ASCII value. Typically 1 byte. |
| `bool` | Stores boolean values (`true` or `false`). Requires `<stdbool.h>`. |
| `void` | Represents the absence of a value or a function returning no type. |

---

## 2. Format Specifiers

| Specifier | Description |
| :---: | :--- |
| `%d` | Signed decimal integer |
| `%u` | Unsigned decimal integer |
| `%o` | Unsigned octal integer |
| `%x` | Unsigned hexadecimal integer (lowercase) |
| `%X` | Unsigned hexadecimal integer (uppercase) |
| `%f` | Floating-point number (decimal representation) |
| `%e` | Floating-point number (scientific notation/exponential) |
| `%c` | Single character |
| `%s` | String of characters |
| `%ld` | Signed long decimal integer |

---

## 3. Input/Output Functions

* **`scanf()`**: Reads formatted input from the standard input stream (`stdin`). Requires memory addresses (`&`) for non-array variables.
* **`printf()`**: Prints formatted text and variable values to the standard output stream (`stdout`).
* **`getchar()`**: Reads a single character from standard input and returns it as an integer.
* **`putchar()`**: Displays a single character passed as an argument onto standard output.
* **`fgets()`**: Reads a string from a specified stream up to a specified character limit, safely avoiding buffer overflows.
* **`puts()`**: Writes a string to standard output and automatically appends a newline character (`\n`).

---

## 4. Escape Sequences

1. **`\n` (Newline):** Moves the cursor to the beginning of the next line.
   ```c
   printf("Hello\nWorld");
