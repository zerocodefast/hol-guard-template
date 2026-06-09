# HOL Guard Template

[![HOL Guard](https://img.shields.io/badge/HOL%20Guard-secure%20AI%20agents-00a67e)](https://hol.org/guard)
[![CI](https://img.shields.io/badge/CI-HOL%20Guard%20scan%20gate-00a67e)](.github/workflows/hol-guard.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue)](LICENSE)

A pre-configured secure plugin starter that passes HOL Guard scanning with 80+ points out of the box.

## What you get

- `plugin.json` — valid manifest with all required fields
- `SECURITY.md` — security policy template
- `SKILL.md` — skill documentation template
- `.github/workflows/hol-guard.yml` — CI gate that fails on score < 80 or high/critical findings
- `.github/dependabot.yml` — automated dependency updates

## Quick start

1. Click **Use this template** → Create new repository
2. Replace `my-safe-plugin` with your plugin ID in `plugin.json`
3. Write your skill in `skills/`
4. Push — CI runs automatically on every PR

## HOL Guard

Open-source security scanner for AI coding agents. Built by Hashgraph Online.

- [GitHub](https://github.com/hashgraph-online/hol-guard)
- [Website](https://hol.org/guard)
- [PyPI](https://pypi.org/project/plugin-scanner/)
- [Examples](https://github.com/zerocodefast/hol-guard-examples)
- [Examples](https://github.com/zerocodefast/hol-guard-examples)
