# C++ Learning Log

This repository documents my C++ learning through concept-wise practice programs written by me.

## Progress

### Day 1 — September 1, 2026

| Order | Concept | Practice file |
| --- | --- | --- |
| 1 | Hello World and basic program structure | [`HelloWorld.cpp`](./01-Basics/HelloWorld.cpp) |
| 2 | Taking input and displaying output | [`InputOutput.cpp`](./01-Basics/InputOutput.cpp) |
| 3 | Variable naming rules | [`VariableNamingRules.cpp`](./01-Basics/VariableNamingRules.cpp) |

## Concepts learned

### Basic program structure

- `#include <iostream>` provides standard input and output functionality.
- `main()` is the entry point of a C++ program.
- `cout` displays output on the screen.
- `endl` moves the cursor to a new line.

### Input and output

- `cin` takes input from the user.
- The input value can be stored in a variable and displayed with `cout`.

### Variable naming rules

- Variable names cannot contain spaces.
- Variable names cannot begin with a number.
- Special characters cannot be used in ordinary variable names.
- C++ keywords such as `if`, `for`, `while`, and `do` cannot be used as variable names.

## Compile and run

Use a C++ compiler such as GCC:

```bash
g++ 01-Basics/HelloWorld.cpp -o HelloWorld
./HelloWorld
```

On Windows Command Prompt:

```bat
HelloWorld.exe
```

