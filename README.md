# SiegWEBv2

A developer-friendly desktop browser for developing responsive web apps —
device lab, DevTools, screenshots, suites — plus an AI Dev Assistant
(OmniRoute), Cloudflare Quick Tunnel sharing, a Security Checker
(ZAP/Semgrep/Trivy), and a picture-in-picture media player.

## Origin

SiegWEBv2 is a **modified derivative of Responsively App**
(https://github.com/responsively-org/responsively-app), based on upstream
`main` @ `f3be9713` (2.0.0-beta.0 era), modified 2026-09-11 by Clark M. Pateño.
See `compliance/PROVENANCE.md` and `compliance/MODIFICATIONS.md`. Upstream
contributors are listed in `.all-contributorsrc` / `MAINTAINERS.md`.

## Modifications (highlights)

- OmniRoute Dev Assistant (`/sieg` palette, tools, memory, file generation)
- Cloudflare Quick Tunnel integration (managed tunnel + status toast)
- Security Checker (ZAP/Semgrep/Trivy, redacted reports, JSON/HTML export)
- MediaToast PiP, DeveloperDialog, Sieg branding/assets, approval chime
- Toolbar/StatusBar/Previewer/store rework hosting the above

## Build & test

```bash
cd desktop-app
yarn install
yarn run typecheck
yarn lint
yarn test
yarn run build
yarn run package   # electron-builder installers (never publish upstream)
```

Details: `compliance/BUILD_REPRODUCTION.md`.

## License

GNU Affero General Public License v3.0 — see `LICENSE`. The whole distributed
work (retained + modified + new code) is conveyed under AGPL-3.0. Third-party
scaffold material and its notices are preserved (see
`compliance/LICENSE_SCOPE.md`).

## Upstream Attribution

Responsively App © its contributors,
https://github.com/responsively-org/responsively-app, AGPL-3.0.
SiegWEBv2 is not an official Responsively release and is not endorsed by them.

## Source

SOURCE REPOSITORY PENDING CONFIGURATION — no public source location is
configured yet (see `compliance/SOURCE_AVAILABILITY.md`). Do not treat any
other URL as the SiegWEBv2 source until this file says otherwise.

## Third-Party Software

See `compliance/THIRD_PARTY_NOTICES.md` and `compliance/SBOM/sbom.json`
(dual-license elections, cloudflared/Apache-2.0 terms, font/icon notices).

## Trademark

"Responsively" / "Responsively App" branding belongs to its respective owners.
SiegWEBv2 uses independent product identity (`SiegWEBv2`, `com.sieg.siegwebv2`,
`siegweb://`). See `compliance/TRADEMARK_AND_BRANDING.md`.
