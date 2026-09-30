# AGENTS.md

## Project context

- This repository currently contains a minimal README and no confirmed app source, package manifests, or deployment config.
- The project is described in [README.md](README.md) as a Cloudflare Pages / Node.js travel-service site named “Rạch Giá 24h TMQ”. Treat that as the only confirmed product context until additional files are added.
- Do not assume a framework, server, build system, or deployment pipeline exists yet. Confirm the repo structure before making architectural assumptions.

## Working conventions

- Keep changes minimal, explicit, and aligned with the repo’s current maturity.
- Avoid creating new app scaffolds, frameworks, or conventions unless the task explicitly requires them.
- Before adding dependencies, tooling, or deployment scripts, check whether the repo already contains the relevant files.
- Prefer solutions that are easy to deploy to Cloudflare Pages if the project later grows into a static or Node-based site.

## Validation

- Inspect the repo before running or suggesting build commands; the correct validation step depends on what files exist.
- Use the smallest relevant validation command for the change being made.
- If the repository remains README-only, avoid broad setup work and focus on documentation or the exact requested change.

## Guidance for future agents

- Start from the actual repository state, not a guessed architecture.
- Re-read [README.md](README.md) before making any assumptions about the project or deployment target.
- Prefer small increments that match the repository’s current scope and keep future work easy to extend.
