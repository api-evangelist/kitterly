# Kitterly

Kitterly, Inc. was a direct-to-consumer craft commerce startup that sold knitting and crochet kits, yarn, needles and notions online, and ran a monthly Kit Club subscription that shipped members a pattern plus the yarn required to complete it. Kitterly was backed by 500 Global (500 Startups) along with Manatt Ventures and the Jordan x 2080 accelerator.

The company was later consolidated under the **Cotton Cuts** brand — a Chesterfield, Missouri based quilting fabric shop selling designer die-cut and pre-cut fabric, threads, patterns and notions, plus quilting memberships and the Puzzle Mystery Quilt program, serving roughly 4,000 members across more than 15 countries. `kitterly.com` now redirects to `cottoncuts.com`.

## API surface

**None.** Kitterly / Cotton Cuts publishes no public API, developer portal, API reference, SDKs, CLI, webhooks or machine-readable specifications. Every `/.well-known/` discovery path probed returns 404 (see `well-known/kitterly-well-known.yml`). This repo is an identity profile, not an API profile.

## Artifacts

| Artifact | File |
|---|---|
| APIs.json profile | `apis.yml` |
| Domain security (probed) | `security/kitterly-domain-security.yml` |
| Well-known probe record | `well-known/kitterly-well-known.yml` |
| llms.txt (generated) | `llms/kitterly-llms.txt` |

Backed by: 500-global — https://www.cottoncuts.com/
