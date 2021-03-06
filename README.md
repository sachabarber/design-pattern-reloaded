# Implementation of GoF design patterns in Scala

The idea comes from a [talk by Remi Forax](https://github.com/forax/design-pattern-reloaded/), and I can't resist to implement this in Scala.

GoF patterns are still up to date with Scala, but may be coded in a more straightforward way. 
SOLID principles apply also.

The code is less verbose, because we benefit from language features such as **first-class functions**, **type alias**.

## Abstract Factory

Companion object

## Logger
For me, it's a kind of Decorator

## Adapter
curryfication

## Observer
lambda with mutable local var

Note : In this use case, reduce is a far better choice.

## Visitor
partial function

ADT

NB : if no ADT => typeclasses

# Additional thoughts

"Don't apply GoF pattern implementation in Scala." - Debasish Ghosh

Scalaz : collection of functinal design patterns : Monoid, Functor, Applicative.

https://www.quora.com/How-are-the-Gang-of-Four-Design-Patterns-applied-to-Scala-code

Note : excellent blog post on the same subject : https://pavelfatin.com/design-patterns-in-scala/