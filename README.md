<div align="center">

<h1>AI Agents & Document Intelligence</h1>

<h3>255 production-ready n8n workflows &mdash; every credential stripped, every model current</h3>

<p>
<img alt="Workflows" src="https://img.shields.io/badge/workflows-255-EA4B71?style=for-the-badge">
<img alt="Secrets" src="https://img.shields.io/badge/secrets-0-brightgreen?style=for-the-badge">
<img alt="License" src="https://img.shields.io/badge/license-MIT-3b82f6?style=for-the-badge">
</p>

<p><em>AI agents, RAG chatbots, and document-extraction workflows for n8n.<br>Sanitized of all secrets, modernized to current n8n nodes and AI models, and continuously scanned by CI.</em></p>

<p><b><a href="#-whats-inside">What's Inside</a> &nbsp;·&nbsp; <a href="#-categories">Categories</a> &nbsp;·&nbsp; <a href="#-featured-workflows">Featured</a> &nbsp;·&nbsp; <a href="#-quick-start">Quick Start</a> &nbsp;·&nbsp; <a href="#-security">Security</a></b></p>

</div>

---

## 📦 What's inside

This repository collects **255 ready-to-import workflows** across **2 categories**. Every file has been engineered to the same standard:

| | |
|---|---|
| 🔐 **Zero secrets** | No credentials, API keys, instance IDs, webhook secrets, or personal data. Verified by GitHub secret scanning + gitleaks. |
| 🔄 **Current stack** | Latest AI models (GPT-4o, Claude 4.x, Gemini 2.5) and current n8n node types &mdash; no deprecated nodes, no 2023-era models. |
| ✅ **CI-validated** | Every push runs JSON/structure validation and a full-history secret scan. |
| 📁 **Organized** | Grouped by category so you find the right workflow in seconds. |

### Built with

<p>
<img alt="n8n" src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white">
<img alt="OpenAI" src="https://img.shields.io/badge/GPT--4o-412991?style=flat-square&logo=openai&logoColor=white">
<img alt="Telegram" src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white">
<img alt="Google Drive" src="https://img.shields.io/badge/Google%20Drive-4285F4?style=flat-square&logo=googledrive&logoColor=white">
<img alt="Airtable" src="https://img.shields.io/badge/Airtable-18BFFF?style=flat-square&logo=airtable&logoColor=white">
<img alt="Gmail" src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white">
<img alt="Google Sheets" src="https://img.shields.io/badge/Google%20Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white">
<img alt="Slack" src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white">
<img alt="Notion" src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white">
</p>

---

## 🗂️ Categories

| Category | Workflows | What it covers |
|---|:--:|---|
| 🤖 AI Agents & Chatbots | 169 | Autonomous agents and retrieval-augmented chatbots |
| 📄 Document & Data Extraction | 86 | PDF/OCR parsing, scraping, and structured extraction |

---

## ⭐ Featured workflows

*The most comprehensive automations in this collection.*

- **[Agent Workflow](workflows/ai-agents-chatbots/0910_Bitly_Datetime_Update_Webhook.json)** &mdash; `Event` trigger · 113 nodes · Gmail · Google Calendar · Google Docs · Google Sheets
- **[API Schema Extractor.json](workflows/document-data-extraction/API Schema Extractor.json)** &mdash; `Event` trigger · 88 nodes · HTTP · Gemini · Qdrant · Google Sheets
- **[Host Your Own AI Deep Research Agent with n8n, Apify and OpenAI o3.json](workflows/ai-agents-chatbots/Host Your Own AI Deep Research Agent with n8n, Apify and OpenAI o3.json)** &mdash; `Form` trigger · 87 nodes · OpenAI · LLM · HTTP · Notion
- **[Outputparserstructured Workflow](workflows/document-data-extraction/0719_Stopanderror_Splitout_Create_Webhook.json)** &mdash; `Form` trigger · 85 nodes · Notion · HTTP

