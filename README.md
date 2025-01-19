# Tcl Factorial Stack Overflow Bug

This repository demonstrates a common error in Tcl: stack overflow due to excessive recursion. The `factorial.tcl` file contains a recursive implementation of the factorial function that fails for larger inputs.  The `factorialSolution.tcl` file provides a corrected, iterative version.

## Bug

The recursive implementation exceeds the maximum recursion depth for larger numbers, resulting in a stack overflow error.

## Solution

The solution uses an iterative approach, avoiding the recursion and resolving the stack overflow issue.  This provides a more robust and efficient way to calculate factorials in Tcl.