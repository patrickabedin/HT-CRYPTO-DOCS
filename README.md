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

Parents are desk books (Grade B, Grade A, Hunter Unique, Hunter Tape, EARLY, Scalp, USELESS, Desk ops, Advisory, Research). Children are engines or workers. See `how-to-write.mdx`.

```
index.mdx                         Home
policy/document-on-mintlify.mdx    Same-turn hard rule
how-to-write.mdx                  Book map + engine template
grok-trading-desk/                Desk books and engines
skynet-sol/                       SOL boundary + adapter
skynet-astra/                     Astra + shared-stack checkpoints
docs.json                         Tabs, groups, site settings
```
