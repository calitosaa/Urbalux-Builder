# Urbalux-Builder — Claude Code Configuration

## Project Context
Urbalux-Builder is a full-stack application project with a complete AI-powered development ecosystem.

---

## Installed Skills (1538+)
All skills are available via `@skill-name` in Claude Code.

### Key Skills by Category

#### UI/UX & Design
- `@ui-ux-pro-max` — 67 UI styles, 161 color palettes, 57 font pairings, 99 UX guidelines
- `@stitch-ui-design` — Google Stitch AI UI/UX design integration
- `@stitch-loop` — Stitch design iteration loops
- `@shadcn` — shadcn/ui component patterns
- `@tailwind-design-system` / `@tailwind-patterns` — Tailwind CSS design systems
- `@radix-ui-design-system` — Radix UI patterns
- `@beercss` — BeerCSS Material Design 3 (lightweight, 14.5kb)
- `@design-spells` / `@design-md` / `@design-orchestration` — Design workflows
- `@liquid-glass-design` / `@swiftui-liquid-glass` — Liquid glass effects
- `@magic-ui-generator` — Magic UI components
- `@antigravity-design-expert` — Advanced design patterns

#### Frontend Development
- `@react-best-practices` / `@react-patterns` / `@react-ui-patterns` — React
- `@nextjs-app-router-patterns` / `@nextjs-best-practices` — Next.js
- `@typescript-pro` / `@typescript-expert` — TypeScript
- `@sveltekit` / `@astro` / `@angular` — Other frameworks
- `@threejs-*` — Three.js 3D (fundamentals, shaders, animation, materials, etc.)
- `@animejs-animation` — Anime.js animations
- `@spline-3d-integration` — Spline 3D

#### Backend & APIs
- `@fastapi-pro` / `@fastapi-templates` — FastAPI
- `@nodejs-best-practices` / `@nodejs-backend-patterns` — Node.js
- `@nestjs-expert` / `@nestjs-patterns` — NestJS
- `@django-pro` / `@django-patterns` — Django
- `@python-pro` / `@python-patterns` — Python
- `@golang-pro` / `@golang-patterns` — Go
- `@rust-pro` / `@rust-patterns` — Rust
- `@graphql` / `@graphql-architect` — GraphQL

#### Databases
- `@postgresql` / `@postgres-best-practices` — PostgreSQL
- `@neon-postgres` — Neon serverless Postgres
- `@supabase-automation` — Supabase
- `@prisma-expert` — Prisma ORM
- `@drizzle-orm-expert` — Drizzle ORM
- `@database-architect` / `@database-design` — Database design

#### AI/ML & Agents
- `@ai-agent-development` / `@ai-agents-architect` — Agent development
- `@multi-agent-patterns` / `@multi-agent-task-orchestrator` — Multi-agent
- `@langchain-architecture` / `@langgraph` — LangChain/LangGraph
- `@crewai` — CrewAI framework
- `@pydantic-ai` — Pydantic AI
- `@autonomous-agents` / `@autonomous-agent-patterns` — Autonomous agents
- `@browser-automation` / `@computer-use-agents` — Browser agents
- `@notebooklm` — NotebookLM integration
- `@agent-memory-systems` / `@agent-memory-mcp` — Agent memory
- `@hierarchical-agent-memory` — Hierarchical memory

#### DevOps & Cloud
- `@docker-expert` / `@docker-patterns` — Docker
- `@kubernetes-architect` / `@kubernetes-deployment` — K8s
- `@terraform-specialist` / `@terraform-infrastructure` — Terraform
- `@github-actions-templates` — GitHub Actions
- `@cloud-architect` / `@multi-cloud-architecture` — Cloud
- `@gcp-cloud-run` / `@aws-skills` — GCP/AWS

#### Testing
- `@tdd-orchestrator` / `@tdd-workflow` — TDD
- `@e2e-testing` / `@e2e-testing-patterns` — E2E
- `@playwright-skill` — Playwright
- `@k6-load-testing` — Load testing

#### Security
- `@security-audit` / `@security-auditor` — Security audits
- `@red-team-tactics` / `@red-team-tools` — Red team
- `@penetration-testing` / `@pentest-commands` — Pentesting
- `@top-web-vulnerabilities` — OWASP Top 10

#### Workflow Automation
- `@n8n-workflow-patterns` / `@n8n-code-python` / `@n8n-code-javascript` — n8n
- `@workflow-automation` / `@workflow-patterns` — Workflows
- `@antigravity-workflows` / `@antigravity-skill-orchestrator` — Antigravity

