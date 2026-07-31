# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.2.0] - 31/07/2026

### Added

- `.github/workflows/snake.yml` — daily (03:00 UTC) and manually triggerable job that renders the contribution snake with `Platane/snk/svg-only@v3` and publishes `snake.svg` / `snake-dark.svg` to the `output` branch
- Light/dark `<picture>` element for the snake so the dark variant is used under `prefers-color-scheme: dark`

### Changed

- Setup notes rewritten: the inline workflow YAML is replaced with first-run instructions (workflow permissions, manual trigger, `output` branch) and a note that only public contributions are counted

### Removed

- "Requires the GitHub Action below" caveat under the snake, now that the workflow ships with the repo

## [1.1.0] - 31/07/2026

### Added

- Selected Work expanded from a single table into four grouped tables: AI & Automation, Data/Ad Ops & Analytics, Event Platforms, and WordPress/Forums & Compliance (20 projects)
- Closing note covering the 360 review platform, work planner, Cloudflare Workers threat map, register scrapers and smaller plugins
- New "AI & Agents" badge group: Claude API, OpenAI embeddings, MCP, RAG pipelines
- MariaDB and Composer badges to Core; Google Ad Manager and Dotdigital badges to Data & Analytics
- Two extra lines in the animated typing banner covering ad tech, analytics pipelines, event platforms and RAG chatbots

### Changed

- Projects described generically, without internal subdomains or system names

## [1.0.1] - 31/07/2026

### Removed

- Custom WP Plugins badge link from the header
- Custom WP Plugins line from the animated typing banner
- Custom WP Plugins row from the Selected Work table

## [1.0.0] - 31/07/2026

### Added

- Initial GitHub profile README
