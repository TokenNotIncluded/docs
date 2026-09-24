# LMM API 文档

This repository contains the Mintlify documentation site for [LMM API](https://api.lmm.best).

The site is written for end users: how to sign up, create an API key, call the API, connect common clients, and understand model groups, ratios, and billing. Internal engineering and operations notes are kept under `drafts/` and are excluded from the build.

## Local preview

Install the Mintlify CLI and start the local preview:

```bash
npm install -g mint
mint dev
```

The preview runs at `http://localhost:3000`.

## Structure

- `introduction.mdx`, `quickstart.mdx`, `how-it-works.mdx` — getting started.
- `docs/` — user-facing guides (`api-keys`, `api-reference`, `clients`, `models`, `billing`, `account`, `referral`, `faq`, `troubleshooting`) plus `docs/legal/` and the OpenAPI specs.
- `docs/openapi/` — the two OpenAPI contracts registered in `docs.json` for generated API reference pages.
- `docs.json` — branding, colors, OpenAPI sources, navigation, and footer links.
- `drafts/` — internal notes and operations documentation, ignored by Mintlify.
