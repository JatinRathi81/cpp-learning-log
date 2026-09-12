# C++ Learning Log

This repository documents my C++ learning journey through daily practice, concept-wise programs, theory notes, and problem-solving exercises.

## Topics

- C++ Basics
- Operators and Typecasting
- Conditional Statements
- Loops and Iteration
- Pattern Printing and Nested Loops
- Functions and Scope
- Pointers

## Daily Progress

### Day 1 — September 1, 2026

**Topic: C++ Basics**

#### Theory

- A C++ program starts execution from the `main()` function.
- `#include <iostream>` provides standard input/output functionality such as `cin` and `cout`.
- `cout` is used to display output, while `cin` is used to take input from the user.
- `<<` is used with `cout` to send data to the output stream, and `>>` is used with `cin` to receive input.
- `endl` moves the output to the next line.
- Variables are named storage locations used to hold values.
- Variable names can contain letters, digits, and underscores, but cannot start with a digit or use C++ keywords.
- C++ variable names are case-sensitive.

#### Practice

| Order | Concept | Practice file |
| --- | --- | --- |
| 1 | Hello World and basic program structure | [`HelloWorld.cpp`](./01-Basics/HelloWorld.cpp) |
| 2 | Taking input and displaying output | [`InputOutput.cpp`](./01-Basics/InputOutput.cpp) |
| 3 | Variable naming rules | [`VariableNamingRules.cpp`](./01-Basics/VariableNamingRules.cpp) |

### Day 2 — September 2, 2026

**Topic: Operators, Typecasting and Basic Calculations**

#### Theory

- Arithmetic operators perform basic calculations: `+`, `-`, `*`, `/`, and `%`.
- Integer division produces an integer result when both operands are integers. Using a floating-point operand produces a floating-point result.
- Operator precedence determines the order in which parts of an expression are evaluated. Parentheses can be used to control the order explicitly.
- Increment and decrement operators change a variable by one. Prefix form changes the value before it is used, while postfix form uses the current value before changing it.
- The modulus operator `%` gives the remainder of an integer division.
- Typecasting converts a value from one data type to another. It can happen implicitly or be requested explicitly.
- `char` is used to represent character values. Characters can also participate in arithmetic through their character codes.
- Basic formulas can be implemented by combining variables, input, arithmetic operators, and output.

#### Practice

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

**Topic: Conditional Statements and Decision Making**

#### Theory

- Conditional statements allow a program to make decisions based on whether a condition is true or false.
- `if` executes a block when its condition is true. `else` provides an alternative path.
- `else if` allows multiple conditions to be checked in sequence.
- Nested `if` statements place one decision inside another decision.
- Relational operators such as `<`, `>`, `<=`, `>=`, `==`, and `!=` compare values and produce a Boolean result.
- Logical operators such as `&&`, `||`, and `!` combine or modify conditions.
- A `bool` represents a logical value: `true` or `false`.
- `switch` selects between different cases based on the value of an expression. `break` prevents execution from continuing into the next case.
- The ternary operator `condition ? value1 : value2` is a compact way to choose between two expressions.
- Data types have limits. `int`, `short`, `long long`, and `unsigned int` differ in the values they can represent.
- `float` and `double` use floating-point representation and can show different levels of precision.
- Conditions can be used to solve practical decision problems such as odd/even checks, number validation, profit/loss, eligibility, and triangle validation.

#### Practice

