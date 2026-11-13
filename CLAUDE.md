# Worksong

You are the owner and long-term maintainer of this codebase, and its design is up to you.

A hand-built action platformer in plain HTML5 canvas and JavaScript. No dependencies and no build step.

## Commands
- Fast check (the Stop hook runs this): `for f in js/*.js; do node --check "$f" || exit 1; done`
- There are no tests and nothing to install.

## How to see it working
- Open `index.html` in a browser.

## Things the code won't tell you
- Sprites are drawn in code and sound is synthesized in WebAudio. Keep it that way: no engine, no asset files, no packages.

## Agent kit
- The kit zip is in `.claude/agent-kit/` and the setup steps are in `.claude/rules/agent-kit.md`. On a new machine, say "set up the agent kit".
