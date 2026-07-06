# Changelog

All notable functional changes to the interview pipeline (agents, skills, question bank, workflow) are logged here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/); versions follow [SemVer](https://semver.org/) (MAJOR.MINOR.PATCH — MAJOR for workflow-breaking changes, MINOR for new capabilities, PATCH for fixes/tweaks).

Adding a new role, candidate, JD, or CV is not a functional change to the tool and is not logged here.

## [1.0.0] - 2026-07-06

Baseline version at the time versioning was introduced.

### Added
- PDF export for `questions.md` and `summary.md` via `.claude/scripts/md_to_pdf.py`
- Additional behavioral topics in `roles/_behavioral_question_bank.md`

### Changed
- Pinned models per agent in `.claude/agents/*.md`
