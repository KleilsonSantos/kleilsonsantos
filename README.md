<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/219923809-b86dc415-a0c2-4a38-bc88-ad6cf06395a8.gif" width="500" alt="Banner animado">
</div>

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385dfa7ed2.gif" width="70" alt="">
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28" alt=""> Olá, eu sou Kleilson Santos<img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385dfa7ed2.gif" width="70" alt="">
</h1>

<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1500&color=22D3EE&center=true&vCenter=true&width=680&lines=Analista+de+Sistemas+S%C3%AAnior+%7C+CI%26T;Java+%C2%B7+Spring+Boot+%C2%B7+Kafka+%C2%B7+Microsservi%C3%A7os;AppSec+%26+DevSecOps+%7C+Setor+Financeiro;IA+Aplicada+%7C+GitHub+Copilot+%C2%B7+SDD+%C2%B7+MCP;Arquitetura+Hexagonal+%7C+GitOps+%7C+ArgoCD" alt="Analista de Sistemas Sênior na CI&T. Java, Spring Boot, Kafka e microsserviços. AppSec e DevSecOps. IA aplicada. Arquitetura hexagonal e GitOps." />
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/kleilson-dev-full-stack/" target="_blank">
    <img src="https://img.shields.io/badge/-CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A66C2" alt="LinkedIn"/>
  </a>
  <a href="mailto:kleilson@icloud.com">
    <img src="https://img.shields.io/badge/-EMAIL-EA4335?style=for-the-badge&logo=icloud&logoColor=white&labelColor=EA4335" alt="E-mail"/>
  </a>
  <a href="https://kleilson-portfolio.pages.dev" target="_blank">
    <img src="https://img.shields.io/badge/-SITE-F38020?style=for-the-badge&logo=cloudflare&logoColor=white&labelColor=F38020" alt="Portfólio"/>
  </a>
  <a href="https://github.com/KleilsonSantos/kleilson-portfolio">
    <img src="https://img.shields.io/badge/-PORTFÓLIO_REPO-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=181717" alt="Repositório do portfólio"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=KleilsonSantos&label=PROFILE+VIEWS&style=for-the-badge&color=22D3EE&labelColor=22D3EE" alt="Visualizações do perfil"/>
  <img src="https://img.shields.io/github/followers/KleilsonSantos?style=for-the-badge&label=FOLLOWERS&color=181717&labelColor=181717&logo=github" alt="Seguidores no GitHub"/>
</p>

---

## Sobre

**Analista de Sistemas Sênior na CI&T.** Engenharia backend e full stack sênior: microsserviços Java, AppSec e DevSecOps, com IA aplicada e governança.

