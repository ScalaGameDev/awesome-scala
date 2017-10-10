# Awesome Scala GameDev [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Join the chat at https://gitter.im/ScalaGameDev/incubator](https://badges.gitter.im/ScalaGameDev/incubator.svg)](https://gitter.im/ScalaGameDev/incubator?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


A community driven list of libraries, software, and resources useful for Scala game development. Also lists of games being written in or already completed in Scala. This is not a catalog of all the libraries, just a starting point for your explorations. That said, due to the incubating environment here at ScalaGameDev, we welcome projects at any stage of development, so please submit a PR if you have or know about a project to get it added to the list. The list is inspired by [awesome-scala](https://github.com/lauris/awesome-scala). Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

Also awesome is [Scaladex](https://index.scala-lang.org/), the searchable, tagged, and centralized index of Scala libraries.

Projects with over 500 stargazers are in bold.

- [Awesome Scala GameDev](#awesome-scala-gamedev)
    - [Concurrency](#concurrency)
    - [Emulators](#emulators)
    - [Games](#games)
    - [Game Engines and Libraries](#game-engines-and-libraries)
    - [Game Tools](#game-tools)
    - [Graphical User Interfaces](#graphical-user-interfaces)
    - [Resources](#resources)
    - [Ray tracing](#ray-tracing)
    - [Wrappers for Engines and Libraries](#wrappers-for-engines-and-libraries)
- [Contributing](#contributing)

## Concurrency

* [Reactors ★ 224 ⧗ 0](https://github.com/reactors-io/reactors) - [a concurrent, distributed programming framework](http://reactors.io) based on asynchronous event streams; currently targets Scala.js and the JVM.

## Build Tools

* [CBT ★ 375 ⧗ 1](https://github.com/cvogt/cbt) - `pre-release` An upcoming, flexible build tool. Game development in Scala is one area where flexibility is often needed.
* [sbt-lwjgl-plugin ★ 42 ⧗ 194](https://github.com/philcali/sbt-lwjgl-plugin) - `inactive` For use with SBT, pulls in various LWJGL dependencies, including the appropriate native dependencies. Currently doesn't work with [coursier](https://github.com/coursier/coursier). Suggest using the following patched version: `addSbtPlugin("com.storm-enroute" % "sbt-lwjgl-plugin" % "3.1.6")`.
* [ScalaMeter ★ 358 ⧗ 25](https://github.com/scalameter/scalameter) - Microbenchmarking and performance regression testing framework for the JVM platform: http://scalameter.github.io.

## Emulators

* [scalagb ★ 13 ⧗ 125](https://github.com/dbousamra/scalagb) - `untested` A Z80 Gameboy emulator written in Scala.

## Games


### Open-Source

* [BlockSmith ★ 0 ⧗ 342](https://github.com/bbarker/BlockSmith/) - `pre-release` BlockSmith is currently an experiment in the ways of MineCraft-like voxel games. 
* [Checkers ★ 9 ⧗ 43](https://github.com/kschuetz/checkers) - [live demo](http://kschuetz.github.io/checkers/) Checkers game rendered in web browser using SVG (about 10000 lines of Scala.js using React). Supports AI opponents.
* [CodeCraft ★ 12 ⧗ 128](https://github.com/cswinter/CodeCraftGame) - [live demo](http://www.codecraftgame.org/demo) A real-time strategy game in which you write a program to command an army of virtual drones, written in Scala.js.
* [doubletetris ★ 1 ⧗ 233](https://github.com/Jasper-M/doubletetris) - [live demo](http://jasper-m.github.io/doubletetris/) An interesting take on tetris.
* [hexiles-web ★ 1 ⧗ 239](https://github.com/phillipjohnson/hexiles-web) - [live demo](http://phillipjohnson.github.io/hexiles-web/game.html) An HTML5 single-player puzzle game in Scala.js.
* [scalajs-react-2048 ★ 25 ⧗ 113](https://github.com/fijolekProjects/scalajs-react-2048) - [live demo](https://fijolekprojects.github.io/scalajs-react-2048/) This is [2048](http://gabrielecirulli.github.io/2048/) game clone made using [scalajs-react](https://github.com/japgolly/scalajs-react) in just 350 lines of Scala and 250 lines of CSS.
* **[Scalatron ★ 578 ⧗ 14](https://github.com/scalatron/scalatron)** - [Scalatron](https://scalatron.github.io/), a multi-player programming game in which coders pit bot programs (written in Scala) against each other.
* [scalawarrior ★ 103 ⧗ 12](https://github.com/scalawarrior/scalawarrior) - This is a game for learning Scala which is inspired by [ruby-warrior](https://github.com/ryanb/ruby-warrior). On each floor you instruct the warrior to battle enemies, rescue captives, and reach the stairs by writing some Scala!
* [stargame ★ 1 ⧗ 1450](https://github.com/tommycli/stargame) - Multiplayer browser-based space 4X RTS. 
* [UltraBlackBloodDeath ★ 2 ⧗ 506](https://github.com/sykophant/sykophant-game) - `untested` An open-source FPS tournament game made using Scala on top of JME3.

### Closed-Source

* [Rat Trap](https://play.google.com/store/apps/details?id=com.regblanc.rattrap&hl=en) - Rat Trap is a small and addictive puzzle game, where your role is to protect your reserve of cheese by carefully positioning blocking elements to prevent the rat from reaching it and eventually trap it. 
* [ScalaQuest](https://www.kickstarter.com/projects/andanthor/scalaquest-a-game-to-learn-scala) - `pre-release` An online game to learn Scala. Battle Goblins and Wizards and face all kinds of challenges while learning a new programming language. Written using [Phaser.js](https://phaser.io) and the [Play Framework](https://playframework.com).
* [WinSmash](https://play.google.com/store/apps/details?id=com.regblanc.winsmash&hl=en) - WinSmash is a classic arcade game that pays homage to the late Microsoft Windows XP by reminding nostalgic people of the good old days.

### Mini-games

* [monadic mario](https://github.com/OlivierBlanvillain/monadic-html/blob/master/examples/src/main/scala/mhtml/examples/Mario.scala) - [live demo](https://olivierblanvillain.github.io/monadic-html/examples/#/Mario) A very simple mario "game", writtein in [monadic-html](https://github.com/OlivierBlanvillain/monadic-html).
* [scala-js-games ★ 88 ⧗ 4](https://github.com/lihaoyi/scala-js-games) - [live demo](http://www.lihaoyi.com/scala-js-games/) Demo collection including Asteroids, Astrolander, Snake, Pong, Brick, and Tetris.
* [scalajs-snake ★ 4 ⧗ 152](https://github.com/vmunier/scalajs-snake) - [live demo](http://vmunier.github.io/scalajs-snake/) Snake game written in Scala.js.

## Game Engines and Libraries

* [RPG Boss ★ 233 ⧗ 1](https://github.com/rpgboss/rpgboss) - Multiplatform, point and click rpg game editor and engine, based on [libgdx](https://github.com/libgdx/libgdx).
* [Scage ★ 155 ⧗ 65](https://github.com/dunnololda/scage) - `inactive` 2D OpenGL game engine, based on phys2d, lwjgl, and slick.
* [sgine ★ 12 ⧗ 217](https://github.com/outr/sgine) - `inactive` Scala Engine for OpenGL-based Desktop, Android, and iOS game and business development; based on [libgdx](https://github.com/libgdx/libgdx).
* [SGL ★ 37 ⧗ 23](https://github.com/regb/scala-game-library) - `pre-release` Scala Game Library is a library for developing cross-platform 2D video games in Scala. It provides a high-level API for building 2D games, and can deploy for Desktop, Android, and HTML5, while iOS and console platforms are on the roadmap. Makes use of [Graphics Bindings for Scala Native](#wrappers-for-engines-and-libraries) for some platforms.
* [Simplex3D ★ 28 ⧗ 217](https://github.com/lexn82/simplex3d) - `inactive` The (first?) Scala 3D engine.

## Game Tools

* [scalacloth ★ 1 ⧗ 1399](https://github.com/dbousamra/scalacloth) - `untested` A cloth simulation in Scala.

## Graphical User Interfaces

* [ScalaFX ★ 371 ⧗ 2](https://github.com/scalafx/scalafx) - [Scala DSL](http://www.scalafx.org/) for creating Graphical User Interfaces that sits on top of JavaFX.
* [youi ★ 106 ⧗ 5](https://github.com/outr/youi) - Next generation user interface and application development in Scala.js for web, mobile, and desktop. Currently has support for a 2D API; WebGL may be added later.

## Wrappers for Engines and Libraries

* [Graphics Bindings for Scala Native ★ 9 ⧗ 94](https://github.com/regb/scalanative-graphics-bindings) - `pre-release` Scala Native bindings for the popular graphics programming libraries SDL2 and OpenGL. The bindings try as much as possible to reproduce the original programming interface in C. In particular, they won't hide scalanative interoperability types behind regular Scala types.
* [MacroGL ★ 81 ⧗ 7](https://github.com/storm-enroute/macrogl) - `inactive` Scala macro-based frontend for OpenGL for structured and efficient graphics code. Currently targets Scala.js and the JVM.
* [SME ★ 0 ⧗ 111](https://github.com/bbarker/SME) - `pre-release` Scala Monkey Engine is a thin wrapper around [JMonkeyEngine 3](http://jmonkeyengine.org), helping to provide a more idiomatic feel to JME3 where possible. Currently requires and targets [Dotty](http://dotty.epfl.ch/).

## Ray tracing

* [Scala Collections RayTracer](https://github.com/scala-blitz/scala-blitz/blob/master/src/test/scala/org/scala/optimized/test/examples/RayTracer.scala) - `inactive` A small example meant to take advantage of Scala's parallel collections, complete [with a writeup](https://scala-blitz.github.io/home/documentation/examples//raytracer.html).
* [ScalaRay ★ 6 ⧗ 999](https://github.com/jesperdj/scalaray) - `inactive` Educational raytracer based on pbrt, the ray tracer described in the book Physically Based Rendering - From Theory to Implementation by Matt Pharr and Greg Humphreys
* [scalasimpleray ★ 7 ⧗ 768](https://github.com/dbousamra/scalasimpleray) - `inactive` This is a VERY basic raytracer, but it's quite clean, and could be used by someone to learn.
* [SunBurn ★ 1 ⧗ 1353](https://github.com/hsyl20/SunBurn) - `inactive` 

## Resources

* [How to make a simple HTML5 Canvas game](http://www.lostdecadegames.com/how-to-make-a-simple-html5-canvas-game/) - The style is roughly that of an NES/SNES-era Zelda game. The tutorial targets JavaScript, but there is a [Scala.js port](https://github.com/vmunier/scalajs-simple-canvas-game) ([live demo](http://vmunier.github.io/scalajs-simple-canvas-game/)). An alternative [Scala.js port](https://github.com/amsterdam-scala/Sjs-Simple-HTML5-canvas-game) using various technologies.
* [Scala on Android](http://scala-android.org/) - Resources that will help you get your app (game) working on Android.

# Contributing

Your contributions are always welcome! Please submit a pull request or create an issue to add a new Scala game, game library (in Scala or a Scala wrapper library), article on game development related to Scala. If the project is inactive, deprecated, or pre-release a tag should be added to indicate this.
