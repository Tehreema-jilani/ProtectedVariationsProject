# Protected Variations Principle

## Overview
This project demonstrates the **Protected Variations** principle, which is a design pattern that protects a system from changes when new payment methods are introduced.

### Project Structure:
- **withprinciple**: Demonstrates how the **Protected Variations** principle is applied by using **dependency injection** and interfaces.
- **withoutprinciple**: Shows a tightly coupled approach where the `Order` class directly depends on the `CreditCardPayment` class.

### How to Use:
- **Run the `Main.java` file in the `withprinciple` package** to see how easy it is to add new payment methods by following the **Protected Variations** principle.
- **Run the `Main.java` file in the `withoutprinciple` package** to see the limitations of the tightly coupled approach.

### Conclusion:
- The **withprinciple** approach allows for easier modification and extension of the system.
- The **withoutprinciple** approach is rigid and makes adding new features harder.

## Key Concepts:
- **Abstraction**: Using interfaces or abstract classes to hide implementation details.
- **Dependency Injection**: Injecting dependencies to avoid tight coupling between classes.
- **Flexibility**: Making systems open for extension but closed for modification.
