# Awesome-AI-Productivity-Service-Copilot

# Awesome-AI-Productivity-Service-Copilot

**Top AI Productivity Service Copilot (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Agent Assist, Drafting Automation, Context Summarization & Self-Hosted Support Copilots*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Productivity & Service Copilot**. These tools sit beside human agents—drafting replies, summarizing case history, surfacing knowledge, and reducing handle time—from fully managed platforms with deep CRM integration to open-source agent frameworks that give teams control over their LLM provider and data.



**Examples** include Microsoft Copilot for Service, Zendesk Agent Copilot, Intercom Copilot, Kustomer KIQ Copilot, Forethought Assist, Salesforce Einstein Copilot, Freshworks Freddy AI Copilot, Gladly Sidekick, LivePerson Copilot, and Ada Copilot (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted agent assist, drafting, and open support automation. **Critical note**: True open-source service copilots are rare—**GopherAgent** is the most complete open-source agent framework with human-in-the-loop approvals, audit logging, and multi-provider LLM support , but it is a building block, not a turnkey copilot. **Owly** provides a complete self-hosted support agent with an admin dashboard and multi-channel support , though its copilot capabilities are less mature than commercial offerings. No open-source project matches Microsoft Copilot for Service's native CRM integration or Zendesk Agent Copilot's procedure generation from internal sources, but for teams wanting to build custom copilot workflows, the foundations exist.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The AI customer service and real-time agent assist software market is estimated at **$15B–$20B in 2025–2026** (scaling past $140B+ by the mid-2030s at an annual growth rate of ~25%). The sector exhibits a distinct split in market concentration: it is **highly concentrated at the enterprise CRM/data system-of-record layer** (dominated by titans like Microsoft, Salesforce, and Zendesk), but **moderately-to-highly fragmented at the specialized AI copilot and agentic application layer**, where emerging point solutions and fast-iterating startups vigorously compete alongside open-source frameworks.

## SaaS/Hosted Platforms

| Company / Product | Size (Revenue / Valuation) | Pricing (Starting Tier) | Free Tier / Trial Limits | Key Features & Best For |
| :--- | :--- | :--- | :--- | :--- |
| **Microsoft Copilot for Service** | ~$3.1T Market Cap / $245B+ Rev | $50/user/month standalone (or $40/user/month add-on with M365 Copilot; included in Dynamics 365 Customer Service Premium at $135/user/month) | No standalone free plan or trial; 30-day trial available via broader Dynamics 365 Customer Service | Deep CRM integrations (Dynamics 365, Salesforce, ServiceNow), context-aware drafting, real-time call summarization. Best for Microsoft-centric organizations. |
| **Salesforce Einstein Copilot / Agentforce** | ~$280B Market Cap / $38B+ Rev | $165/user/month (Sales Cloud / Service Cloud Enterprise starting tier; Agentforce usage billed separately) | 30-day free trial of Service Cloud (sample data and workflows included); free Developer Edition environment | Native Service Cloud CRM integration, workflow automation, knowledge surfacing. Best for organizations committed to Salesforce CRM. |
| **Zendesk Agent Copilot** | $10.2B Valuation (Acquired) / ~$2B Rev | $50/agent/month add-on below Enterprise (included in Suite Enterprise, which starts at $115/agent/month) | 14-day free trial of Suite Professional (no credit card required; talk limited to 2 min/call, one-time 14-day extension available) | Procedure generation directly from internal sources, Admin Copilot with 70+ proactive workflow recommendations. Best for Zendesk workspace users. |
| **Intercom Copilot** | $3.6B Valuation (Acquired by Salesforce) / ~$400M ARR | $39/seat/month (Essential tier base) + $35/user/month for unlimited Copilot add-on | 14-day free trial of full platform features; paid seats include a permanent free allowance of 10 Copilot conversations/month | Inbox assistant for real-time answer surfacing, message drafting, and translation. Best for teams wanting agent assist integrated alongside Fin AI. |
| **Freshworks Freddy AI Copilot** | ~$3.4B Market Cap / ~$840M Rev | $29/agent/month (Freshdesk Pro annual tier base) + Freddy Copilot add-on | 14-day free trial of Enterprise features; permanent free plan for up to 2 agents (includes 500 free Freddy AI sessions on Pro/Enterprise trial) | Affordable per-seat ticketing copilot, automated draft responses, ticket summarization. Best for cost-conscious support teams. |
| **Ada Copilot** | $1.2B Valuation / ~$70M+ ARR | $30,000/year (~$2,500/month custom entry contract floor; included in Pro, Team, and Enterprise packages) | No free tier; no public self-serve free trial (custom proof-of-concept / evaluation sandboxes available via enterprise sales) | Cross-application desktop overlay driving external tools, automated playbook execution. Best for enterprise multi-channel service centers. |
| **Forethought Assist** | >$200M Valuation (Acquired by Zendesk) / $115M+ Raised | Custom quote-only enterprise contracts (typically starts at ~$50–$100/agent/month platform add-on) | No free tier; no self-serve free trial (offers customized guided Proof of Value / POV pilot using historical support data) | Real-time agent assist alongside Solve and Triage, automated intent routing and macro recommendations. Best for large support teams already using Zendesk/Forethought. |
| **Kustomer KIQ Copilot** | ~$250M Valuation (Spinout from Meta) | $30/user/month standalone copilot add-on (Kustomer platform base starts at $89/user/month Enterprise) | No free tier; no public self-serve free trial (custom sales-led demo and proof-of-concept evaluation available upon request) | Real-time suggested responses, conversation summarization, tone adjustment within CRM. Best for high-volume D2C service operations (>50 tickets/agent/day). |
| **Gladly Sidekick** | ~$415M Valuation / ~$48M ARR | $150/agent/month (Hero entry plan, 10-seat minimum; + $0.25/payment or AI resolution add-ons) | No core free plan; no self-serve free trial for core platform (occasional 30-day trial offered on specific Shopify app store plugins) | Lifelong customer timeline conversation tracking, AI sidekick assistance, chat payments. Best for retail and D2C brands. |
| **LivePerson Copilot** | ~$40M Market Cap / ~$240M Rev | Custom enterprise quote; available strictly on Gold entitlement tier (requires minimum token package commitments) | No free tier; no self-serve free trial (enterprise demonstrations and custom-scoped sandbox pilots available via sales) | Conversational Cloud generative copilot with BYO-LLM integration and automated routing. Best for enterprise contact centers on LivePerson Gold. |



## Open-Source GitHub Projects



- **GopherAgent**

  **Open-source AI agent framework in Go** (Apache-2.0) — **the most complete open-source foundation for building a service copilot**, with production-oriented features . **Features**: **Multi-provider**—OpenAI, Anthropic, Gemini, Vertex, OpenRouter, and OpenAI-compatible backends; **custom tools** with schema derived from Go structs and middleware chain for logging, timing, rate limiting, and tracing; **sub-agents & async**—conversation forking, background workers, task tracking; **cross-session memory**—post-session consolidator distills transcripts into notes for future sessions; **observability**—OpenTelemetry traces and metrics; **audit log (experimental)**—HMAC-signed who-did-what records over OTLP, optionally fail-closed; **evaluation**—trajectory + answer + HITL grading with CI-ready CLI; **human-in-the-loop** approvals over HTTP . **Tech stack**: Go. **Deploy**: Self-hosted (Go module). **Trade-off**: **Framework, not a copilot**—you build the agent logic, tools, and UI; requires Go engineering. **Best for**: developers wanting a production-grade foundation for building custom service copilots with audit trails and HITL—especially those wanting Go performance and OpenTelemetry-native observability.



- **Owly**

  **Open-source AI customer support agent** (MIT) — **the most complete self-hosted support agent with copilot-adjacent features** . **Features**: **Multi-channel**—WhatsApp, email, phone; **AI conversations** with OpenAI GPT, function calling, RAG knowledge base, automatic ticket creation, customer history; **admin dashboard**—unified inbox, customer CRM, ticket system, analytics; **automation**—routing rules, SLA rules, canned responses; **audit log** and webhooks; **Docker Compose deployment** . **Tech stack**: Next.js 14, TypeScript, PostgreSQL, Prisma . **Deploy**: Self-hosted (Docker Compose; Node.js 20+, PostgreSQL 16+) . **Trade-off**: **Agent-focused, not copilot-focused**—it resolves customer inquiries autonomously; agent assist features are less developed than commercial copilots. **Best for**: teams wanting a self-hosted support agent with admin capabilities—especially those wanting to own their conversation data.



### Additional Strong Open-Source Options



- **No mature open-source service copilot exists as a standalone product.** Microsoft, Zendesk, Intercom, Kustomer, Forethought, Salesforce, Freshworks, Gladly, LivePerson, and Ada are proprietary. **GopherAgent** provides the agent framework; **Owly** provides the support agent. For a turnkey copilot, commercial platforms are required.



**Frameworks for building custom systems**: **GopherAgent** is the strongest open-source starting point for building a custom copilot with audit trails and HITL. **Owly** provides the support agent foundation. **Neither matches Microsoft Copilot for Service's CRM integration or Zendesk Agent Copilot's procedure generation.**



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Service copilot platforms handling customer conversations and agent workflows must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "standalone copilot" vs. "included copilot" vs. "agent framework" distinction is critical.** **Microsoft Copilot for Service** is a **standalone copilot**—it works across Dynamics, Salesforce, and ServiceNow for a per-user fee . **Zendesk Agent Copilot and Intercom Copilot** are **included or add-on copilots**—they are gated by plan tier (Zendesk $50/agent below Enterprise; Intercom $35/user for unlimited) . **Kustomer KIQ Copilot** is a **standalone add-on**—$30–$60/user/month on top of platform . **GopherAgent** is a **framework**—you build the copilot yourself . **Choose based on whether you need a turnkey copilot, an included add-on, or a build-it-yourself framework.**

- **Microsoft Copilot for Service's total cost depends on your existing stack.** Standalone is **$50/user/month** on top of your case management license; included in Dynamics Customer Service Premium at **$135/user/month** . **A 500-agent center on Salesforce + Copilot costs ~$1.29M/year** . **Model your existing platform costs before adding copilot.**

- **Zendesk Agent Copilot is $50/agent/month below Enterprise**—and the **Admin Copilot** (included with Suite Enterprise) offers 70+ proactive recommendations, saving Kaizen Gaming **11 hours/week** . **The trade-off**: full intelligent triage and custom agent roles require Enterprise, priced through sales.

- **Intercom Copilot's 10 conversations/month included with seats is a small allowance**—unlimited is **$35/user/month** . **For a 10-agent team, unlimited Copilot adds ~$4,200/year on top of seat and Fin costs** .

- **Kustomer KIQ Copilot's ROI is volume-dependent**—it requires **50+ tickets per agent per day** to achieve clear ROI; for lower-volume, higher-complexity agents, the ROI is marginal . **Do not evaluate for low-volume support teams.**

- **GopherAgent is the most complete open-source foundation for a service copilot**—multi-provider, audit logging, HITL approvals, and OpenTelemetry observability . **The trade-off**: framework, not product; requires Go engineering. **For teams wanting to build a custom copilot with full control, it is the strongest starting point.**

- Self-hosted open-source solutions require proper infrastructure (Go for GopherAgent, Next.js/PostgreSQL for Owly), security hardening, and ongoing maintenance. **Service copilots handle customer PII and conversation data**—ensure your deployment meets your organization's privacy and compliance requirements before processing live customer interactions.



---



**Made for support teams, service operations leaders, and organizations building transparent AI copilot solutions.**

Let's make AI Productivity & Service Copilots more open, data-driven, and agent-friendly.
