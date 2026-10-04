<h1 align="center">Hi, I'm Danila — Python / C++ developer</h1>
<p align="center">
  <b>Backend · REST API · Automation</b>
</p>

<p align="center">
  <a href="https://teivrimoriginal.github.io/Partfolio-Site/"><b>Portfolio</b></a>
  &nbsp;·&nbsp;
  <a href="https://teivrimoriginal.github.io/Partfolio-Site/resume.html"><b>Resume (RU)</b></a>
  &nbsp;·&nbsp;
  <a href="https://teivrimoriginal.github.io/Partfolio-Site/resume-en.html"><b>Resume (EN)</b></a>
  &nbsp;·&nbsp;
  <a href="https://t.me/Smishnyavko"><b>Telegram</b></a>
  &nbsp;·&nbsp;
  <a href="mailto:teivrim@gmail.com"><b>Email</b></a>
  &nbsp;·&nbsp;
  <a href="tel:+79014318298"><b>+7 901 431-82-98</b></a>
</p>

---

**769 tests across these repositories** — 564 in the Rust catalogue (CI green),
158 in the image editor, 47 UI tests. CI runs rustfmt, clippy `-D warnings` and
`cargo test` on every push to the catalogue.

## What I build

**Backend and APIs**
- **Anime DB** — catalogue backend rewritten from Node.js to Actix-Web: SQLite FTS5, Docker,
  ~20k records aggregated from three public APIs, JSON API with filters and pagination, Android client.
  564 unit tests, and CI on every push: rustfmt, clippy with `-D warnings`, `cargo test`.
  → [repo](https://github.com/TeivrimOriginal/TeivrimSite) · [CI](https://github.com/TeivrimOriginal/TeivrimSite/actions/workflows/ci.yml)

**Automation and testing**
- **practice-automation-tests** — 47 UI autotests (Selenium + Pytest + Allure): positive,
  negative and contact-form cases with Allure HTML reports. These drive a live
  third-party site, so CI runs them but does not gate on them — the site sits
  behind a browser check and blocks the runner.
  → [repo](https://github.com/TeivrimOriginal/practice-automation-tests)
- Client work on Kwork: Telegram bots in Python, website scrapers, REST APIs, automation.

**Tools and desktop software**
- **TPaint** — image editor in Rust with a custom immediate-mode UI: 15+ tools, layers with masks
  and 10 blend modes, PSD export, 158 unit tests.
  → [repo](https://github.com/TeivrimOriginal/Copy-SAI-Paint-with-Rust)
- **Teivrim-Engine** — C++17 engine from scratch: runtime backend selection, scene graph,
  FBX/OBJ import via Assimp.
  → [repo](https://github.com/TeivrimOriginal/Teivrim-Engine)
- **Visual novel editor** — C++ / Win32 / GDI+: 6 panels, drag-and-drop from Explorer.
  → [repo](https://github.com/TeivrimOriginal/teivrim-novell-engine)

## Stack

| | |
|---|---|
| Languages | Python, C++17, SQL (SQLite), C# (Unity) |
| Backend | Actix-Web, REST API, JSON, SQLite FTS5, Docker |
| Automation | Scrapers, Telegram bots, third-party API integrations, Selenium, Pytest, Allure |
| Tools | Git, CMake, Cargo, MinGW / MSVC, Linux, debugging and profiling |
| Practices | Automated testing (769 tests across the repos above), CI, code review, architecture docs |

## Currently looking for

A first job in backend, automation or tooling. Open to remote.