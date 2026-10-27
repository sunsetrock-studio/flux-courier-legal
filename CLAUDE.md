# CLAUDE.md

This repo is the **SunsetRock Studio LLC** company website, served at `https://www.sunsetrockstudio.com` by GitHub Pages (branch `master`, root, custom domain in `CNAME`). Pushing to `master` publishes within a minute or two.

## What's here

- `index.html`: the studio home page.
- `legal/<app>/privacy-policy/` and `legal/<app>/terms-of-service/`: per-app legal pages. Folia's paywall and the App Store listings link to these exact URLs, so never rename or move a page. Each app repo keeps a source copy of its own pages too; keep the wording in both copies the same.
- Pages name **SunsetRock Studio LLC** as publisher and `support@sunsetrockstudio.com` as contact. Never use John's personal name or personal email.
- Change a page's "Last updated" date whenever its wording changes.

## Where things live

- **GitHub:** `sunsetrock-studio/flux-courier-legal`, public, in the `sunsetrock-studio` organization (moved from `jvivenzio814` on 2026-10-26).
- **Domain and DNS:** Squarespace Domains, where John edits records himself. `@` has four A records to GitHub Pages (`185.199.108.153`, `.109.153`, `.110.153`, `.111.153`), and `www` is a CNAME to `sunsetrock-studio.github.io`. The bare domain redirects to the same path on www. Before 2026-10-26, `@` pointed at Google forwarding (`216.239.3x.21`), which dropped paths and had no HTTPS.
- **Email:** Google Workspace. When editing DNS, never touch the MX, SPF, DKIM (`google._domainkey`), `google-site-verification`, or `_domainconnect` records.
- **Repo name:** "flux-courier-legal" is historical. It began as FLUX's legal page and now serves the whole studio. Renaming it is optional; GitHub would redirect, but the Pages setup would need a check afterward.
