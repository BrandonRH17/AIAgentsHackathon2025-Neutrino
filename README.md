# Tasker

<p align="center">
  <img src="https://raw.githubusercontent.com/BrandonRH17/AIAgentsHackathon2025-Neutrino/main/assets/profile_picture.jpeg" alt="Profile Picture" width="300"/>
</p>

## Reinventing how high-ticket businesses sell — through AI agents that turn every customer interaction into a high-converting conversation.

---

## The Problem

### The cost of not responding fast

> ⏱️ According to a [MIT study](https://hbr.org/2011/03/the-short-life-of-online-sales-leads), companies that respond to leads within **5 minutes** are **100x more likely** to connect with them than those that wait 30 minutes or more.

Most sales teams respond hours or days later.

### Before Tasker

| 🏢 Real Estate Listing | 🚗 Automobile Dealership |
|------------------------|--------------------------|
| A customer asks about a new project. | A customer asks about a specific model. |
| The agent replies with the same generic PDF as 10 others. | The agent replies with the same generic PDF as 20 others. |
| If there's interest, they manually build a quote in Google Sheets and follow up via WhatsApp. | If interested, a manual quote is built in Google Sheets and followed up via WhatsApp. |
| Eventually, the deal may close. | Eventually, the deal may close. |

---

## Key Features

<p align="center">
  <img src="https://raw.githubusercontent.com/BrandonRH17/AIAgentsHackathon2025-Neutrino/main/assets/quote_ready.jpeg" alt="Quote Ready" width="600"/>
</p>

- Responds within the first 5 minutes of receiving a new lead via Facebook Ads or Instagram Forms.
- Contacts the lead using their preferred method (WhatsApp or Gmail).
- Sends generic prequalification content to engage the lead immediately.
- Notifies the assigned real estate advisor with lead details and status update.
- Automatically creates the client in the CRM and updates the deal status.
- Supports the advisor by generating personalized content or full quotes in under 30 seconds.

---
## Architecture

<p align="center">
  <img src="https://raw.githubusercontent.com/BrandonRH17/AIAgentsHackathon2025-Neutrino/main/assets/quote_ready_2.jpeg" alt="Quote Ready 2" width="700"/>
</p>

- **CRM:** Retool  
- **Agent Web App:** Static Web Apps  
- **Database:** Azure SQL  

- **Vector Searcher:** Azure AI Search  
- **Agent Functions:** Azure Logic Apps  
- **Agent Deployment:** Azure AI Agents  

<p align="center">
  <img src="https://raw.githubusercontent.com/BrandonRH17/AIAgentsHackathon2025-Neutrino/main/assets/Tasker%20-%20Architecture-General%20Architecture.drawio.png" alt="Tasker Architecture Diagram" width="800"/>
</p>

For more technical details, each folder in the repository documents the corresponding component in depth.

---
## Components

### Retool CRM

<p align="center">
  <img src="https://raw.githubusercontent.com/BrandonRH17/AIAgentsHackathon2025-Neutrino/main/assets/Retool%20-%20Clients.png" alt="Retool - Clients" width="600"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/BrandonRH17/AIAgentsHackathon2025-Neutrino/main/assets/Retool%20-%20Projects.png" alt="Retool - Projects" width="600"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/BrandonRH17/AIAgentsHackathon2025-Neutrino/main/assets/Retool%20-%20Resources.png" alt="Retool - Resources" width="600"/>
</p>


---
## 👇 Try It Yourself

> [🔗 Chat with Tasker](https://foundryagentchat-gdfjggbpbgchhadu.mexicocentral-01.azurewebsites.net/)

---

## Next Steps

<p align="center">
  <img src="[https://raw.githubusercontent.com/BrandonRH17/AIAgentsHackathon2025-Neutrino/main/assets/Retool%20-%20Resources.png](https://github.com/BrandonRH17/AIAgentsHackathon2025-Neutrino/blob/main/assets/new_lead.png)" alt="Tasker - Dancing" width="600"/>
</p>

- User validation through Redis  
- Deployment across channels such as WhatsApp, Telegram, and SMS

