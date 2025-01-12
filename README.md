# Unhandled Throw Exception in Elixir Enum.each

This example demonstrates an uncommon error in Elixir related to exception handling within `Enum.each`.  The `throw` macro is used to exit the loop prematurely, but the exception isn't properly caught, leading to an unexpected termination of the program.

The solution shows how to use a `try-catch` block to handle the thrown exception and continue the execution gracefully.

This is a subtle error because `Enum.each` doesn't explicitly indicate how exceptions should be handled.