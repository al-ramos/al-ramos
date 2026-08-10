<div align="center">

# 👋 Alexsandro Ramos

<h3>Engenheiro de Software · .NET 10 + AWS · São Paulo</h3>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/progalexramos/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/al-ramos)
![Profile Views](https://komarev.com/ghpvc/?username=al-ramos&style=for-the-badge&color=blueviolet&label=PROFILE+VIEWS)
[![Followers](https://img.shields.io/github/followers/al-ramos?style=for-the-badge&color=blue&label=FOLLOWERS)](https://github.com/al-ramos?tab=followers)

</div>

<div align="left">

Desenvolvedor com trajetória construída em ambientes de missão crítica no mercado financeiro — **B3, Itaú e Bradesco** — especialista em sustentação de sistemas legados, alta volumetria, bases de dados críticas (SQL Server, Oracle, Sybase) e ciclos de entrega controlados por GMUD.

Nos últimos anos evolui para um stack moderno full-stack e cloud-native. Hoje trabalho com **.NET 8/10 (C#)**, **Node.js + TypeScript**, **React/Next.js**, **Clean Architecture** e **DevOps completo**: infraestrutura como código com **Terraform**, pipelines no **GitHub Actions** e deploy em **AWS ECS Fargate** com ALB, EFS e ECR.

Atualmente desenvolvo o **AMR SYSTEM** — ecossistema ERP/MES corporativo com 14 módulos (Release 3.0 entregue · Release 4.0 em andamento), integrações via eventos (RabbitMQ + MassTransit), autenticação **JWT**, e infra unificada na AWS (ECS Fargate + ALB + EFS + Terraform). É o projeto que consolida e demonstra toda a minha stack atual, do back ao cloud.

Em paralelo, mantenho o **Radar Carreira** — portal + extensão Chrome para coletar vagas, calcular aderência de perfil e acompanhar candidaturas — e o **TodaAtividade**, marketplace de materiais didáticos em produção.

</div>

---

## 📁 Projetos

| # | Projeto | Descrição | Status |
|:-:|---------|-----------|:------:|
| 1 | **[AMR ECOSYSTEM](#-amr-ecosystem)** | ERP/MES full-suite (Core · Financeiro · Fábrica · CRM · WMS · HCM · RH · TMS · Compras · Eventos · Portal · Analytics · IA · Mobile), cloud-native na AWS | 🟢 14 módulos · Release 4.0 em andamento |
| 2 | **[Radar Carreira](#-radar-carreira-coletor-e-aderência-de-vagas)** | Portal + extensão Chrome para coletar vagas, calcular aderência e acompanhar candidaturas | 🟢 Em produção |
| 3 | **[TodaAtividade](#-todaatividade-marketplace-de-atividades-pedagógicas)** | Marketplace de atividades pedagógicas em PDF | 🟢 Em produção |
| 4 | **[Hydac Services](#-hydac-services-workflow-management-bpm)** | BPM corporativo para indústria hidráulica | 🟡 Aguardando cliente |
| 5 | **[linkedin-job-collector](#-radar-carreira-coletor-e-aderência-de-vagas)** | Extensão Chrome que coleta vagas do LinkedIn e exporta CSV/JSON, ou envia direto ao Radar Carreira | 🟢 v2.2.0 publicada |

---

## 🏭 AMR ECOSYSTEM

(Ecossistema ERP/MES corporativo full-suite — 14 módulos cobrindo financeiro, produção, estoque, comercial, pessoas e logística — cloud-native na AWS, do zero com Clean Architecture e integração orientada a eventos).

![Módulos](https://img.shields.io/badge/Módulos-14-brightgreen?style=flat-square)
![Release](https://img.shields.io/badge/Release-4.0_em_andamento-orange?style=flat-square)
![Stack](https://img.shields.io/badge/Stack-.NET_8%2F10_·_Node.js%2FTS-informational?style=flat-square)

> Elimina sistemas isolados. Unifica financeiro, produção, estoque, comercial, pessoas e logística com módulos independentes que se comunicam automaticamente.

### 📦 Módulos

#### Release 1.0 (Sprints 1–10)

| Módulo | Repo | Descrição | Runtime |
|--------|------|-----------|---------|
| 🧠 **AMR Core** | [AMR-Core](https://github.com/al-ramos/AMR-Core) | ERP base — produtos, fornecedores, clientes, estoque, pedidos, dashboard | .NET 10 · React 18 |
| 💰 **AMR Financeiro** | [AMR-Financeiro](https://github.com/al-ramos/AMR-Financeiro) | Contas a pagar/receber, lançamentos, fluxo de caixa, plano de contas | .NET 8 · React 18 |
| 🏭 **AMR Fábrica** | [AMR-Forms-Fabrica](https://github.com/al-ramos/AMR-Forms-Fabrica) | MES — fichas de produção, inspeções, ordens de reparo, NF | .NET 8 · React 18 |
| 🤝 **AMR CRM** | [AMR-CRM](https://github.com/al-ramos/AMR-CRM) | CRM — leads, contatos, oportunidades, pipeline de vendas | .NET 10 · React 19 |
| 📦 **AMR WMS** | [AMR-WMS](https://github.com/al-ramos/AMR-WMS) | WMS — armazém, recebimento, endereçamento, picking | .NET 10 · React 19 |

#### Release 2.0 (Sprints 11–14)

| Módulo | Descrição | Runtime |
|--------|-----------|---------|
| 👥 **AMR HCM** | Gestão de pessoas — funcionários, ponto eletrônico, férias, departamentos | .NET · React |
| 🧑‍💼 **AMR RH** | Recrutamento e seleção | Node.js 22 |
| 🚛 **AMR TMS** | Gestão de transporte — ordens de entrega, rastreamento, cálculo de frete | Node.js · Angular |
| 🛒 **AMR Compras** | Pedidos de compra, cotações, fornecedores | Node.js 22 |
| 📅 **AMR Eventos** | Barramento de eventos entre módulos | Node.js · Angular |

#### Release 3.0 (Sprints 15–22) — ✅ entregue

| Módulo | Descrição | Runtime |
|--------|-----------|---------|
| 🖥️ **AMR Portal** | PWA — visão do cliente sobre Core + Financeiro | Next.js 14 |
| 📊 **AMR Analytics** | BI consolidado — Kafka + ClickHouse + Grafana | Node.js |
| 🤖 **AMR IA** | Assistente sobre dados do ERP (RAG/LangChain) | Node.js |
| 📱 **AMR Mobile** | App mobile (Expo) | React Native |

#### Release 4.0 (Sprints 23–31) — 🔨 em andamento

v2 de cada módulo (Financeiro → Fábrica → Core → CRM → HCM → Compras → WMS → TMS) + novo módulo **AMR-Fiscal** (Sprint 31 — ICMS/IPI/PIS/COFINS, SPED). Sprint atual: **AMR-Financeiro v2** (NF-e SEFAZ, Boleto + CNAB, Conciliação OFX, DRE, Centro de Custo, Multi-banco).

---

## 🛠️ Stack Tecnológica

### Backend

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET 8/10](https://img.shields.io/badge/.NET_8%2F10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Entity Framework](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![MediatR](https://img.shields.io/badge/MediatR_CQRS-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![JWT](https://img.shields.io/badge/JWT_Auth-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Serilog](https://img.shields.io/badge/Serilog-informational?style=for-the-badge&logo=dotnet&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Infra & DevOps

![AWS](https://img.shields.io/badge/AWS_ECS_Fargate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

### Arquitetura & Padrões

```
Clean Architecture  ·  CQRS + MediatR  ·  DDD
Integração orientada a eventos (RabbitMQ / MassTransit)  ·  REST API  ·  JWT Bearer
Health Checks  ·  Serilog Structured Logging  ·  Unit Testing (xUnit)
```

---

## ☁️ Infraestrutura AWS — AMR SYSTEM

```
                        ┌─────────────────────────────────┐
                        │     GitHub Actions CI/CD        │
                        │  (deploy por repositório)        │
                        └────────────┬────────────────────┘
                                     │ docker build + push
                                     ▼
                        ┌─────────────────────────────────┐
                        │            AWS ECR               │
                        │   um par API/Web por módulo      │
                        └────────────┬────────────────────┘
                                     │ pull image
                                     ▼
┌────────────────────────────────────────────────────────────┐
│            Cluster ECS Fargate — amr-system (sa-east-1)     │
│                                                            │
│  ALB único roteando para os 14 módulos (Frontend + API)   │
│  EFS (volumes persistentes)  ·  ECR (repositórios por módulo) │
└────────────────────────────────────────────────────────────┘
             Provisionado via Terraform (IaC)
```

---

## 🔄 Arquitetura de Eventos — Integração entre Módulos

```
AMR-Core ←→ AMR-Financeiro   (pedidos → faturamento)
AMR-Core ←→ AMR-CRM          (clientes → leads)
AMR-Core ←→ AMR-WMS          (pedidos → estoque)
AMR-Fábrica ←→ AMR-WMS       (produção → estoque)
AMR-WMS ←→ AMR-Compras       (entrada → pedido de reposição)
AMR-Financeiro ←→ AMR-Compras (contas a pagar)
AMR-HCM ←→ AMR-Financeiro    (folha de pagamento)
AMR-Analytics ← todos os módulos (dados consolidados)
AMR-Portal ←→ AMR-Core + AMR-Financeiro (visão do cliente)
AMR-IA ← AMR-Analytics + AMR-CRM + AMR-WMS (modelos preditivos)
AMR-TMS ←→ AMR-WMS           (saída → entrega)
```

---

## 🗺️ Roadmap

```
Release 1.0  ✅  Core · Financeiro · Fábrica · CRM · WMS              (Sprints 1–10)
Release 2.0  ✅  + RH · TMS · Compras · Eventos                       (Sprints 11–14)
Release 3.0  ✅  + HCM aprofundado · Portal · Analytics · IA · Mobile (Sprints 15–22)
Release 4.0  🔨  v2 de cada módulo + novo módulo AMR-Fiscal           (Sprints 23–31)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
              ⚡ Sprint atual — AMR-Financeiro v2
              NF-e SEFAZ · Boleto + CNAB · Conciliação OFX · DRE · Centro de Custo · Multi-banco
```

---

## 🧭 Radar Carreira — Coletor e Aderência de Vagas

![Status](https://img.shields.io/badge/Status-Em_produção-brightgreen?style=flat-square)
![Extensão](https://img.shields.io/badge/Extensão_Chrome-v2.2.0-blue?style=flat-square)

> Portal multiusuário que reúne vagas de várias fontes, calcula aderência ao perfil profissional e organiza um pipeline pessoal de candidaturas — com uma extensão Chrome dedicada para coletar vagas do LinkedIn.

[![Repo](https://img.shields.io/badge/GitHub-radar--carreira--platform-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/al-ramos/radar-carreira-platform)
[![Extensão](https://img.shields.io/badge/GitHub-linkedin--job--collector-181717?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/al-ramos/linkedin-job-collector)

### 📊 O que faz

| Componente | Descrição |
|------------|-----------|
| 🌐 **radar-carreira-platform** | Portal web (Next.js 16 + Cloudflare D1) — importa vagas via Gmail/JSON/CSV/ATS públicos (Greenhouse, Lever, Ashby), deduplica, calcula score explicável, mantém pipeline de candidaturas e envia resumo diário |
| 🧩 **linkedin-job-collector** | Extensão Chrome (Manifest V3) que percorre pesquisas de vagas do LinkedIn, remove duplicidades, filtra por stack e exporta CSV/JSON — ou envia direto para o Radar |

### 🔄 Fluxo dos dados

```
Gmail/RadarVagas ─┐
JSON ou CSV ──────┼─> normalização e deduplicação ─> Cloudflare D1 ─> Radar e pipeline
ATS públicos ─────┤                                        │
Extensão LinkedIn ┘                                        └─> score, alertas e resumo diário
```

### 🧰 Stack

| Camada | Tecnologia |
|--------|------------|
| Frontend | Next.js 16 · React 19 · Tailwind CSS |
| Runtime | Cloudflare Workers (vinext + Vite) |
| Banco de Dados | Cloudflare D1 + Drizzle ORM |
| Autenticação | Sign in with ChatGPT |
| Extensão | Chrome Manifest V3 (JS/HTML/CSS puro) |
| Automação | GitHub Actions + Google Apps Script |

### 📋 Status

Já em produção: portal público, deduplicação, importação JSON/CSV, integração Gmail, conectores Greenhouse/Lever/Ashby, pipeline de candidaturas, alertas, auditoria e extensão Chrome v2.2.0 publicada.

---

## 🎓 TodaAtividade — Marketplace de Atividades Pedagógicas

![Status](https://img.shields.io/badge/Status-Em_produção-brightgreen?style=flat-square)
![Sprints](https://img.shields.io/badge/Sprints-5%2F5_entregues-success?style=flat-square)

> Marketplace B2C de atividades pedagógicas em PDF para o ensino fundamental. Professores encontram, visualizam prévia e compram materiais com download imediato após confirmação do pagamento.

[![Demo](https://img.shields.io/badge/Produção-todaatividade.com.br-00C7B7?style=for-the-badge&logo=vercel&logoColor=white)](https://todaatividade.com.br)
[![Repo](https://img.shields.io/badge/GitHub-TodaAtividade--Ecommerce-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/al-ramos/TodaAtividade-Ecommerce)

### 🧰 Stack

| Camada | Tecnologia |
|--------|------------|
| Framework | Next.js 14 (App Router) + TypeScript |
| Estilo | Tailwind CSS + shadcn/ui |
| Auth | NextAuth.js (Google, Microsoft, Facebook, email/senha) |
| Banco | Supabase (PostgreSQL + RLS) |
| Storage | Cloudflare R2 (PDFs privados + prévias públicas) |
| Pagamento | Mercado Pago SDK v3 (Pix, Boleto, Cartão) |
| Email | Resend |
| Deploy | Vercel + GitHub Actions |

### ✅ Sprints entregues

| Sprint | Épico | Entregáveis |
|--------|-------|-------------|
| Sprint 1 | 🔐 Auth | Cadastro, login, OAuth, recuperação de senha |
| Sprint 2 | 📚 Catálogo + Preview | Listagem com filtros, página de produto, prévia de PDF |
| Sprint 3 | 🛒 Checkout | Carrinho, pagamento via Pix/Boleto/Cartão (Mercado Pago Bricks) |
| Sprint 4 | 📦 Entrega + Email | Webhook Mercado Pago (HMAC), download seguro via R2, emails transacionais |
| Sprint 5 | ⚙️ Admin + SEO | Painel admin (CRUD, upload R2, pedidos), SEO, Meta Pixel |

---

## 💧 Hydac Services — Workflow Management (BPM)

![Status](https://img.shields.io/badge/Status-Aguardando_aprovação_do_cliente-yellow?style=flat-square)
![Prototipagem](https://img.shields.io/badge/Prototipagem-Validada-success?style=flat-square)

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
