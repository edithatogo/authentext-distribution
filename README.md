# Authentext distribution: compatibility snapshot

This repository preserves the previously generated **v3.2.0** installation
packages. Active development, tests, offline verification tools and future
package builds now belong to the single canonical repository:
[edithatogo/authentext](https://github.com/edithatogo/authentext).

The canonical repository has merged the v3.3 foundation. That does not upgrade
this snapshot, publish a v3.3 release, or prove a new registry listing. Existing
version tags and installation paths remain intact while migration is verified.

## Use the canonical source for new development

Follow the canonical
[installation and distribution guide](https://github.com/edithatogo/authentext/blob/main/docs/skill-distribution.md).
Host-specific packages are generated from that repository. Select a verified
release artifact or an explicitly pinned source revision; do not assume an
unpublished version tag exists.

Do not maintain a second copy of the skill here. Proposed editorial changes,
runtime fixes and tests belong in the canonical repository. Retain this
compatibility snapshot until clean-install, update and rollback checks have
been recorded for existing consumers. No automatic redirect or migration of
an already installed package is implied.

## Existing v3.2.0 installations

The following commands refer to the historical snapshot, not the new canonical
runtime tools.

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

## Historical package provenance

The generated skill body remains canonical Authentext **3.2.0** at source
commit `48dbab6b47d7cb06b8ccc6694432957c975bef94`. This documentation update does
not modify that body, its manifests, receipts or historical release tags.

These historical packages contain no apps, MCP servers, executable tools,
hooks, telemetry or network capability. See `distribution-receipt.json` for
generated package provenance and file digests.

- Canonical source: <https://github.com/edithatogo/authentext>
- License: MIT
- Snapshot version: `3.2.0`
