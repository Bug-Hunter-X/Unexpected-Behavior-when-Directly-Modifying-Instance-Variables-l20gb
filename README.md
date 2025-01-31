# Unexpected Behavior when Directly Modifying Instance Variables in Ruby

This example demonstrates a potential issue in Ruby when instance variables are modified directly using `instance_variable_set` instead of through accessor methods.  This practice can violate encapsulation and lead to unpredictable results.

The `bug.rb` file shows the problem: modifying the instance variable `@value` directly without using a setter method. The `bugSolution.rb` provides a better approach using accessor methods.  This enhances code maintainability and readability.

**Key takeaway:** Favor using accessor methods (getters and setters) to interact with instance variables for better code organization, maintainability, and preventing unexpected side effects.