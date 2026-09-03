# C++ Learning Log

This repository documents my C++ learning through concept-wise practice programs and progress notes.

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

### Day 3 — September 3, 2026

| Order | Concept | Practice file |
| --- | --- | --- |
| 1 | Finding the absolute value of a number | [`AbsoluteValue.cpp`](./02-Conditionals/AbsoluteValue.cpp) |
| 2 | Boolean data type | [`BoolDataType.cpp`](./02-Conditionals/BoolDataType.cpp) |
| 3 | Divisibility using logical OR | [`DivisibleBy5Or3.cpp`](./02-Conditionals/DivisibleBy5Or3.cpp) |
| 4 | Comparing double and float precision | [`DoubleVSFloat.cpp`](./02-Conditionals/DoubleVSFloat.cpp) |
| 5 | Checking for a four-digit number | [`FourDigitNumber.cpp`](./02-Conditionals/FourDigitNumber.cpp) |
| 6 | Finding the greatest of three numbers | [`GreatestOfThree.cpp`](./02-Conditionals/GreatestOfThree.cpp) |
| 7 | Checking whether a value is an integer | [`IntegerOrNot.cpp`](./02-Conditionals/IntegerOrNot.cpp) |
| 8 | Selecting a day with switch | [`IthDayOfWeek.cpp`](./02-Conditionals/IthDayOfWeek.cpp) |
| 9 | Long long integer limits | [`LongLongDataType.cpp`](./02-Conditionals/LongLongDataType.cpp) |
| 10 | Else-if ladder with divisibility conditions | [`NamesElseIf.cpp`](./02-Conditionals/NamesElseIf.cpp) |
| 11 | Nested ternary expressions | [`NestedTernary.cpp`](./02-Conditionals/NestedTernary.cpp) |
| 12 | Odd and even number checking | [`OddEven.cpp`](./02-Conditionals/OddEven.cpp) |
| 13 | Profit and loss calculation | [`ProfitLoss.cpp`](./02-Conditionals/ProfitLoss.cpp) |
| 14 | Integer data type limits | [`RangeOfInt.cpp`](./02-Conditionals/RangeOfInt.cpp) |
| 15 | Relational operators | [`RelationalOperators.cpp`](./02-Conditionals/RelationalOperators.cpp) |
| 16 | Short integer limits | [`ShortDataType.cpp`](./02-Conditionals/ShortDataType.cpp) |
| 17 | Conditional ternary operator | [`Ternary.cpp`](./02-Conditionals/Ternary.cpp) |
| 18 | Storing a ternary result in a variable | [`TernaryVariable.cpp`](./02-Conditionals/TernaryVariable.cpp) |
| 19 | Checking for a three-digit number | [`ThreeDigitNumber.cpp`](./02-Conditionals/ThreeDigitNumber.cpp) |
| 20 | Validating triangle sides | [`TriangleOrNot.cpp`](./02-Conditionals/TriangleOrNot.cpp) |
| 21 | Unsigned integer data type | [`Unsigned.cpp`](./02-Conditionals/Unsigned.cpp) |
| 22 | Checking driving-age eligibility | [`ValidAgeForDriving.cpp`](./02-Conditionals/ValidAgeForDriving.cpp) |
| 23 | Conditions, assignment, and post-increment behavior | [`VariableInsideIf.cpp`](./02-Conditionals/VariableInsideIf.cpp) |

> Compilation status: 22 programs compile successfully. `ShortDataType.cpp` is stored unchanged and currently fails to compile because `INT16_MIN` and `INT16_MAX` are not declared by the included headers on the tested compiler. `Unsigned.cpp` compiles with an unused-variable warning.

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

### Conditional statements and decision-making

- `if`, `else if`, and `else` select different execution paths.
- Relational operators compare values, while logical operators combine conditions.
- Nested conditions support decisions involving several related checks.
- A `switch` statement selects one case from several fixed options.
- The ternary operator provides a compact conditional expression.

### Conditional practice problems

- Conditions can check divisibility, number length, odd/even status, and driving eligibility.
- Multiple comparisons can find the greatest value and validate triangle sides.
- Conditional branches can calculate profit or loss and identify integer input.
- Variables, assignments, increments, and short-circuit expressions affect how a condition is evaluated.

### Numeric data types and limits

- `bool` stores either `true` or `false`.
- `float` and `double` differ in precision.
- `short`, `int`, `long long`, and `unsigned int` represent different integer ranges and signedness.
- Constants from standard headers can be used to inspect numeric limits.

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

