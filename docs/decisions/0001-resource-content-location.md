# ADR 0001: Resource content location

- Status: Accepted
- Date: 2026-07-29

## Context

EzoraVideo may publish standalone reference material that should remain
separate from the product landing page. The first such document is the English
article “How VS Code Extensions Should Be Built.”

## Decision

Standalone reference material will live below `/resources/`. This article uses
the stable, descriptive path:

`/resources/vscode-extension-design-principles/`

The document is stored as that directory's `index.html`, so its public URL does
not expose an implementation-specific filename.

## Consequences

- The root landing page is not added, replaced, linked, or otherwise modified.
- The resource can evolve independently of the product website.
- Future standalone material can follow the same `/resources/<slug>/` pattern.
