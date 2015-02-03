#Scala Job Interview Questions

This file contains a number of Scala interview questions that can be used when vetting potential candidates. It is by no means recommended to use every single question here on the same candidate (that would take hours). Choosing a few items from this list should help you vet the intended skills you require.

**Note:** Keep in mind that many of these questions are open-ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

## Table of Contents

  1. [General Questions](#general-questions)
  1. [Language Questions](#language-questions)
  1. [Functional Questions](#functional-questions)
  1. [Reactive Programming Questions](#reactive-programming-questions)
  1. [Coding Questions](#coding-questions)
  1. [Fun Questions](#fun-questions)

## Getting Involved

  1. [Contributors](#contributors)
  1. [How to Contribute](https://github.com/jarlakxen/Scala-Interview-Questions/blob/master/CONTRIBUTING.md)
  1. [License](https://github.com/jarlakxen/Scala-Interview-Questions/blob/master/LICENSE.md)

#### General Questions:

* What did you learn yesterday/this week?
* Why and How do you started learning Scala?
* What excites or interests you about coding in Scala?
* What is a recent technical challenge you experienced and how did you solve it?
* Talk about your preferred development environment. (OS, Editor or IDE, Tools, etc.)
* What are you thoughts about the other JVM languages in compared to Scala?
* Do you think that the Scala language and community it's mature enough?

#### Language Questions:

* What is the difference between a `var`, a `val` and `def`?
* What is the difference between a `trait` and an `abstract class`?
* What is the difference between an `object` and a `class`?
* What is `case class`?
* What is the difference between a Java future and a Scala future?
* What is the difference between `unapply` and `apply`, when would you use them?
* What is a companion object?
* What’s the difference between the following terms and types in Scala: `Nil`, `Null`, `None`, `Nothing`?
* What is `Unit`?

#### Functional Questions:

* What is Monad?
  * Which are the Monad laws?
  * Which Scala data types are or it behave like Monads?
  * Which are the basic requirement/s, and the optionals, to conform a Monad?
* Explain higher order functions.
* What is gained using immutable objects?
* What operations is a for comprehension syntactic sugar for?
* What is recursion tail?
  * What issue do you have with the tail recursive function in the JVM?
  * How the Scala compiler optimised a tail recursive function?
  * How do you ensure that compiler optimises the tail recursive function?
* What is function currying?
* What are implicit parameters?

#### Reactive Programming Questions:

* Explain the actor model.
* Explain the Reactive Manifesto.
* Which are benefits of non-blocking (asynchronous I/O) over blocking (synchronous I/O).
* Do you think that Scala have the same async spirit than NodeJS?
* Explain the difference between ‘concurrency’ and ‘parallelism,’ and name some constructs you can use in Scala to leverage both.
* What is the global ExecutionContext?
  * What does the global ExecutionContext underlies?

#### Coding Questions:

* How can you make a List[String] from a List[List[String]]?
* What is the difference (if any) between these 2 statements: var x = immutable.set[Int] and val y = mutable.set[Int]?

#### Fun Questions:

* What's a cool project that you've recently worked on?