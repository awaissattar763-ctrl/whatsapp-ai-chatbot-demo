# WhatsApp AI Chatbot (Concept Demo)

Interactive concept demo for a **WhatsApp Business AI chatbot** built on the
WhatsApp Business API + n8n orchestration + an LLM.

- **Live demo:** https://awaissattar763-ctrl.github.io/whatsapp-ai-chatbot/
- `index.html` — WhatsApp-styled chat simulation for a restaurant: menu/catalog
  cards, table booking with availability, hours/location, delivery, human handoff,
  after-hours queuing (scripted replies mirroring production behavior)
- `workflow.json` — import-ready n8n blueprint:
  `WA webhook → business-hours check → Switch(intent) → OpenAI → WA reply → Sheets log`,
  with booking-availability lookup, after-hours queue branch, and staff-alert escalation

**Why this gap:** Upwork's 2026 in-demand-skills data shows AI Chatbot Development
growing +71% YoY; the job feed also surfaced WhatsApp chatbot roles. This demo
also backs the "auto-replies" line in Pakistan WhatsApp outreach.

**Honest labeling:** every reply is a scripted simulation of the production
chatbot's behavior. No live WhatsApp backend is connected. Built as a proposal
and outreach asset — shows approach, not a client deployment.
