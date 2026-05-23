# skylinetrailcomputing.com

Public landing site for [Skyline Trail Computing
LLC](https://skylinetrailcomputing.com) — an independent software
studio based in Colorado, USA.

## What this is

Single-page static site at `skylinetrailcomputing.com`. Mirrors the
[`veganalysis-web`](https://github.com/skylinetrailcomputing/veganalysis-web)
pattern (public repo, GitHub Pages, custom domain via Cloudflare
DNS-only) — chosen for the same per-app-portability reason laid out
in `claude-workspace-2026/knowledge/aws/organization.md`, and because
Skyline's umbrella site is naturally public-facing.

## Contents

- `index.html` — the landing page. Plain HTML + inline CSS, no build
  step.
- `CNAME` — GitHub Pages custom-domain marker for
  `skylinetrailcomputing.com`.

## Deployment

Pushes to `main` auto-deploy via GitHub Pages. DNS for the apex
points at GitHub Pages IPs (Cloudflare DNS-only, gray cloud — *not*
proxied; the orange cloud interferes with Pages' Let's Encrypt
issuance).

## Deferred / follow-ups

Iterate when Skyline needs a real marketing surface — post-Veganalysis
F&F at earliest, or when a second app under the umbrella warrants
portfolio pages. Today's content is the same placeholder that
satisfied Google Play Console's verification field.

## Cross-references

- [`skylinetrailcomputing/veganalysis-web`](https://github.com/skylinetrailcomputing/veganalysis-web)
  — sibling per-app landing site, same Pages pattern.
- [`skylinetrailcomputing/veganalysis-legal`](https://github.com/skylinetrailcomputing/veganalysis-legal)
  — second sibling, same Pages pattern.
