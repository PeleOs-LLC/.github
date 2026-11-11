# Security Policy

This is the organisation default for [PeleOs-LLC](https://github.com/PeleOs-LLC). It applies to every repository here that has no `SECURITY.md` of its own; if a repository has one, follow that file instead.

## Supported versions

Unless a repository says otherwise, the default branch (`main`) and the latest release. Fixes land there; there is no long-lived release branch to backport to.

## Reporting a vulnerability

Use GitHub's private vulnerability reporting on the repository the problem is in. The link pattern is `https://github.com/PeleOs-LLC/<repo>/security/advisories/new`, or open the repository's **Security** tab and choose **Report a vulnerability**. The report stays private between you and us until a fix ships.

Please do not open a public issue, pull request or discussion for a suspected vulnerability.

A useful report has the affected repository and version (or commit), steps to reproduce, what an attacker gets and under which conditions, and whether anyone else knows.

## What counts as a vulnerability

A vulnerability is a flaw that lets someone cross a boundary they should not: run code, read or change data they have no right to, escape a sandbox or path restriction, or leak a credential. A bug is anything else that misbehaves, such as a crash on your own input, wrong output or a slow path; open an ordinary issue for those. If you are unsure which one you have, report it privately and we will say.

## Coordinated disclosure

We handle the report inside the private advisory, so you see each status change and can comment on the fix. The advisory goes public when the fix ships, or 90 days after your report, whichever comes first. If a fix is close, either of us can ask for more time in the thread. You are credited in the advisory unless you would rather not be.

## Response timelines

- We acknowledge your report within 3 business days.
- We give you an assessment (accepted, needs more information or declined, with reasons) within 10 business days.
- We aim to ship a fix within 90 days of the report.

## Safe harbour

We will not pursue legal action against good-faith research that avoids privacy violations, data destruction and disruption of services, stops at a proof of concept, and keeps the details private until the advisory is published. PeleOs Technologies maintains this repository.
