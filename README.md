# GainIt

**A full-stack platform helping junior developers gain real-world experience through structured projects**

[![Frontend](https://img.shields.io/badge/Frontend_Repo-React%2019-61DAFB?style=for-the-badge&logo=react)](https://github.com/LetsGainit/gainit-frontend)
[![Backend](https://img.shields.io/badge/Backend_Repo-.NET%208-512BD4?style=for-the-badge&logo=dotnet)](https://github.com/LetsGainit/Gainit)
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org)
[![Azure](https://img.shields.io/badge/Cloud-Azure-0078D4?style=for-the-badge&logo=microsoftazure)](https://azure.microsoft.com)

---

## 📦 Repositories

| | Repository | Tech |
|--|------------|------|
| **Frontend** | **[LetsGainit/gainit-frontend](https://github.com/LetsGainit/gainit-frontend)** | React 19, Vite, Azure Static Web Apps |
| **Backend** | **[LetsGainit/Gainit](https://github.com/LetsGainit/Gainit)** | .NET 8, PostgreSQL, Azure |

---

## 🎬 Demo

[![Watch Demo](https://img.youtube.com/vi/DRbK8Y0UX3M/maxresdefault.jpg)](https://www.youtube.com/watch?v=DRbK8Y0UX3M)

**[▶️ Watch the Full Demo on YouTube](https://www.youtube.com/watch?v=DRbK8Y0UX3M)**

---

## 💡 What is GainIt?

Junior developers are stuck in a loop: **jobs require experience, but you can't get experience without a job.**

**GainIt breaks this cycle** by connecting juniors with:
- **Template Projects** — Portfolio-worthy projects with clear scope and deliverables
- **Nonprofit Projects** — Real requests from organizations that need digital solutions

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🤖 **AI-Powered Discovery** | **Azure AI Search** with vector search for smart project matching and semantic search |
| 📊 **Smart Summaries** | AI-generated project insights and recommendations |
| 🔗 **GitHub Integration** | Pulls repo data for smart summaries, contribution stats, and user involvement tracking |
| 👥 **Role-Based System** | Tailored experiences for Gainers, Mentors, and Nonprofits |
| 📋 **Project Workspace** | Collaboration environment with milestones and task tracking |
| 🔐 **Enterprise Auth** | Azure AD B2C authentication |

---

## 🛠️ Tech Stack

> ☁️ **Fully deployed on Microsoft Azure** — frontend, backend, database, and all services

**Frontend:** React 19 • Vite 6 • React Router 7 • Azure MSAL • Azure Static Web Apps

**Backend:** .NET 8 • ASP.NET Core • EF Core • PostgreSQL • Azure AI Search • Azure OpenAI • Azure Blob Storage • GitHub API

---

## 🏗️ Architecture

```
                      ┌──────────────┐
                      │ Azure AD B2C │
                      └──────────────┘
                          ▲ │   ▲ │
                          │ │   │ │
               ┌──────────┘ │   │ └──────┐
               │ ┌──────────┘   └──────┐ │
               │ ▼                     │ ▼
        ┌──────────────┐       ┌──────────────┐       ┌──────────────┐
        │    React     │──────▶│  .NET 8 API  │─────▶│  PostgreSQL  │
        │   Frontend   │       │              │       │              │
        └──────────────┘       └──────┬───────┘       └──────────────┘
                                      │
                                      │
                       ┌──────────────┼──────────────┐
                       ▼              ▼              ▼
                 ┌──────────┐  ┌──────────┐  ┌──────────┐
                 │ Azure AI │  │  GitHub  │  │  Azure   │
                 │ Search   │  │  API     │  │  OpenAI  │
                 └──────────┘  └──────────┘  └──────────┘
```

---

## 🏆 Recognition

- ✅ **Accepted to Microsoft for Startups program**
- 🥉 **3rd place in college project contest**

---

## 👨‍💻 About

Final project for our **Computer Science degree**, demonstrating full-stack development, cloud architecture, and AI integration.
