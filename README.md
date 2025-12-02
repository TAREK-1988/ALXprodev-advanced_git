# ALX ProDev Advanced Git

This repository is used to practice the Git-Flow branching model as part of the ALX ProDev DevOps curriculum.

## Branch Types

- `main` – production-ready code.
- `develop` – integration branch for ongoing development.
- `feature/*` – branches for new features.
- `release/*` – branches used to prepare production releases.
- `hotfix/*` – branches for critical fixes applied directly to `main`.

## Git-Flow Usage

The following Git-Flow commands are used in this project:

- Initialize Git-Flow with default settings: `git flow init -d`
- Start a feature: `git flow feature start <name>`
- Finish a feature: `git flow feature finish <name>`
- Start a release: `git flow release start <version>`
- Finish a release: `git flow release finish <version>`

## Version

Current release: `v1.0.0`.
