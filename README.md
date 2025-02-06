# Haskell Undefined Value Bug

This repository demonstrates a common error in Haskell: attempting to use an undefined value. The `undefined` value represents a computation that hasn't been defined, leading to a runtime exception.

## Bug

The `bug.hs` file contains the erroneous code. It attempts to add 1 to the `undefined` value, which results in a runtime error.

## Solution

The `bugSolution.hs` file shows how to correct this by providing a proper definition for the variable `x`.