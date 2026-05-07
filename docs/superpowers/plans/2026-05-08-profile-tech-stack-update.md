# Profile Tech Stack Update Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Update the GitHub profile README to display full-stack badges (frontend + backend + AI + database + DevOps) instead of frontend-only.

**Architecture:** Single-file change — replace the entire README.md content with the new flat-grouped badge layout. No code, no build, no tests.

**Tech Stack:** shields.io badges with Markdown syntax

---

### Task 1: Replace README.md with updated tech stack badges

**Files:**
- Modify: `README.md`

- [ ] **Step 1: Replace README.md content**

Replace the entire file with:

```markdown
### Hi there 👋

![Go](https://img.shields.io/badge/-Go-%2300ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/-Java-%23ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/-Python-%233776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-%23F7DF1C?style=flat-square&logo=javascript&logoColor=000000&labelColor=%23F7DF1C&color=%23FFCE5A)
![Node.js](https://img.shields.io/badge/-Node.js-%23339939?style=flat-square&logo=node.js&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-%23E44D27?style=flat-square&logo=html5&logoColor=ffffff)
![CSS3](https://img.shields.io/badge/-CSS3-%231572B6?style=flat-square&logo=css3)

![React](https://img.shields.io/badge/-React-%23282C34?style=flat-square&logo=react)
![Vue.js](https://img.shields.io/badge/-Vue.js-%232c3e50?style=flat-square&logo=vuedotjs)
![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-%231a202c?style=flat-square&logo=tailwind-css)
![Sass](https://img.shields.io/badge/-Sass-%23CC6699?style=flat-square&logo=sass&logoColor=ffffff)
![Less](https://img.shields.io/badge/-Less-%23173051?style=flat-square&logo=less&logoColor=ffffff)

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-%236DB33F?style=flat-square&logo=springboot&logoColor=white)
![Gin](https://img.shields.io/badge/-Gin-%2300ADD8?style=flat-square&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-%23009688?style=flat-square&logo=fastapi&logoColor=white)
![NestJS](https://img.shields.io/badge/-NestJS-%23E0234E?style=flat-square&logo=nestjs&logoColor=white)

![LangChain](https://img.shields.io/badge/-LangChain-%231C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-%23412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-%23D97757?style=flat-square&logo=anthropic&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/-LlamaIndex-%237C3AED?style=flat-square&logo=llamaindex&logoColor=white)

![MySQL](https://img.shields.io/badge/-MySQL-%234479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-%234169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-%2347A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-%23DC382D?style=flat-square&logo=redis&logoColor=white)

![Docker](https://img.shields.io/badge/-Docker-%232496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-%23326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-%23009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-%232671E5?style=flat-square&logo=githubactions&logoColor=white)

![Vite](https://img.shields.io/badge/-Vite-%23A643F8?style=flat-square&logo=vite&logoColor=#d595fa)
![Webpack](https://img.shields.io/badge/-Webpack-%232C3A42?style=flat-square&logo=webpack)
![ESLint](https://img.shields.io/badge/-ESLint-%234B32C3?style=flat-square&logo=eslint)
![Prettier](https://img.shields.io/badge/-Prettier-%234B32C3?style=flat-square&logo=prettier)
![Git](https://img.shields.io/badge/-Git-%23F05032?style=flat-square&logo=git&logoColor=%23ffffff)
![VS Code](https://img.shields.io/badge/-VSCode-%23007ACC?style=flat-square&logo=visual-studio-code)
```

- [ ] **Step 2: Verify badges render correctly**

Open the file locally or push to GitHub and check the profile page. All badge images should load without broken icons.

- [ ] **Step 3: Commit**

```bash
git add README.md
git commit -m "Update tech stack badges: add backend, AI, database, DevOps"
```
