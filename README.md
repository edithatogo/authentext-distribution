# Authentext distribution

Generated, versioned distribution packages for
[Authentext](https://github.com/edithatogo/authentext), a portable Agent Skill
for reviewing and rewriting prose naturally while preserving meaning and
technical literals.

This repository is generated from canonical Authentext version **3.2.0** at
source commit `48dbab6b47d7cb06b8ccc6694432957c975bef94`. Do not edit the skill
body here; changes belong in the canonical repository.

## Install

### GitHub CLI / Copilot and supported agents

```sh
gh skill install edithatogo/authentext-distribution authentext
```

### Gemini CLI extension

```sh
gemini extensions install https://github.com/edithatogo/authentext-distribution --ref v3.2.0
```

### Claude Code marketplace

```sh
claude plugin marketplace add edithatogo/authentext-distribution
claude plugin install authentext@authentext-marketplace
```

The packages contain no apps, MCP servers, executable tools, hooks, telemetry,
or network capability. See `distribution-receipt.json` for generated package
provenance and file digests.

## Canonical source

- Source: <https://github.com/edithatogo/authentext>
- License: MIT
- Release: `3.2.0`
