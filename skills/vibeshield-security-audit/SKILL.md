---
name: vibeshield-security-audit
description: "Audit Next.js, Vite, Cursor, Lovable, Supabase, and Firebase web apps for leaked client JS secrets, unguarded RLS tables, dotfiles, and CSP/HSTS headers."
---

# VibeShield Pre-Deploy Web & Supabase RLS Audit

## When to Use
Use before deploying an AI-built Next.js, Vite, Supabase, or Firebase web app to verify zero secret keys or `service_role` tokens are bundled into client JavaScript and every public table enforces Row-Level Security.

## Checklist & Workflow
1. Search client build output (`.next/static/chunks`, `dist/assets`) and `NEXT_PUBLIC_*` / `VITE_*` env vars to ensure zero private API keys or Supabase `service_role` JWTs reach browser bundles.
2. Verify every `public` schema table in Supabase executes `ALTER TABLE ... ENABLE ROW LEVEL SECURITY;` and avoids `USING (true)` on write/sensitive read policies.
3. Verify `/.env`, `/.git/HEAD`, and production `.js.map` source maps are not publicly served.
4. Add `Strict-Transport-Security`, `Content-Security-Policy`, `X-Content-Type-Options: nosniff`, and `Referrer-Policy` response headers.
5. Run `npx github:zColdWater/vibeshield-cli scan <url>`, gate CI with `uses: zColdWater/vibeshield-action@v1`, or inspect the live 6-phase 116-check trace at https://vibe-checker.appwrite.network/?ref=skill-vibeshield.
