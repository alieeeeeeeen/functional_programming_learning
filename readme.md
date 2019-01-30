# Prerequisites

## Programming paradigm

Programming paradigms are a way to classify programming language based on their features. Languages can be classified into multiple paradigms.

- imperative
    - procedural - which merely includes instructions
    - object-oriented - which inculdes instructions and state

- declarative
    - functional - *the desired result* is declared as the value of a *series* of function applications
    - logic - *the desired result* is declared as the answer to a question about a system of facts or rules
    - mathematical - *the desired result* is declared as the solution of an optimization problem

- symbolic: To build intricate processes by combining smaller units of logic or functionality. Thus, such programs can effetively modify themselves and appear to "learn".

## Immutable object

An immutable object is an object whose state cannot be modified after it is created. Immutable objects are useful because they are inherently ***thread-safe***

# Functional Programming

Functional programming is designed to handle symbolic computation. Functional programming is based on mathematical functions.

- Pure functional programming
- Impure functional programming

## Functional Programming Advantages

- Bug-Free Code - Functional programming does not support state, so there are no side-effect

- Efficient Parallel Programming - Functional Programming has immutable state, so there are no state-change issues. One can programe "Functions" to work parallelly as "instructions". Such code supports reusability and testability.

## Functional Programming Characteristics

- Functional Programming supports **high-order functons** and **lazy evaluation** features
- States are Immutable
- Lazy evaluation - which delays the evaluation of the an expression until its value is needed

# Functional Programming vs Object-oriented Programming

Functional Programming | Object-oriented Programming
--- | ---
Uses Immutable data | Uses Mutable data
Follows Declarative Programming | Follows Imperative Programming Model
Focus is on "What you are doing" | Focus is on "How you are doing"
Supports parallel programming | Not suitable for parallel programming
Its function has no side-effects | It function can produce serious side-effects
Flow control is done using function calls & function calls with recursion | Flow controls is done using loops and conditional statements
It uses Recursion concept to iterate Collection Data | It uses Loop concept to iterate Collection Data. For example, `for-each` in Java
Execution order of statements is not so important | Execution order of statements is very important
Supports both "Abstraction over behavior" and "Abstraction over data" | Supports only "Abstraction over data"

# References

- [Wiki](https://en.wikipedia.org/wiki/Programming_paradigm)
- [Wiki](https://en.wikipedia.org/wiki/Immutable_object)
- [Tutorialpoints](https://www.tutorialspoint.com)