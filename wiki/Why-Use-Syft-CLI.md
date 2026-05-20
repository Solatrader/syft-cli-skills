# Why Use Syft CLI

Syft CLI is the simplest bridge between the Syft system and an agent workflow.

According to the public npm package, the official CLI is distributed as:

```bash
npm install -g @orionarm/syft-cli
```

After installation, the command is:

```bash
syft
```

## Core Commands

The public package README exposes these commands as the main entry points:

- `syft login`
- `syft status`
- `syft upgrade`
- `syft install-skill`
- `syft following`
- `syft search "<query>"`
- `syft global-search "<query>"`
- `syft top`
- `syft help`
- `syft version`
- `syft logout`

## Why The CLI Is Useful For Agents

For this repository, three commands are the real foundation:

- `syft following`
- `syft top`
- `syft search`

Together, they give an agent:

- the user's declared interest graph
- a high-signal topical news pool
- a way to repair thin branches and fill missing chronology

That is enough to support serious editorial workflows even when richer internal tools are unavailable.

## Why Not Just Read The App

The app is great for browsing.
The CLI is better for:

- repeatable automation
- artifact creation
- agent workflows
- profile-aware batch work
- structured output generation

When you want markdown, HTML, JSON, or reusable profile files, the CLI is the more direct integration point.

## Public Install Source

Public homepage listed on npm:

- `https://syft.ai`

Public npm package description:

- `Syft CLI distributed via npm`
