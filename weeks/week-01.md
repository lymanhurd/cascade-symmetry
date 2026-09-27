---
layout: default
title: Week 1 - Rules & Nim-Sum
nav_order: 2
---

# Week 1: Rules & Strategy

## Visual Breakdown
Here is the initial token setup for the three-pile game:

![Three-pile board setup](../assets/board-setup.png)

## Core Concepts
* Piles start with 3, 4, and 5 tokens.
* Players take turns removing any number of counters from a single pile.
* The normal play convention determines the winner.

### Key Observation
Notice the symmetry in the reduction step:

![State reduction diagram](../assets/diagram1.png)

## Exercises for Next Week
1. Determine the winning first move for the state shown above.
2. Draw the game tree for piles sized `(1, 2, 2)`.
