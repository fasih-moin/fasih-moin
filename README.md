<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:0F172A,100:6FDA44&amp;height=170&amp;section=header&amp;text=Muhammad%20Fasih%20Ud%20Din&amp;fontSize=38&amp;fontColor=ffffff&amp;fontAlignY=36&amp;desc=API%20Integration%20%26%20AI%20Automation&amp;descAlignY=58&amp;descSize=16&amp;descColor=E2E8F0&amp;animation=fadeIn" width="100%" />

<a href="https://fasih-alpha.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=18&amp;pause=1200&amp;color=6FDA44&amp;center=true&amp;vCenter=true&amp;width=620&amp;lines=I+connect+your+tools+so+data+moves+on+its+own.;n8n+%C2%B7+Make+%C2%B7+Zapier+%E2%80%94+and+Python+when+they+hit+a+wall.;AI+workflows+that+actually+earn+their+keep." alt="Typing intro" />
</a>

<br/>

<a href="YOUR_UPWORK_PROFILE_URL"><img src="https://img.shields.io/badge/Hire%20me%20on-Upwork-6FDA44?style=for-the-badge&amp;logo=upwork&amp;logoColor=white" alt="Upwork" /></a>
<a href="https://fasih-alpha.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-fasih--alpha.vercel.app-0F172A?style=for-the-badge&amp;logo=vercel&amp;logoColor=white" alt="Portfolio" /></a>
<a href="https://linkedin.com/in/muhammad-fasih-ud-din-b50323323"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:fasihuddin.moin@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-EA4335?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email" /></a>

</div>

<br/>

> **I help businesses stop copy-pasting between tools.** I build integrations and automations in n8n, Make and Zapier, drop into custom Python the moment no-code hits its ceiling, and add AI only where it pays for itself.

<br/>

## 👋 About me

<table>
<tr>
<td width="50%" valign="top">

**What I bring**

- ⚡ Fast builds in **n8n, Make & Zapier**
- 🐍 **Custom Python** when a platform can't do it reliably
- 🔐 The unglamorous parts done right: OAuth, API keys, rate limits, pagination, webhooks, retries
- 🛡️ Error handling, logging & security from day one, not bolted on

</td>
<td width="50%" valign="top">

**How I work**

- 🧭 **Honest scoping.** If automation won't help, I'll tell you before building anything
- 📚 **Clear documentation.** You own your system; you don't depend on me
- 🎓 BS Computer Science, ITU Lahore
- 📍 Lahore, Pakistan · working with clients worldwide

</td>
</tr>
</table>

## 💼 What I can build for you

<table>
<tr>
<td width="50%" valign="top">

### 🔗 Integrations
Connect the tools you already run on (**Shopify, Stripe, QuickBooks, HubSpot, Slack, Google Workspace** and more) so data syncs automatically.

</td>
<td width="50%" valign="top">

### ⚡ Workflow automation
Lead routing, invoice follow-ups, onboarding sequences, inventory alerts, built on whichever of **n8n, Make or Zapier** fits your stack.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 AI agents & LLM workflows
Support-ticket triage, invoice & document extraction, lead qualification, content repurposing, and human-reviewed auto-replies, powered by **Claude, GPT or Gemini**.

</td>
<td width="50%" valign="top">

### 🐍 Custom Python
For what no-code can't reliably handle: complex auth flows, high-volume webhook processing, custom retry & dedup logic, exposed as clean **FastAPI** services.

</td>
</tr>
</table>

## 🚀 Flagship build: Resilient Webhook Processor

> It started in n8n and hit a wall, so I rewrote the one piece that needed it in Python.
> It's built for integrations that can't afford to **silently drop** or **silently duplicate** an event.

```mermaid
flowchart LR
    A([Incoming webhook]) --> B{Signature valid?}
    B -- No --> R[Reject and log]
    B -- Yes --> C{Idempotency key seen before?}
    C -- Yes --> D[Acknowledge and skip duplicate]
    C -- No --> E[Process event]
    E --> F{Downstream OK?}
    F -- No --> G[Retry with exponential backoff]
    G --> E
    F -- Yes --> H([Store key and log success])
```

| Feature | Why it matters |
|---|---|
| ✅ **Signature verification** | Only trusted senders get processed |
| ✅ **Idempotency-key dedup** | Retried events never run twice |
| ✅ **Exponential backoff retries** | Downstream hiccups don't lose data |
| ✅ **Full audit logging** | Every event is traceable when debugging |

<p>
  <a href="YOUR_WEBHOOK_PROCESSOR_REPO_URL"><img src="https://img.shields.io/badge/View%20the%20code-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="View the code" /></a>
</p>

## 🛠 Tech stack

| Area | Tools |
|---|---|
| **Automation** | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white) ![Zapier](https://img.shields.io/badge/Zapier-FF4A00?style=flat-square&logo=zapier&logoColor=white) |
| **APIs & integration** | ![REST APIs](https://img.shields.io/badge/REST%20APIs-02569B?style=flat-square&logo=swagger&logoColor=white) ![Webhooks](https://img.shields.io/badge/Webhooks-000000?style=flat-square&logo=webhooks&logoColor=white) ![OAuth](https://img.shields.io/badge/OAuth%202.0-3C3C3D?style=flat-square&logo=auth0&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) |
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **AI & LLMs** | ![Claude](https://img.shields.io/badge/Claude%20API-CC785C?style=flat-square&logo=anthropic&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-F59E0B?style=flat-square&logo=bookstack&logoColor=white) |

## 🔄 How a project with me goes

```
 1. Discover   →  2. Scope honestly  →  3. Build & test  →  4. Document  →  5. Hand over
 your tools &     what's worth          error handling,      runbooks &      you own it,
 pain points      automating (or not)   logging, retries     walkthroughs    no lock-in
```

## 🏆 Certifications

| | Certification |
|:-:|---|
| <img src="https://cdn.simpleicons.org/google/4285F4" width="20" /> | **Google Cybersecurity Professional Certificate** |
| <img src="https://cdn.simpleicons.org/ibm/052FAD" width="20" /> | **IBM: Generative AI for Cybersecurity** |
| <img src="https://cdn.simpleicons.org/coursera/0056D2" width="20" /> | **AI Security Specialization** |
| <img src="https://cdn.simpleicons.org/google/4285F4" width="20" /> | **Google AI Essentials** |

<br/>

<div align="center">

### 💬 Have a process that eats hours every week?

**Tell me about it. I'll tell you honestly whether it's worth automating.**

<a href="YOUR_UPWORK_PROFILE_URL"><img src="https://img.shields.io/badge/Start%20a%20project-6FDA44?style=for-the-badge&amp;logo=upwork&amp;logoColor=white" alt="Start a project" /></a>
<a href="mailto:fasihuddin.moin@gmail.com"><img src="https://img.shields.io/badge/fasihuddin.moin%40gmail.com-EA4335?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:6FDA44,100:0F172A&amp;height=100&amp;section=footer" width="100%" />

</div>