| Order | Concept | Practice file |
| --- | --- | --- |
| 1 | Absolute value | [`AbsoluteValue.cpp`](./02-Conditionals/AbsoluteValue.cpp) |
| 2 | Boolean data type | [`BoolDataType.cpp`](./02-Conditionals/BoolDataType.cpp) |
| 3 | Divisibility using logical OR | [`DivisibleBy5Or3.cpp`](./02-Conditionals/DivisibleBy5Or3.cpp) |
| 4 | Double and float precision | [`DoubleVSFloat.cpp`](./02-Conditionals/DoubleVSFloat.cpp) |
| 5 | Checking a four-digit number | [`FourDigitNumber.cpp`](./02-Conditionals/FourDigitNumber.cpp) |
| 6 | Greatest of three numbers | [`GreatestOfThree.cpp`](./02-Conditionals/GreatestOfThree.cpp) |
| 7 | Checking whether a value is an integer | [`IntegerOrNot.cpp`](./02-Conditionals/IntegerOrNot.cpp) |
| 8 | Switch statement | [`IthDayOfWeek.cpp`](./02-Conditionals/IthDayOfWeek.cpp) |
| 9 | Long long integer limits | [`LongLongDataType.cpp`](./02-Conditionals/LongLongDataType.cpp) |
| 10 | Else-if ladder | [`NamesElseIf.cpp`](./02-Conditionals/NamesElseIf.cpp) |
| 11 | Nested ternary expressions | [`NestedTernary.cpp`](./02-Conditionals/NestedTernary.cpp) |
| 12 | Odd and even number checking | [`OddEven.cpp`](./02-Conditionals/OddEven.cpp) |
| 13 | Profit and loss calculation | [`ProfitLoss.cpp`](./02-Conditionals/ProfitLoss.cpp) |
| 14 | Integer data type limits | [`RangeOfInt.cpp`](./02-Conditionals/RangeOfInt.cpp) |
| 15 | Relational operators | [`RelationalOperators.cpp`](./02-Conditionals/RelationalOperators.cpp) |
| 16 | Short integer limits | [`ShortDataType.cpp`](./02-Conditionals/ShortDataType.cpp) |
| 17 | Conditional ternary operator | [`Ternary.cpp`](./02-Conditionals/Ternary.cpp) |
| 18 | Storing a ternary result in a variable | [`TernaryVariable.cpp`](./02-Conditionals/TernaryVariable.cpp) |
| 19 | Checking a three-digit number | [`ThreeDigitNumber.cpp`](./02-Conditionals/ThreeDigitNumber.cpp) |
| 20 | Validating triangle sides | [`TriangleOrNot.cpp`](./02-Conditionals/TriangleOrNot.cpp) |
| 21 | Unsigned integer data type | [`Unsigned.cpp`](./02-Conditionals/Unsigned.cpp) |
| 22 | Driving-age eligibility | [`ValidAgeForDriving.cpp`](./02-Conditionals/ValidAgeForDriving.cpp) |
| 23 | Conditions, assignment, and post-increment behavior | [`VariableInsideIf.cpp`](./02-Conditionals/VariableInsideIf.cpp) |

### Day 4 — September 4, 2026

**Topic: Loops and Iteration**

#### Theory

- Loops repeat a block of code while a condition or iteration rule allows it.
- A `for` loop is useful when the initialization, condition, and update of an iteration are known in one place.
- A `while` loop repeats while its condition remains true.
- A `do-while` loop executes its body at least once because the condition is checked after the body.
- `break` immediately exits the loop.
- A loop can become infinite when its condition never becomes false.
- Loop variables can be incremented or decremented to control the number of iterations.
- Repeated calculations can solve problems such as factorial, powers, multiplication tables, arithmetic/geometric progressions, and printing ranges of numbers.
- Digit-based problems can be solved using `% 10` to obtain the last digit and `/ 10` to remove the last digit.
- Factors can be found by checking divisibility. The practice also explores checking factors up to the square root of a number.
- Prime-number checking uses the idea that a number greater than one with no divisor other than one and itself is prime.

#### Practice

