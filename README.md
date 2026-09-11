<div align="center">

# Michel Fioravante

**Analista de Processos · Full-Stack B2B · Automação Industrial e Comercial**

Mapeio a operação no chão de fábrica e no comercial. Depois construo o sistema que tira o processo da planilha e coloca em produção.

*Process analyst who ships software — BPMN & Lean first, then React/Next.js, Supabase and n8n.*

Sapucaia do Sul, RS · Aberto a oportunidades

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michel-fioravante/)
[![E-mail](https://img.shields.io/badge/michelfioravante@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:michelfioravante@gmail.com)
[![EDM Lean](https://img.shields.io/badge/Produto-edmlean.com.br-111111?style=flat-square)](https://edmlean.com.br)

</div>

---

## Sobre

Sou formado em **Gestão da Produção Industrial (ULBRA)** com **MBA em Engenharia de Processos (PUCRS)**. Atuo na interseção entre operação e software: levantamento AS-IS/TO-BE, POPs, KPIs — e o desenvolvimento full-stack da ferramenta que sustenta o novo fluxo.

Não entrego só código. Entrego processo mapeado, regra de negócio no banco e uma interface que a operação consegue usar no dia a dia.

---

## Impacto (o que um recrutador precisa ver)

| Resultado | Contexto |
| :--- | :--- |
| **OEE 48% → 61% em 3 meses** | SaaS MES/Kanban para usinagem CNC e eletroerosão a fio |
| **Planilha de 30 usuários → CRM em produção** | Operação B2B de campo, com OCR de odômetro e painel executivo |
| **1ª resposta 4h → ~45s** | Atendimento WhatsApp com roteamento por LLM (n8n + Supabase) |
| **RLS e triggers no PostgreSQL** | Isolamento Gestor vs. Operador sem regra de acesso no frontend |

---

## Projetos em destaque

Os deploys usam dados anonimizados ou fictícios.

### [EDM Lean](https://edmlean.com.br) — SaaS MES, Kanban e OEE
Plataforma multi-setor para ferramentaria e usinagem: Kanban de O.S., horas máquina, importação de folhas CAM (ZW3D / Siemens NX), estoque de ferramental e visão de gestor com PIN master. Arquitetura multi-tenant com Supabase + RLS.

**Stack:** React 18 · Vite · Supabase · PostgreSQL · Tailwind · Vercel  
[Live](https://edmlean.com.br) · [Repositório](https://github.com/michelfioravante-alt/edm-lean)

### [CRM MWK](https://crm-mwk.vercel.app) — CRM de campo B2B
Substituiu o controle comercial em Excel. Dois perfis (técnico de campo e gestor): agenda do dia, sell-out com aprovação, OCR de odômetro (Google Cloud Vision), PWA e exportação para Excel/Power BI.

**Stack:** Next.js · TypeScript · Supabase · Tailwind · Playwright · Vercel  
[Demo](https://crm-mwk.vercel.app) · [Repositório](https://github.com/michelfioravante-alt/crm-mwk)

### [Nexlog AI](https://github.com/michelfioravante-alt/nexlog-ai-automation) — Orquestração cognitiva de atendimento
Triagem de chamados no WhatsApp com classificação por LLM, sessão stateful no Postgres, transcrição de áudio (Whisper/Groq) e escalation humano no ClickUp quando a confiança da IA é baixa.

**Stack:** n8n · Supabase · Evolution API · LLM routing · Whisper  
[Repositório](https://github.com/michelfioravante-alt/nexlog-ai-automation)

### [NovaPay](https://novapay-dashboard.vercel.app) — Dashboard comercial com automação
Painel gestor/vendedor com pipeline, metas e comissão. Lançamentos financeiros via trigger PL/pgSQL; alerta de meta abaixo de 70% via n8n (cron + webhook).

**Stack:** React · TypeScript · Supabase · n8n · RLS  
[Demo](https://novapay-dashboard.vercel.app) · [Repositório](https://github.com/michelfioravante-alt/novapay-dashboard)

---

## Stack

**Produto e frontend**  
`Next.js` `React` `TypeScript` `JavaScript` `Tailwind CSS` `Vite` `PWA`

**Dados e backend**  
`Supabase` `PostgreSQL` `SQL` `RLS` `PL/pgSQL` `Auth`

**Automação e IA**  
`n8n` `Webhooks` `LLM routing` `Evolution API` `Google Cloud Vision` `Whisper`

**Processos**  
`BPMN` `Lean` `OEE` `VSM` `AS-IS / TO-BE` `Power BI` `Excel avançado`

**Qualidade e deploy**  
`Playwright` `Puppeteer` `Vercel`

---

## Formação

- **MBA** em Gestão da Qualidade e Engenharia de Processos — PUCRS (2024–2025)
- **Graduação** em Gestão da Produção Industrial — ULBRA (2020–2024)
- **Técnico** em Qualidade — Senac RS

---

## O que busco

Conversas para papéis em que processo e software andam juntos:

- Analista de Processos / Melhoria Contínua com implementação de sistemas
- Full-Stack (React / Next.js) em produtos B2B ou industriais
- Automação operacional (n8n, integrações, IA aplicada)

Remoto ou Grande Porto Alegre (RS).

[LinkedIn](https://www.linkedin.com/in/michel-fioravante/) · [michelfioravante@gmail.com](mailto:michelfioravante@gmail.com)
