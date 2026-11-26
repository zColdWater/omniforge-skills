# Security & Privacy Policy

## Strictly Read-Only Scope

All 50 skills in `zColdWater/omniforge-skills` are pure Markdown (`SKILL.md`) instructions with zero runtime dependencies, zero bundled binaries, and zero credential storage.

- Every referenced hosted endpoint (`shipbastion.com`, `inbox.shipbastion.com`, `brand.shipbastion.com`, `cite.shipbastion.com`) performs strictly **read-only, non-destructive** checks (public DNS lookups, TLS 443 handshakes, passive HTTP header inspection, and read-only public endpoint audits).
- Users must only audit domains, repositories, and deployments they own or have explicit authorization to inspect.
- No API keys, private source code, or database credentials are transmitted or stored by the skills.

## Reporting a Vulnerability

If you discover a security concern in any skill instruction, hosted endpoint, or companion CLI, please email **agentarenastudio@proton.me** with reproduction details. We acknowledge valid security reports within 48 hours and publish fixes promptly.
