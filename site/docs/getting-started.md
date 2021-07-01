---
title: Getting started
---

# Getting Started

## Setup

Add the following dependency to your `build.sbt` file:

``` scala
libraryDependencies += "ch.epfl.scala" %% "library-example" % "@VERSION@"
```

Further reading:

 - [Getting Started](getting-started.md)
 - [Reference](reference.md)


## Usage

First, start with the following import:

```scala mdoc
import ch.epfl.scala.Example
```

Then, do nothing with something:

```scala mdoc
Example.doNothing(42)
```