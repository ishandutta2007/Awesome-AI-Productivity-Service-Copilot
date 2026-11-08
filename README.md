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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **Microsoft Copilot for Service**

  **Agent assist copilot** integrated with Dynamics 365, Salesforce, and ServiceNow. **Features**: Drafts customer responses, summarizes case history, suggests knowledge base articles; real-time call summarization and case-context-aware drafting . **Pricing**: **Standalone $50/user/month** (on top of existing case management license); **$40/user/month with M365 Copilot**; included in **Dynamics 365 Customer Service Premium at $135/user/month** . **Free tier**: None. **Best for**: Microsoft-centric organizations wanting copilot across multiple CRM platforms—**trade-off**: standalone requires paying for both your case management platform and the copilot add-on.



- **Zendesk Agent Copilot**

  **AI assistant embedded in Zendesk agent workspace**. **Features**: **Generates procedures directly from internal sources**—guides agents from day one; part of Zendesk's Resolution Platform with Resolution Learning Loop improving over time . **Admin Copilot** offers **70+ proactive recommendations** for workflow improvements, saving customers like Kaizen Gaming an average of **11 hours of admin work per week** . **Pricing**: **$50/agent/month add-on below Enterprise**; included in Suite Enterprise . **Free tier**: No free plan; trial available. **Best for**: Zendesk customers wanting copilot integrated with their helpdesk—**trade-off**: gated to paid add-on below Enterprise; full intelligent triage requires Enterprise.



- **Intercom Copilot**

  **AI assistant within Intercom inbox**. **Features**: Helps human agents find answers, draft replies, troubleshoot issues, and translate messages in real time; separate from Fin (which resolves autonomously) . **Pricing**: **All full-seat teammates get access with usage included for up to 10 conversations per month**; **unlimited usage add-on $35/user/month** on any plan . **Free tier**: 10 Copilot conversations/month included with seats. **Best for**: Intercom customers wanting agent assist without committing to unlimited usage—**trade-off**: 10 conversations/month is a small allowance; unlimited requires add-on.



- **Kustomer KIQ Copilot**

  **Real-time agent assist** within Kustomer. **Features**: Suggested responses, summarization, tone adjustment, conversation context . **Pricing**: **$30–$60/user/month standalone**; Kustomer Enterprise **$89/user/month**; Ultimate **$139/user/month** . **Free tier**: None. **Best for**: high-volume D2C service operations—**trade-off**: **ROI requires 50+ tickets per agent per day**; marginal for lower-volume, higher-complexity agents .



- **Forethought Assist**

  **Agent productivity copilot** within Forethought's support platform. **Features**: Assists agents alongside Solve (resolution) and Triage; **Proof of Value (POV) instead of free trial** . **Pricing**: **Quote-only**; platform access fee plus outcome-based pricing; POV model. **Free tier**: POV only. **Best for**: teams already evaluating Forethought Solve wanting unified agent and customer AI—**trade-off**: no self-serve evaluation.



- **Salesforce Einstein Copilot**

  **AI copilot within Salesforce Service Cloud**. **Pricing**: **Sales Cloud Enterprise from $165/user/month**; some Einstein features included; **Agentforce (AI Agents) uses new consumption-based pricing** since 2025 . **Free tier**: Developer Edition available. **Best for**: Salesforce customers wanting copilot within their CRM—**trade-off**: total cost of ownership is high; Agentforce consumption pricing adds unpredictability.



- **Freshworks Freddy AI Copilot**

  **AI copilot within Freshdesk**. **Pricing**: **$29/agent/month** (annual) for Freshdesk; **Freddy AI Copilot purchasable for any number of agents**; **500 free sessions** with Pro and Enterprise subscriptions (one-time) . **Free tier**: 500 sessions trial. **Best for**: Freshworks customers wanting copilot at accessible per-agent pricing—**trade-off**: session-based AI Agent pricing separate from copilot.



- **Gladly Sidekick**

  **AI sidekick within Gladly platform** (now called Gladly AI). **Features**: Gladly charges **$0.25 per successful payment over chat** . **Pricing**: Quote-only; payment processing fee separate. **Free tier**: None. **Best for**: retail and D2C brands wanting AI alongside unified customer history—**trade-off**: limited public pricing detail.



- **LivePerson Copilot**

  **Generative AI copilot** within LivePerson. **Pricing**: **Gold entitlement only**—Bronze, Silver, Gold packages with no fixed dollar price; token allowance requires sales confirmation . **Free tier**: None. **Best for**: LivePerson customers on Gold tier wanting copilot with BYO LLM—**trade-off**: no public pricing; token costs separate.



- **Ada Copilot**

  **Desktop overlay** that drives any app (per ADA pricing page). **Pricing**: **ADA Copilot included in Pro, Team, and Enterprise plans** . **Free tier**: Starter plan does not include Copilot. **Best for**: teams wanting an overlay copilot that works across applications—**trade-off**: newer product; limited independent validation.



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
