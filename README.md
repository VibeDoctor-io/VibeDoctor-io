# VibeDoctor — Production Readiness for AI-Coded Apps

**Your AI has no quality gate. We are.**

[vibedoctor.io](https://vibedoctor.io) · [911@vibedoctor.io](mailto:911@vibedoctor.io) · [LinkedIn](https://www.linkedin.com/company/vibedoctor)

---

## What is VibeDoctor?

VibeDoctor scans apps built with AI coding tools — Cursor, Claude Code, GitHub Copilot, Lovable, Bolt — and finds the problems they left behind before those problems reach your users.

Security vulnerabilities. Performance bottlenecks. Hallucinated imports. Exposed secrets. Broken error handling. We find them. We tell you exactly how to fix them.

**Cursor wrote it. Claude shipped it. Nobody checked it. VibeDoctor does.**

---

## Who It's For

- Seed-stage startups shipping fast with AI coding tools
- CTOs who are also the dev team
- Founders with paying users and no dedicated security engineer
- Any team where "move fast" can't mean "ship broken"

---

## What We Scan

| Category | What We Check |
|---|---|
| **Secrets & Credentials** | API keys, tokens, credentials committed to repos |
| **AI Code Safety** | Hallucinated imports, phantom functions, invented env vars |
| **Dependencies** | Known CVEs, outdated packages, supply chain risks |
| **Authentication** | Exposed API routes, missing auth, broken access control |
| **Performance** | LCP, TTI, TBT, CLS - real user experience metrics |
| **Code Quality** | Dead code, N+1 queries, unhandled promises, memory leaks |
| **Infrastructure** | SSL, HSTS, TLS config, security headers |
| **Accessibility** | WCAG compliance, screen reader support |

15 production readiness checks. One score. Clear fix prompts.

---

## Key Features

- **Instant scan** - connect GitHub, get results in minutes
- **Push scan** - automatic scan on every commit
- **MCP integration** - run checks directly inside Cursor, VS Code, Windsurf
- **AI fix prompts** - not just "here's the bug" but "here's the fix, here's why, here's how to verify"
- **PR reviews** - automated code review comments on every pull request
- **Uptime monitoring** - 1-minute intervals, SSL/domain alerts
- **Shareable reports** - send your security certificate to investors or clients
- **EU infrastructure** - hosted in Germany, GDPR compliant, raw code never leaves your environment

---

## MCP Integration (Cursor / VS Code / Windsurf)

```json
{
  "mcpServers": {
    "vibedoctor": {
      "url": "https://vibedoctor.io/mcp/YOUR_TOKEN"
    }
  }
}
```

Available tools: `vibedoctor_check` · `vibedoctor_check_security` · `vibedoctor_check_imports` · `vibedoctor_check_performance` · `vibedoctor_check_structure`

---

## Plans

| | Watch | Guard | Shield |
|---|---|---|---|
| **Price** | $15/mo | $39/mo | $79/mo |
| **Projects** | 3 | 10 | 25 |
| **Scans/day** | 10 | 50 | 200 |
| **MCP checks** | 500/mo | 2,000/mo | 5,000/mo |
| **Uptime monitoring** | 5 min | 1 min | 1 min |

All plans include push scans, PR reviews, SSL alerts, and team seats.

---

## Tech Stack

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat&logo=sonarqube&logoColor=white)

Scanning stack: SonarQube · Gitleaks · Trivy · ESLint · Lighthouse · Puppeteer

---

## Start Free

**[Sign up at vibedoctor.io →](https://vibedoctor.io)**

Connect your GitHub repo. Run your first scan. See what your AI left behind.

No credit card required. First scan is free.

---

*VibeDoctor - App Emergency Room · EU-based · GDPR compliant · vibedoctor.io*
