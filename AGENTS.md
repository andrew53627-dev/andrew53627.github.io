# Repository Guidelines

## Project Structure & Module Organization

This repository is currently a small, static website project. The root-level
[`README.md`](README.md) contains the club's public-facing content and project
overview. Keep future site files organized by purpose: place pages at the root
or in a `pages/` directory, reusable styles in `css/`, scripts in `js/`, and
images or other media in `assets/`. Do not commit generated files, local editor
settings, credentials, or large source media unless they are required for the
site.

## Build, Test, and Development Commands

There is no build system, package manager, or automated test suite yet. Review
Markdown changes locally in a Markdown preview before committing. When HTML is
added, open the relevant page in a browser and verify links, layout, and mobile
rendering. If tooling is introduced, document its commands in `README.md` and
add the corresponding configuration files to version control.

## Coding Style & Naming Conventions

Use UTF-8 text, LF line endings where possible, and two-space indentation for
HTML, CSS, and JavaScript. Prefer semantic HTML elements and accessible labels,
alt text, and heading order. Use lowercase, hyphen-separated filenames such as
`club-events.html` and `flight-safety.css`. Keep content clear for students and
families; avoid jargon unless it is explained. Format Markdown with one blank
line around headings and lists.

## Testing Guidelines

Manually check every edited page in a current desktop and narrow mobile browser
viewport. Confirm navigation works, images have meaningful `alt` text, and
external links use the intended URL. If JavaScript or a test framework is added,
place tests alongside the code or under `tests/` and name them after the feature,
for example `navigation.test.js`.

## Commit & Pull Request Guidelines

Use short, imperative commit subjects consistent with the existing history, for
example `Add club website README` or `Update meeting schedule`. Keep commits
focused on one change. Pull requests should explain the visitor-facing impact,
link any related issue, and include screenshots for visual changes. Before
requesting review, confirm the working tree is clean and the manual checks above
have passed.
