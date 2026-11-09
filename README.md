# lexcus

Automation and systems work. I build tools that remove manual steps, then measure whether they actually hold up.

## What I'm building

**[sandbox-keepalive](https://github.com/lexcusishere/sandbox-keepalive)**
Keeps a free-tier cloud sandbox awake through an activity lease, supervises workloads as systemd user units with checkpoints, and wakes the machine from outside after the platform stops it.

**[instabox-waker](https://github.com/lexcusishere/instabox-waker)**
GitHub Actions chain that survives a 480 minute hard limit. It reads real run gaps from the Actions API instead of trusting `schedule` cron, then re-dispatches itself at 420 minutes.

**[devlog](https://github.com/lexcusishere/devlog)**
Daily engineering log generated from machine telemetry: service uptime, commit activity, disk, running jobs. Entries carry the numbers they came from.

## Stack

Python · TypeScript · Pawn · Java · Shell · Linux · systemd · GitHub Actions

## Working notes

Most of the work happens inside a Linux VM: process supervision, API reverse engineering, and tooling that survives a reboot. I would rather ship a small tool with a measured result than a large one with a promise.
