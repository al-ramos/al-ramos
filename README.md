![AMR SYSTEM](./amr_github_banner.png)
<div align="left">

<h3>Engenheiro de Software · .NET 8 + AWS · São Paulo </h3>

Desenvolvedor com trajetória construída em ambientes de missão crítica no mercado financeiro — **B3, Itaú e Bradesco** — especialista em sustentação de sistemas legados, alta volumetria, bases de dados críticas (SQL Server, Oracle, Sybase) e ciclos de entrega controlados por GMUD.

Nos últimos anos evolui para um stack moderno full-stack e cloud-native. Hoje trabalho com **.NET 8 (C#)**, **React/TypeScript**, **Clean Architecture** e **DevOps completo**: infraestrutura como código com **Terraform**, pipelines no **GitHub Actions** e deploy em **AWS ECS Fargate** com ALB, EFS e ECR.

Atualmente desenvolvo o **AMR SYSTEM** — ecossistema ERP corporativo com 10 módulos, integrações via **RabbitMQ + MassTransit**, autenticação **JWT**, **32 testes unitários** passando e infra unificada na AWS. É o projeto que consolida e demonstra toda a minha stack atual, do back ao cloud.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/progalexramos/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/al-ramos)

</div>

---

## 🏭 AMR ECOSYSTEM  
(Ecossistema ERP corporativo full-suite — MES · WMS · TMS · CRM · HCM · BI — cloud-native na AWS, do zero com Clean Architecture e event-driven).

> Elimina sistemas isolados. Unifica financeiro, produção, RH, compras, logística e analytics com rastreabilidade total via event-driven.

### 📦 Módulos

| Módulo | Descrição | Entregue | Status |
|--------|-----------|----------|--------|
| 🧠 **AMR Core** | ERP base — produtos, fornecedores, clientes, estoque, pedidos de compra, dashboard | Sprint 4 | ✅ Produção |
| 💰 **AMR Financeiro** | Contas a pagar/receber, lançamentos, fluxo de caixa, plano de contas | Sprint 3 | ✅ Produção |
| 🏭 **AMR Forms Fábrica** | MES — ordens de fabricação, controle de produção | Sprint 1 | ✅ AWS ECS |
| 👥 **AMR RH** | Gestão de pessoas e ponto eletrônico | Sprint 6 | 📋 Planejado |
| 🛒 **AMR Compras** | Pedidos, fornecedores e cotações (módulo dedicado) | Sprint 6 | 📋 Planejado |
| 📊 **AMR Analytics** | Dashboards e relatórios em tempo real | Sprint 5 | 📋 Planejado |
| 🌐 **AMR Portal** | Acesso externo via web | Sprint 6 | 📋 Planejado |
| 🤖 **AMR IA** | Módulo de inteligência artificial embarcada | Sprint 6 | 📋 Planejado |
| 📦 **AMR WMS** | Gestão de armazém e estoque | Sprint 8 | 📋 Planejado |
| 🚛 **AMR TMS** | Gestão de transporte e logística | Sprint 9 | 📋 Planejado |

---

## 🛠️ Stack Tecnológica

### Backend
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![MediatR](https://img.shields.io/badge/MediatR_CQRS-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![JWT](https://img.shields.io/badge/JWT_Auth-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Serilog](https://img.shields.io/badge/Serilog-informational?style=for-the-badge&logo=dotnet&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=for-the-badge&logo=react&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

### Infra & DevOps
![AWS](https://img.shields.io/badge/AWS_ECS_Fargate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Arquitetura & Padrões
```
Clean Architecture  ·  CQRS + MediatR  ·  DDD
Event-Driven (RabbitMQ + MassTransit)  ·  REST API  ·  JWT Bearer
Health Checks  ·  Serilog Structured Logging  ·  Unit Testing (xUnit)
```

---

## ☁️ Infraestrutura AWS — AMR SYSTEM

```
                        ┌─────────────────────────────────┐
                        │     GitHub Actions CI/CD        │
                        │  (deploy-aws.yml por repositório)│
                        └────────────┬────────────────────┘
                                     │ docker build + push
                                     ▼
                        ┌─────────────────────────────────┐
                        │         AWS ECR (6 repos)        │
                        │  Core-API · Core-Web            │
                        │  Financeiro-API · Financeiro-Web │
                        │  Fábrica-API · Fábrica-Web       │
                        └────────────┬────────────────────┘
                                     │ pull image
                                     ▼
┌────────────────────────────────────────────────────────────┐
│                  Cluster ECS Fargate — amr-system           │
│                                                            │
│  ALB (:80)  ──► AMR-Financeiro  (Frontend + API :5015)    │
│  ALB (:8081) ──► AMR-Core       (Frontend + API :5001)    │
│  ALB (:8082) ──► AMR-Fábrica    (Frontend + API :5186)    │
│                                                            │
│  EFS (3 volumes persistentes)  ·  ECR (6 repositórios)    │
└────────────────────────────────────────────────────────────┘
             Provisionado via Terraform (IaC)
```

---

## 🔄 Arquitetura de Eventos — Integração entre Módulos

```
AMR Forms Fábrica
  │  Saída de ficha de produção
  │  ──► RabbitMQ (MassTransit)
  │                │
  │                ▼
  │       AMR Financeiro
  │         ContaPagar criada automaticamente
  │
  │  NF Transmitida
  └──► RabbitMQ (MassTransit)
                  │
                  ▼
         AMR Financeiro
           ContaReceber criada automaticamente
           LancamentoFinanceiro de crédito gerado
```

---

## 🗺️ Roadmap — Release 1.0

```
Sprint 1  ✅  AMR Core + Forms Fábrica          (28/04/2026)
Sprint 2  ✅  BackgroundService + Infra          (29/04/2026)
Sprint 3  ✅  AMR Financeiro + JWT + Docker      (13/05/2026)
Sprint 4  ✅  AMR Core completo + Dashboard      (27/05/2026)
Sprint 5  ⚡  Infra & CI/CD unificado AWS        (28/05 – 10/06/2026)  ← ATIVO
Sprint 6  🔜  AMR Portal + IA                   (11/06 – 24/06/2026)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
         🎯  Release 1.0  (24/06/2026)
```

### ✅ Sprint 5 — Infra & CI/CD (em andamento)
- [x] Terraform unificado — 1 cluster `amr-system`, 1 ALB (3 listeners), 3 EFS, 6 ECR, 6 ECS services
- [x] Dockerfiles AMR-Core (API + Web)
- [x] Dockerfile AMR-Fábrica corrigido (namespace RDS → AMR)
- [x] nginx.conf corrigido (porta 3000 → 80)
- [x] CI/CD GitHub Actions — `deploy-aws.yml` para AMR-Core e AMR-Fábrica
- [x] READMEs profissionais com diagrama de arquitetura (3 repos)
- [ ] `terraform apply` — provisionar infra unificada na AWS *(em andamento)*

---

## 🧪 Cobertura de Testes

| Módulo | Framework | Testes |
|--------|-----------|--------|
| AMR.Financeiro | xUnit | ✅ 15 passando |
| AMR.Core | xUnit | ✅ 13 passando |
| AMR.Forms.Fabrica | xUnit | ✅ 4 passando |
| **Total** | | **✅ 32 testes** |

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
Evento disparado via RabbitMQ (MassTransit)
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

*Construindo o futuro da gestão corporativa, um sprint de cada vez.*

</div>
