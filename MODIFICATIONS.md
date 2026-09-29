# Modifications

This file is the prominent notice that AGPL-3.0 §5(a) requires. It records every modification this
fork makes to upstream Whatomate, newest first, each with its date. The upstream base is named in
`UPSTREAM_BASE.md`. Upstream's copyright and licence notices are unchanged.

## 2026-09-29 — fork established; no source modified

- Added `UPSTREAM_BASE.md`, which pins the upstream commit this fork is based on.
- Added this file.
- **No upstream source file has been changed.** At this entry the fork's behaviour is identical to
  upstream `23bee8cd2341f9363901a0c1ef8db6aff8f08774`.

### Planned modifications (not yet made)

This fork exists so that Whatomate can operate under Aakashvani's governance. The integration
contract names eleven items, F-1 to F-11, that this fork is expected to provide. Examples are an
organisation id on outbound events, a stable delivery-status event, idempotent sends, governed
campaign creation, governed chatbot mode, calling events, and a build-identity endpoint
(`GET /api/aakashvani/build`). **None of them is implemented at this entry.** Each one will be
recorded here, dated, when it lands.
