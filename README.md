# Dart Reduce Method and Empty Lists
This example demonstrates a common error when using the `reduce` method in Dart with an empty list.  The `reduce` method requires at least one element in the list; otherwise, it throws an error.  The solution shows how to handle this gracefully using a check for an empty list.

## Bug
The `bug.dart` file shows the error scenario: attempting to use `reduce` on an empty list.