# OmniForge Agent Skills — 20 Pre-Launch Security, Email DNS, Domain & AI Search Skills

[![GitHub Release](https://img.shields.io/badge/release-v2.0.0-16a34a)](https://github.com/zColdWater/omniforge-skills/releases)
[![Skills Count](https://img.shields.io/badge/skills-20-2563eb)](https://www.skills.sh/zColdWater/omniforge-skills)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

**Zero-dependency `SKILL.md` pack (20 specialized developer skills) for Claude Code, Cursor, OpenAI Codex CLI, Windsurf, Cline, Antigravity, and Gemini CLI** — teaching coding agents how to run deterministic, strictly read-only pre-launch audits via free live APIs and MIT CLIs across **Web/AI App Security (VibeShield v7.0)**, **Email DNS Deliverability (InboxShield v7.0)**, **78-TLD Domain & Trademark Clearance (BrandShield v6.2 — 100% Free)**, and **AI Search / `/llms.txt` Citation Readiness (CiteReady v6.0)**.

## Install All 20 Skills in 10 Seconds (`npx skills`)

```bash
# Install across Claude Code, Cursor, Antigravity, Codex, Cline & Windsurf
npx skills add zColdWater/omniforge-skills

# Or clone manually
git clone https://github.com/zColdWater/omniforge-skills.git
cp -R omniforge-skills/skills/* ~/.claude/skills/
```

- **Live Vercel Skills Registry Directory:** [https://www.skills.sh/zColdWater/omniforge-skills](https://www.skills.sh/zColdWater/omniforge-skills)
- **OmniForge 3-in-1 Complete Suite ($5 Launch Special, ~~$29~~ — Unlocks VibeShield + InboxShield + CiteReady):** [https://omnipulse-x402.appwrite.network/go/gumroad/launch-stack](https://omnipulse-x402.appwrite.network/go/gumroad/launch-stack)

---

## Included Skills (20)

| # | Skill | Pillar | Focus & Free Live Check |
| :---: | :--- | :--- | :--- |
| 1 | [`vibeshield-security-audit`](./skills/vibeshield-security-audit/SKILL.md) | VibeShield v7.0 | Run a read-only 6-phase security audit on Next.js, Vite, Cursor, Lovable, Bolt, Supabase, and Firebase apps: TLS 443, CNAME take... |
| 2 | [`supabase-rls-audit`](./skills/supabase-rls-audit/SKILL.md) | VibeShield v7.0 | Audit Supabase projects for CVE-2025-48757: leaked service_role JWTs, unauthenticated PostgREST table reads across up to 20 tabl... |
| 3 | [`nextjs-security-scanner`](./skills/nextjs-security-scanner/SKILL.md) | VibeShield v7.0 | Audit Next.js App Router and Pages Router deployments for CVE-2025-29927 middleware bypass versions, exposed NEXT_PUBLIC secrets... |
| 4 | [`cursor-security-audit`](./skills/cursor-security-audit/SKILL.md) | VibeShield v7.0 | Pre-launch security audit tailored for AI-generated apps built in Cursor, Lovable, Bolt.new, and v0: detects 52 leaked key types... |
| 5 | [`firebase-security-rules-audit`](./skills/firebase-security-rules-audit/SKILL.md) | VibeShield v7.0 | Detect unauthenticated Firebase Realtime Database (/.json?shallow=true) and Cloud Firestore (documents?pageSize=1) public read e... |
| 6 | [`client-secret-leak-scanner`](./skills/client-secret-leak-scanner/SKILL.md) | VibeShield v7.0 | Unpack up to 24 complete production JavaScript bundles (up to 2.5MB each) to catch leaked OpenAI, Anthropic, Stripe, AWS, Supaba... |
| 7 | [`csp-hsts-security-headers`](./skills/csp-hsts-security-headers/SKILL.md) | VibeShield v7.0 | Parse Content-Security-Policy syntax for unsafe-inline, unsafe-eval, wildcards, missing frame-ancestors/object-src/base-uri, aud... |
| 8 | [`tls-ssl-cname-takeover-audit`](./skills/tls-ssl-cname-takeover-audit/SKILL.md) | VibeShield v7.0 | Inspect real port 443 TLS protocol (TLSv1.3 vs weak TLS 1.0/1.1), cipher suite, CA issuer, certificate expiry countdown, SAN lis... |
| 9 | [`api-endpoint-sourcemap-audit`](./skills/api-endpoint-sourcemap-audit/SKILL.md) | VibeShield v7.0 | Run 28 SPA-filtered non-destructive probes (/.env, /.git, Swagger/OpenAPI, GraphQL introspection, Spring Actuator, backup.sql, O... |
| 10 | [`spf-dmarc-deliverability-audit`](./skills/spf-dmarc-deliverability-audit/SKILL.md) | InboxShield v7.0 | Run a 6-phase email DNS audit: NS/SOA consistency, MX IPv4 redundancy, recursive SPF per-layer CIDR expansion (RFC 7208), 24 DKI... |
| 11 | [`spf-dkim-dmarc-fix`](./skills/spf-dkim-dmarc-fix/SKILL.md) | InboxShield v7.0 | Step-by-step live diagnosis and DNS fix workflow for SaaS onboarding, password-reset, and newsletter emails landing in Gmail/Yah... |
| 12 | [`spf-flattener-10-lookup-fix`](./skills/spf-flattener-10-lookup-fix/SKILL.md) | InboxShield v7.0 | Resolve RFC 7208 SPF PermError (>10 recursive DNS lookups or >2 void lookups) by inspecting nested L0/L1/L2 include trees and fl... |
| 13 | [`dmarc-rfc7489-policy-linter`](./skills/dmarc-rfc7489-policy-linter/SKILL.md) | InboxShield v7.0 | Validate _dmarc TXT records against RFC 7489 tag rules (exact-case v=DMARC1 first tag, duplicate _dmarc detection, tag allowlist... |
| 14 | [`mx-ns-dns-redundancy-audit`](./skills/mx-ns-dns-redundancy-audit/SKILL.md) | InboxShield v7.0 | Audit authoritative NS resolver drift (native vs Cloudflare DoH), glue IPv4 /16 subnet diversity, SOA primary-in-NS check, MX mu... |
| 15 | [`brand-domain-trademark-audit`](./skills/brand-domain-trademark-audit/SKILL.md) | BrandShield v6.2 (100% Free) | Check startup names across 78 TLDs via live IANA RDAP/DNS, detect real aftermarket for-sale listings across 17 broker/parking NS... |
| 16 | [`domain-availability-search`](./skills/domain-availability-search/SKILL.md) | BrandShield v6.2 (100% Free) | Check real-time availability across 78 domain extensions (.com, .ai, .io, .dev, .app, .co, .sh, .gg) via live RDAP/DNS and ident... |
| 17 | [`startup-brand-name-generator`](./skills/startup-brand-name-generator/SKILL.md) | BrandShield v6.2 (100% Free) | Generate 60 available startup domain ideas, verify GitHub/npm/PyPI/Bluesky handles, and check live USPTO Class 009/042 trademark... |
| 18 | [`llms-txt-citation-readiness`](./skills/llms-txt-citation-readiness/SKILL.md) | CiteReady v6.0 | Audit website readiness for ChatGPT Search, Perplexity, Claude, and Google AI Overviews: 10 AI crawler robots.txt rules, /llms.t... |
| 19 | [`llms-txt-generator`](./skills/llms-txt-generator/SKILL.md) | CiteReady v6.0 | Check whether a site serves a valid llmstxt.org /llms.txt index (catching SPA HTML soft-404s) and generate structured Markdown d... |
| 20 | [`ai-search-geo-schema-audit`](./skills/ai-search-geo-schema-audit/SKILL.md) | CiteReady v6.0 | Audit Schema.org JSON-LD entity graphs (Organization, SoftwareApplication, FAQPage, Offer), AI crawler robots.txt policies, and ... |

---

## Live Cloud Workbenches & Launch Special Pricing

| Product | Free Live Tool (Zero Signup) | Pricing |
| :--- | :--- | :--- |
| **VibeShield v7.0** | [vibe-checker.appwrite.network](https://vibe-checker.appwrite.network/?ref=gh-omniforge-skills) | Free 6-Phase Scan · [$2 Launch Special Fix Unlock (~~$9~~)](https://omnipulse-x402.appwrite.network/go/gumroad/vibeshield) |
| **InboxShield v7.0** | [inbox-checker.appwrite.network](https://inbox-checker.appwrite.network/?ref=gh-omniforge-skills) · [/spf-flattener](https://inbox-checker.appwrite.network/spf-flattener?ref=gh-omniforge-skills) | Free 6-Phase DNS Trace · [$2 Launch Special Fix (~~$9~~)](https://omnipulse-x402.appwrite.network/go/gumroad/inboxshield) |
| **CiteReady v6.0** | [citeready-checker.appwrite.network](https://citeready-checker.appwrite.network/?ref=gh-omniforge-skills) · [/generator](https://citeready-checker.appwrite.network/generator?ref=gh-omniforge-skills) | Free GEO PK & Audit · [$2 Launch Special Kit (~~$12~~)](https://omnipulse-x402.appwrite.network/go/gumroad/citeready) |
| **BrandShield v6.2** | [brand-checker.appwrite.network](https://brand-checker.appwrite.network/?ref=gh-omniforge-skills) · [/namer](https://brand-checker.appwrite.network/namer?ref=gh-omniforge-skills) | **100% Free Forever** (78 TLDs + 17 Aftermarket + USPTO) |
| **Complete 3-in-1 Suite** | Unlocks VibeShield + InboxShield + CiteReady | [$5 Launch Special (~~$29~~, one-time, $0/mo)](https://omnipulse-x402.appwrite.network/go/gumroad/launch-stack) |

## Companion GitHub Actions (`@v1`) & MCP Server

- `uses: zColdWater/vibeshield-action@v1` — [GitHub Repo](https://github.com/zColdWater/vibeshield-action)
- `uses: zColdWater/inboxshield-action@v1` — [GitHub Repo](https://github.com/zColdWater/inboxshield-action)
- `uses: zColdWater/citeready-action@v1` — [GitHub Repo](https://github.com/zColdWater/citeready-action)
- `npx -y github:zColdWater/mcp-launch-audit` — [5-Tool MCP Server](https://github.com/zColdWater/mcp-launch-audit)

## License

MIT (c) OmniForge · Agent Arena Studio (`agentarenastudio@proton.me` · [@agentarenastudi](https://x.com/agentarenastudi))
