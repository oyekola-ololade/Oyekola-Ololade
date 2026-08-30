<p align="center">
  <img src="./assets/banner.png" width="100%" alt="Oyekola Ololade — AI Systems and Integration Engineer"/>
</p>

<h1 align="center">Oyekola Ololade</h1>

<p align="center">
  <strong>AI Systems & Integration Engineer</strong><br>
  Designing evidence-led n8n, API, data, and AI workflows with explicit validation, fallback, and human-review paths.
</p>

<p align="center">
  <a href="https://github.com/oyekola-ololade">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/ololade-oyekola-5b1797397/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:oyekolaololade69@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## What I Engineer

I begin with the operational problem: what enters the system, what decisions must be made, where state is stored, how failures surface, and when a person must remain in control.

My work focuses on:

- n8n workflow architecture, diagnosis, and repair
- API and webhook integrations
- AI-assisted classification, routing, and summarization
- Data validation, deduplication, and state handling
- Failure paths, alerts, fallbacks, and human review
- Clear implementation notes and handoff documentation

### Reference architecture pattern

This is the design pattern I use when reasoning about automation systems; individual repositories implement only the components shown in their own exports and documentation.

```mermaid
flowchart LR
    A["Events: webhooks, schedules, and messages"] --> B["Validation and normalization"]
    B --> C["Rules and AI-assisted decisions"]
    C --> D["Business APIs and workflow actions"]
    D --> E["State, records, and audit trail"]
    C --> F["Fallback and human review"]
    D --> G["Alerts and operational handoff"]
```

---

## Portfolio Evidence

The status labels below are deliberate. A template, demo, prototype, and production deployment are not the same thing.

| System | Evidence status | What the repository or project demonstrates | Current limitation |
|---|---|---|---|
| [FlowForge AVA](https://github.com/oyekola-ololade/FlowForge-Ava-AI) | **Verified build with limitations** | Multi-agent lead and customer-operations flow with WhatsApp intake, validation, intent handling, memory, specialized agents, human handoff, CRM, calendar, and alerts | Production readiness and measurable business outcomes are not claimed |
| [Candidate Screening](https://github.com/oyekola-ololade/cv-screening-automation) | **Working demo** | Structured intake, extraction, duplicate detection, controlled AI matching, scoring, database update, and recruiter review | Demonstration only; not an autonomous hiring or production-compliance system |
| [MailIQ](https://github.com/oyekola-ololade/Mail-IQ) | **Prototype under repair · historical/offline** | Substantial multi-tenant email-intelligence architecture for Gmail/Outlook monitoring and structured routing to messaging channels | Offline, no paying customers, and reliability gaps remain |
| NewsIQ | **Partial MVP** | Python, SQL, Docker/Railway, and five n8n workflows for an AI news-intelligence pipeline | Not a complete live production or social-publishing system |
| [30-workflow template library](#n8n-template-library) | **Sanitized portfolio templates** | Importable n8n workflow JSON, setup notes, visual pages, and repository-specific architecture diagrams | Credentials are placeholders and configured live-run videos are not included yet |
| SwiftRoute | **Concept / specification** | Logistics-system architecture and product thinking | Not client work, a deployment, or evidence of measured outcomes |

---

## n8n Template Library

Each template repository includes a sanitized workflow export, setup instructions, a visual HTML project page, and a Mermaid architecture diagram. They are portfolio/template assets and require the user's own credentials, service identifiers, configuration, and testing before use.

### Priority proof repositories

1. [WhatsApp Lead AI Scoring → Slack](https://github.com/oyekola-ololade/whatsapp-lead-ai-scoring-slack)
2. [Website Form Qualification → Calendar](https://github.com/oyekola-ololade/website-form-qualification-calendar)
3. [Email Ticket Auto-Router](https://github.com/oyekola-ololade/email-ticket-autorouter)
4. [Shopify Invoice → Email + WhatsApp](https://github.com/oyekola-ololade/shopify-invoice-email-whatsapp)
5. [Multi-Channel Inquiry Unifier](https://github.com/oyekola-ololade/multi-channel-inquiry-unifier)

The remaining repositories cover lead operations, customer support, reporting, ecommerce operations, content workflows, data cleanup, and internal task routing. Browse them from the [repositories tab](https://github.com/oyekola-ololade?tab=repositories).

---

## Engineering Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,javascript,docker,git,github,postgres,supabase" alt="Python, JavaScript, Docker, Git, GitHub, PostgreSQL, and Supabase"/>
</p>

- **Workflow orchestration:** n8n, Make, webhooks, scheduled and event-driven workflows
- **Software and data:** Python, JavaScript, SQL, PostgreSQL, Supabase
- **Infrastructure:** Docker, Railway, Git, GitHub
- **Integrations:** WhatsApp, Slack, Google Workspace, Airtable, Telegram, Discord, and REST APIs
- **AI workflow patterns:** classification, structured extraction, summarization, routing, scoring support, and human-review controls

---

## Engineering Principles

> Solve the business problem before choosing the technology.

- Claims should match inspectable evidence.
- Generated or importable workflows are not production-tested by default.
- AI-assisted decisions need validation, fallback behavior, and appropriate human control.
- State, failure handling, observability, and handoff are part of the system—not optional polish.
- Simplicity is an engineering advantage when it improves reliability and maintenance.

---

## Current Focus

- Diagnosing and repairing n8n/API workflow failures
- Building bounded integration systems with testable acceptance criteria
- Improving state handling, error paths, and operational documentation
- Converting existing technical work into truthful, buyer-readable proof

---

## GitHub Activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=oyekola-ololade&show_icons=true&hide_border=true&theme=github_dark" alt="Oyekola Ololade GitHub statistics"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=oyekola-ololade&layout=compact&hide_border=true&theme=github_dark" alt="Languages used across public repositories"/>
</p>

---

## Contact

For a bounded workflow diagnostic, repair, or integration discussion:

- [LinkedIn](https://www.linkedin.com/in/ololade-oyekola-5b1797397/)
- [Email](mailto:oyekolaololade69@gmail.com)

<p align="center">
  <i>Engineering systems that make their evidence, boundaries, and failure paths visible.</i>
</p>
