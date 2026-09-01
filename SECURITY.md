# Security policy

## Reporting a vulnerability

**Do not open a public issue.**

Use GitHub's private vulnerability reporting on this repository:
**Security → Report a vulnerability**. That channel is private to the
maintainers and is the preferred route.

Please include what you would put in any bug report — which artefact, which
version, what you did — plus the impact you believe it has. A proof of
concept helps; a working exploit is not required and is not wanted in a
first message.

## Scope

Published artefacts and the code that produces them: the VS Code extensions
distributed via Open VSX, and the automation libraries distributed as
packages.

Out of scope: findings that depend on an attacker already controlling the
developer's machine, and reports produced by a scanner with no analysis of
whether the finding is reachable in practice.

## What to expect

An acknowledgement, an assessment of whether it is reachable, and a fix or a
statement of why not. Where a fix ships, the advisory will credit the
reporter unless asked otherwise.

## A note on what these tools read

This tooling parses workflow files and project metadata from disk. It does
not send them anywhere. If you find that untrue for any published version,
that is a vulnerability under this policy and worth reporting.
