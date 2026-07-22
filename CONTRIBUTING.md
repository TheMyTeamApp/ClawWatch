# Contributing to ClawWatch

Thanks for your interest in ClawWatch, the AI agent running natively on a smartwatch (NullClaw + Vosk offline STT + Claude on Galaxy Watch).

## Where help is most useful

- **Service integrations**: connecting the watch agent to more services and tools
- **Watch UI/UX**: the Wear OS interface in `app/` (screens, complications, voice flow)
- **NullClaw upstream sync**: keeping our embedded NullClaw current with [nullclaw/nullclaw](https://github.com/nullclaw/nullclaw)
- **Docs and examples**: setup guides, demo flows, troubleshooting
- **Device testing**: reports from watch models we have not tested ourselves

## Project layout

- `app/` - the Wear OS watch app (Kotlin)
- `phone/` - phone-side companion
- `admin/`, `tools/` - development and administration utilities
- `docs/` - documentation

## How to contribute

1. For anything beyond a small fix, **open an issue first** describing what you want to change and why. It saves you from building something we cannot merge.
2. Fork, create a focused branch, and keep each PR to one logical change.
3. In the PR description, say what changed and why; add screenshots or a short clip for UI changes.
4. Match the style of the surrounding code.
5. Every PR gets a review before merge; we aim to respond within a few days.

## Licensing

By contributing you agree that your contributions are provided under the terms of this repository's [LICENSE](LICENSE).

## Questions

Open an issue. We would rather answer early than review a PR that went in the wrong direction.
