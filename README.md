# Awesome Scala Native [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a list of Scala Native resources and libraries.

## Table of Contents
* [Tutorials and Templates](#tutorials-and-templates)
* [Functional Programming](#functional-programming)
* [Unit Tests](#unit-tests)
* [Bindings](#bindings)
* [File Formats and Parsers](#file-formats-and-parsers)
* [Databases](#databases)
* [Logging](#logging)
* [Console](#console)
* [Programs](#programs)
* [Infrastructure](#infrastructure)

## Tutorials and Examples
* [Giter8 template for a minimal Scala Native project](https://github.com/scala-native/scala-native.g8): Official [Giter8](http://www.foundweekends.org/giter8/) template for a minimal Scala Native project.
* [Hands on Scala Native](https://github.com/MasseGuillaume/hands-on-scala-native): Tutorial for implementing a bandwidth monitor with Ncurses.
* [Starter for Scala Native](https://github.com/GnaneshKunal/scala-native-starter): Scala Native project that links to a custom C library.
* [Building C code using sbt-jni](https://github.com/nadavwr/scala-native-sbt-jni-example): Example for compiling C code in a Scala Native project using [sbt-jni](https://github.com/jodersky/sbt-jni).
* [Example project with external dependencies](https://github.com/lihaoyi/scala-native-example-app): Example project that uses external dependencies to generate HTML and run a test suite.

## Functional Programming
* [Shapeless](https://github.com/milessabin/shapeless): Library for generic programming.
* [Squants](https://github.com/typelevel/squants): DSL for quantities, units of measure and dimensional analysis.
* [scalaz](https://github.com/scalaz/scalaz): Type classes and instances for data structures.
* [nobox](https://github.com/xuwei-k/nobox): Immutable primitive array wrapper for Scala.
* [PPrint](https://github.com/lihaoyi/PPrint): Pretty-print values and types.
* [SourceCode](https://github.com/lihaoyi/sourcecode): Implicits providing meta data similar to `__LINE__` in C.
* [reactify](https://github.com/outr/reactify): Functional Reactive Programming framework for Scala.

## Unit Tests
* [utest](https://github.com/lihaoyi/utest): Library for unit tests.
* [scalaprops](https://github.com/scalaprops/scalaprops): Library for property-based testing.
    * [scalaprops-shapeless](https://github.com/scalaprops/scalaprops-shapeless): Generation of arbitrary ADT instances.
    * [scalaprops-cross-example](https://github.com/scalaprops/scalaprops-cross-example): Cross-platform example.
* [Makeshift](https://github.com/nadavwr/makeshift): Library for unit tests.

## Bindings
* [cmark](https://github.com/sparsetech/cmark-scala): Bindings for the [cmark](https://github.com/commonmark/cmark) CommonMark parser library.
* [libuv](https://github.com/TimothyKlim/scala-native-libuv): Bindings for [libuv](https://github.com/libuv/libuv), a library for asynchronous I/O.
* [SDL2 and OpenGL](https://github.com/regb/scalanative-graphics-bindings): Bindings for the graphical frameworks [SDL2](https://www.libsdl.org/) and [OpenGL](https://www.opengl.org/).
* [Cocoa](https://github.com/jokade/scalanative-cocoa): Bindings for the macOS graphical framework [Cocoa](https://en.wikipedia.org/wiki/Cocoa_(API)).
* [GNU Scientific Library](https://github.com/ruivieira/scala-gsl): Bindings for [GNU Scientific Library (GSL)](https://www.gnu.org/software/gsl/).
* [BLAS](https://github.com/ekrich/scala-native-ml): Bindings for [BLAS](http://www.netlib.org/blas/), a library for Linear Algebra.
* [Gtk+](https://github.com/jokade/scalanative-gtk): Bindings for the [GTK+](https://www.gtk.org/) graphical toolkit.

## File Formats and Parsers
* [msgpack4z](https://github.com/msgpack4z/msgpack4z-native): Implementation of [MessagePack](https://msgpack.org/), a binary serialisation format.
* [FastParse](https://github.com/lihaoyi/fastparse): Library for defining and running parsers.
* [scalatags](https://github.com/lihaoyi/scalatags): HTML and XML construction and rendering.
* [Pine](https://github.com/sparsetech/pine): HTML and XML parsing, manipulation and rendering.
* [scala-json](https://github.com/MediaMath/scala-json): JSON parser.
* [toml-scala](https://github.com/sparsetech/toml-scala): TOML parser with codec derivation.
* [argonaut](https://github.com/argonaut-io/argonaut): Purely functional JSON parser and library.
* [ScalaPB](https://github.com/scalapb/ScalaPB): [Protocol Buffer](https://developers.google.com/protocol-buffers/) compiler for Scala.
    * [scalapb-argonaut](https://github.com/scalapb-json/scalapb-argonaut): JSON and Protocol Buffer converters for ScalaPB based on [Argonaut](http://argonaut.io/).

## Databases
* [JDBC](https://github.com/jokade/scalanative-jdbc): Port of the database access layer [JDBC](https://en.wikipedia.org/wiki/Java_Database_Connectivity) to Scala Native.

## Logging
* [slogging](https://github.com/jokade/slogging): [Typesafe-logging](https://github.com/lightbend/scala-logging) and [SLF4J](https://www.slf4j.org/)-compatible logging library based on macros.

## Console
* [fansi](https://github.com/lihaoyi/fansi): Library for creating [ANSI-coloured strings](https://en.wikipedia.org/wiki/ANSI_escape_code).
* [scopt](https://github.com/scopt/scopt): Command-line argument parser.

## Robotics
* [Potassium](https://github.com/Team846/potassium): Framework for writing robot software.
* [WPILib](https://github.com/Team846/scala-native-wpilib): Reimplementation of the [FIRST Robotics WPILib libraries](http://first.wpi.edu/FRC/roborio/release/docs/java/).

## Programs
* [sglgears](https://github.com/Milyardo/sglgears): Port of GL [gears.c](https://github.com/JoakimSoderberg/mesademos/blob/master/src/xdemos/glxgears.c).
* [k8s-cli](https://github.com/fsat/k8s-cli): CLI tools to generate [Kubernetes](https://kubernetes.io/) resources for [Akka](https://akka.io/), [Play Framework](https://www.playframework.com/) and [Lagom](https://www.lagomframework.com/)-based applications.

## Infrastructure
* [scala-native-sbt-docker](https://github.com/ScalaWilliam/scala-native-sbt-docker): Docker image for Scala Native and sbt.

## Licence
<a rel="licence" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg" /></a><br />This work is licenced under a <a rel="licence" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International Licence</a>.
