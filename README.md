# JavaScript Type Coercion Bug

This repository demonstrates a common type coercion issue in JavaScript that leads to unexpected results when performing arithmetic operations with mixed data types (numbers and strings).

## The Bug

The `foo` function is intended to add two numbers. However, due to JavaScript's implicit type coercion, when one of the arguments is a string, the number is coerced into a string, resulting in string concatenation rather than numerical addition.

## Solution

The solution involves explicit type checking and conversion to ensure both operands are numbers before performing the addition.