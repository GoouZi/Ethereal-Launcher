# Changelog

This file records verified development milestones and public release changes for Ethereal Launcher.

> Earlier development happened before the GitHub repository became the main public release channel. The entries below only include milestones that can be confirmed; missing historical version numbers are intentionally not invented.

## 2026-09-24

### Project and release infrastructure

- Unified the product-facing name as **Ethereal Launcher**.
- Kept **EMCL** as the established short name used by the project and website.
- Established the official website at **https://emcl.goouzi.top**.
- Connected the GitHub repository **GoouZi/Ethereal-Launcher** with the website server through GitHub Actions and SSH deployment.
- Verified automatic deployment to the website update directory.
- Defined the release structure for GitHub Releases, website downloads, changelogs, and launcher update metadata.
- Prepared the project to use **Sparkle 2** for in-app updates on macOS, with the update feed hosted at:
  - https://emcl.goouzi.top/update/appcast.xml

### Website

- Reworked the Ethereal Launcher website around the product's core positioning:
  - macOS
  - native
  - beginner friendly
  - lightweight
- Added a direct-download path alongside the GitHub release channel.
- Added support for displaying release information from website update metadata.

## 2026-09-23

### Public project setup

- Created the public GitHub repository:
  - https://github.com/GoouZi/Ethereal-Launcher
- Established the project positioning as a beginner-friendly Minecraft launcher for macOS.
- Defined the core goal: reduce the need for users to manually deal with Java setup, dependencies, and other computer configuration before playing Minecraft.

---

Future public releases will be recorded here with explicit version numbers, dates, additions, changes, and fixes.
