# EMMA Public Preview

This repository is a public preview of the EMMA project prepared for paper review.

It is intentionally not a full reproduction package yet. The preview exposes the project
layout, benchmark-facing package boundaries, configuration schema, and release policy,
while withholding the unpublished core implementation until the paper is accepted.

## What is here
- Project structure and high-level documentation
- Benchmark entry points as placeholders
- Public-facing notes for reviewers

## Repository layout
- `emma/`: package boundary and benchmark shells
- `docs/`: public preview policy and release notes
- `CONTRIBUTING.md`: contribution guidance for the preview
- `SECURITY.md`: reporting policy for accidental exposure
- `CITATION.cff`: citation placeholder for the released work

## What is intentionally withheld
- Core implementation details
- Energy/potential scoring internals and task-family parameterization
- Private seed memories and benchmark-private artifacts
- Local experiment logs, migrated runs, and hidden heuristics
- Any material needed to directly reproduce the unpublished core behavior

## Release policy
The full implementation will be released after acceptance.
Until then, this repository stays as a public preview only and should be cited as a
placeholder code link rather than a complete artifact.

## Current status
- Public link: available for review metadata and project inspection.
- Reproducibility: deferred until the post-acceptance release.
- Security posture: no secrets, private seeds, local paths, or internal benchmark artifacts are bundled.

## Versioning
This preview is versioned as a staging artifact. The full repository will be expanded after acceptance.
