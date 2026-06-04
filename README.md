![AMR SYSTEM](./amr_github_banner.png)
<div align="left">

<h3>Engenheiro de Software · .NET 10 + AWS · São Paulo </h3>

Desenvolvedor com trajetória construída em ambientes de missão crítica no mercado financeiro — **B3, Itaú e Bradesco** — especialista em sustentação de sistemas legados, alta volumetria, bases de dados críticas (SQL Server, Oracle, Sybase) e ciclos de entrega controlados por GMUD.

Nos últimos anos evolui para um stack moderno full-stack e cloud-native. Hoje trabalho com **.NET 10 (C#)**, **React/TypeScript**, **Clean Architecture** e **DevOps completo**: infraestrutura como código com **Terraform**, pipelines no **GitHub Actions** e deploy em **AWS ECS Fargate** com ALB, EFS e ECR.

Atualmente desenvolvo o **AMR SYSTEM** — ecossistema ERP corporativo com 7 módulos (3 em produção + 4 na Release 2.0), integrações via **RabbitMQ + MassTransit**, autenticação **JWT**, **61 testes** passando e infra unificada na AWS (ECS Fargate + ALB + EFS + Terraform). É o projeto que consolida e demonstra toda a minha stack atual, do back ao cloud.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/progalexramos/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/al-ramos)

</div>

---

## 🏭 AMR ECOSYSTEM  
(Ecossistema ERP corporativo full-suite — MES · WMS · TMS · CRM · HCM · BI — cloud-native na AWS, do zero com Clean Architecture e event-driven).

> Elimina sistemas isolados. Unifica financeiro, produção, RH, compras, logística e analytics com rastreabilidade total via event-driven.

### 📦 Módulos

#### Release 1.0 — Em produção / Sprint 6 concluído

| Módulo | Repo | Descrição | Status |
|--------|------|-----------|--------|
| 🧠 **AMR Core** | [AMR-Core](https://github.com/al-ramos/AMR-Core) | ERP base — produtos, fornecedores, clientes, estoque, pedidos, dashboard | ✅ Produção |
| 💰 **AMR Financeiro** | [AMR-Financeiro](https://github.com/al-ramos/AMR-Financeiro) | Contas a pagar/receber, lançamentos, fluxo de caixa, plano de contas | ✅ Produção |
| 🏭 **AMR Forms Fábrica** | [AMR-Forms-Fabrica](https://github.com/al-ramos/AMR-Forms-Fabrica) | MES — fichas de produção, inspeções, ordens de reparo, NF | ✅ Produção |

#### Release 2.0 — Sprints 7–10 (Jun–Ago 2026)

| Módulo | Repo | Descrição | Status |
|--------|------|-----------|--------|
| 🤝 **AMR CRM** | [AMR-CRM](https://github.com/al-ramos/AMR-CRM) | CRM — leads, contatos, oportunidades, pipeline de vendas · API :5187 · Web :5176 | 🔨 Sprint 7 ativo |
| 📦 **AMR WMS** | `em breve` | Gestão de armazém — recebimento, endereçamento, picking, integração Core | 📋 Sprint 8 |
| 🚛 **AMR TMS** | `em breve` | Gestão de transporte — ordens de entrega, rastreamento, cálculo de frete | 📋 Sprint 9 |
| 👥 **AMR HCM** | `em breve` | Gestão de pessoas — funcionários, ponto eletrônico, férias, departamentos | 📋 Sprint 10 |

---

## 🛠️ Stack Tecnológica

### Backend
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET 10](https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
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

## 🗺️ Roadmap

### Release 1.0

```
Sprint 1  ✅  AMR Core + Forms Fábrica                        (28/04/2026)
Sprint 2  ✅  BackgroundService + Infra                        (29/04/2026)
Sprint 3  ✅  AMR Financeiro + JWT + Docker                    (13/05/2026)
Sprint 4  ✅  AMR Core completo + Dashboard                    (27/05/2026)
Sprint 5  ✅  Infra AWS unificada + CI/CD (Terraform + ECS)   (03/06/2026)
Sprint 6  ✅  Polish AMR-Core · Testes · Security Hardening   (02/06 – 04/06/2026)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
              🎯  Release 1.0  ✅  (04/06/2026)
```

### ✅ Sprint 6 — entregues
- [x] CRUD completo AMR-Core (Produto, PedidoCompra, PedidoVenda) com workflows de status
- [x] MovimentosEstoque `/estoque/movimentos` com filtros e badges
- [x] ExceptionHandlingMiddleware (ProblemDetails RFC 7807) em todos os módulos
- [x] FluentValidation + ValidationBehavior no pipeline MediatR (todos os módulos)
- [x] Repository Pattern em AMR-Financeiro
- [x] 26 testes unitários AMR-Core (domain + application handlers)

### Release 2.0

```
Sprint 7   ⚡  AMR CRM — leads, contatos, pipeline de vendas  (04/06 – 24/06/2026)  ← ATIVO
Sprint 8   🔜  AMR WMS — armazém, recebimento, picking         (09/07 – 22/07/2026)
Sprint 9   🔜  AMR TMS — transporte, rastreamento, frete       (23/07 – 05/08/2026)
Sprint 10  🔜  AMR HCM — pessoas, ponto, férias, salários      (06/08 – 19/08/2026)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
              🎯  Release 2.0  (19/08/2026)
```

---

## 🧪 Cobertura de Testes

| Módulo | Framework | Testes |
|--------|-----------|--------|
| AMR.Financeiro | xUnit | ✅ 15 passando |
| AMR.Core | xUnit | ✅ 26 passando |
| AMR.Forms.Fabrica | xUnit + Vitest/RTL | ✅ 20 passando |
| **Total** | | **✅ 61 testes** |

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