| Order | Concept | Practice file |
| --- | --- | --- |
| 1 | Arithmetic progression | [`AP.cpp`](./03-Loops/AP.cpp) |
| 2 | ASCII characters and values | [`ASCII.cpp`](./03-Loops/ASCII.cpp) |
| 3 | `break` statement | [`Break.cpp`](./03-Loops/Break.cpp) |
| 4 | Counting digits | [`CountDigits.cpp`](./03-Loops/CountDigits.cpp) |
| 5 | `do-while` loop | [`DoWhileLoop.cpp`](./03-Loops/DoWhileLoop.cpp) |
| 6 | Factorial | [`Factorial.cpp`](./03-Loops/Factorial.cpp) |
| 7 | Finding factors | [`Factors.cpp`](./03-Loops/Factors.cpp) |
| 8 | `for` loop | [`ForLoop.cpp`](./03-Loops/ForLoop.cpp) |
| 9 | Geometric progression | [`GP.cpp`](./03-Loops/GP.cpp) |
| 10 | Repeating output with a loop | [`GoodMorning.cpp`](./03-Loops/GoodMorning.cpp) |
| 11 | Infinite-loop behavior | [`InfiniteLoop.cpp`](./03-Loops/InfiniteLoop.cpp) |
| 12 | Printing numbers from N to 1 | [`Nto1.cpp`](./03-Loops/Nto1.cpp) |
| 13 | Skipping multiples of four | [`OneTo100Except4Multiples.cpp`](./03-Loops/OneTo100Except4Multiples.cpp) |
| 14 | Calculating powers iteratively | [`Power.cpp`](./03-Loops/Power.cpp) |
| 15 | Prime or composite numbers | [`PrimeOrComposite.cpp`](./03-Loops/PrimeOrComposite.cpp) |
| 16 | Printing numbers from 1 to 100 | [`Print1To100.cpp`](./03-Loops/Print1To100.cpp) |
| 17 | Printing even numbers | [`PrintEven.cpp`](./03-Loops/PrintEven.cpp) |
| 18 | Reversing a number | [`ReverseNumber.cpp`](./03-Loops/ReverseNumber.cpp) |
| 19 | Sum of digits | [`SumOfDigits.cpp`](./03-Loops/SumOfDigits.cpp) |
| 20 | Multiplication table | [`TableOf19.cpp`](./03-Loops/TableOf19.cpp) |
| 21 | `while` loop | [`While.cpp`](./03-Loops/While.cpp) |
| 22 | Decrementing inside a while condition | [`WhileTMinusMinus.cpp`](./03-Loops/WhileTMinusMinus.cpp) |

### Day 5 — September 5, 2026

**Topic: Pattern Printing and Nested Loops**

#### Theory

- Pattern printing uses loops to control rows, columns, spaces, numbers, characters, and symbols.
- Nested loops place one loop inside another. The outer loop commonly controls rows, while the inner loop controls the contents of each row.
- The number of inner-loop iterations can change for each row to create triangles, pyramids, diamonds, and other shapes.
- Spaces are used to control alignment and create centered or shifted patterns.
- Pattern logic can be expressed using row and column relationships instead of writing each output manually.
- Different values can be printed based on conditions, allowing patterns using stars, numbers, alphabets, binary values, and odd numbers.
- Variable scope determines where a variable can be accessed. A variable declared inside a loop or block is not accessible outside that scope.
- More complex patterns can be built by combining multiple nested loops and changing the number of spaces or printed elements as the row changes.

#### Practice

| Order | Concept | Practice file |
| --- | --- | --- |
| 1 | Alphabet square pattern | [`AlphabetSquare.cpp`](./04-PatternPrinting/AlphabetSquare.cpp) |
| 2 | Binary triangle pattern | [`BinaryTriangle.cpp`](./04-PatternPrinting/BinaryTriangle.cpp) |
| 3 | Bridge pattern | [`Bridge.cpp`](./04-PatternPrinting/Bridge.cpp) |
| 4 | Diamond pattern | [`Diamond.cpp`](./04-PatternPrinting/Diamond.cpp) |
| 5 | Floyd's triangle | [`FloydTriangle.cpp`](./04-PatternPrinting/FloydTriangle.cpp) |
| 6 | Hollow rectangle pattern | [`HollowRectangle.cpp`](./04-PatternPrinting/HollowRectangle.cpp) |
| 7 | Nested-loop structure | [`LoopKeAndarLoop.cpp`](./04-PatternPrinting/LoopKeAndarLoop.cpp) |
| 8 | Number spiral pattern | [`NumberSpiral.cpp`](./04-PatternPrinting/NumberSpiral.cpp) |
| 9 | Number square pattern | [`NumberSquare.cpp`](./04-PatternPrinting/NumberSquare.cpp) |
| 10 | Number triangle pattern | [`NumberTriangle.cpp`](./04-PatternPrinting/NumberTriangle.cpp) |
| 11 | Odd-number triangle pattern | [`OddNumberTriangle.cpp`](./04-PatternPrinting/OddNumberTriangle.cpp) |
| 12 | Odd triangle pattern | [`OddTriangle.cpp`](./04-PatternPrinting/OddTriangle.cpp) |
| 13 | Pyramid pattern | [`Pyramid.cpp`](./04-PatternPrinting/Pyramid.cpp) |
| 14 | Rhombus pattern | [`Rhombus.cpp`](./04-PatternPrinting/Rhombus.cpp) |
| 15 | Variable scope | [`ScopeOfVariable.cpp`](./04-PatternPrinting/ScopeOfVariable.cpp) |
| 16 | Star plus pattern | [`StarPlus.cpp`](./04-PatternPrinting/StarPlus.cpp) |
| 17 | Star rectangle pattern | [`StarRectangle.cpp`](./04-PatternPrinting/StarRectangle.cpp) |
| 18 | Star triangle pattern | [`StarTriangle.cpp`](./04-PatternPrinting/StarTriangle.cpp) |
| 19 | Horizontally flipped star triangle | [`StarTriangleHorizontallyFlipped.cpp`](./04-PatternPrinting/StarTriangleHorizontallyFlipped.cpp) |
| 20 | Vertically flipped star triangle | [`StarTriangleVerticallyFlipped.cpp`](./04-PatternPrinting/StarTriangleVerticallyFlipped.cpp) |

