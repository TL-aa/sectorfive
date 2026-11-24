# SectorFive

> A game built in C# with SplashKit, structured around object-oriented design patterns.

![Type](https://img.shields.io/badge/type-university%20project-blue)

---

## Overview

A game built in C# with SplashKit, structured around object-oriented design patterns. This repository describes the project at a high level. The source code is not public (see below).

## The Problem

Game code gets messy fast. If every enemy, bullet and collision is handled with special cases, adding anything new means rewriting existing code. The goal was a structure where new objects and behaviour can be added without breaking what already works.

## Why I Built It

Built to apply object-oriented programming and design patterns in a real project instead of just reading about them.

## Key Features

- Class hierarchy: GameObject → MovingObject → Enemy, Player and Bullet
- Factory pattern for creating enemies
- Visitor pattern for handling collisions between different objects
- Finite state machine for game states such as menu, playing and game over

## Tools & Technologies

| Area | Tools |
|---|---|
| Languages | C# |
| Frameworks / libraries | SplashKit |
| Concepts | Inheritance, polymorphism, Factory, Visitor, state machines |
| Other | Git |

## My Role

- **Project type:** University project at Swinburne University of Technology
- **Duration:** One semester
- **Responsibilities:** [Add what you personally built, and whether this was solo or a group project]

## How It Works

1. A GameObject base class defines what every object can do
2. MovingObject, Enemy, Player and Bullet extend it
3. A factory creates enemies so the game loop doesn't depend on concrete types
4. The Visitor pattern decides what happens when two object types collide
5. A state machine switches between menu, play and game over

## What I Learned

- When each design pattern is the right tool
- Keeping code open to extension but closed to rewrites
- Structuring a larger program across many classes
- Managing game states cleanly

---

## Source Code Availability

The source code for this project is **not public** because it was university coursework and the assessment material cannot be shared publicly.

I'm happy to walk through the project, explain my design decisions, or share more detail on request:

- **Email:** limtisang.shs@gmail.com

---

## Not Included in This Repository

- The assignment brief, marking criteria and solutions
- Datasets that cannot be redistributed
- Any code that would breach the unit's academic integrity rules

<!-- Suggested GitHub description: A game built in C# with SplashKit, structured around object-oriented design patterns. (README only, source available on request) -->
<!-- Suggested topics: csharp,splashkit,game-development,oop,design-patterns,university-project -->
