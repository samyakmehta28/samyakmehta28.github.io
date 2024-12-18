---
layout: page
title: Low-Level Design Patterns
description: A comprehensive collection of low-level design patterns implemented in C++, showcasing various solutions to common software design problems, such as object creation, object structure, and behavior management.
img: assets/img/project_13.png
importance: 13
category: Software Engineering
---

I created this project to explore and apply various low-level design patterns to solve common software engineering challenges. By leveraging principles like abstraction, encapsulation, and modularity, this project demonstrates how to build flexible and maintainable software systems. The code for these patterns can be found in the GitHub repository [here](https://github.com/samyakmehta28/Low-Level-Design-Patterns).

# [Low-Level Design Patterns](https://github.com/samyakmehta28/Low-Level-Design-Patterns)

### Overview:

This project is a collection of code examples that demonstrate various low-level design patterns in software development. These patterns provide solutions for building efficient and scalable systems by handling object creation, object structure, and interactions between different components. The patterns are implemented in C++ and cover a range of scenarios such as building complex objects, managing system states, and structuring code to improve maintainability and scalability.

### Design Patterns Implemented:

- **Creational Patterns**

  - **Builder**: Separates object construction from its representation, allowing for the creation of complex objects step by step.
  - **Singleton**: Ensures that a class has only one instance and provides a global access point to that instance.
  - **Factory**: Creates objects without specifying the exact class of object that will be created.

- **Structural Patterns**

  - **Adapter**: Allows incompatible interfaces to work together.
  - **Bridge**: Decouples an abstraction from its implementation, allowing the two to vary independently.
  - **Composite**: Allows you to compose objects into tree structures to represent part-whole hierarchies.
  - **Decorator**: Adds responsibilities to an object dynamically.
  - **Facade**: Provides a simplified interface to a complex subsystem.
  - **Flyweight**: Reduces the memory usage by sharing common parts of objects.
  - **Proxy**: Controls access to another object, allowing for additional functionality such as lazy loading or access control.

- **Behavioral Patterns**
  - **Chain of Responsibility**: Passes a request along a chain of handlers.
  - **Command**: Encapsulates a request as an object, allowing for parameterization and queuing of requests.
  - **Interpreter**: Defines a grammar and uses that grammar to interpret text.
  - **Iterator**: Provides sequential access to elements in an aggregate object without exposing its internal structure.
  - **Mediator**: Defines an object that encapsulates how a set of objects interact.
  - **Memento**: Captures and externalizes an object’s internal state without violating its encapsulation.
  - **Observer**: Allows one object to notify multiple other objects about changes in its state.
  - **State**: Alters the behavior of an object when its internal state changes.
  - **Strategy**: Defines a family of algorithms, encapsulates each one, and makes them interchangeable.
  - **Template Method**: Defines the structure of an algorithm but allows subclasses to modify specific steps.
  - **Visitor**: Allows new operations to be added to an object structure without modifying the objects themselves.

### Technical Details:

- Language: C++ for implementation of the design patterns
- Object-Oriented Design: Emphasis on modularity, extensibility, and reusability of components
- Patterns Covered: 23 distinct patterns, organized into Creational, Structural, and Behavioral categories

### Conclusion:

This project serves as a practical guide to understanding and implementing low-level design patterns in C++. It covers a wide range of common software engineering problems and provides solutions that are flexible, maintainable, and scalable. The patterns demonstrated in this project are fundamental tools in building efficient and robust software systems.
