# docs.tigrcorn.com

Standalone ZDX documentation repository for [docs.tigrcorn.com](https://docs.tigrcorn.com).

## Commands

- `npmctl install`
- `npmctl check`
- `npmctl build`
- `npmctl docker:build`
- `npmctl dns:plan`
- `npmctl deploy:dry-run`

The local npm scripts mirror those npmctl lifecycle commands for CI and Docker workers.

## Deployment

This repo deploys as the `docs-tigrcorn-com` self-hosted Docker service. DNS is managed through Namecheap for the `tigrcorn.com` zone and is declared in `site.manifest.json`.
