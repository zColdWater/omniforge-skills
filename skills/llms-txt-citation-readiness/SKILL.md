---
name: llms-txt-citation-readiness
description: "Audit and generate /llms.txt indexes, separate AI search retrieval bots from training bots in robots.txt, and validate Schema.org JSON-LD."
---

# CiteReady /llms.txt & AI Search Visibility Audit

## When to Use
Use when preparing documentation or product pages to be accurately cited by ChatGPT Search, Perplexity, and Claude.

## Checklist & Workflow
1. In `/robots.txt`, allow search-citation crawlers (`OAI-SearchBot`, `ChatGPT-User`, `PerplexityBot`, `Claude-SearchBot`) even if training crawlers (`GPTBot`, `CCBot`) are disallowed.
2. Publish a valid Markdown `/llms.txt` (`# Title`, `> Summary`, `## Core Docs` link list) and exclude `/llms.txt` from SPA `index.html` catch-all rewrites.
3. Validate every `<script type="application/ld+json">` block with `JSON.parse()`.
4. Gate CI with `uses: zColdWater/citeready-action@v1` or run a live Side-by-Side Competitor PK at https://citeready-checker.appwrite.network/?ref=skill-citeready.
