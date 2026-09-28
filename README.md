# Michel Fioravante

**Automação e sistemas com IA · n8n · Supabase · React**

Construo automações e sistemas de gestão que empresas usam no dia a dia: modelo o banco, escrevo as regras no backend, monto os fluxos no n8n e coloco em produção.

Sapucaia do Sul, RS · Remoto · Aberto a oportunidades

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michel-fioravante/)
[![E-mail](https://img.shields.io/badge/michelfioravante@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:michelfioravante@gmail.com)

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white)

---

## Projetos para clicar e ver funcionando

| Projeto | O que é | Resultado | Links |
| :--- | :--- | :--- | :--- |
| **CRM MWK** | CRM comercial B2B para equipe de campo | Substituiu a planilha usada por ~30 pessoas | [Demo](https://crm-mwk.vercel.app) · [Código](https://github.com/michelfioravante-alt/crm-mwk) |
| **EDM Lean** | MES de ferramentaria: Kanban, horas máquina e OEE | OEE de 48% para 61% em 3 meses nos pilotos | [Produção](https://edmlean.com.br) · [Código](https://github.com/michelfioravante-alt/edm-lean) |
| **Nexlog AI** | Atendimento no WhatsApp com n8n e LLM | 1ª resposta de ~4h para ~45s | [Workflows](https://github.com/michelfioravante-alt/nexlog-ai-automation) |
| **NovaPay** | Dashboard comercial com alertas em n8n | Alerta automático de meta em risco | [Demo](https://novapay-dashboard.vercel.app) · [Código](https://github.com/michelfioravante-alt/novapay-dashboard) |

O CRM MWK tem acesso de demonstração sem cadastro (botões "Entrar como Técnico" e "Entrar como Gestor"). O NovaPay tem credenciais de teste no README do projeto.

---

## O que tem por trás

**Nexlog AI — automação em n8n**
Webhook da Evolution API recebe a mensagem, o Whisper transcreve áudio, um classificador LLM decide a intenção e a sessão fica no Supabase. Se a confiança for baixa, o fluxo não inventa resposta: abre tarefa no ClickUp para um atendente. Rodava em n8n self-hosted numa VPS Hostinger.

**CRM MWK — banco e regras no backend**
Supabase com Auth e RLS por perfil: o técnico só enxerga a própria carteira, o gestor vê a operação inteira, e nada disso depende do frontend. OCR com Google Vision para ler o odômetro e calcular o reembolso de KM. Testes E2E com Playwright.

**EDM Lean — modelagem multiempresa**
PostgreSQL com isolamento por `empresa_id` via RLS, O.S. agrupadas por molde e ligadas à O.S. de origem em retrabalho, trigger que grava cada mudança de status numa tabela de eventos e baixa de estoque feita no banco para dois terminais não sobrescreverem a contagem um do outro.

**NovaPay — trigger + automação agendada**
Trigger no PostgreSQL gera o lançamento financeiro quando a venda é ganha. Um cron no n8n chama uma função via RPC e dispara alerta quando a receita fica abaixo de 70% da meta perto do fim do mês.

---

## Como eu trabalho

1. Entendo o processo e a regra de negócio antes de abrir o editor.
2. Modelo o banco pensando nas consultas e nas permissões que o sistema vai precisar.
3. Coloco regra crítica no backend (RLS, triggers, funções), não só na tela.
4. Automação com caminho de falha definido: quando algo dá errado, vai para um humano e fica registrado.
5. Uso Cursor e Claude para acelerar, mas reviso a lógica e a arquitetura antes de subir.

A formação em engenharia de processos ajuda aqui: consigo pegar um fluxo mapeado e transformar em estrutura técnica sem perder a regra no caminho.

---

## Stack

**Automação e IA:** n8n, webhooks, APIs REST, Evolution API (WhatsApp), Dify, LLMs, Whisper
**Backend e dados:** Supabase, PostgreSQL, RLS, triggers e funções SQL
**Frontend:** React, Next.js, TypeScript, Tailwind
**Infra e ferramentas:** Vercel, VPS Hostinger, GitHub, Cursor, Claude, Playwright

---

## Formação

- MBA em Gestão da Qualidade e Engenharia de Processos — PUCRS (2024–2025)
- Tecnólogo em Gestão da Produção Industrial — ULBRA (2020–2024)
- Técnico em Qualidade — Senac RS

---

## O que busco

Vagas de **automação, no-code/low-code e desenvolvimento de sistemas com IA**: Especialista em Automação, Desenvolvedor No-Code, Analista de Automação, AI Engineer Júnior. Remoto.

[LinkedIn](https://www.linkedin.com/in/michel-fioravante/) · [michelfioravante@gmail.com](mailto:michelfioravante@gmail.com)
