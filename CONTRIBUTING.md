# Contributing

Most CPMForge source repositories are private, so the usual route — fork,
branch, pull request — is closed for most projects. That does not leave
nothing. It changes what is valuable.

This file is the organisation-wide default, so it applies to every CPMForge
repository that does not override it.

## What is actually worth sending

**A precise report.** The single most useful thing. What you did, what you
expected, what happened instead. Version and host included. See
[SUPPORT.md](SUPPORT.md).

**A reduced case.** A twenty-line workflow that reproduces a parsing bug is
worth more than a description of a two-hundred-file project, and far more
than the project itself. Reducing it is the work; doing that work is the
contribution.

**A shape we have not seen.** These tools are built against a handful of real
projects, so the gaps are wherever reality differs from those. A construct
that renders wrongly, an activity nobody mapped, a `.xaml` shape that breaks
an assumption — that is evidence we cannot generate ourselves.

**A correction.** Documentation that is wrong, out of date, or describes
something that no longer behaves that way. Including in this repository.

**Naming and wording.** What a command should be called, what a message
should say, which term is confusing. Cheap to change early and expensive
later, and outside eyes are better at it than the author's.

**Disagreement with a decision**, where you can say what it costs you. That
is more useful than a feature request, because it can be weighed.

## What is likely to be declined

- Reformatting, renaming, or dependency bumps with no stated problem
- Changes that add a build-time dependency on one machine's setup
- New configuration for something that could be derived
- Feature requests with no account of the situation that prompted them

## Never send customer material

No real customer workflow, project name, path, credential or data — not in an
issue, a discussion, a pull request or a test fixture. Reduce it to the
smallest synthetic case that still shows the behaviour; if it cannot be
reduced, describe it in words.

This is not a formality. These tools are used on client work, and a project
name in a public issue is a leak that no later edit undoes.

## If a repository is public

Normal rules apply: raise an issue before a large change, one concern per
pull request, and describe what you observed rather than only what you
changed. Commit messages explain **why** — the diff already shows what.

## Licensing of what you send

Code and documentation are licensed differently here, and contributions
follow the same split:

| What you send | Offered under |
| --- | --- |
| Code — a patch, a snippet, a reduced repro | [Apache 2.0](LICENSE) |
| Prose — issue text, discussion, documentation | [CC BY 4.0](LICENSE-docs) |

For code this is what Apache-2.0 §5 already provides; it is stated here so it
also covers material sent *about* a project rather than into it. If you
cannot offer something on those terms, say so in the message — that is a
reasonable thing to say, and better than sending it silently.