---

## 📚 Browse by category


### 🤖 AI Agents & Chatbots

*Autonomous agents and retrieval-augmented chatbots — 169 workflows.*

| Workflow | Trigger | Built with | Nodes |
|---|:--:|---|:--:|
| [Agent Workflow](workflows/ai-agents-chatbots/0910_Bitly_Datetime_Update_Webhook.json) | `Event` | Gmail · Google Calendar · Google Docs · Google Sheets | 113 |
| [Host Your Own AI Deep Research Agent with n8n, Apify and O](workflows/ai-agents-chatbots/Host Your Own AI Deep Research Agent with n8n, Apify and OpenAI o3.json) | `Form` | OpenAI · LLM · HTTP · Notion | 87 |
| [RAG & GenAI App With WordPress Content](workflows/ai-agents-chatbots/1752_Postgres_Wordpress_Automation_Webhook.json) | `Event` | Postgres · WordPress · HTTP | 53 |
| [RAG & GenAI App With WordPress Content](workflows/ai-agents-chatbots/1942_Postgres_Wordpress_Automation_Webhook.json) | `Event` | Postgres · WordPress · HTTP | 53 |
| [RAG & GenAI App With WordPress Content](workflows/ai-agents-chatbots/WordPress - AI Chatbot to enhance user experience - with Supabase and OpenAI.json) | `Event` | OpenAI Embeddings · OpenAI · Postgres · WordPress | 53 |
| [BambooHR AI-Powered Company Policies and Benefits Chatbot](workflows/ai-agents-chatbots/BambooHR AI-Powered Company Policies and Benefits Chatbot.json) | `Event` | OpenAI Embeddings · OpenAI · LLM · AI Agent | 50 |
| [AI Powered RAG Chatbot for Your Docs + Google Drive + Gemi](workflows/ai-agents-chatbots/1185_Telegram_Wait_Automate_Webhook.json) | `Event` | Google Drive · Telegram · Webhook · Google Docs | 50 |
| [AI Agent for Top n8n Creators Leaderboard Reporting](workflows/ai-agents-chatbots/2052_Telegram_Splitout_Automation_Scheduled.json) | `Scheduled` | HTTP · Google Drive · Gmail · Telegram | 49 |
| [AI Agent  for Top n8n Creators Leaderboard Reporting](workflows/ai-agents-chatbots/1113_Telegram_Splitout_Automation_Scheduled.json) | `Scheduled` | HTTP · Google Drive · Gmail · Telegram | 49 |
| [All-in-One Telegram/Baserow AI Assistant  Voice/Photo/Save](workflows/ai-agents-chatbots/1305_Telegram_Splitout_Export_Webhook.json) | `Webhook` | Telegram · Webhook | 48 |
| [Memorybufferwindow Workflow](workflows/ai-agents-chatbots/0898_Code_Schedule_Create_Scheduled.json) | `Scheduled` | HTTP | 45 |
| [AI Agent  for n8n Creators Leaderboard - Find Popular Work](workflows/ai-agents-chatbots/1810_Limit_Splitout_Automate_Webhook.json) | `Manual` | HTTP | 43 |
| *…and 157 more* | | [`ai-agents-chatbots/`](workflows/ai-agents-chatbots/) | |


### 📄 Document & Data Extraction

*PDF/OCR parsing, scraping, and structured extraction — 86 workflows.*

