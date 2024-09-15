---
draft: true
---
NOTE: This should not be published! Keep the draft flag ON!

This site was setup using Quartz: [Welcome to Quartz 4 (jzhao.xyz)](https://quartz.jzhao.xyz/)

## Setup
To set up on a new machine, clone the `ultra-flavour` repository to somewhere on the machine.

Setup `npm`, do `npx quartz create` to symlink the content folder to the `blog` folder of this Obsidian vault.
## Post Blog
You theoretically should not need to do anything else except call `npx quartz sync`.

This is the deploy workflow that should run if everything goes well with the call to sync:
[Deploy Quartz site to GitHub Pages · Workflow runs · BlakeBouchard/ultra-flavour](https://github.com/BlakeBouchard/ultra-flavour/actions/workflows/deploy.yml)
## Commands
- `npx quartz sync`
- `npx quartz sync --no-pull`
	- Not sure what this is for, perhaps to prevent pulling from the v4 upstream
- `npx quartz build --serve`
	- Builds and hosts at http://localhost:8080
## Links
- https://blakebouchard.github.io/ultra-flavour/
- https://github.com/BlakeBouchard/ultra-flavour
	- https://github.com/BlakeBouchard/ultra-flavour/actions/workflows/deploy.yml
- http://localhost:8080/
- [Configuration (jzhao.xyz)](https://quartz.jzhao.xyz/configuration#plugins)