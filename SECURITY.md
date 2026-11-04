# Security Policy

## Reporting a vulnerability

Please report security problems privately through
[GitHub's private vulnerability reporting](https://github.com/koedame/scoop-bucket/security/advisories/new).
Do not open a public issue for them.

We will reply within 7 days to confirm that we received your report, and keep you updated until it is fixed.

## Supported versions

Only the manifests on the `main` branch receive security fixes.

## What counts as a vulnerability

- A manifest in this repository that downloads or installs something other than what its own repository released (wrong URL, wrong hash, or a tampered manifest)
- A manifest script that runs unexpected commands on the machine that installs it

A vulnerability in an application that this bucket installs belongs to that application's own repository. For ChordSketch, use
[its reporting form](https://github.com/koedame/chordsketch/security/advisories/new).
