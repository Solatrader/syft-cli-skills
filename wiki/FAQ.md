# FAQ

## Do I need the local Python MVP pipeline to use these skills?

No.
This repository is specifically designed for Syft CLI based workflows.

## Do I need all six skills?

No.

- install `syft-news-pipeline` if you want one entry point
- install the atomic skills if you want direct control over specific routes

## What language do the final outputs use?

The skills default to Simplified Chinese unless the user asks otherwise.

## What if I only want a daily briefing?

You can go directly from profile generation to briefing generation.
The full storyline workflow is optional.

## Can I use these skills in GitHub Copilot as well as Codex?

Yes.
That is why the repository includes both:

- `.github/skills/`
- `codex-skills/`

## Where should I look if I want to understand the overall product logic first?

Start with:

1. [What Is Syft AI](What-Is-Syft-AI.md)
2. [Why Use Syft CLI](Why-Use-Syft-CLI.md)
3. [Why Use Syft Skills](Why-Use-Syft-Skills.md)
