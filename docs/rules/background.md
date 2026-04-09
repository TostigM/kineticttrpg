# Background Definitions

This document outlines character backgrounds in the Kinetic System.

## PART 7.5: BACKGROUND DEFINITIONS (DEEP BRANCHING)

Each background origin uses a strict 5-level binary decision tree. Every node branches into exactly 2 child nodes.

* Decision Level 1: 2 nodes (`1`, `2`)
* Decision Level 2: 4 nodes (`1.1`, `1.2`, `2.1`, `2.2`)
* Decision Level 3: 8 nodes
* Decision Level 4: 16 nodes
* Decision Level 5: 32 final outcomes

Path notation follows this format: `1`, `2`, `1.1`, `2.2.1`, `1.2.2.1.2`.

### Usage Rules

* Choose 1 origin.
* Start at Decision Level 1.
* At each level, pick one child path from your current node.
* Continue until Decision Level 5 to finalize your background path.
* Each decision choice must grant one of: `+1 Stat Point`, `+2 Stat Points and -1 Stat Point`, or `a basic proficiency`.

## Background Files

* [Rural](backgrounds/rural.md)
* [Urban](backgrounds/urban.md)
* [Badlands](backgrounds/badlands.md)
* [Frontier](backgrounds/frontier.md)
* [Courtly](backgrounds/courtly.md)
* [Monastic](backgrounds/monastic.md)
* [Nomadic](backgrounds/nomadic.md)
* [Undercity](backgrounds/undercity.md)

## Design Note

Full trees now live in separate files under `docs/rules/backgrounds/` so each origin is easier to navigate.
