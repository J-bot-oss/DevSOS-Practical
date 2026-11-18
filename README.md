# DevSOS Practical

DevSOS is a Software Project Management practical to plan and build a small guided troubleshooting website for beginner computing students. The site will explain selected development-environment errors in simple language, suggest steps to try, and explain how to check the result.

## Assessment period

**18 November to 1 December 2026**, inclusive: **14 calendar days**.

These are the planned assessment dates recorded in the Project Charter, not evidence that any scheduled activity has been completed.

## Current repository contents

This initial repository contains project documentation and a folder structure. Website source code and development evidence have not been added. The existing charter is retained locally because it contains personal information. Stakeholder confirmation and acceptance remain pending as recorded in that draft.

## Scope

- Three pages: Home, Troubleshooting Guides, and About & Resources.
- Four beginner-focused troubleshooting guides covering selected Git, Python and Node.js problems.
- A simple guide/category selector, navigation links and responsive layouts.
- Basic functional and usability testing, a demonstrable website, documentation and handover.

The project excludes AI diagnosis, automatic detection of computer problems, user accounts, logins, databases, backend services, execution of terminal commands through the website, private student records, a mobile application, a paid custom domain and a large troubleshooting library.

The planned implementation uses static HTML, CSS and JavaScript. A local demonstration or suitable free static hosting service may be used; no deployment is claimed here.

## Objectives

1. By Day 10, develop the three-page website.
2. By Day 10, write and review four guides, each explaining the error, a possible cause, troubleshooting steps and a verification check.
3. By Day 12, test internal links, guide/category navigation and layouts at mobile, tablet and desktop widths, and record results and fixes.
4. By Day 14, collect feedback from at least two available volunteer learners, obtain the stakeholder representative's acceptance decision, and hand over the website files and a short guide. Volunteer availability and the representative's identity must first be confirmed.

These are planned targets, not completed activities or approvals.

## Project structure

```text
website/          Website source when actual implementation is ready
docs/             Project documentation suitable for the repository
docs/local/       Local document copies; excluded from Git
evidence/         Guidance for handling real assessment evidence
```

The original charter remains at its existing location in the local project root. A byte-for-byte copy is kept under `docs/local/` for organization. Both are excluded from Git.

## Working with this repository

Add website code only when it exists and has been reviewed. Record actual activity dates and results when the work takes place. Do not create retrospective evidence, signatures, approvals or stakeholder statements.

Before each commit, inspect `git status --short`, `git diff --cached --name-only` and `git diff --cached`. Use explicit file paths when staging. The ignore rules help prevent accidental additions but do not inspect file contents or remove information already committed. Never use `git add -f` to bypass these rules for private material.

This repository is intended to remain **private**. Do not add credentials, personal identifiers, signatures, private correspondence, unredacted screenshots or confidential assessment evidence.