### Day 6 — September 6, 2026

**Topic: Functions and Scope**

#### Theory

- A function is a reusable block of code that performs a specific task.
- Functions can receive data through parameters and arguments.
- A function can have a return type such as `int` or `void`. A non-`void` function can return a value using `return`.
- `return` also exits a function immediately.
- Pass by value gives a function a copy of an argument, so changing the parameter does not change the original variable.
- References can allow a function to work with the original variable. This can be used to modify values such as when swapping two numbers.
- Default parameters provide a value that is used when an argument is not supplied.
- Function overloading allows multiple functions to have the same name when their parameter lists are different.
- Overloaded functions can differ by the number, types, or order of their parameters.
- Local variables belong to their scope, while global variables can be accessed from wider scopes where they are visible.
- Shadowing occurs when a variable declared in an inner scope uses the same name as a variable from an outer scope.
- Functions can call other functions, allowing larger problems to be broken into smaller reusable parts.
- Mathematical problems such as combinations and Pascal's triangle can be organized using helper functions such as factorial and `nCr`.
- Inbuilt functions from standard libraries can provide common operations such as mathematical calculations.

#### Practice

| Order | Concept | Practice file |
| --- | --- | --- |
| 1 | Accessing a shadowed global variable | [`AccessingAShadowedGlobalVariable.cpp`](./05-Functions/AccessingAShadowedGlobalVariable.cpp) |
| 2 | Function arguments | [`Arguments.cpp`](./05-Functions/Arguments.cpp) |
| 3 | Basic functions | [`BasicFunction.cpp`](./05-Functions/BasicFunction.cpp) |
| 4 | Block scope | [`BlockScope.cpp`](./05-Functions/BlockScope.cpp) |
| 5 | Combinations using functions | [`Combinations.cpp`](./05-Functions/Combinations.cpp) |
| 6 | Default parameters | [`Default_Parameters.cpp`](./05-Functions/Default_Parameters.cpp) |
| 7 | Function overloading | [`FunctionOverloading.cpp`](./05-Functions/FunctionOverloading.cpp) |
| 8 | Function overloading with parameter order | [`FunctionOverloadingCase3.cpp`](./05-Functions/FunctionOverloadingCase3.cpp) |
| 9 | Function overloading with different parameter types | [`FunctionOverloadingPart2.cpp`](./05-Functions/FunctionOverloadingPart2.cpp) |
| 10 | Global variables | [`GlobalVariables.cpp`](./05-Functions/GlobalVariables.cpp) |
| 11 | Implicit typecasting from int to char | [`ImplicitTypecastingIntChar.cpp`](./05-Functions/ImplicitTypecastingIntChar.cpp) |
| 12 | Inbuilt functions | [`InbuiltFunctions.cpp`](./05-Functions/InbuiltFunctions.cpp) |
| 13 | Local variables | [`LocalVariables.cpp`](./05-Functions/LocalVariables.cpp) |
| 14 | Local vs global variables | [`Local_VS_Global.cpp`](./05-Functions/Local_VS_Global.cpp) |
| 15 | Nested scope and shadowing | [`NestedScopeShadowing.cpp`](./05-Functions/NestedScopeShadowing.cpp) |
| 16 | Pascal triangle using functions | [`PascalTriangle.cpp`](./05-Functions/PascalTriangle.cpp) |
| 17 | Pass by value | [`PassByValue.cpp`](./05-Functions/PassByValue.cpp) |
| 18 | Return keyword | [`ReturnKeyword.cpp`](./05-Functions/ReturnKeyword.cpp) |
| 19 | Return type | [`ReturnType.cpp`](./05-Functions/ReturnType.cpp) |
| 20 | Star triangle using a function | [`StarTriangle.cpp`](./05-Functions/StarTriangle.cpp) |
| 21 | Sum of three numbers using a function | [`SumOfThree.cpp`](./05-Functions/SumOfThree.cpp) |
| 22 | Swapping two numbers | [`Swap.cpp`](./05-Functions/Swap.cpp) |
| 23 | Swapping two numbers using references | [`Swap2NumbersFunction.cpp`](./05-Functions/Swap2NumbersFunction.cpp) |

