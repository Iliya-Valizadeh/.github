## What this changes

<!-- One or two plain sentences: what changed and why. Link the issue, e.g. "Closes #12". -->

## How I checked it

<!-- The commands you ran and what you saw. If a number changed, give the old value and the new one. -->

## Checklist

Mark a line "N/A" if the repo does not have that step. The rules behind each line are in
[`STANDARD.md`](https://github.com/Iliya-Valizadeh/ds-project-standard/blob/main/STANDARD.md).

Code

- [ ] `make lint` passes (ruff, ruff format, mypy).
- [ ] `make test` passes, including data tests. New repos keep coverage of `src/` at 80% or more. <!-- not-a-claim -->
- [ ] `make demo` runs with no downloads and no API keys.
- [ ] If a result changed, `make all` from a clean clone gives the new numbers.

Docs

- [ ] `make check-docs` passes. It runs the claims, readability, AI-writing signs, link
      and README section checks.
- [ ] Every new or changed number is in `CLAIMS.md`, with the file it comes from.
- [ ] A new evaluation has its plan in `docs/eval_plan.md`, committed before the results.
- [ ] A judgment call has a decision record in `docs/decisions/`.
- [ ] A new weak point is written down in `docs/whats_weak.md`.
- [ ] `CHANGELOG.md` has a line for this change.

Safety

- [ ] The diff has no secrets, API keys, raw data files or personal financial data.
