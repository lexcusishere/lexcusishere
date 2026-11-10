<div align="center">

<a href="https://lexcusishere.github.io">
<img src="https://lexcusishere.github.io/assets/banner.svg" width="100%" alt="lexcus — automation, systems, tooling" />
</a>

<!-- Animated Typing Header (DenverCoder1/readme-typing-svg) -->
<a href="https://github.com/DenverCoder1/readme-typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=3FB950&center=true&vCenter=true&width=640&lines=Building+tooling+that+survives+a+reboot;One+problem%2C+one+cause%2C+one+diff;Focused+pull+requests+with+a+reproduction" alt="Typing SVG" />
</a>

</div>

## Systems

I build tooling that stays up: process supervision, keepalive logic, API clients, and small utilities that delete a manual step. The interesting part is rarely the feature — it is the restart, the rate limit, the half-finished run.

Most of it lands as focused pull requests. One problem, one cause, one diff, with a reproduction in the description.

## Deployed

<div align="center">

<a href="https://github.com/lexcusishere/onlyread">
<img width="48%" src="https://opengraph.githubassets.com/1/lexcusishere/onlyread" alt="onlyread" />
</a>
<a href="https://github.com/lexcusishere/instabox-waker">
<img width="48%" src="https://opengraph.githubassets.com/1/lexcusishere/instabox-waker" alt="instabox-waker" />
</a>

</div>

**onlyread** makes AI browser agents read-only — a Chrome extension that refuses writes (send, post, edit, delete) before they leave the browser.

![TypeScript](https://img.shields.io/badge/TypeScript-0B0F14?style=flat-square&logo=typescript&logoColor=3FB950&labelColor=10161D)
![Chrome Extension](https://img.shields.io/badge/Chrome_Extension-0B0F14?style=flat-square&logo=googlechrome&logoColor=3FB950&labelColor=10161D)

**instabox-waker** keeps a sandbox with a 480 minute hard limit alive. It reads real run gaps from the Actions API instead of trusting `schedule` cron, then re-dispatches itself at 420 minutes, before the stop.

![Python](https://img.shields.io/badge/Python-0B0F14?style=flat-square&logo=python&logoColor=3FB950&labelColor=10161D)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0B0F14?style=flat-square&logo=githubactions&logoColor=3FB950&labelColor=10161D)

## Changelog

Pull requests against other people's projects, where the work is a bug fix with a reproduction:

- [webdriverio#16404](https://github.com/webdriverio/webdriverio/pull/16404) — reads an svg `aria-label` or `<title>` into the accessible name, so `@wdio/snapshot` stops emitting `role/link` selectors that resolve to nothing
- [webdriverio#16405](https://github.com/webdriverio/webdriverio/pull/16405) — stops emitting an `aria/` candidate that resolves to a different element than the ref it is attached to
- [icalendar#2085](https://github.com/collective/icalendar/pull/2085) — fixes the last broken Sphinx cross-references after the 7.0 module reorg

## Metrics

<div align="center">

<img height="250" src="https://lexcusishere.github.io/assets/stats.svg" alt="metrics" />
<img height="250" src="https://lexcusishere.github.io/assets/streak.svg" alt="streak" />

<img width="48%" src="https://lexcusishere.github.io/assets/languages.svg" alt="languages" />
<img width="48%" src="https://lexcusishere.github.io/assets/activity.svg" alt="activity" />

</div>

<!-- Animated Contribution Snake via GitHub Actions (Platane/snk) -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lexcusishere/lexcusishere/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/lexcusishere/lexcusishere/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/lexcusishere/lexcusishere/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=py,ts,js,java,bash,linux,git,github,docker,mysql&perline=10" alt="stack" />

</div>

## Contact

<div align="center">

<a href="https://github.com/lexcusishere"><img src="https://img.shields.io/badge/GitHub-lexcusishere-0B0F14?style=for-the-badge&logo=github&logoColor=3FB950&labelColor=10161D" alt="github" /></a>
<a href="https://github.com/lexcusishere?tab=repositories"><img src="https://img.shields.io/badge/Repositories-0B0F14?style=for-the-badge&logo=git&logoColor=3FB950&labelColor=10161D" alt="repositories" /></a>
<a href="https://github.com/lexcusishere/lexcusishere/issues"><img src="https://img.shields.io/badge/Open%20an%20issue-0B0F14?style=for-the-badge&logo=githubactions&logoColor=3FB950&labelColor=10161D" alt="issues" /></a>

<!-- Uncomment and fill in your LinkedIn handle:
<a href="https://linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-YOUR_LINKEDIN-0B0F14?style=for-the-badge&logo=linkedin&logoColor=3FB950&labelColor=10161D" alt="linkedin" /></a>
-->

</div>

<div align="center">
<sub>Graphite, signal green. Every number generated from the GitHub API, served as animated SVG.</sub>
</div>
