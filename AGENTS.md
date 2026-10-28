# Repository Guidelines

## Project Structure & Module Organization

This repository develops short Siemens NX lessons for an 11-year-old learner using **NX 2212 with classic Sketch**. It contains documentation, a lesson template, and 24 lesson drafts; finished lessons and NX models are not yet available.

NX используем с включённым русским языком интерфейса. В инструкциях и проверках ориентируемся на русские названия команд, меню и диалогов NX 2212; непроверенные названия явно помечаем.

- `README.md`: project overview and current stage.
- `docs/`: original brief, requirements, and the 24-topic course plan. Preserve `docs/project-brief-v1.0.md` as the unchanged source brief.
- `lessons/lesson-template.md`: starting point for each lesson.
- `lessons/NN-short-name/lesson.md`: lesson drafts, with supporting `drawings/`, `images/`, and `models/` directories as needed. `lessons/README.md` links to every lesson.

Use course numbers, not pilot-development order. Fill existing drafts one at a time; create asset directories when materials exist. The initial pilots are lessons **01, 02, and 06**.

## Build, Test, and Development Commands

There is no build system, dependency installation, development server, or automated test suite. Work directly in Markdown and validate native models in NX.

- `Get-Content docs/requirements.md`: review lesson acceptance criteria before editing.
- `Get-Content lessons/01-free-sketch/lesson.md`: review the first draft before filling its sections. Do not overwrite existing lessons with the template.
- `git diff --check`: check changes for whitespace errors.
- `git diff --stat` and `git diff`: review scope and content before committing.

## Writing Style & Naming Conventions

Write learner-facing materials and project documentation in Russian. Follow existing Markdown: descriptive headings, blank lines between blocks, hyphenated bullets, numbered steps, and relative links. Use backticks for paths and command names.

Use two-digit lesson numbers and lowercase, hyphen-separated directory names. Preserve the template sections and explicitly mark missing assets or unverified behavior. No formatter or linter is configured.

## Testing Guidelines

Check links, dimensions, asset references, and consistency with the requirements. Verify command names and model behavior in NX 2212 with classic Sketch; opening a document does not validate an NX model.

Record documentation checks, model checks, and learner trials separately in each lesson. Measure time to the visible result and total duration: target a result within ten minutes and a complete lesson within fifteen. Keep one new idea per lesson. No automated coverage threshold applies.

## Commit & Pull Request Guidelines

The single existing commit uses a short Russian action phrase: `Создать основу учебного проекта Siemens NX`. Follow that style with focused, descriptive commits.

In pull requests, describe affected lessons, the learning outcome, completed checks, and outstanding materials. Link related issues when applicable; include screenshots for geometry or visual changes. Never describe untested models as ready for teaching.
