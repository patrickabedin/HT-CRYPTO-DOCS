# HT Crypto Docs — agent instructions

This repository is the **canonical Mintlify documentation** for all of Patrick's crypto-only systems.

## Hard rule

From 2026-09-13, document **everything** crypto here **in the same turn as the work**:

- grok-trading-desk
- SKYNET-SOL
- skynet-astra
- any other crypto-only matter

Do not satisfy a "document this" request by adding long-form markdown in those code repos. Write MDX here, register the page in `docs.json`, and push `main`.

## Information architecture

Parents are desk books (Grade B, Grade A, Hunter Unique, Hunter Tape, EARLY, Scalp, USELESS, Desk ops, Advisory, Research). Children are engines or workers. Everything you do for an engine is a section on that engine page. See `how-to-write.mdx`.

New engine / book / radio lane → new child page under the right parent.

## About this project

- Pages are MDX with YAML frontmatter
- Configuration lives in `docs.json`
- Mintlify publishes from the default branch (`main`)
- The GitHub repo is **public**

## Public-repo safety

Never commit secrets, tokens, API keys, chat IDs, private URLs, host IPs, SSH material, or env-file values.

## Style

- Active voice and second person
- One idea per sentence
- Sentence case for headings
- Bold UI elements; backticks for files, commands, and paths
- Label SHADOW / paper / research. Do not imply live fills
- Missing money stays unknown / `null`

## Do not document here

- Live enter / skip / hold / exit timing calls
- Iteration control logs (`STATUS.md`, QA dumps) — those stay in the code repo; durable conclusions still get a page here

## Finish

Land docs on `main`. Do not leave an open PR. Connect the Mintlify GitHub app if production is not updating: https://dashboard.mintlify.com/settings/organization/github-app
