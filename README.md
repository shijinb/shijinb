# Shijin B

Full-stack engineer building SaaS products end to end: recruitment and HR platforms, CRM and lead pipelines, AI-assisted document processing, search and SEO tooling, and e-commerce.

I care about the parts that keep software running after launch: tests that exercise real databases, safe defaults, honest documentation and code that the next engineer can change with confidence.

**Areas:** backend and API design · multi-tenant SaaS · LLM integration · technical SEO · e-commerce

**Stack:** Python (FastAPI) · PHP (Laravel, OpenCart) · TypeScript (Next.js, React) · PostgreSQL · MySQL · Redis · Elasticsearch · Docker · GitHub Actions · AWS

## Projects

| Project | What it shows | Tech | Status |
|---|---|---|---|
| [search-engine-indexing-toolkit](https://github.com/shijinb/search-engine-indexing-toolkit) | CLI and library that parses sitemaps safely, cleans URLs and notifies IndexNow, Bing and Google through their official APIs. Dry run by default, with retries, quotas and submission history. Each API's real scope is documented, including that Google has no general URL submission API. | Python, httpx, SQLite | Tested, CI passing |
| [master-llm-humanization-guide](https://github.com/shijinb/master-llm-humanization-guide) | A practical guide, prompt templates and scoring rubric for AI-assisted writing that is accurate and specific, plus `prose-check`, a tested editorial linter. Built from a production content pipeline. | Python, Markdown | Tested, CI passing |
| [opencart-extension-collection](https://github.com/shijinb/opencart-extension-collection) | 13 production OpenCart 3 extensions, reviewed and hardened: SQL-injection fixes, schema.org JSON-LD, stock reporting. Verified against 4 OpenCart releases with a harness that reproduces OpenCart's OCMOD engine, plus MySQL integration tests in CI. | PHP, MySQL, Twig, GitHub Actions | Tested, CI passing |

### In progress

These are being built and will be linked here once their tests pass:

- **fastapi-production-starter**: multi-tenant FastAPI service with JWT rotation, RBAC, audit log and Alembic migrations.
- Resume parsing (Python and Laravel), an AI engineering playground, a SaaS admin dashboard, SaaS system design notes and an AWS deployment lab.
