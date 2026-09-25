# Contributing

Thank you for taking the time to look at this project.

## In plain words

You can report a bug, ask a question or suggest an idea by opening an issue. Pick the
form that fits. If you want to change code or text, open a pull request and fill in the
checklist. Please never post personal financial data. [`SECURITY.md`](SECURITY.md) says
why and what to do instead.

## Before you open an issue

- Search the open and closed issues first. Your point may already be there.
- Use the bug, question or idea form. Blank issues are turned off so that each issue
  has the facts needed to act on it.
- For a security problem, follow [`SECURITY.md`](SECURITY.md) and do not open a
  public issue with the details.

## Sending a change

1. Open an issue first for anything larger than a typo, so we can agree on the change
   before you spend time on it.
2. Fork the repo and make a branch from `main`.
3. Keep one idea per commit. Write the commit message in plain words: what changed and
   why.
4. Run the checks on your machine. Most repos have a `Makefile`, so this is usually:

   ```bash
   make setup
   make lint
   make test
   make check-docs
   make demo
   ```

5. Open a pull request and fill in the checklist. Mark a line "N/A" if the repo does not
   have that step.

CI runs the same checks. A pull request is merged only when they all pass.

## The house standard

Every repo follows the same house standard. The rules live in
[`STANDARD.md`](https://github.com/Iliya-Valizadeh/ds-project-standard/blob/main/STANDARD.md)
in the `ds-project-standard` repo. It covers the README order, the files each repo
needs and the checks CI runs. The rules that matter most for a change are these:

- Every number in the docs comes from a committed script. `CLAIMS.md` lists each number
  and the file it comes from.
- Text is written in plain words: short sentences, active voice, each term defined
  once in `docs/glossary.md`.
- A judgment call gets a short decision record in `docs/decisions/`.
- Known weak points go in `docs/whats_weak.md` instead of being left for a reader to find.
- `make demo` runs with no downloads and no API keys.

## Conduct

Be kind and stay on the topic of the project. I may lock or delete comments that attack
people or share someone else's private data.
