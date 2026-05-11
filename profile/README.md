# BaseDiff

**Schema Comparison & Script Generation**

A fast, precise, cross-platform tool for comparing database schemas and generating update SQL scripts.

[![Website](https://img.shields.io/badge/website-basediff.com-09090b)](https://basediff.com)
[![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20Linux%20%7C%20macOS-blue)](https://basediff.com/#download)
[![Databases](https://img.shields.io/badge/databases-MS%20SQL%20Server%20%7C%20PostgreSQL-336791)](https://basediff.com/#databases)
[![Issues](https://img.shields.io/github/issues/BaseDiff/tracker?label=issues)](https://github.com/BaseDiff/tracker/issues)
[![YouTube](https://img.shields.io/badge/YouTube-@BaseDiff-FF0000)](https://www.youtube.com/@BaseDiff)

[Download](https://basediff.com/#download) ·
[Features](https://basediff.com/#features) ·
[Video guides](https://youtube.com/playlist?list=PLmSJ6iIhpwF1Hoh57vU-x39o7DH5zTW0X) ·
[Issues](https://github.com/BaseDiff/tracker/issues) ·
[FAQ](https://basediff.com/#faq)

---

## What is BaseDiff?

BaseDiff is a desktop application for comparing and synchronizing database structures. It generates clean, human-readable SQL scripts (`CREATE`, `ALTER`, `DROP`) to migrate one schema to another — without writing SQL by hand.

It was originally built as an internal tool at [ELVAC SOLUTIONS](https://www.elvacsolutions.eu) because we were tired of expensive licenses and Windows-only tooling. We use it daily on our own projects and decided to share it with the community.

## Highlights

- **Schema comparison** — visual diff of two database schemas with one-click source/target swap.
- **Script generation** — automatic `ALTER`, `CREATE`, and `DROP` scripts for synchronization.
- **Script editing** — preview and edit generated SQL before export; pick exactly what ends up in the output.
- **Flexible export** — single file or split files (`create`, `alter`, `drop`, data migration).
- **Save projects** — persist comparison configuration to JSON and resume later.
- **Query Tool** — build `SELECT` queries with `JOIN`s and reuse them in migration scripts.
- **Migration Data Editor** — manage data migration scripts alongside schema changes.
- **100% offline** — runs locally; no cloud, no telemetry of your schemas, safe for isolated networks.
- **Portable builds** — no installer required on any supported platform.

## Supported databases

| Database         | Status                                                                                                  |
| ---------------- | ------------------------------------------------------------------------------------------------------- |
| MS SQL Server    | ✅ Available — Windows Auth & SQL Auth · [details](https://basediff.com/compare-sql-server-schemas.html) |
| PostgreSQL       | ✅ Available — full schema support · [details](https://basediff.com/compare-postgresql-schemas.html)     |
| MySQL            | 🔜 Coming soon                                                                                          |
| Oracle           | 🔜 Coming soon                                                                                          |
| SQLite           | 🔜 Coming soon                                                                                          |

### Tracked object types

Tables · Indexes · Constraints (FK, CK, UQ) · Views · Stored procedures · Functions · Triggers · Migrations

## Privacy

BaseDiff runs entirely on your machine. Database connections go directly from your computer to your databases — schemas and data never leave your network. The app does not require internet access to operate; you only need it to download updates.

## Feedback & community

- 🐛 Bug reports and feature requests: [BaseDiff/tracker](https://github.com/BaseDiff/tracker/issues) — public issue tracker on GitHub.
- 💬 General feedback or contact: [basediff.com/feedback.html](https://basediff.com/feedback.html)
- 📺 Video guides: [YouTube — @BaseDiff](https://www.youtube.com/@BaseDiff)
- 📰 Changelog: [basediff.com/changelog.html](https://basediff.com/changelog.html)
- ☕ Like BaseDiff? [Buy us a coffee on Ko-fi](https://ko-fi.com/basediff)

## About

BaseDiff is developed by [**ELVAC SOLUTIONS**](https://www.elvacsolutions.eu), part of the ELVAC group.

[Privacy Policy](https://basediff.com/privacy.html) ·
[Terms of Use](https://basediff.com/terms.html) ·
[Cookies](https://basediff.com/cookies.html)