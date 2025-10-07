# attestation-demo

This repository demonstrates GitHub Actions build attestations using a .NET class library.

## Overview
This demo showcases how to:
- Build a .NET class library
- Create build attestations for artifacts
- Validate attestations using GitHub CLI

## Source
Based on Demo 14 from [github-intro-to-actions-demos](https://github.com/djredman99/github-intro-to-actions-demos)

## Workflow
The `14-build-attestations.yml` workflow demonstrates:
1. Building a .NET 8.0 class library
2. Creating an artifact with build attestations
3. Validating the attestation