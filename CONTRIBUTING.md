# Contributing

The most useful contribution is a good report. Most source repositories here
are private, so pull requests are usually not the route — a precise issue is.

See [SUPPORT.md](SUPPORT.md) for where things go and what to include.

## If a repository is public

Normal rules: an issue before a large change, one concern per pull request,
and a description of what you observed rather than only what you changed.

Commit messages explain **why**. The diff already shows what.

## What is likely to be declined

- Reformatting, renaming, or dependency bumps with no stated problem
- Changes that add a build-time dependency on a specific machine's setup
- New configuration for something that could be derived

## On sample files

Never attach a real customer workflow, project, or path — to an issue, a pull
request, or a test fixture. Reduce it to the smallest synthetic case that
still shows the behaviour. If it cannot be reduced, describe it instead.
