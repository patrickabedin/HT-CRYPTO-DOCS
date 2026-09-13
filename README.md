# HT Crypto Docs

Canonical Mintlify documentation for **grok-trading-desk**, **SKYNET-SOL**, **skynet-astra**, and every other crypto-only system.

GitHub: https://github.com/patrickabedin/ht-crypto-docs/

From 13 September 2026, agents write new crypto docs **here**, not in the code repositories.

This repo is **public**. Never commit secrets, tokens, host IPs, or env-file values.

## Preview

```bash
npm i -g mint
mint dev
```

Open `http://localhost:3000`.

## Publish

Push `main`. Mintlify deploys from the default branch after the [GitHub app](https://dashboard.mintlify.com/settings/organization/github-app) is connected.

## Layout

```
index.mdx                      Home
policy/document-on-mintlify.mdx   The hard rule
how-to-write.mdx               How agents add a page
grok-trading-desk/             Desk pages
skynet-sol/                    SOL pages
skynet-astra/                  Astra pages
docs.json                      Navigation and site settings
```