### Day 7 — September 7, 2026

**Topic: Pointers**

#### Theory

- A pointer is a variable that stores the memory address of another variable.
- The address-of operator `&` is used to obtain the address of a variable.
- A pointer is declared using `*`, such as `int* ptr`.
- A pointer can be initialized with the address of a variable, for example `int* ptr = &x`.
- The dereference operator `*` accesses the value stored at the address held by a pointer.
- Changing a value through a dereferenced pointer changes the original variable because the pointer refers to its memory location.
- A pointer can be passed to a function so that the function can modify the original variable.
- Pointer-based parameter passing is demonstrated through digit counting, changing a value, and swapping two numbers.
- A null pointer does not point to a valid object. The practice uses `NULL` to represent a null pointer.
- A pointer itself also has an address, so the address of a pointer is different from the address stored inside that pointer.
- A pointer to a pointer, such as `int**`, stores the address of another pointer. Dereferencing it twice can reach the original value.
- Pointer concepts connect memory addresses, indirection, function parameter passing, and low-level memory understanding.

#### Practice

| Order | Concept | Practice file |
| --- | --- | --- |
| 1 | Address of a variable | [`AddressOfVariable.cpp`](./06-Pointers/AddressOfVariable.cpp) |
| 2 | Storing digit count through a pointer | [`CountDigitStore.cpp`](./06-Pointers/CountDigitStore.cpp) |
| 3 | Dereference operator | [`DereferenceOperator.cpp`](./06-Pointers/DereferenceOperator.cpp) |
| 4 | Pointer to a pointer | [`DoublePointer.cpp`](./06-Pointers/DoublePointer.cpp) |
| 5 | Dereferencing a double pointer | [`DoublePointerDereference.cpp`](./06-Pointers/DoublePointerDereference.cpp) |
| 6 | Null pointer | [`NullPointer.cpp`](./06-Pointers/NullPointer.cpp) |
| 7 | Passing a pointer to a function | [`PassByReference.cpp`](./06-Pointers/PassByReference.cpp) |
| 8 | Pointer basics and addresses | [`Pointer.cpp`](./06-Pointers/Pointer.cpp) |
| 9 | Swapping values using pointers | [`SwapUsingPointers.cpp`](./06-Pointers/SwapUsingPointers.cpp) |
| 10 | Pointer declaration practice | [`SyntaxIssue.cpp`](./06-Pointers/SyntaxIssue.cpp) |

## Folder Structure

```text
cpp-learning-log/
├── 01-Basics/
├── 02-Conditionals/
├── 03-Loops/
├── 04-PatternPrinting/
├── 05-Functions/
├── 06-Pointers/
├── .gitignore
└── README.md
```

## Goals

- Build a strong foundation in C++.
- Understand programming concepts through theory and practice.
- Improve problem-solving skills through regular practice.
- Progress toward DSA and interview preparation.
- Maintain a clean and consistent GitHub learning portfolio.
