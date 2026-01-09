# 1. Use actions to create ADRs

Date: 2026-01-09

## Status

Accepted

## Context

We can leverage the adr-tools cli tool to create consistent ADRs with the same format and naming conventions. We can do this directly from github actions and then, if desired, the developer can just edit them within github.

## Decision

Use adr-tools for formatting. Add a github action to do this.

## Consequences

Bit of a different workflow, but there's no reason you can't copy existing ADRs or run adr-tools locally if desired.
