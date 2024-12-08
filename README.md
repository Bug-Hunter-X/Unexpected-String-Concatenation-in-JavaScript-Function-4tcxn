# Unexpected String Concatenation in JavaScript Function

This example demonstrates a common but subtle error in JavaScript where implicit type coercion leads to unexpected string concatenation instead of numerical addition.

## Bug Description

The `foo` function is intended to add two numbers. However, when a string is passed as an argument, JavaScript performs string concatenation instead of numerical addition.  This results in an incorrect output.

## Bug Solution

To fix this, you should explicitly convert the input arguments to numbers before performing the addition.  This ensures that the `+` operator performs numerical addition as intended.  The solution provides a revised function with type checking and conversion.
