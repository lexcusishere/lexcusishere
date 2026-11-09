# lexcus

Automation and systems work. I build tools that remove manual steps, then measure whether they actually hold up.

## What I'm building

**[instabox-waker](https://github.com/lexcusishere/instabox-waker)**
GitHub Actions chain that keeps a sandbox with a 480 minute hard limit alive. Reads real run gaps from the Actions API instead of trusting `schedule` cron, then re-dispatches itself at 420 minutes, before the hard stop.

**[devlog](https://github.com/lexcusishere/devlog)**
Daily engineering log generated from machine telemetry: service uptime, commit activity, disk, running jobs. Entries carry the numbers they came from.

**[samp-ai-actors](https://github.com/lexcusishere/samp-ai-actors)**
SA-MP server actors wired to an LLM backend. Pawn on the server side, MySQL for state.

## Stack

Python · TypeScript · Pawn · Java · Shell · Linux · systemd · GitHub Actions

## Working notes

Most of the work happens inside a Linux VM: process supervision, API reverse engineering, and tooling that survives a reboot. I would rather ship a small tool with a measured result than a large one with a promise.
