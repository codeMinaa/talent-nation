# PY-SECTION 1 — TIER 3
## PRACTICAL EXERCISE: INPUT → PROCESSING → OUTPUT
### Mission: The Simple Calculator

## 1. Introduction

The purpose of this exercise is to understand how a computer receives information, processes it and produces a result.

A simple calculator receives two numbers, performs a mathematical operation on them and displays the answer.

For this exercise, we will use:

- First number: 20
- Second number: 5

The three major stages are:

1. Input
2. Processing
3. Output

## 2. Addition

**Input:** 20 and 5

**Processing:** Addition (20 + 5)

**Output:** 25

Explanation:

The calculator receives two numbers, adds them together and produces 25 as the result.

## 3. Subtraction

**Input:** 20 and 5

**Processing:** Subtraction (20 - 5)

**Output:** 15

Explanation:

The calculator subtracts the second number from the first number and produces 15.

## 4. Multiplication

**Input:** 20 and 5

**Processing:** Multiplication (20 × 5)

**Output:** 100

Explanation:

The calculator multiplies the two numbers together and produces 100.

## 5. Division

**Input:** 20 and 5

**Processing:** Division (20 ÷ 5)

**Output:** 4 or 4.0

Explanation:

The calculator divides the first number by the second number and produces 4.

The result can also be represented as 4.0 when using a floating-point number (float).

## 6. Reasoning Challenge: Division by Zero

Consider the following values:

- number_1 = 20
- number_2 = 0

The requested operation is:

20 ÷ 0

**What happens?**

Division by zero is mathematically undefined. It does not produce zero because a number cannot be divided into zero groups in a meaningful mathematical way.

**What should a well-designed calculator do?**

It should display an error message instead of producing an incorrect result.

Example:

`Error: Cannot divide by zero.`

This is an example of error handling in programming.

## 7. Understanding Input, Processing and Output

**Input:** The information a program receives from a user or another source.

**Processing:** The operations or instructions the program performs on the received information.

**Output:** The result or information produced after processing.

The relationship can be represented as:

INPUT
↓
PROCESSING
↓
OUTPUT

## 8. Final Reflection

This exercise has taught me that a computer program receives information, performs specific operations on that information and produces a result.

I also learned that different mathematical operations produce different outputs even when they use the same input values.

Another important lesson is that a well-designed program must consider errors and unexpected situations. For example, when dividing by zero, the calculator should display an error message instead of producing a false answer.

**My conclusion:**

A program follows the Input → Processing → Output model. It receives data, processes it according to instructions and produces a useful result.