# Tenkr Plugin Marketplace

The catalogue of [Tenkr](https://tenkr.online) plugins for Claude Code.

## Add this marketplace

```
/plugin marketplace add TenkrAS/tenkr-plugin-marketplace
```

## Available plugins

| Plugin | Version | Description |
|--------|---------|-------------|
| **core-methodology** | 0.1.1 | Four reasoning disciplines for Claude Code — explore before committing, reason in the open, prove work is done, and find the root cause before fixing. |
| **knowledge-vault** | 0.1.0 | Per-project knowledge search for Claude Code — indexes your session transcripts, project memory, and your own documents into a local hybrid (vector + keyword) index, then answers natural-language questions with citations. Optional OCR for PDFs, Office docs, and images. |
| **plan-and-build** | 0.1.0 | Researches and plans complex work, then executes it with an evidence-gated builder-and-validator team — pre-plan, plan-with-team, and build, plus a tech-stack doctor. |

## Install a plugin

```
/plugin install core-methodology@tenkr-plugin-marketplace
```

Each plugin lives in its own repository under the [`TenkrAS`](https://github.com/TenkrAS)
organisation; this marketplace only holds the catalogue manifest
(`.claude-plugin/marketplace.json`).
