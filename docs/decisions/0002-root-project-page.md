# ADR 0002: Root project page

- Status: Accepted
- Date: 2026-07-29
- Supersedes: The root-page consequence in ADR 0001

## Context

EzoraVideo now has an approved project description that should be visible both
at the beginning of the GitHub repository and on the public website.

## Decision

The project description is stored at the repository root in `README.md`. A
corresponding static landing page is published from the repository root as
`index.html`.

Standalone reference material continues to live below `/resources/` as decided
in ADR 0001.

## Consequences

- GitHub displays the project identity and positioning on the repository page.
- The website root introduces EzoraVideo and links back to its source.
- Existing `/resources/<slug>/` URLs remain unchanged.
