# OmniForge Agent Skills — Security, Email DNS, Domain & /llms.txt Skills

[![GitHub Release](https://img.shields.io/badge/release-v1.0.0-16a34a)](https://github.com/zColdWater/omniforge-skills/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

**Zero-dependency `SKILL.md` pack for Claude Code, Cursor, OpenAI Codex CLI, Windsurf, Cline, and Gemini CLI** — teaching coding agents how to run deterministic pre-launch audits across web security, email deliverability, domain/trademark availability, and `/llms.txt` citation readiness.

## Included Skills (4)

| Skill Folder | What It Teaches Your Coding Agent | Live Cloud Workbench & Pricing |
| :--- | :--- | :--- |
| [`skills/vibeshield-security-audit`](./skills/vibeshield-security-audit/SKILL.md) | Unpack Next.js/Vite JS bundles for leaked secrets, verify Supabase RLS & Firebase exposure, and check CSP/HSTS headers | [Free 6-Phase 116-Check Scan](https://vibe-checker.appwrite.network/?ref=gh-omniforge-skills) · [$2 Fix Unlock (~~$9~~)](https://omnipulse-x402.appwrite.network/go/gumroad/vibeshield) |
| [`skills/spf-dmarc-deliverability-audit`](./skills/spf-dmarc-deliverability-audit/SKILL.md) | Recursively count RFC 7208 10-lookup SPF trees, probe DKIM keys, and validate RFC 7489 DMARC `p=reject` enforcement | [Free 6-Phase DNS Trace](https://inbox-checker.appwrite.network/?ref=gh-omniforge-skills) · [$2 Flattened Fix (~~$9~~)](https://omnipulse-x402.appwrite.network/go/gumroad/inboxshield) |
| [`skills/llms-txt-citation-readiness`](./skills/llms-txt-citation-readiness/SKILL.md) | Separate AI search bots (`OAI-SearchBot`, `PerplexityBot`) from training bots, fix SPA `/llms.txt` soft-404s & validate JSON-LD | [Free Side-by-Side PK](https://citeready-checker.appwrite.network/?a=linear.app&b=stripe.com&ref=gh-omniforge-skills) · [$2 Fix Kit (~~$12~~)](https://omnipulse-x402.appwrite.network/go/gumroad/citeready) |
| [`skills/brand-domain-trademark-audit`](./skills/brand-domain-trademark-audit/SKILL.md) | Check 78 TLDs via RDAP/DNS, detect aftermarket listings, and screen live USPTO trademark filings before naming a product | [**100% Free Forever** at brand-checker.appwrite.network](https://brand-checker.appwrite.network/?ref=gh-omniforge-skills) |

- **OmniForge 3-in-1 Complete Suite ($5 Launch Special, ~~$29~~):** [https://omnipulse-x402.appwrite.network/go/gumroad/launch-stack](https://omnipulse-x402.appwrite.network/go/gumroad/launch-stack)

## Install in 10 Seconds

```bash
# Copy into Claude Code (~/.claude/skills) or Cursor (.cursor/skills)
git clone https://github.com/zColdWater/omniforge-skills.git
cp -R omniforge-skills/skills/* ~/.claude/skills/
```

## Companion GitHub Actions (`@v1`)

- `uses: zColdWater/vibeshield-action@v1` — [GitHub Repo](https://github.com/zColdWater/vibeshield-action)
- `uses: zColdWater/inboxshield-action@v1` — [GitHub Repo](https://github.com/zColdWater/inboxshield-action)
- `uses: zColdWater/citeready-action@v1` — [GitHub Repo](https://github.com/zColdWater/citeready-action)

## License

MIT © OmniForge · Agent Arena Studio (`agentarenastudio@proton.me`)
