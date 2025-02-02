# Uncommon Scala Error: Exception Handling in Custom Setter

This repository demonstrates a subtle error related to exception handling in Scala within a custom setter method.  The `MyClass` class includes a setter that throws an `IllegalArgumentException` if a negative value is attempted to be assigned.  The `Main` object showcases how this exception should be handled, but failure to properly catch and handle this exception could lead to silent failures or unexpected application crashes in real-world scenarios. 

**Key Points:**

* **Custom Setters:** Illustrates best practices for creating robust setters that validate input.
* **Exception Handling:** Emphasizes the importance of proper exception handling to maintain application stability and reliability.
* **Silent Failures:** Highlights potential problems where unchecked exceptions might cause unexpected behavior.

This example can serve as a learning resource for understanding potential pitfalls in Scala code related to exception handling, particularly within custom classes and setter methods.