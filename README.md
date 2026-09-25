# .github

Default issue forms, pull request template and contributor guides for Iliya Valizadeh's public repos.

## In plain words

GitHub reads this repo when one of my other repos does not have its own copy of these
files. So every repo gets the same forms for bugs, questions and ideas. It also gets the
same pull request checklist and the same rules for reporting a security problem. A repo
that has its own copy of a file uses that copy instead.

## What is here

| File | What it does |
|---|---|
| [`.github/ISSUE_TEMPLATE/bug.yml`](.github/ISSUE_TEMPLATE/bug.yml) | Form for reporting something that does not work |
| [`.github/ISSUE_TEMPLATE/question.yml`](.github/ISSUE_TEMPLATE/question.yml) | Form for asking how something works or why it was built that way |
| [`.github/ISSUE_TEMPLATE/idea.yml`](.github/ISSUE_TEMPLATE/idea.yml) | Form for suggesting a change or a new feature |
| [`.github/ISSUE_TEMPLATE/config.yml`](.github/ISSUE_TEMPLATE/config.yml) | Turns off blank issues and links to the security policy |
| [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md) | Checklist that matches the checks each repo runs in CI |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | How to report a problem or send a change |
| [`SECURITY.md`](SECURITY.md) | How to report a security problem, and what never to post |
| [`.github/workflows/ci.yml`](.github/workflows/ci.yml) | Runs the writing and link checks on the files in this repo |

## Where the rules come from

The checklist and the contributor guide follow the house standard in the
[`ds-project-standard`](https://github.com/Iliya-Valizadeh/ds-project-standard) repo.
Its `STANDARD.md` file lists every rule and why it exists. When a rule changes there,
the checklist here should change with it.

## No license here

This repo has no license file on purpose. GitHub does not use a default license from a
`.github` repo, so each repo carries its own license.
