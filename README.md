# Python GitHub Actions Matrix Demo

A compact learning project that runs a Python script in GitHub Actions across multiple supported Python versions.

## What this demonstrates

- Triggering continuous integration on pushes and pull requests
- Checking out repository code on a hosted Linux runner
- Testing a small Python program against a version matrix
- Keeping an automated workflow in `.github/workflows/`

## Workflow

The workflow runs `helloworld.py` with Python 3.10, 3.11, and 3.12. It is intentionally small so the automation is easy to inspect.

## Why it belongs in this portfolio

Reliable security and infrastructure work depends on repeatable automation. This repository is an early CI exercise and a foundation for future automated linting, security checks, and lab validation.
