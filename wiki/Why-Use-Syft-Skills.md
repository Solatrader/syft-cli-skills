# Why Use Syft Skills

Syft CLI gives you primitives.
This repository gives you workflows.

## The Gap

Without a skill layer, an agent still has to decide:

- which command to run first
- how to interpret followed topics
- how to repair missing coverage
- how to distinguish a hobby branch from noise
- how to keep output style consistent over time

Those are not just command-execution problems.
They are editorial workflow problems.

## What The Skill Layer Adds

### 1. Reusable profile interpretation

`syft following` is a good declared-interest source, but it is not yet a reusable profile artifact.

`syft-profile-summary` turns that raw list into:

- canonical follows
- heuristic interest layers
- a readable profile summary

### 2. Profile-aware daily editions

`syft top` alone gives a pool.
It does not give a finished edition.

`syft-daily-briefing` adds:

- triage rules
- gap repair rules
- interest coverage checks
- lane-aware prose

### 3. Relationship-first reading

A list is not a storyline.

`syft-storyline-tree` turns the pool into trunks, branches, and merged timelines so the user can browse a day as a structured map instead of a pile of links.

### 4. Controlled deepening

Once a tree exists, users often want more history on one branch.

`syft-storyline-backfill` provides a disciplined way to deepen the branch without rebuilding the whole ontology.

### 5. Durable preferences

Editorial behavior should improve over time.

`syft-guidance-rulebook` helps the agent keep stable preferences instead of relearning them from scratch every run.

## Why This Matters In Practice

These skills help an agent produce outputs that are:

- more readable
- more stable
- more personal
- easier to reuse
- easier to share with another operator
