# OmniForge Agent Skills — 50 Pre-Launch Security, Email DNS, Domain & AI Search Skills

[![GitHub Release](https://img.shields.io/badge/release-v2.4.0-16a34a)](https://github.com/zColdWater/omniforge-skills/releases)
[![Skills Count](https://img.shields.io/badge/skills-50-2563eb)](https://www.skills.sh/zColdWater/omniforge-skills)
[![AI Search Readiness](https://citeready-checker.appwrite.network/api/badge?url=zcoldwater.github.io/omniforge-skills)](https://citeready-checker.appwrite.network/?url=https://zcoldwater.github.io/omniforge-skills/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

**Zero-dependency `SKILL.md`, Codex Plugin & Claude Code Plugin pack (50 specialized developer skills) for Claude Code, OpenAI Codex CLI, Cursor, Windsurf, Cline, Antigravity, and Gemini CLI** — teaching coding agents how to run deterministic, strictly read-only pre-launch audits via free live APIs, a zero-install POSIX `cli.sh` one-liner, and MIT CLIs across **Web/AI App Security (VibeShield v7.0)**, **Email DNS Deliverability (InboxShield v7.0)**, **78-TLD Domain & Trademark Clearance (BrandShield v6.2 — 100% Free)**, and **AI Search / `/llms.txt` Citation Readiness (CiteReady v6.0)**.

## Zero-Install 1-Line Terminal Audit (`cli.sh` — No Node/npm Required)

```bash
# 6-phase Web/AI Security audit (116+ read-only checks)
curl -fsSL https://vibe-checker.appwrite.network/cli.sh | sh -s -- yourdomain.com

# Parallel 3-in-1 Suite (VibeShield + InboxShield + CiteReady)
curl -fsSL https://vibe-checker.appwrite.network/cli.sh | sh -s -- --suite yourdomain.com

# CI/CD Score Gate (exits code 2 if score < 80) or raw JSON for jq
curl -fsSL https://vibe-checker.appwrite.network/cli.sh | sh -s -- --fail-below 80 yourdomain.com
curl -fsSL https://vibe-checker.appwrite.network/cli.sh | sh -s -- --json yourdomain.com | jq '.assessment'
```

## Install All 50 Skills in 10 Seconds (`npx skills`)

```bash
# Install across Claude Code, Cursor, Antigravity, Codex, Cline & Windsurf
npx skills add zColdWater/omniforge-skills

# Or clone manually
git clone https://github.com/zColdWater/omniforge-skills.git
cp -R omniforge-skills/skills/* ~/.claude/skills/
```

- **Black Friday 2026 Deal Stack ($2 Single / $5 Complete 3-in-1 Suite — 83% OFF, One-Time):** [Black Friday 2026 Developer Security, DNS & AI Search Deal](https://zcoldwater.github.io/omniforge-skills/black-friday-2026-developer-security-deal.html)
- **Live Vercel Skills Registry Directory:** [https://www.skills.sh/zColdWater/omniforge-skills](https://www.skills.sh/zColdWater/omniforge-skills)
- **2026 Flagship Empirical Report Hub (330 Live Audits Across Security, Email DNS, AI Search & TLDs):** [2026 State of Indie & AI Startup Infrastructure Report](https://zcoldwater.github.io/omniforge-skills/state-of-ai-startup-infrastructure-2026.html) · [Master JSON](https://zcoldwater.github.io/omniforge-skills/state-of-ai-startup-infrastructure-2026.json)
- **OmniForge 3-in-1 Complete Suite ($5 Launch Special, ~~$29~~ — Unlocks VibeShield + InboxShield + CiteReady):** [https://omnipulse-x402.appwrite.network/go/gumroad/launch-stack](https://omnipulse-x402.appwrite.network/go/gumroad/launch-stack)

---

## Included Skills (50)

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
| 21 | [`lovable-security-audit`](./skills/lovable-security-audit/SKILL.md) | VibeShield v7.0 | Audit Lovable.dev (.lovable.app & custom domain) apps before launch: detects leaked VITE_ API keys across 52 patterns, open Supa... |
| 22 | [`bolt-new-security-audit`](./skills/bolt-new-security-audit/SKILL.md) | VibeShield v7.0 | Audit Bolt.new (.bolt.host, Netlify, Vercel) web apps across 6 phases: unpacks full JS bundles for 52 leaked API key types, test... |
| 23 | [`vercel-security-headers`](./skills/vercel-security-headers/SKILL.md) | VibeShield v7.0 | Verify live Vercel deployments against 10 Mozilla Observatory security headers, CSP AST syntax defects, HSTS preload compliance,... |
| 24 | [`cloudflare-waf-security-audit`](./skills/cloudflare-waf-security-audit/SKILL.md) | VibeShield v7.0 | Audit Cloudflare-proxied sites across TLS 443, CNAME takeover, 28 sensitive endpoint probes, CSP/HSTS/COOP/CORP headers, and gen... |
| 25 | [`graphql-introspection-audit`](./skills/graphql-introspection-audit/SKILL.md) | VibeShield v7.0 | Test live /graphql and /api/graphql endpoints for enabled production schema introspection ({__schema{types{name}}}) plus exposed... |
| 26 | [`oauth-cookie-cors-security-audit`](./skills/oauth-cookie-cors-security-audit/SKILL.md) | VibeShield v7.0 | Audit response Set-Cookie headers (Secure, HttpOnly, SameSite), test untrusted Origin reflection with Access-Control-Allow-Crede... |
| 27 | [`google-workspace-spf-dmarc-setup`](./skills/google-workspace-spf-dmarc-setup/SKILL.md) | InboxShield v7.0 | Verify Google Workspace custom domain DNS: MX priority redundancy, include:_spf.google.com lookup count (RFC 7208), google._doma... |
| 28 | [`resend-postmark-email-audit`](./skills/resend-postmark-email-audit/SKILL.md) | InboxShield v7.0 | Audit transactional SaaS email DNS (Resend, Postmark, SendGrid, Amazon SES): catches SPF >10 lookup PermErrors, missing DKIM CNA... |
| 29 | [`bimi-mta-sts-email-security`](./skills/bimi-mta-sts-email-security/SKILL.md) | InboxShield v7.0 | Audit advanced email transport & brand trust records: _mta-sts policy & HTTPS policy host, _smtp._tls (TLS-RPT), and default._bi... |
| 30 | [`robots-txt-ai-crawler-audit`](./skills/robots-txt-ai-crawler-audit/SKILL.md) | CiteReady v6.0 | Audit /robots.txt rules across 10 AI crawlers (OAI-SearchBot, ChatGPT-User, PerplexityBot, ClaudeBot, GPTBot, Google-Extended, A... |
| 31 | [`v0-security-audit`](./skills/v0-security-audit/SKILL.md) | VibeShield v7.0 | Audit Vercel v0.dev generated Next.js and React apps for NEXT_PUBLIC_ secret leaks, CVE-2025-29927 middleware bypass, unauthenti... |
| 32 | [`replit-security-audit`](./skills/replit-security-audit/SKILL.md) | VibeShield v7.0 | Run a read-only 6-phase security audit on Replit Agent deployed web apps: detect client JS API key leaks, exposed .env/.git/debu... |
| 33 | [`vite-env-leak-scanner`](./skills/vite-env-leak-scanner/SKILL.md) | VibeShield v7.0 | Scan live compiled Vite/React/Vue/Svelte JS chunks and sourcemaps for accidentally exposed VITE_* / PUBLIC_* private keys (Strip... |
| 34 | [`stripe-webhook-security-audit`](./skills/stripe-webhook-security-audit/SKILL.md) | VibeShield v7.0 | Audit SaaS payment apps for leaked Stripe sk_live_/rk_live_/whsec_ secret keys in client JS bundles, unsigned webhook endpoints,... |
| 35 | [`cold-email-deliverability-audit`](./skills/cold-email-deliverability-audit/SKILL.md) | InboxShield v7.0 | Audit secondary cold-email and outbound SaaS domains for SPF 10-lookup limits, 24 DKIM selectors, enforced DMARC (p=quarantine/r... |
| 36 | [`aws-ses-sendgrid-dns-audit`](./skills/aws-ses-sendgrid-dns-audit/SKILL.md) | InboxShield v7.0 | Verify custom MAIL FROM / Return-Path SPF alignment, Easy DKIM / SendGrid s1/s2 CNAME selectors, RFC 7489 DMARC policy, and 10-l... |
| 37 | [`microsoft-365-spf-dmarc-audit`](./skills/microsoft-365-spf-dmarc-audit/SKILL.md) | InboxShield v7.0 | Verify Microsoft 365 / Office 365 Exchange Online DNS authentication: include:spf.protection.outlook.com lookup budget, selector... |
| 38 | [`chatgpt-perplexity-seo-audit`](./skills/chatgpt-perplexity-seo-audit/SKILL.md) | CiteReady v6.0 | Audit how well ChatGPT Search, Perplexity, and Claude can discover, parse, and cite your SaaS product pages: checks /llms.txt, O... |
| 39 | [`uspto-trademark-domain-check`](./skills/uspto-trademark-domain-check/SKILL.md) | BrandShield v6.2 (100% Free) | 100% free live startup naming clearance: screen USPTO trademark collisions, verify 78+ TLD availability via real-time RDAP, dete... |
| 40 | [`saas-launch-audit`](./skills/saas-launch-audit/SKILL.md) | OmniForge Complete Suite ($5 Launch) | Run a complete pre-launch audit across all 4 production pillars in 30 seconds: Web/AI Security (VibeShield v7.0), Email DNS Deli... |
| 41 | [`clerk-auth-security-audit`](./skills/clerk-auth-security-audit/SKILL.md) | VibeShield v7.0 | Audit Clerk-authenticated web apps for accidental CLERK_SECRET_KEY (sk_live_) leaks in client JS bundles, unprotected API routes... |
| 42 | [`auth0-oauth-security-audit`](./skills/auth0-oauth-security-audit/SKILL.md) | VibeShield v7.0 | Audit Auth0 and OIDC single-page web apps for exposed client secrets, open redirect probes, CORS credential reflection, cookie f... |
| 43 | [`netlify-security-headers-audit`](./skills/netlify-security-headers-audit/SKILL.md) | VibeShield v7.0 | Audit live Netlify deployments for missing HSTS, CSP, X-Frame-Options, Permissions-Policy, COOP, public .js.map sourcemaps, dang... |
| 44 | [`cloudflare-pages-security-audit`](./skills/cloudflare-pages-security-audit/SKILL.md) | VibeShield v7.0 | Audit Cloudflare Pages and Workers deployments for _headers CSP/HSTS hardening, client JS secret exposure across 52 rules, expos... |
| 45 | [`zoho-mail-spf-dkim-audit`](./skills/zoho-mail-spf-dkim-audit/SKILL.md) | InboxShield v7.0 | Verify Zoho Mail custom domain DNS setup: include:zoho.com / zoho.eu SPF 10-lookup budget, zmail._domainkey DKIM selector, MX pr... |
| 46 | [`fastmail-proton-dns-audit`](./skills/fastmail-proton-dns-audit/SKILL.md) | InboxShield v7.0 | Audit Proton Mail and Fastmail custom domain DNS authentication: SPF include budget, 3x DKIM CNAME selectors (protonmail/fm1-3),... |
| 47 | [`mailchimp-klaviyo-dmarc-audit`](./skills/mailchimp-klaviyo-dmarc-audit/SKILL.md) | InboxShield v7.0 | Verify Google, Yahoo, and Microsoft 2026 bulk-sender compliance for Mailchimp, Klaviyo, Kit (ConvertKit), and Substack custom do... |
| 48 | [`schema-org-jsonld-validator`](./skills/schema-org-jsonld-validator/SKILL.md) | CiteReady v6.0 | Validate live Schema.org JSON-LD structured data (SoftwareApplication, Organization, Product, FAQPage, HowTo, BreadcrumbList) so... |
| 49 | [`canonical-sitemap-geo-audit`](./skills/canonical-sitemap-geo-audit/SKILL.md) | CiteReady v6.0 | Audit technical AI-search and SEO indexability signals: canonical tags, /sitemap.xml, /llms.txt + /llms-full.txt, Open Graph / T... |
| 50 | [`saas-domain-aftermarket-check`](./skills/saas-domain-aftermarket-check/SKILL.md) | BrandShield v6.2 (100% Free) | 100% free live domain intelligence: check 78+ TLDs via real-time RDAP and detect domains listed for sale across 17 aftermarket m... |

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
