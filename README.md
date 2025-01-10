# Elixir Enum.reduce Accumulator Handling

This repository showcases a common error in Elixir when using `Enum.reduce` and provides a solution to fix the issue.  The problem arises when the function within `Enum.reduce` doesn't always update the accumulator, causing incorrect results.

The `bug.ex` file demonstrates the flawed code and its unexpected output. `bugSolution.ex` presents the corrected version, ensuring accurate accumulator management.

This example highlights the importance of handling all cases within the function passed to `Enum.reduce` to guarantee correct results in the final accumulator value.  Understanding the nuances of accumulator behavior in functional programming is crucial for writing robust and predictable Elixir code.