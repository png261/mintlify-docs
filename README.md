# appleai.codes Docs

This repo contains a Mintlify documentation site for CLI tool setup guides. The content is organized around one OpenAI-compatible endpoint and tool-specific configuration pages.

## Local development

Install the Mintlify CLI if you do not already have it:

```bash
npm i -g mint
```

Start the local preview server from the repo root:

```bash
mint dev
```

Run a link check before you ship content changes:

```bash
mint broken-links
```

## Main content areas

- `index.mdx` for the landing page
- `getting-started/` for shared configuration
- `cli-tools/` for tool-specific setup guides
- `reference/` for model paths, troubleshooting, and notices
