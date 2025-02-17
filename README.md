# Elixir Enum.each Modification Bug

This repository demonstrates a common mistake in Elixir when attempting to modify a list while iterating over it using `Enum.each`. The code attempts to remove the element '3' from the list, but due to the immutable nature of lists, the modification within the loop does not affect the original list.

The `bug.exs` file contains the buggy code. The `bugSolution.exs` file shows a corrected implementation using `Enum.filter` or `for` comprehension to achieve the intended result.
