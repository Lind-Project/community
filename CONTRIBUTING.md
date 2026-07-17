# Contributing to Lind

Thanks for your interest in contributing to Lind! Lind is a community-driven,
open-source project, and it grows through the people who use it, file issues,
improve the docs, and send patches. Contributions of every size are welcome.

This guide applies across **all repositories in the [Lind-Project][org]
organization**. It covers the conventions and expectations that are common to
every repo. Anything specific to a single repository — how to build it, run its
tests, or lay out its code — lives in that repository's own `CONTRIBUTING.md` 
and docs.

## Ways to Contribute

There are many ways to contribute, depending on your interests:

- **Isolation Backends** — Work on improving Wasmtime or build the MPK runtime.
- **Lind as a Shared Library** — Test and harden this support for real use in
  scientific library isolation.
- **Performance** — Analyze and improve the performance of the existing system.
- **Tooling & CI** — Improve the build system, Docker images, benchmarks, and CI
  pipelines.
- **Documentation** — Improve guides, internal design docs, and getting-started
  material.

New to the project? Look for issues labeled **`good first issue`** in any of our
repositories, and feel free to introduce yourself on the community channels
below.

## Getting Started

1. Find the repository you want to work on in the
   [Lind-Project organization][org].
2. Read that repository's `README` for build and test instructions — these are
   maintained per repo and are the source of truth for local setup.
3. If you are unsure where a change belongs or want feedback on an idea before
   investing time, open an issue or raise it on one of the
   [communication channels](#communication) below.

## Submitting Changes

We use a standard GitHub fork-and-pull-request workflow:

1. **Fork** the repository and create a topic branch from the default branch.
2. **Make your change.** Keep commits focused and write clear commit messages.
   Follow the coding conventions and testing expectations of the repository you
   are contributing to — code should be sufficiently tested and must not break
   the build.
3. **Open a pull request** against the upstream repository. Describe what the
   change does and why, and link any related issues.
4. **Review.** Every pull request must be approved by at least one maintainer who
   is not its author before it can be merged. Security-sensitive or substantial
   architectural changes require approval from at least two maintainers. See
   [GOVERNANCE.md](GOVERNANCE.md) for the full decision-making process.
5. **Merge.** Once a PR has the required approvals, a maintainer merges it. As the
   author, please keep your branch up to date and merge-ready.

### Licensing

By contributing, you agree that your contributions will be licensed under the
same license as the repository you are contributing to (see each repository's
`LICENSE` file).

## Communication

- **GitHub Issues & Discussions** — Per-repository questions, bugs, and design
  discussion.
- **Slack** — Day-to-day discussion and questions.
- **Community calls** — Regular monthly meetings open to users, contributors, and maintainers.

Maintainers and the areas they focus on are listed in
[MAINTAINER.md](MAINTAINER.md).

## Governance

Lind uses a flattened maintainer model, and project ownership is collective. For
how decisions are made, how PRs are approved, and how contributors become
maintainers, see [GOVERNANCE.md](GOVERNANCE.md) and [MAINTAINER.md](MAINTAINER.md).

## Code of Conduct

Participation in the Lind community is governed by our
[Code of Conduct](CODE_OF_CONDUCT.md).
By participating, you agree to uphold it.

[org]: https://github.com/Lind-Project