Mais de 9 anos em sistemas do setor financeiro: microsserviços event-driven, Apache Kafka e AppSec. Autor do [AIOS](https://github.com/KleilsonSantos/ai-operating-system), plataforma open source de governança de IA no SDLC.

- 📍 Paulo Afonso, Bahia, Brasil · Remoto · Tempo integral
- ☕ Backend com **Java 21**, **Spring Boot 4.x** e **Apache Kafka**, em arquitetura hexagonal (Saga, DLQ e idempotência)
- 🔐 **AppSec e DevSecOps**: Mend (SCA), Fortify (SAST), SonarQube e OWASP Dependency-Check
- 🖥️ Full stack com Angular, React e TypeScript
- 🤖 IA aplicada: GitHub Copilot, Spec-Driven Development (SDD) e agentes customizados
- 🏅 Certificação Microsoft Azure AI Fundamentals (AI-900)

> Conteúdo alinhado ao [portfólio](https://kleilson-portfolio.pages.dev).

---

## Destaques

- **50%** de redução em vulnerabilidades com Mend (SCA) e Fortify (SAST)
- **20+ APIs RESTful** em Spring Boot com arquitetura hexagonal
- **≥ 80%** de cobertura de testes JaCoCo com JUnit 5 e Testcontainers
- Migração **Spring Boot 2→3→4** sem downtime, com eliminação das APIs depreciadas
- **GitOps** end-to-end com ArgoCD, Gitea e k3d
- **SDD** aplicado com 10 agentes Copilot, 7 prompts e 6 `applyTo`

---

## Projetos

### Em destaque

| Projeto | Descrição | Stack |
|---------|-----------|-------|
| 🧠 [AIOS](https://github.com/KleilsonSantos/ai-operating-system) | AI Operating System: control plane de governança de IA no SDLC (intent → políticas → agents-as-plugins → quality gates) | MCP, TypeScript, Turborepo, React, Vitest |
| 🔐 [VaultSpring](https://github.com/KleilsonSantos/VaultSpring) | Serviço Spring Boot de credenciais seguras, com segredos no HashiCorp Vault, autenticação JWT/RBAC e CI DevSecOps | Spring Boot, Vault, PostgreSQL, Flyway, Testcontainers |
| ☁️ [cloud-event-lab](https://github.com/KleilsonSantos/cloud-event-lab) | Lab de eventos cloud-native multi-cloud, com profiles local, AWS, Azure e GCP validados em emuladores (não é produção em cloud real) | Java 21, Spring Boot, OpenTelemetry, React, Kubernetes |

#### AIOS: fluxo de governança

```mermaid
flowchart LR
    subgraph AIOS["AIOS · control plane"]
        direction LR
        I[Intent] --> P[Políticas] --> A[Agents-as-plugins] --> Q[Quality gates]
    end
    C["AIOS Companion<br/>(experiência CLI/UI)"] -->|MCP / CLI| AIOS
```

<details>
<summary><strong>Outros projetos (6)</strong></summary>

| Projeto | Descrição | Stack |
|---------|-----------|-------|
| 💬 [AIOS Companion](https://github.com/KleilsonSantos/aios-companion) | Experiência CLI/UI sobre o AIOS via MCP (Conversation Manager, doctor e auditoria) | TypeScript, React 19, Vite, MCP |
| 📊 [infra-devtools](https://github.com/KleilsonSantos/infra-devtools) | Stack DevSecOps para times, com automação via Makefile | Docker, SonarQube, Prometheus, Grafana, OWASP |
| 🌐 [kleilson-portfolio](https://github.com/KleilsonSantos/kleilson-portfolio) | Código-fonte do [portfólio](https://kleilson-portfolio.pages.dev) | React, TypeScript, Vite, Cloudflare |
| ⚙️ [Mongo-RestFull-API](https://github.com/KleilsonSantos/Mongo-RestFull-API) | API REST com CRUD, autenticação JWT e middlewares de segurança | Node.js, Express, TypeScript, MongoDB |
| 🛡️ [appsec-daily-hub](https://github.com/KleilsonSantos/appsec-daily-hub) | Hub de conteúdo AppSec: vulnerabilidades críticas, ferramentas OWASP e tutoriais | HTML, OWASP |
| 🛒 [OrderProcessingSystem](https://github.com/KleilsonSantos/OrderProcessingSystem) | Processamento assíncrono de pedidos com foco em performance | Java, Spring Boot, Spring Batch, Redis |

</details>

---

## 📊 GitHub Summary Cards

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=KleilsonSantos&theme=github_dark">
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=KleilsonSantos&theme=github">
    <img alt="Detalhes do perfil" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=KleilsonSantos&theme=github_dark">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=KleilsonSantos&theme=github_dark">
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=KleilsonSantos&theme=github">
    <img alt="Estatísticas" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=KleilsonSantos&theme=github_dark">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=KleilsonSantos&theme=github_dark&utcOffset=-3">
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=KleilsonSantos&theme=github&utcOffset=-3">
    <img alt="Horário mais produtivo" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=KleilsonSantos&theme=github_dark&utcOffset=-3">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KleilsonSantos&theme=github_dark">
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KleilsonSantos&theme=github">
    <img alt="Repositórios por linguagem" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KleilsonSantos&theme=github_dark">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=KleilsonSantos&theme=github_dark">
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=KleilsonSantos&theme=github">
    <img alt="Linguagens mais usadas em commits" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=KleilsonSantos&theme=github_dark">
  </picture>
</p>

## 📈 Estatísticas

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=KleilsonSantos&show_icons=true&theme=dark_github&count_private=true">
    <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api?username=KleilsonSantos&show_icons=true&theme=light_github&count_private=true">
    <img alt="Estatísticas do GitHub" src="https://github-stats-extended.vercel.app/api?username=KleilsonSantos&show_icons=true&theme=dark_github&count_private=true">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=KleilsonSantos&theme=dark">
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=KleilsonSantos&theme=default">
    <img alt="Sequência de contribuições" src="https://streak-stats.demolab.com/?user=KleilsonSantos&theme=dark">
  </picture>
</p>

---

## 🛠️ Competências

### ☕ Backend & Arquitetura
<p>
  <img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 21">
  <img src="https://img.shields.io/badge/Spring_Boot_4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot 4.x">
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Apache Kafka">
  <img src="https://img.shields.io/badge/Arquitetura_Hexagonal-0F172A?style=for-the-badge" alt="Arquitetura Hexagonal">
  <img src="https://img.shields.io/badge/Microsservi%C3%A7os-0F172A?style=for-the-badge" alt="Microsserviços">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
</p>

### ☁️ DevSecOps & Cloud
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="ArgoCD">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white" alt="SonarQube">
  <img src="https://img.shields.io/badge/OWASP_Top_10-000000?style=for-the-badge&logo=owasp&logoColor=white" alt="OWASP Top 10">
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure">
  <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS">
</p>

### 🤖 AI Applied Engineering
<p>
  <img src="https://img.shields.io/badge/GitHub_Copilot-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Copilot">
  <img src="https://img.shields.io/badge/Spec--Driven_Development-22D3EE?style=for-the-badge&logo=gitbook&logoColor=white" alt="Spec-Driven Development">
  <img src="assets/badges/agentes-customizados.svg" alt="Agentes customizados">
  <img src="https://img.shields.io/badge/Prompt_Engineering-FF6F00?style=for-the-badge&logo=googlebard&logoColor=white" alt="Prompt Engineering">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/MCP-412991?style=for-the-badge&logo=protocol&logoColor=white" alt="MCP">
  <img src="https://img.shields.io/badge/Azure_AI--900-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure AI-900">
</p>

### 🌐 Frontend
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
</p>

### 🗃️ Dados & Observabilidade
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana">
  <img src="assets/badges/spring-actuator.svg" alt="Spring Actuator">
</p>
