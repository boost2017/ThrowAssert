# ThrowAssert
C++ assertion macro which raises an exception (AssertionFailureException) rather than aborting when the assertion fails.

Example usage to assert a condition:
  `throw_assert(state == ExpectedState, "Not in expected state.");`

Example usage to assert unreachable code, with formatted error message:
  `throw_assert(false, "Encountered unexpected state " << state);`

See [Assertions in C++, and why not to use assert() (Softwariness.com)](https://www.softwariness.com/articles/assertions-in-cpp/) for more information.
