# Uncommon Java Bug: Silent ArithmeticException

This repository demonstrates a subtle and easily overlooked bug in Java: a silent `ArithmeticException`. The code appears simple, but hides a runtime error that can be difficult to debug without careful attention to detail.

## The Bug

The `Bug.java` file contains a program that attempts to divide an integer by zero. This action results in an `ArithmeticException`, which, while a common error, can easily go unnoticed if not properly handled.

## The Solution

The `BugSolution.java` file presents a corrected version. It includes a check to prevent division by zero, gracefully handling the potential error and preventing unexpected crashes.