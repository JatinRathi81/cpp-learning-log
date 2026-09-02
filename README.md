# C++ Learning Log

This repository documents my C++ learning through concept-wise practice programs written by me.

## Progress

### Day 1 — September 1, 2026

| Order | Concept | Practice file |
| --- | --- | --- |
| 1 | Hello World and basic program structure | [`HelloWorld.cpp`](./01-Basics/HelloWorld.cpp) |
| 2 | Taking input and displaying output | [`InputOutput.cpp`](./01-Basics/InputOutput.cpp) |
| 3 | Variable naming rules | [`VariableNamingRules.cpp`](./01-Basics/VariableNamingRules.cpp) |

### Day 2 — September 2, 2026

| Order | Concept | Practice file |
| --- | --- | --- |
| 1 | Arithmetic operators with integers | [`ArithmeticOperators.cpp`](./01-Basics/ArithmeticOperators.cpp) |
| 2 | Arithmetic operators with floating-point values | [`ArithmeticOperatorsOnFloat.cpp`](./01-Basics/ArithmeticOperatorsOnFloat.cpp) |
| 3 | Operator precedence and integer arithmetic | [`Bodmas.cpp`](./01-Basics/Bodmas.cpp) |
| 4 | Prefix increment and decrement operators | [`PostPreIncrementDecrementOperators.cpp`](./01-Basics/PostPreIncrementDecrementOperators.cpp) |
| 5 | Prefix and postfix behavior | [`PostVsPre.cpp`](./01-Basics/PostVsPre.cpp) |
| 6 | Simple interest calculation | [`SimpleInterest.cpp`](./01-Basics/SimpleInterest.cpp) |
| 7 | Square of a number | [`SquareOfANumber.cpp`](./01-Basics/SquareOfANumber.cpp) |
| 8 | Sum of two numbers | [`SumOfTwo.cpp`](./01-Basics/SumOfTwo.cpp) |
| 9 | Implicit and explicit typecasting | [`Typecasting.cpp`](./01-Basics/Typecasting.cpp) |
| 10 | Character data type | [`CharDataType.cpp`](./01-Basics/CharDataType.cpp) |
| 11 | Integer and floating-point division | [`IntByInt.cpp`](./01-Basics/IntByInt.cpp) |
| 12 | Modulus operator | [`Modulus.cpp`](./01-Basics/Modulus.cpp) |

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

### Arithmetic operators and numeric types

- The `+`, `-`, `*`, and `/` operators perform basic arithmetic.
- Division between integers produces an integer result.
- Using a floating-point operand allows the result to include a fractional part.
- Operator precedence and left-to-right evaluation determine the order of arithmetic operations.

### Increment and decrement operators

- The increment operator increases a value by one.
- The decrement operator decreases a value by one.
- Prefix and postfix operators differ in when the updated value is used in an expression.

### Character data and typecasting

- The `char` data type stores a single character.
- Implicit typecasting happens automatically.
- Explicit typecasting requests a conversion using a specified type.
- Character values can participate in arithmetic and can be converted to integer or character form.

### Modulus and calculation programs

- The modulus operator (`%`) returns the remainder after integer division.
- Input values can be used to calculate a sum, square, or simple interest.

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

