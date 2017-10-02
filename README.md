Awesome Scala GameDev [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
=============

A community driven list of libraries, software, and resources useful for Scala game development. Also lists of games being written in or already completed in Scala. This is not a catalog of all the libraries, just a starting point for your explorations. That said, due to the incubating environment here at ScalaGameDev, we welcome projects at any stage of development, so please submit a PR if you have or know about a project to get it added to the list. The list is inspired by [awesome-scala](https://github.com/lauris/awesome-scala). Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

Also awesome is [Scaladex](https://index.scala-lang.org/), the searchable, tagged, and centralized index of Scala libraries.

Projects with over 500 stargazers are in bold.

- [Awesome Scala GameDev](#awesome-scala-gamedev)
    - [Concurrency](#concurrency)
    - [Games](#games)
    - [Game Engines and Libraries](#game-engines-and-libraries)
    - [Game Tools](#game-tools)
    - [Graphical User Interfaces](#graphical-user-interfaces)
    - [Wrappers for Engines and Libraries](#wrappers-for-engines-and-libraries)
- [Contributing](#contributing)

## Concurrency

* [Reactors](http://reactors.io) - a concurrent, distributed programming framework based on asynchronous event streams; currently targets Scala.js and the JVM.

## Games

### Open-Source

### Closed-Source

## Game Engines and Libraries

* [RPG Boss](https://github.com/rpgboss/rpgboss) - Multiplatform, point and click rpg game editor and engine, based on [libgdx](https://github.com/libgdx/libgdx).
* [SGL](https://github.com/regb/scala-game-library) `pre-release` - Scala Game Library is a library for developing cross-platform 2D video games in Scala. It provides a high-level API for building 2D games, and can deploy for Desktop, Android, and HTML5, while iOS and console platforms are on the roadmap. Makes use of [Graphics Bindings for Scala Native](#wrappers-for-engines-and-libraries) for some platforms.

## Game Tools

## Graphical User Interfaces

## Libraries for creation of graphical user interfaces*

* [ScalaFX](http://www.scalafx.org/) - Scala DSL for creating Graphical User Interfaces that sits on top of JavaFX.

## Wrappers for Engines and Libraries

* [Graphics Bindings for Scala Native](https://github.com/regb/scalanative-graphics-bindings) `pre-release` - Scala Native bindings for the popular graphics programming libraries SDL2 and OpenGL. The bindings try as much as possible to reproduce the original programming interface in C. In particular, they won't hide scalanative interoperability types behind regular Scala types.
* [MacroGL](https://github.com/storm-enroute/macrogl) `inactive` - Scala macro-based frontend for OpenGL for structured and efficient graphics code. Currently targets Scala.js and the JVM.
* [SME](https://github.com/bbarker/SME) `pre-release`  - Scala Monkey Engine is a thin wrapper around [JMonkeyEngine 3](http://jmonkeyengine.org), helping to provide a more idiomatic feel to JME3 where possible. Currently requires and targets [Dotty](http://dotty.epfl.ch/).


# Contributing

Your contributions are always welcome! Please submit a pull request or create an issue to add a new Scala game, game library (in Scala or a Scala wrapper library), article on game development related to Scala. If the project is inactive, deprecated, or pre-release a tag should be added to indicate this.
