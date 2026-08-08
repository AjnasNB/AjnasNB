<div align="center">

# Ajnas N B

### Building the infrastructure stack for enterprise AI agents.

**Founder & CTO at [Cognifyr](https://cognifyr.co/)**

I build open-source infrastructure that helps AI agents **remember context, retrieve evidence, interact with software, and execute actions under explicit human control**.

[Portfolio](https://ajnasnb.com/) · [LinkedIn](https://linkedin.com/in/ajnasnb) · [Cognifyr](https://cognifyr.co/) · [Email](mailto:ajnas@cognifyr.co)

</div>

---

## Open-source agent stack

| Layer | Project | What it provides |
| --- | --- | --- |
| **Context** | **[Qarinah](https://qarinah.io/)** · [GitHub](https://github.com/AjnasNB/qarinah) · [Paper](https://qarinah.io/paper/) · [DOI](https://doi.org/10.5281/zenodo.21547684) | Evidence-linked project memory that turns large histories into compact, cited context for AI and coding agents. |
| **Retrieval** | **[Cockroach Crawler](https://cockroachcrawler.com/)** · [GitHub](https://github.com/AjnasNB/cockroach-crawler) · [Docs](https://cockroachcrawler.com/docs/) | Bounded crawling, browser rendering, structured extraction, and provenance-preserving web evidence for agents and RAG systems. |
| **Interaction** | **[Cockroach Browser](https://cockroachbrowser.com/)** · [GitHub](https://github.com/AjnasNB/cockroach-browser) · [Paper](https://cockroachbrowser.com/paper/) · [DOI](https://doi.org/10.5281/zenodo.21701792) | Local-first Chromium runtime for scoped sessions, semantic interaction, evidence capture, and controlled browser actions. |
| **Governance** | **[Maqam](https://maqamagent.com/)** · [GitHub](https://github.com/AjnasNB/maqam) · [Docs](https://maqamagent.com/docs/) | Policy checks, exact approvals, registered execution, and verifiable receipts for AI-agent actions. |

<div align="center">

### Context → Retrieval → Interaction → Governed Execution

</div>

Together, these projects form an open-source infrastructure stack for agents that need **durable context, real web evidence, controlled software interaction, explicit authority, and auditable execution**.

The goal is not simply more autonomy. It is making agents useful in environments where **control, provenance, security, and accountability matter**.

---

## How the stack fits together

```text
                         AI Agent
                            │
                            ▼
                     ┌─────────────┐
                     │   Qarinah   │
                     │             │
                     │   Context   │
                     └──────┬──────┘
                            │
                            ▼
             ┌─────────────────────────────┐
             │                             │
             ▼                             ▼
      ┌───────────────┐             ┌───────────────┐
      │   Cockroach   │             │   Cockroach   │
      │    Crawler    │             │    Browser    │
      │               │             │               │
      │   Retrieval   │             │  Interaction  │
      └───────┬───────┘             └───────┬───────┘
              │                             │
              └──────────────┬──────────────┘
                             │
                             ▼
                      ┌─────────────┐
                      │    Maqam    │
                      │             │
                      │ Governance  │
                      │ & Execution │
                      └─────────────┘
```

**Qarinah** preserves the context an agent needs to continue work.  
**Cockroach Crawler** retrieves bounded, source-linked evidence from the web.  
**Cockroach Browser** gives agents controlled interaction with real browser environments.  
**Maqam** governs higher-authority actions through policy, approvals, execution boundaries, and receipts.

---

## Production work

Through [Cognifyr](https://cognifyr.co/), I have built **enterprise knowledge assistants with SSO and permission-aware retrieval, private on-premises AI for healthcare research, real-time voice agents, workflow automation, and multi-tenant SaaS platforms**.

---

## Background

**Founder & CTO at [Cognifyr](https://cognifyr.co/)** · B.Tech in Computer Science, CUSAT · Winner of the **Arbitrum Open House** and **BNB Chain Global Hackathon**.

**Core stack:** TypeScript · Node.js · Python · Next.js · PostgreSQL · Docker · Azure/AWS · RAG · MCP · Agent Evaluation

---

## Build with me

I’m looking for **contributors, early users, research collaborators, and design partners** building enterprise agents, coding agents, context infrastructure, browser agents, secure tool execution, or governed automation.

Start in a project’s issues or discussions, or reach me at **[ajnas@cognifyr.co](mailto:ajnas@cognifyr.co)**.
