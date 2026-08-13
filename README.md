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

Nos últimos anos evolui para um stack moderno full-stack e cloud-native. Hoje trabalho com **.NET 10 (C#)**, **React/TypeScript**, **Clean Architecture** e **DevOps completo**: infraestrutura como código com **Terraform**, pipelines no **GitHub Actions** e deploy em **AWS ECS Fargate** com ALB, EFS e ECR.

Atualmente desenvolvo o **AMR SYSTEM** — ecossistema ERP corporativo com 7 módulos (3 em produção + 4 na Release 2.0), integrações via **RabbitMQ + MassTransit**, autenticação **JWT**, **61 testes** passando e infra unificada na AWS (ECS Fargate + ALB + EFS + Terraform). É o projeto que consolida e demonstra toda a minha stack atual, do back ao cloud.

Em paralelo, mantenho o **Radar Carreira** — plataforma multiusuário que reúne vagas de diversas fontes, combina score explicável e veredito estratégico, e acompanha todo o ciclo da candidatura — e o **TodaAtividade**, marketplace de materiais didáticos em produção.

</div>

---

## 📁 Projetos

| # | Projeto | Descrição | Status |
|:-:|---------|-----------|:------:|
| 1 | **[AMR ECOSYSTEM](#-amr-ecosystem)** | ERP corporativo full-suite (MES · WMS · TMS · CRM · HCM · BI), cloud-native na AWS | 🟢 Em produção |
| 2 | **[Radar Carreira](#-radar-carreira-coletor-e-aderência-de-vagas)** | Sistema de decisão de carreira com coleta multicanal, aderência explicável, alertas e pipeline | 🟢 Em produção |
| 3 | **[TodaAtividade](#-todaatividade-marketplace-de-atividades-pedagógicas)** | Marketplace de atividades pedagógicas em PDF | 🟢 Em produção |
| 4 | **[Hydac Services](#-hydac-services-workflow-management-bpm)** | BPM corporativo para indústria hidráulica | 🟡 Aguardando cliente |
| 5 | **[Coletor de Vagas](#-radar-carreira-coletor-e-aderência-de-vagas)** | Extensão Chrome unificada para LinkedIn e APInfo, com CSV/JSON e integração direta ao Radar | 🟢 v3.0.0 |

---

## 🏭 AMR ECOSYSTEM  
(Ecossistema ERP corporativo full-suite — MES · WMS · TMS · CRM · HCM · BI — cloud-native na AWS, do zero com Clean Architecture e event-driven).

![Status](https://img.shields.io/badge/Status-3%2F7_módulos_em_produção-brightgreen?style=flat-square)
![Release](https://img.shields.io/badge/Release-2.0_em_andamento-orange?style=flat-square)
![Tests](https://img.shields.io/badge/Testes-61_passando-success?style=flat-square)

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
| 📦 **AMR WMS** | [AMR-WMS](https://github.com/al-ramos/AMR-WMS) | WMS — armazém, recebimento, endereçamento, picking, dashboard de ocupação | 🔨 Sprint 8 ativo |
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
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=for-the-badge&logo=react&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

### Infra & DevOps
![AWS](https://img.shields.io/badge/AWS_ECS_Fargate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
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
Sprint 7   ⚡  AMR CRM — leads, contatos, pipeline de vendas  (04/06 – 24/06/2026)
Sprint 8   ⚡  AMR WMS — armazém, recebimento, picking         (09/07 – 22/07/2026)  ← ATIVO
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

## 🧭 Radar Carreira — Coletor e Aderência de Vagas

![Status](https://img.shields.io/badge/Status-Em_produção-brightgreen?style=flat-square)
![Testes](https://img.shields.io/badge/Testes-automatizados-success?style=flat-square)
![Extensão](https://img.shields.io/badge/Extensão_unificada-v3.0.0-blue?style=flat-square)

> Sistema pessoal de decisão de carreira, com operação multiusuário: reúne vagas de várias fontes, explica a aderência, aplica bloqueadores estratégicos e organiza o ciclo completo da candidatura.

[![Repo](https://img.shields.io/badge/GitHub-radar--carreira--platform-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/al-ramos/radar-carreira-platform)
[![Produção](https://img.shields.io/badge/Abrir-Radar_Carreira-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://radar-carreira-platform.al-ramos.workers.dev)
[![Extensão](https://img.shields.io/badge/GitHub-linkedin--job--collector-181717?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/al-ramos/linkedin-job-collector)

### 📊 O que faz

| Componente | Descrição |
|------------|-----------|
| 🌐 **radar-carreira-platform** | Portal web que normaliza e deduplica vagas, calcula score e veredito, mantém pipeline individual e envia alertas e resumo diário |
| 🧩 **Coletor unificado** | Extensão Chrome Manifest V3 v3.0.0 que reconhece LinkedIn ou APInfo e abre o painel especializado de cada portal |
| 🔵 **Módulo LinkedIn** | Percorre pesquisas abertas, filtra por stack, remove duplicidades e exporta CSV/JSON ou envia direto ao Radar |
| 🟢 **Módulo APInfo** | Coleta páginas, controla a paginação permitida e captura contatos após ação e autenticação manual do usuário |
| 🛡️ **Administração** | Gestão de usuários, papéis e permissões RBAC, fontes, qualidade dos dados, métricas, monitoramento, auditoria e backup operacional |

### 🔄 Fluxo dos dados

```
Gmail/RadarVagas ──────┐
JSON ou CSV ───────────┤
Greenhouse/Lever/Ashby ┼─> normalização e deduplicação ─> Cloudflare D1 ─> Radar e pipeline
Coletor LinkedIn ──────┤                                         │
Coletor APInfo ────────┘                                         ├─> score + veredito estratégico
                                                                 └─> pipeline, alertas e resumo diário
```

### 🧠 Decisão explicável

| Camada | Resultado |
|--------|-----------|
| **Score numérico** | Mede aderência por competências, experiência e preferências, com explicação dos critérios |
| **Veredito estratégico** | Classifica a oportunidade em quatro fases e aplica bloqueadores de stack, idioma, senioridade, atuação e geografia |
| **Regras de elegibilidade** | Excluem vagas incompatíveis por senioridade e zeram o score quando há termos bloqueados no perfil |
| **Análise da candidatura** | Mostra competências aderentes, lacunas e recomendações diretamente no detalhe da vaga |

O pipeline registra vagas visualizadas, salvas, candidaturas, entrevistas e encerramentos sem rebaixar automaticamente um estágio já avançado.

### 🧰 Stack

| Camada | Tecnologia |
|--------|------------|
| Frontend | Next.js 16 · React 19 · Tailwind CSS |
| Runtime | Cloudflare Workers (vinext + Vite) |
| Banco de Dados | Cloudflare D1 + Drizzle ORM |
| Autenticação | Sign in with ChatGPT + login local (PBKDF2 + sessão HMAC) |
| Inteligência | Regras determinísticas, score explicável, veredito e análise de lacunas |
| Extensão | Chrome Manifest V3 unificada para LinkedIn e APInfo |
| Segurança | RBAC por papéis, grupos e permissões, com validação no servidor |
| Automação | GitHub Actions + Google Apps Script |

### 📋 Status

Plataforma em produção, com **19 tabelas no modelo atual**, testes automatizados e publicação contínua pelo GitHub Actions no Cloudflare Workers. O fluxo principal — descobrir, avaliar, salvar, candidatar-se e acompanhar — está implementado.

A fase atual é de **consolidação operacional**: concluir a administração de grupos do RBAC, ampliar o backup para perfis, pipeline e alertas, eliminar a convivência com o papel legado e formalizar a distribuição da extensão unificada. A arquitetura, as regras de negócio, as funcionalidades e os riscos conhecidos estão registrados na documentação técnica do ecossistema.

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

![GitHub Stats](./generated/overview.svg#gh-dark-mode-only)
![Top Languages](./generated/languages.svg#gh-dark-mode-only)

</div>

---

<div align="center">

*Construindo o futuro da gestão corporativa, um sprint de cada vez.*

</div>
