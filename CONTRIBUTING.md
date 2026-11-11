# Contributing to HexAI repositories

This guide applies to every repository in `HexAI-inc` that does not have its own. The full version, with the reasons behind each rule, is in the team handbook.

## The short version

1. **Start from an issue.** If there is no issue for the work, create one first.
2. **Branch from `main`.** Name the branch `<type>/<issue-number>-<short-description>`, for example `feat/12-past-question-search`. Types are `feat`, `fix`, `docs` and `chore`.
3. **Commit in small steps** with clear messages in the imperative, such as "Add past question search".
4. **Open a pull request against `main`.** Fill in the template and write `Closes #<issue-number>` in the description.
5. **Get one approval** from someone other than yourself. Changes to architecture, the data model, authentication or deployment need the CTO.
6. **Squash and merge**, then delete the branch.
7. **Move the card** on the project board as the work moves: In Progress when you branch, In Review when the PR opens, Staging when it merges.

## Before you ask for a review

- The code runs locally and the tests pass.
- New behaviour has a test.
- Documentation that your change makes wrong is updated.
- The PR contains no secrets: no `.env` files, API keys or database URLs with passwords.

## Reporting a security problem

Do not open a public issue. Contact the CTO directly.
