# LMM API documentation

This repository contains the Mintlify documentation site for [LMM API](https://api.lmm.best).

The site includes the complete upstream documentation set from `TokenNotIncluded/api.lmm.best/docs`, converted to MDX with Mintlify frontmatter and organized into navigation groups. The two OpenAPI contracts are stored in `docs/openapi/` and registered in `docs.json` for generated endpoint reference pages.

## Local preview

Install the Mintlify CLI and start the local preview:

```bash
npm install -g mint
mint dev
```

The preview runs at `http://localhost:3000`.

## Structure

- `introduction.mdx` is the site overview.
- `docs/` contains the migrated MDX pages and OpenAPI specifications.
- `docs.json` defines branding, OpenAPI sources, navigation, and footer links.
