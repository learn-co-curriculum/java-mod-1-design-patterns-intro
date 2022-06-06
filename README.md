# Introduction to Design Patterns

## Learning Goals

- Understand design patterns overview

## What are Design Patterns?

As we gain more programming experience and the systems we build are increasingly
more complex, we can build on the experience of people who have come before us
by implementing patterns that have evolved over decades of experience.

Design patterns provide specific solutions for specific problems. They describe
ways in which features of Java can be leveraged to solve well known problems
with flexible and mature solutions.

There are many design patterns, and you will continue to learn them as you make
progress in your career. We will introduce you to several essential ones here
and go through examples to see how they might apply in actual systems.

The patterns we will cover fall in the following categories:

- Creational patterns - these patterns aim to abstract how objects are created
  to allow clients to use different implementations of interfaces without having
  to be aware of each specific implementation. As we strive to rely less on a
  strict class extension-based hierarchy for the components of our systems, and
  migrate more towards composition using smaller, more specific interfaces to
  isolate specific functions, creational patterns will help us achieve that
  flexibility:
  - Singleton
  - Factory
- Structural patterns - these patterns help deal with the complexity that comes
  with large systems by giving us different ways to combine multiple classes to
  implement functionality that takes advantage of each class without binding us
  to a tightly coupled relationship between those classes:
  - Facade
  - Adapter
  - Composite
- Behavioral patterns - these patterns aim to define how objects communicate
  with each other in addition to how classes relate to one another:
  - Observer
