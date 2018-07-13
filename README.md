# scalaz-snippets

A range of code snippets designed to demonstrate how to use various features of Scalaz libraries, including Scalaz 8 core.

# Intro

The `scalaz-snippets` is a collection of self contained examples. Each example focuses on
demonstrating a concept in a scalaz library. They should serve to develop an understanding of
functional programming design using scalaz. The accompanied web page (insert link here) discusses
each example in detail.

## Examples

The (webpage link) describes the complete set. For starters try:

~~~
sbt compile
~~~

to build all examples. And

~~~
sbt run
~~~

to run the classic "Hello World!" using scalaz's IO monad.

## Requirements

1. `scalaz-snippets` is a project that can be checked out and compiled.
2. Each example is an executable that can be run with no required arguments.
2. Examples are self contained. Each only requires the stated scalaz libraries available. Each can be
   compiled separate from other examples.
3. The scalaz-snippets are available to view via a website describing the examples with the
   corresponding code inline.
4. Examples should strive to clearly communicate how the design is implemented using the scalaz
   feature. Include further documentation where necessary but prefer improving the scalaz
   documentation over explaining core concepts in the example.

## Code Organization

Each scalaz library has a corresponding subproject. For example, the project "scalaz-core" will
contain snippets demonstrating "scalaz-core" features.

## Resources

[![Gitter](https://badges.gitter.im/scalaz/scalaz-snippets.svg)](https://gitter.im/scalaz/scalaz-snippets?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
