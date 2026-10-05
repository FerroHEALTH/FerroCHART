---
name: repo-moved-to-ferrohealth
description: "2026-10-01 the repo moved to FerroHEALTH/FerroCHART; image ghcr.io/ferrohealth/ferrochart (lowercase literal); releases up to v0.1.0 stay signed as rubentalstra/FerroCHART"
metadata:
  node_type: memory
  type: project
---

<!-- SPDX-FileCopyrightText: Cadasto B.V. -->
<!-- SPDX-License-Identifier: BUSL-1.1 -->

The repository was transferred from `rubentalstra/FerroCHART` to the
`FerroHEALTH` organization on 2026-10-01 (#224), beside FerroEHR and FerroFED.

- The image is `ghcr.io/ferrohealth/ferrochart`, spelled as a literal:
  `github.repository_owner` is `FerroHEALTH`, and an OCI reference must be
  lowercase. Every tagged manifest up to v0.1.0 was copied there by digest.
- The transfer cleared the Pages custom domain; it was set again the same day.
  A future transfer or Pages change checks `ferrochart.eu` answers afterwards.
- Still under the user account (do not rewrite): FerroTERM and
  `ghcr.io/rubentalstra/ferroterm`, FerroBRIDGE, the FerroEHR 4.1.1 images the
  demo profile pulls, the SonarQube Cloud organization and key
  `rubentalstra_FerroCHART`, and personal handles (CODEOWNERS, FUNDING,
  MAINTAINERS).
- Releases up to v0.1.0 were signed as `rubentalstra/FerroCHART`; SECURITY.md
  and `docs/release.md` say so beside the verify commands.

**Why:** the owner moved the product line under one organization.
**How to apply:** new links name `FerroHEALTH/FerroCHART`; FerroEHR links name
`FerroHEALTH/FerroEHR`. The roadmap board is
<https://github.com/orgs/FerroHEALTH/projects/4>, copied from FerroEHR's
([[sibling-projects]]).
