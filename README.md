<div align="left">

### Full-Stack Developer · .NET 8 + React · AWS ECS · São Paulo, BR ##

Sou desenvolvedor com trajetória construída em ambientes de missão crítica no mercado financeiro — B3, Itaú e Bradesco — especialista na sustentação de sistema legado, alta volumetria, bases de dados críticas (SQL Server, Oracle, Sybase) e ciclos de entrega controlados por GMUD.

Nos últimos anos evolui para um stack moderno full-stack e cloud-native. 
Hoje trabalho com .NET 8 (C#), React/TypeScript, Clean Architecture e DevOps completo: infraestrutura como código com Terraform, pipelines no GitHub Actions e deploy em AWS ECS Fargate com ALB, EFS e ECR.

Atualmente desenvolvo o AMR SYSTEM — ecossistema ERP corporativo com 10 módulos (Financeiro, Core, RH, Compras, Analytics, CRM, WMS, TMS, entre outros), integrações via RabbitMQ + MassTransit e autenticação JWT. É o projeto que consolida e demonstra toda a minha stack atual, do back ao cloud.
Stack: C# · .NET 8 · React · TypeScript · SQL Server · SQLite · Docker · Terraform · AWS (ECS, ECR, ALB, EFS) · GitHub Actions · RabbitMQ · Clean Architecture. ##

**Desenvolvedor de sistemas industriais · MES & ERP · São Paulo, BR**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/progalexramos/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/al-ramos)

</div>

---

## 🏭 AMR ECOSYSTEM

Sistema de gestão industrial modular — MES + ERP — desenvolvido do zero com arquitetura limpa, CQRS e deploy em cloud.

> Cobrindo chão de fábrica, financeiro, RH, compras, logística e analytics numa única plataforma integrada.

### 📦 Módulos

| Módulo | Descrição | Status |
|--------|-----------|--------|
| 🏭 **AMR Forms Fábrica** | MES — controle de produção e ordens de fabricação | 🔄 Em desenvolvimento |
| 💰 **AMR Financeiro** | Contas a pagar/receber, fluxo de caixa, NF-e | 🔄 Em desenvolvimento |
| 🧠 **AMR Core** | ERP base — cadastros, autenticação, integrações | 🔄 Em desenvolvimento |
| 👥 **AMR RH** | Gestão de pessoas e ponto eletrônico | 📋 Planejado |
| 🛒 **AMR Compras** | Pedidos, fornecedores e cotações | 📋 Planejado |
| 📊 **AMR Analytics** | Dashboards e relatórios em tempo real | 📋 Planejado |
| 🌐 **Portal do Cliente** | Acesso externo via web | 📋 Planejado |
| 📦 **AMR WMS** | Gestão de armazém e estoque | 📋 Planejado |
| 🚛 **AMR TMS** | Gestão de transporte e logística | 📋 Planejado |
| 🤖 **AMR IA** | Módulo de inteligência artificial embarcada | 📋 Planejado |

---

## 🛠️ Stack Tecnológica

### Backend
![.NET](https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![Entity Framework](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![MediatR](https://img.shields.io/badge/MediatR_CQRS-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### Infra & DevOps
![AWS](https://img.shields.io/badge/AWS_ECS_Fargate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Arquitetura
```
Clean Architecture  ·  CQRS + MediatR  ·  DDD  ·  Event-Driven (RabbitMQ)
REST API  ·  Multi-tenant  ·  Microserviços
```

---

## 🗺️ Roadmap — Release 1.0

```
Sprint 1  ✅  AMR Core + Forms Fábrica     (28/04)
Sprint 2  ✅  BackgroundService + Infra     (29/04)
Sprint 3  ✅  AMR Financeiro               (13/05)
Sprint 4  🔄  AMR RH + Compras
Sprint 5  📋  Analytics + Mobile
Sprint 6  📋  Portal do Cliente + IA
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
         🎯  Release 1.0
```

---

## 💧 Hydac Services — Workflow Management (BPM)

> Plataforma de **BPM corporativo** desenvolvida para a **Hydac** (indústria hidráulica) em parceria com a **Mac Gestão**.
> Substitui 7 processos que rodavam em Excel puro por um sistema integrado com rastreabilidade total e controle de SLA.

[![Demo](https://img.shields.io/badge/Demo_ao_Vivo-v5.0_SLA_Visual-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://hydac-services-hub.netlify.app/)
[![Repo](https://img.shields.io/badge/GitHub-hydac--services--pb88-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/al-ramos/hydac-services-pb88)

### 📊 Escopo

| Processos especificados | Departamentos envolvidos | Etapas mapeadas |
|:-----------------------:|:------------------------:|:----------------:|
| **7** | **10** | **190+** |

### 🔄 Fluxo do Sistema

```
USUÁRIO grava ação
  ↓
CQRS Command executado
  ↓
Evento disparado via RabbitMQ
  ↓
Próximo departamento recebe em tempo real (SignalR)
  ↓
Formulário carrega automaticamente (Blazor Server)
  ↓
Dados persistidos em MariaDB
```

### 🧰 Stack

| Camada | Tecnologia |
|--------|------------|
| Frontend | Blazor Server + MudBlazor |
| Backend | .NET 9 · CQRS · Clean Architecture |
| Messaging | RabbitMQ + MassTransit |
| Banco de Dados | MariaDB + EF Core 9 |
| Autenticação | Azure AD / LDAP |
| Deploy | Docker + GitHub Actions CI/CD |

### 📋 Status

| Fase | Status |
|------|--------|
| Discovery & Especificação | ✅ Completo (7 processos, 7 diagramas UML) |
| Prototipagem | ✅ Completo (Netlify v5.0 validado) |
| Proposta Comercial | ✅ Completo |
| Arquitetura & Design | ✅ Completo |
| Desenvolvimento | ⏳ Aguardando aprovação do cliente |

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=al-ramos&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=al-ramos&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*Construindo o futuro da gestão industrial, um sprint de cada vez.*

</div>
