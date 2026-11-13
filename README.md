# Awesome-Customer-Support-Service-Automation

## Top Customer Support & Service Automation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI Agents, Workflow Automation & Omnichannel Support Orchestration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Support & Service Automation**. These tools help support teams automate repetitive work—auto-routing tickets, drafting AI responses, enforcing SLAs, and orchestrating workflows across email, chat, and voice channels—so agents can focus on complex issues that need human judgment.

**Examples** include Zendesk, Freshdesk, Intercom, ServiceNow CSM, Ada, Gorgias, Kustomer, LivePerson, and open-source alternatives like Libredesk, Owly, and TGO (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted support automation, open-source AI agents, and community-driven workflow orchestration—ideal for organizations seeking data sovereignty and predictable costs over per-resolution or per-seat SaaS pricing. The open-source support automation space has matured rapidly: Libredesk offers a production-ready omnichannel desk in a single Go binary [citation:1], Owly provides a full AI agent with WhatsApp and voice support [citation:3], and Inbxer delivers account-aware AI drafting for B2B SaaS [citation:6].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Zendesk](https://www.zendesk.com/)** | Enterprise ticketing and support automation with AI agents, intelligent triage, and workflow automation. Transitioning to **Outcome AI Platform** with outcome-based pricing (unlimited seats, pay for eligible outcomes). | Quote-only (bundled with Zendesk Suite) | No free tier; trial via sales |
| **[Freshdesk](https://www.freshworks.com/freshdesk/)** | Cloud helpdesk with Freddy AI for automated responses, routing, and agent assistance. Growth tier covers core support; Pro adds custom dashboards; Enterprise adds skill-based routing. | Growth: **$19/agent/month** (annual); Pro: $55; Enterprise: $89 | No permanent free tier; Freddy AI Agent: 500 free sessions, then $49/100 |
| **[Intercom](https://www.intercom.com/)** | AI-first support platform with **Fin AI agent** resolving conversations autonomously at **$0.99 per outcome**. Copilot assists human agents with drafting and knowledge retrieval. | Essential: **$29/seat/month** (annual); Fin outcomes: $0.99 each | No permanent free tier; trial available |
| **[ServiceNow CSM](https://www.servicenow.com/)** | Enterprise customer service management with AI-powered case resolution, workflow automation, and omnichannel routing. | Quote-only; ~$100–$200/fulfiller/month (smallest band) | No free tier; demo via sales |
| **[Ada](https://www.ada.cx/)** | AI-powered customer service automation platform. Automates resolutions across chat, voice, and email with no-code AI agent building. | Quote-only | No free tier; demo via sales |
| **[Gorgias](https://www.gorgias.com/)** | E-commerce-focused helpdesk with automation for order-related tickets, macros, and intent-based routing. Plans scale by ticket volume. | Quote-only (ticket-volume based) | Free trial available |
| **[Kustomer](https://www.kustomer.com/)** | Timeline-based customer service platform with automation workflows and AI-assisted responses. | From **$89/user/month** (Enterprise) | No permanent free tier |
| **[LivePerson](https://www.liveperson.com/)** | Conversational AI platform for messaging automation, voice bots, and human-agent handoff. | Quote-only | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Libredesk](https://github.com/abhinavxd/libredesk)** | [![Stars](https://img.shields.io/github/stars/abhinavxd/libredesk?style=social&color=white)](https://github.com/abhinavxd/libredesk/stargazers) | **Production-ready omnichannel support desk in a single Go binary.** ~2,500 stars, active as of September 2026. Bundles live chat, email, and other channels with auto-routing, canned responses, and scheduled follow-ups. REST API and webhook support for integration with CRMs and ticketing systems. Go's efficiency means low infrastructure cost for real-time chat [citation:1]. |
| **[Owly](https://github.com/Hesper-Labs/owly)** | [![Stars](https://img.shields.io/github/stars/Hesper-Labs/owly?style=social&color=white)](https://github.com/Hesper-Labs/owly/stargazers) | **Full open-source AI customer support agent with WhatsApp, email, and phone.** MIT licensed. OpenAI GPT integration with function calling and RAG knowledge base. Auto-routing rules, auto-tagging, SLA rules, canned responses, and CSAT surveys. Admin dashboard with unified inbox, customer CRM, and analytics. Docker Compose deployment with Next.js/PostgreSQL stack [citation:3]. |
| **[Inbxer](https://github.com/inbxer/inbxer)** | [![Stars](https://img.shields.io/github/stars/inbxer/inbxer?style=social&color=white)](https://github.com/inbxer/inbxer/stargazers) | **Account-aware AI support for B2B SaaS.** MIT licensed, no per-seat limit. Six focused AI agents (Support Reply, Thread Summary, Urgency, Labeling, Title, Tone Rules) that draft and organize work—but **humans decide** what reaches customers. Unified queue across email, Slack, and in-app chat. Rule-based workflows, business-hours-aware SLAs, CSAT surveys, and auditability. Laravel/MySQL/Redis with Docker Compose [citation:6]. |
| **[TGO](https://github.com/tgoai/tgo)** | [![Stars](https://img.shields.io/github/stars/tgoai/tgo?style=social&color=white)](https://github.com/tgoai/tgo/stargazers) | **Multi-agent AI orchestration with human collaboration workspace.** Multi-channel access (Web Widget, WeChat, Telegram, Slack, email), LLM orchestration (OpenAI, Anthropic), RAG knowledge base (documents, Q&A, website crawling), and MCP tool store. Smart handoff to human agents with unified Agent Workspace. One-click bootstrap deployment [citation:8]. |
| **[Frappe Helpdesk](https://github.com/frappe/helpdesk)** | [![Stars](https://img.shields.io/github/stars/frappe/helpdesk?style=social&color=white)](https://github.com/frappe/helpdesk/stargazers) | Modern open-source customer service platform built on Frappe framework (~3,100 stars). SLAs with business hours, auto-assignment by priority/type/team/workload, unlimited agents with no seat fees, Google/Microsoft/OIDC sign-in, and customer sync with ERPNext. Extensible for AI/RAG integrations without assembling a model stack from scratch [citation:10]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Chatty](https://github.com/PersonaliAI/chatty)** | [![Stars](https://img.shields.io/github/stars/PersonaliAI/chatty?style=social&color=white)](https://github.com/PersonaliAI/chatty/stargazers) | Open-source, self-hostable Zendesk and Intercom alternative for AI customer support. Features chat widget, shared inbox, real-time voice, multimodal RAG, and MCP. Managed-Supabase architecture with Docker Compose, Railway, and Render deployment profiles [citation:5]. |
| **[Znuny](https://github.com/znuny/Znuny)** | [![Stars](https://img.shields.io/github/stars/znuny/Znuny?style=social&color=white)](https://github.com/znuny/Znuny/stargazers) | LTS fork of OTRS Community Edition. One of the most flexible web-based ticketing systems for customer service, help desk, and IT service management. Perl-based with full customer self-service portal and workflow automation [citation:7]. |
| **[Helpy](https://github.com/helpyio/helpy)** | [![Stars](https://img.shields.io/github/stars/helpyio/helpy?style=social&color=white)](https://github.com/helpyio/helpy/stargazers) | Modern open-source helpdesk with knowledgebase, community discussions, and support tickets integrated with email. MIT licensed. A lighter-weight option for teams wanting support automation without enterprise complexity [citation:11]. |

**Frameworks for building custom systems**: Combine **Libredesk** for a lightweight omnichannel desk with minimal infrastructure, **Owly** for full AI agent automation across WhatsApp and voice, and **Inbxer** for account-aware B2B support with human-controlled AI drafting—all deployable via Docker without per-resolution or per-seat fees. For teams already on Frappe/ERPNext, **Frappe Helpdesk** integrates natively.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Support automation platforms handle customer PII and conversation data; enforce role-based access, audit logging, and compliance with applicable data protection regulations. AI-drafted responses should be reviewed before reaching customers.
- **AI automation pricing is shifting toward outcome-based models.** Intercom charges $0.99 per Fin outcome—a 10-agent team with 2,000 resolutions/month pays ~$1,980 in AI outcomes alone. Open-source alternatives like **Owly** and **Inbxer** eliminate per-resolution fees but require self-hosting effort. **Inbxer is explicitly designed for human-controlled AI** ("AI drafts, humans decide"), while **TGO** and **Owly** offer more autonomous agent behavior. Choose based on your risk tolerance for automated customer responses [citation:3][citation:6][citation:8].

---

**Made for support operations managers, CX leaders, helpdesk administrators, and developers building automation infrastructure.**  
Let's make customer support automation more open, controllable, and efficient.
