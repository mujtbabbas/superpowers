# Changelog

All notable changes to this standalone edition of superpowers are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions updates, plus npm updates for `tests/brainstorm-server` (the only `package.json` with real dependencies; upstream had no Dependabot config).
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow — also this repo's first GitHub Actions workflow, since upstream shipped none); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [obra/superpowers](https://github.com/obra/superpowers) at upstream release v7.0.0 (snapshot commit `bb92a77741419a4ab5f06e711a283343f1ada0c3`, upstream HEAD dated 2026-10-09).
- Fork history severed; all files and the MIT licence (`LICENSE`) preserved as-is.
