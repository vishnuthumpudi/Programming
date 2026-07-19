# Release Notes

## [Unreleased] — Documentation Overhaul

### Added
- **Root `README.md`** — new parent overview describing the repo's purpose (learning programming as a non-CS student), a table linking to all subdirectories, a current goals checklist, and a shared learning log.
- **`Java/README.md`** — new template covering core Java, OOP, multithreading, Spring Boot, and design patterns, with a topics log, bugs/gotchas section, and TCS Wings 1 certification tracker.
- **`Data-Structures-and-Algorithms/README.md`** — new template with a 12-week roadmap tracker, per-pattern cheatsheet, and a problem log (includes first logged entry: Path Sum III).
- **`Low-Level-Design/README.md`** — new template covering SOLID principles, design pattern categories, a standard problem-solving approach, and a classic LLD problem bank (parking lot, elevator system, rate limiter, etc.).
- **`High-Level-Design/README.md`** — new template covering system design fundamentals (scalability, caching, databases, CAP theorem), a standard HLD approach, and a classic system design problem bank (URL shortener, chat app, news feed, etc.).

### Changed
- N/A (all files newly added in this release)

### Notes
- Progress trackers and problem logs in each subdirectory `README.md` are currently empty templates — to be filled in as topics/problems are completed.
- Root `README.md` learning log dates are placeholders (`—`) pending backfill.

---

## How to Use This File

Add a new dated entry above `[Unreleased]` each time you merge a meaningful set of changes, e.g.:

```markdown
## [2026-07-19] — Documentation Overhaul
### Added
- ...
```

Keep entries grouped under `Added`, `Changed`, `Fixed`, or `Removed` for consistency.