#### Integrations & Automation
- `@slack-automation` / `@gmail-automation` / `@google-sheets-automation` — Google/Slack
- `@github-automation` / `@github-workflow-automation` — GitHub
- `@stripe-automation` / `@stripe-integration` — Stripe
- `@hubspot-automation` / `@salesforce-automation` — CRM
- `@jira-automation` / `@linear-automation` — Project mgmt
- `@notion-automation` / `@airtable-automation` — Productivity
- `@telegram-automation` / `@discord-automation` / `@whatsapp-automation` — Messaging

---

## Installed MCP Servers

### Active (no API key needed)
| Server | Description |
|--------|-------------|
| `memory` | Persistent memory across sessions |
| `omega-memory` | Semantic search + knowledge graphs |
| `sequential-thinking` | Chain-of-thought reasoning |
| `context7` | Live documentation lookup |
| `filesystem` | Filesystem operations |
| `playwright` | Browser automation |
| `ruflo` | 313 MCP tools, multi-agent orchestration |
| `stitch-mcp` | Google Stitch UI/UX design (needs Google Cloud auth) |
| `cloudflare-docs` | Cloudflare docs search |
| `cloudflare-workers-*` | CF Workers builds/bindings/observability |
| `vercel` | Vercel deployments |
| `railway` | Railway deployments |

### Needs API Key (template in settings.json)
| Server | Required |
|--------|----------|
| `github` | `GITHUB_PERSONAL_ACCESS_TOKEN` |
| `supabase` | Project ref |
| `firecrawl` | `FIRECRAWL_API_KEY` |
| `exa-web-search` | `EXA_API_KEY` |
| `fal-ai` | `FAL_KEY` |
| `jira` | JIRA URL + email + token |

---

## Installed Agents (~62+)
Located in `~/.claude/agents/`. Includes from:
- **superpowers**: code-reviewer, architect, chief-of-staff
- **everything-claude-code**: 47 specialized agents
- **agency-agents**: 191 agents across 15 divisions (engineering, design, marketing, sales, etc.)

---

## Persistent Memory
`claude-mem` is installed as a plugin. Memory is automatic every session.
- View memories: `http://localhost:37777`
- Start worker: `npx claude-mem start`
- Search: use `/mem-search` skill

---

## Tools Available

### ruflo (v3.5.78)
```bash
ruflo init              # Initialize in project
ruflo mcp start         # Start as MCP server
ruflo spawn <task>      # Spawn specialized agents
ruflo --help
```

### browser-use (v0.12.6)
Python browser automation with AI agents.
```python
from browser_use import Agent
agent = Agent(task="...", llm=...)
```

### n8n
Workflow automation (install if needed: `npx n8n`)

### langflow
Visual AI workflow builder (install: `uv pip install --system langflow`)

---

## Design References
- **BeerCSS**: Material Design 3, 14.5kb, CDN: `https://cdn.jsdelivr.net/npm/beercss`
- **Material 3 Expressive**: See `meticha/material-3-expressive-catalog` for Android/Jetpack Compose reference
- **G0DM0D3**: Multi-model AI chat at `godmod3.ai` (red-team research tool)

---

## Stitch MCP Note
The `stitch-mcp` server uses **Google Cloud credentials** (not a traditional API key).
To authenticate: `gcloud auth application-default login`
The server provides 9 tools for AI-powered UI design generation.

---

## Sources
Integrated from:
1. `sickn33/antigravity-awesome-skills` — 1,392+ SKILL.md playbooks
2. `affaan-m/everything-claude-code` — 47 agents, 181 skills, 14 MCP configs
3. `obra/superpowers` — Workflow system (brainstorming → code review)
4. `msitarzewski/agency-agents` — 191 agent personalities
5. `thedotmack/claude-mem` — Persistent memory plugin
6. `ruvnet/ruflo` — AI orchestration platform
7. `nextlevelbuilder/ui-ux-pro-max-skill` — UI/UX skill
8. `Kargatharaakash/stitch-mcp` — Google Stitch MCP
9. `browser-use/browser-use` — Browser automation
10. `teng-lin/notebooklm-py` — NotebookLM Python API
11. `ComposioHQ/awesome-claude-skills` — 78+ curated skills
12. `VoltAgent/awesome-agent-skills` — 1,060+ community skills
13. `langflow-ai/langflow` — Visual AI builder
14. `beercss/beercss` — Material Design 3 CSS framework
15. `meticha/material-3-expressive-catalog` — Material 3 reference
16. `n8n-io/n8n` — Workflow automation
17. `elder-plinius/G0DM0D3` — Multi-model AI interface
