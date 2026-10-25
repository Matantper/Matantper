<h1 align="center">Olá, eu sou o Matheus 👋</h1>

<p align="center">
  <b>Software Engineer · Backend & Integrações · Agentes de IA</b><br>
  Construo serviços, integrações assíncronas e agentes de IA que rodam em produção — sem supervisão e com observabilidade.
</p>

<p align="center">
  <a href="https://linkedin.com/in/matheus-antonio-pereira-da-silva-9a824a149"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:matheusapereiradasilva@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/São_Paulo,_BR-Remoto-2ea44f?style=for-the-badge" alt="Remoto">
</p>

---

## 🧭 Sobre mim

- 🔧 Backend developer focado em **Node.js / TypeScript**, integrações entre serviços e **automação com IA**.
- 🔄 Saí do **no-code (n8n, Make, Zapier)** para o código: levei automações para middlewares em Node.js + Express com estado em banco e controle em tempo real com Redis.
- 🤖 Desenvolvo com **IA como ferramenta principal** — e estou investindo em julgamento de arquiteto sênior (clean code, padrões arquiteturais, segurança e observabilidade) para guiar e revisar o que a IA produz.
- 🎯 Próximo passo: **full stack**.

---

## 💼 Experiência em tech

**Software Engineer — iFood** · *mar/2026 – out/2026*
- Responsável pela comunicação entre serviços na migração de CRM para o Salesforce.
- Construí integrações **assíncronas** entre serviços e refatorei integrações síncronas para assíncronas.
- Conduzi migrações técnicas e de tecnologia dos serviços.
- Desenvolvi **fluxos de IA em grafos** integrados a LLMs, com rastreamento no **Langfuse**.

**Senior Product Manager – Automações e IA — Anota AI (grupo iFood)** · *nov/2024 – mar/2026*
- Fluxos de mensageria orientados a **eventos** do app e de conversões em anúncios.
- Migração de automações do n8n para **Node.js + Express + MySQL + Redis**.
- Construí do zero a automação de suporte que passou a resolver **45% dos atendimentos sem humano**.
- Atuei com engenharia e dados em confiabilidade e performance.
- Três migrações de plataforma me ensinaram a **desacoplar integrações das ferramentas**.

---

## 🚀 Projetos

### 🦷 Bot de atendimento com IA para clínicas (WhatsApp + CRM)
Agente de IA no WhatsApp integrado a CRM, com agenda via tools.
- Mensagens **multimodais**: texto, áudio (transcrição com **Groq Whisper**), imagem e PDF (**Mistral OCR**).
- **Debounce com Redis** para agrupar mensagens picadas antes de acionar o agente.
- Base de conhecimento por cliente com **pgvector** + `text-embedding-3-large`.

### 🔎 RAG para catálogos técnicos (SDR de máquinas e catálogo de peças)
Bot SDR que tria leads, entende a necessidade e encontra o produto certo em catálogos.
- Indexação e busca semântica com **Supabase Vector Store** (embeddings `text-embedding-3-large`).
- Padrão reutilizável: o mesmo pipeline foi aplicado a um catálogo de máquinas industriais e a um catálogo de peças/componentes.

### 🛒 Agente de operações no Mercado Livre via WhatsApp
Agente acionado por **webhook da Evolution API** que executa pedidos usando o **MCP do Mercado Livre**.
- Allowlist de grupos autorizados no **PostgreSQL** e resolução de tokens no **Redis** (refresh gerenciado por um fluxo separado).
- Ingestão, fila, worker e agente em **Node.js + TypeScript**.
- Bot em produção que gerencia múltiplas contas, cria/pausa anúncios em lote e envia relatório consolidado diário.

### 💬 Plataforma de comunicação e CRM para SDR/BDR com IA
Evolução de um agente no n8n para uma **plataforma em código**, com front-end e gestão de leads em **Kanban**.
- Dono de ponta a ponta: serviços, infraestrutura, credenciais, monitoramento e alertas.

### 🏗️ Arquitetura de ecossistema de atendimento a leads
Proposta de arquitetura para um ecossistema **Widget → Gateway → Middleware → IA → CRM**.
- Foco em **observabilidade do estado de cada mensagem**, **fail recovery** com filas, e armazenamento de erros com contexto para um loop de IA sugerir correções.
- CRM tratado como peça substituível (integração desacoplada).

### 🤖 Agência operada por agentes de IA *(em construção)*
Software próprio que acompanha grupos de clientes no WhatsApp, gera demandas num **Kanban** e **orquestra agentes de IA** (design, ads), com aprovações humanas no próprio WhatsApp.

### 📊 Dados para geração de leads — Receita Previsível Agendas
Estruturei de ponta a ponta a geração de bases e o processo de **big data** até a entrada no mercado.

---

## 🛠️ Stack

**Backend**
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/REST_APIs-555555?style=flat-square">
  <img src="https://img.shields.io/badge/Webhooks-555555?style=flat-square">
</p>

**Dados**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white">
</p>

**IA**
<p>
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
  <img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square">
  <img src="https://img.shields.io/badge/RAG-555555?style=flat-square">
  <img src="https://img.shields.io/badge/MCP-555555?style=flat-square">
</p>

**Infra & Observabilidade**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/EasyPanel_(VPS)-555555?style=flat-square">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white">
  <img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white">
</p>

**Automação & Integrações**
<p>
  <img src="https://img.shields.io/badge/n8n_(self--hosted)-EA4B71?style=flat-square&logo=n8n&logoColor=white">
  <img src="https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white">
  <img src="https://img.shields.io/badge/Zapier-FF4A00?style=flat-square&logo=zapier&logoColor=white">
  <img src="https://img.shields.io/badge/Evolution_API-25D366?style=flat-square&logo=whatsapp&logoColor=white">
  <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white">
  <img src="https://img.shields.io/badge/HubSpot-FF7A59?style=flat-square&logo=hubspot&logoColor=white">
</p>

---

## 📈 Aprendendo agora

- Padrões de arquitetura e clean code aplicados a código gerado por IA
- Segurança (gestão de credenciais, autenticação, superfície de ataque)
- Observabilidade de sistemas que rodam sem supervisão
- Front-end, rumo ao full stack

---