| Workflow | Trigger | Built with | Nodes |
|---|:--:|---|:--:|
| [API Schema Extractor.json](workflows/document-data-extraction/API Schema Extractor.json) | `Event` | HTTP · Gemini · Qdrant · Google Sheets | 88 |
| [Outputparserstructured Workflow](workflows/document-data-extraction/0719_Stopanderror_Splitout_Create_Webhook.json) | `Form` | Notion · HTTP | 85 |
| [Selenium Ultimate Scraper Workflow](workflows/document-data-extraction/1711_Limit_Code_Automate_Webhook.json) | `Webhook` | HTTP · Webhook | 63 |
| [Selenium Ultimate Scraper Workflow](workflows/document-data-extraction/1900_Limit_Code_Automate_Webhook.json) | `Webhook` | HTTP · Webhook | 63 |
| [[n8n] Advanced URL Parsing and Shortening Workflow - Switc](workflows/document-data-extraction/0392_Stopanderror_GitHub_Automate_Webhook.json) | `Form` | HTTP · GitHub | 56 |
| [Advanced AI Powered Document Parsing & Text Extraction wit](workflows/document-data-extraction/1904_Telegram_Limit_Process_Webhook.json) | `Webhook` | Webhook · Gmail · HTTP · Google Sheets | 54 |
| [AI Data Extraction with Dynamic Prompts and Airtable.json](workflows/document-data-extraction/AI Data Extraction with Dynamic Prompts and Airtable.json) | `Webhook` | HTTP · LLM · OpenAI · Airtable | 51 |
| [Code_Extractfromfile_Create_Webhook_1.json](workflows/document-data-extraction/Code_Extractfromfile_Create_Webhook_1.json) | `Event` | HTTP · OpenAI · OpenAI Embeddings · Airtable | 50 |
| [AI Logo Sheet Extractor to Airtable](workflows/document-data-extraction/1437_Splitout_Code_Automation_Triggered.json) | `Form` | Airtable | 45 |
| [AI Logo Sheet Extractor to Airtable](workflows/document-data-extraction/1834_Splitout_Code_Automation_Triggered.json) | `Form` | Airtable | 45 |
| [AI Data Extraction with Dynamic Prompts and Baserow.json](workflows/document-data-extraction/AI Data Extraction with Dynamic Prompts and Baserow.json) | `Webhook` | Webhook · HTTP · LLM · OpenAI | 45 |
| [AI Logo Sheet Extractor to Airtable](workflows/document-data-extraction/Extract Information from a Logo Sheet using forms, AI, Google Sheet and Airtable.json) | `Form` | AI Agent · Airtable · OpenAI | 44 |
| *…and 74 more* | | [`document-data-extraction/`](workflows/document-data-extraction/) | |

---

## 🚀 Quick start

```text
1.  Pick a workflow from the categories above
2.  In n8n:  Workflows  →  ⋯  →  Import from File
3.  Open each node and add your own credentials
    (every credential slot is labelled  "Add your <service> credential")
4.  Activate — you're live
```

> **Nothing here can leak.** Every credential is blanked and labelled — you supply your own keys inside n8n's credential manager. No secret material ships in this repo.

---

## 🔒 Security

Security is enforced at three layers:

1. **At rest** — every workflow is stripped of credentials, `instanceId`, `pinData`, webhook UUIDs, emails, and hardcoded keys before it is committed.
2. **In CI** — each push runs structure validation plus a [gitleaks](https://github.com/gitleaks/gitleaks) scan across the full history and working tree. GitHub Actions are **pinned to commit SHAs** to prevent supply-chain tampering.
3. **On the platform** — **secret scanning**, **push protection**, **Dependabot**, and **branch protection** (required checks, linear history, no force-push) are enabled on this repository.

Report a concern via **Security → Report a vulnerability**. Full standard in [SECURITY.md](SECURITY.md).

---

## 🛠️ Engineered by basictechorg

Every workflow here is security-hardened, modernized to the current AI/n8n stack, tested, and reorganized by **basictechorg**. Built on templates from the open-source n8n community (MIT-licensed) — original authors retain rights to their workflow logic. Source licenses in [THIRD_PARTY_LICENSES/](THIRD_PARTY_LICENSES/) · details in [NOTICE](NOTICE).

## 📄 License

Released under the [MIT License](LICENSE).

<div align="center">
<br><sub>Maintained by <a href="https://github.com/basictechorg">basictechorg</a></sub>
</div>