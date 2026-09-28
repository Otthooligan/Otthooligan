# DAW Translation Tool

**Stack:** React, TypeScript, Node.js, Express, Vitest.

## Purpose

Translate supported DAW project data through a common representation while making conversion limitations visible.

## Architecture

A user selects a project file and target format. The React interface uploads the file to an Express API, requests translation, then presents reports and downloadable output.

The processing pipeline separates parsing, routing, automation sampling, optional gain adjustment, and emission. A canonical session model represents timing, tracks, assets, events, automation, plugins, and routing.

## Engineering details

- Explicit source/target validation rather than silently guessing the requested route.
- Local artifact storage and a processing ledger.
- Output re-parsing and regression coverage for timing, deterministic mappings, and unsupported cases.
- Transformation hashes and checksum-bound validation evidence.
- Separate outcomes for preserved, approximated, unsupported, and skipped information.

## Current boundaries

Native host acceptance remains under validation. Structural checks do not establish musical equivalence. Browser preview reports and animated progress are not proof of a completed conversion. The active service is a development implementation, not an established multi-user production service.

This summary describes the project without releasing private code or claiming sole authorship.

[Back to portfolio](../README.md)

