# Dart reduce() method error with empty list

This repository demonstrates a common error encountered when using the `reduce()` method in Dart with an empty list. The `reduce()` method requires at least one element to perform the reduction operation, resulting in an `UnsupportedError` if applied to an empty list. The solution involves adding a check for an empty list before applying the `reduce()` method.  The code examples in `bug.dart` illustrate the problem and `bugSolution.dart` provides a fix.
