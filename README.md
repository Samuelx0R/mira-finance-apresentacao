<p align="center">
  <img src="docs/screenshots/logo.png" width="120" alt="Mira Logo" />
</p>

# 💸 Mira — AI Financial Assistant
> Projeto desenvolvido para o Desafio de Vibe Coding da DIO: **App de Organização de Finanças Pessoais com IA**.

[![Next.js](https://img.shields.io/badge/Next.js-16.2-black?logo=next.js)](https://nextjs.org/)
[![Prisma](https://img.shields.io/badge/Prisma-6.0-2D3748?logo=prisma)](https://www.prisma.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Supabase-3ECF8E?logo=supabase)](https://supabase.com/)
[![Groq](https://img.shields.io/badge/AI-Groq%20LLaMA%203.3-orange)](https://groq.com/)
[![Vercel](https://img.shields.io/badge/Vercel-Hospedado-black?logo=vercel)](https://mira-finance-one.vercel.app/)
[![Remotion](https://img.shields.io/badge/Video-Remotion-blue?logo=react)](https://www.remotion.dev/)

🔗 **Acesse o App online:** [mira-finance-one.vercel.app](https://mira-finance-one.vercel.app/)

---

## 🌐 Website Promocional

O projeto agora conta com uma **Landing Page Promocional** moderna e de alta performance. Ela foi construída com animações dinâmicas, *glassmorphism* e design "True Mobile" (fluido e sem travamentos no scroll), focada na conversão e apresentação do produto, com seções detalhadas de features e chamada para ação integrada à plataforma.

---

## 🧠 O que é a Mira?

A **Mira** é um Web App de finanças pessoais que elimina o atrito do controle financeiro tradicional através de **Inteligência Artificial conversacional**.

![Mira Intro](docs/screenshots/intro.gif)

Em vez de preencher formulários, o usuário simplesmente fala (ou digita):

> *"Gastei 45 reais no Uber hoje"*  
> *"Quero juntar 2000 reais para viajar até dezembro"*

A IA interpreta a intenção, extrai os dados e registra tudo automaticamente no dashboard.

### 📸 Demonstração Visual (Screenshots)

#### 🔐 Telas de Acesso (Login e Cadastro)

| Login (Desktop) | Registro (Desktop) |
| :---: | :---: |
| ![Login Desktop](docs/screenshots/login_desktop.png) | ![Register Desktop](docs/screenshots/register_desktop.png) |

| Login (Mobile) | Registro (Mobile) |
| :---: | :---: |
| ![Login Mobile](docs/screenshots/login_mobile.png) | ![Register Mobile](docs/screenshots/register_mobile.png) |

#### 💻 Versão Desktop (Painel Logado - Light vs. Dark Mode)

| Tela | Light Mode ☀️ | Dark Mode 🌙 |
| :--- | :---: | :---: |
| **Visão Geral** | ![Dashboard Light](docs/screenshots/dashboard_overview_light.png) | ![Dashboard Dark](docs/screenshots/dashboard_overview_dark.png) |
| **Chat de IA** | ![Chat Light](docs/screenshots/dashboard_chat_light.png) | ![Chat Dark](docs/screenshots/dashboard_chat_dark.png) |
| **Lançamentos** | ![Transações Light](docs/screenshots/dashboard_transactions_light.png) | ![Transações Dark](docs/screenshots/dashboard_transactions_dark.png) |
| **Metas** | ![Metas Light](docs/screenshots/dashboard_goals_light.png) | ![Metas Dark](docs/screenshots/dashboard_goals_dark.png) |
| **Insights** | ![Insights Light](docs/screenshots/dashboard_insights_radar_light.png) | ![Insights Dark](docs/screenshots/dashboard_insights_radar_dark.png) |
| **Cartões** | ![Cartões Light](docs/screenshots/dashboard_cards_light.png) | ![Cartões Dark](docs/screenshots/dashboard_cards_dark.png) |
| **Perfil & Config. (Topo)** | ![Perfil Light Topo](docs/screenshots/dashboard_profile_light_01.png) | ![Perfil Dark Topo](docs/screenshots/dashboard_profile_dark_01.png) |
| **Perfil & Config. (Base)** | ![Perfil Light Base](docs/screenshots/dashboard_profile_light_02.png) | ![Perfil Dark Base](docs/screenshots/dashboard_profile_dark_02.png) |

#### 📱 Versão Mobile (Painel Logado)

| Chat IA Mobile 💬 | Insights Mobile (Diagnóstico) 📊 | Insights Mobile (Ações) 📈 | Speech Mobile (Gravando) 🎙️ |
| :---: | :---: | :---: | :---: |
| <img src="docs/screenshots/mobile_chat.jpg" height="420" alt="Chat IA Mobile" /> | <img src="docs/screenshots/mobile_insights_01.jpg" height="420" alt="Insights Mobile 01" /> | <img src="docs/screenshots/mobile_insights_02.jpg" height="420" alt="Insights Mobile 02" /> | <img src="docs/screenshots/mobile_speech.jpg" height="420" alt="Speech Mobile" /> |

---

## 📱 Responsividade & Abordagem Mobile-First

A **Mira** foi desenhada desde o início com foco na experiência do usuário em dispositivos móveis. Entendemos que o controle financeiro acontece na correria do dia a dia — ao pagar uma conta na rua ou logo após fazer uma compra. 

<video src="https://raw.githubusercontent.com/Samuelx0R/mira-finance/main/docs/screenshots/mobile_demo.webm" autoplay loop muted playsinline width="100%" style="max-width: 400px; display: block; margin: 0 auto 20px;"></video>

* **UX Adaptada para o Polegar**: A navegação mobile utiliza uma barra inferior (*Bottom Navigation Bar*) permitindo acesso rápido a todas as abas principais com uma única mão.
* **Componentes Fluídos**: Gráficos do Recharts, modais de confirmação, e tabelas de lançamentos reorganizam-se dinamicamente via Flexbox/Grid CSS nativos para caber perfeitamente de telas pequenas (como o iPhone SE) a telas grandes de desktop.
* **Micro-interações Otimizadas**: Gavetas deslizantes (*Drawers*) e transações animadas garantem que a navegação pareça um app nativo de smartphone.

---

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 💬 **Chat com IA** | Registre gastos, receitas e metas em linguagem natural |
| 🎙️ **Entrada por voz** | Fale e o Whisper transcreve com alta precisão |
| 📊 **Dashboard dinâmico** | Saldo, balanço mensal e gráficos em tempo real |
| 💳 **Múltiplos cartões** | Gerencie várias carteiras com conversão automática de moedas |
| 🎯 **Metas financeiras** | Defina e acompanhe objetivos com prazo e progresso visual |
| 📤 **Exportação CSV** | Exporte todos os seus lançamentos para Excel |
| 🔐 **Autenticação segura** | JWT stateless com cookies HttpOnly |

---

## 🛠️ Tech Stack

| Camada | Tecnologia |
|---|---|
| **Framework** | Next.js 16.2 (App Router + Server Actions) |
| **UI** | React 19 + Framer Motion + CSS Nativo |
| **Banco de Dados** | PostgreSQL via Supabase + Prisma ORM v6 |
| **Inteligência Artificial** | Vercel AI SDK + Groq (LLaMA 3.3 70b) + Whisper |
| **Autenticação** | JWT customizado com `jose` + `bcryptjs` |
| **Gráficos** | Recharts |
| **Deploy** | Vercel |
| **Vídeo/Animação** | Remotion (Geração de vídeo programático com React) |

---

## 📋 Meu Prompt Final (PRD)

Este foi o PRD (Product Requirements Document) usado para guiar o desenvolvimento assistido por IA:

```txt
# Contexto
Quero criar um aplicativo web de Organização de Finanças Pessoais que funcione
por meio de conversas com o usuário via chat de IA.
A ideia é facilitar o controle financeiro de forma simples e natural,
sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem
muita entrada manual e pouca personalização.
Quero resolver isso com uma experiência de conversa com IA e registro automático
de despesas, receitas e metas financeiras.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem
complicação — principalmente quem sente preguiça de abrir planilhas.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural (ex: "Gastei 30 no iFood ontem").
2. Entrada por voz com transcrição automática via Whisper (Groq).
3. Classificação automática de categorias pela IA (LLaMA 3.3 via Groq).
4. Dashboard dinâmico com saldo, balanço mensal e gráfico de pizza.
5. Gestão de metas financeiras com prazo e progresso visual.
6. Suporte a múltiplos cartões/carteiras com conversão de moedas.
7. Exportação de lançamentos para CSV/Excel.

# Stack Técnica
- Next.js 16 (App Router), React 19, CSS Nativo + Framer Motion
- Prisma ORM + PostgreSQL (Supabase)
- Vercel AI SDK + Groq (LLaMA 3.3 70b + Whisper)
- Autenticação JWT própria com jose + bcryptjs
- Deploy na Vercel

# Entregável
MVP funcional hospedado na Vercel com todas as funcionalidades acima,
design mobile-first, animações fluidas e experiência "app-like".
Design anti-genérico: sem roxo, sem templates clássicos SaaS.
```

---

## 🏗️ Arquitetura do Projeto

```
mira-finance/
├── src/
│   ├── app/
│   │   ├── api/
│   │   │   ├── auth/         # Login e registro
│   │   │   ├── chat/         # Cérebro da IA + confirmação
│   │   │   ├── dashboard/    # Dados agregados
│   │   │   ├── goals/        # Metas financeiras
│   │   │   └── speech/       # Transcrição de áudio (Whisper)
│   │   └── (dashboard)/      # Páginas protegidas
│   ├── components/
│   │   ├── features/         # AiChatWidget, GoalsView, etc.
│   │   └── layout/           # Shell, Sidebar, BottomBar, Drawer
│   ├── hooks/                # Custom hooks
│   └── lib/                  # session.ts, utils
├── prisma/
│   └── schema.prisma         # Modelos: User, Card, Transaction, Goal
├── docs/                     # Documentação técnica completa
└── scripts/                  # Scripts de manutenção
```

---

## 🔄 Como a IA Funciona no App

```
Usuário digita/fala → AiChatWidget
        ↓
POST /api/chat  →  LLaMA 3.3 (Groq)
        ↓
JSON estruturado: { intent, amount, category, date, ... }
        ↓
ConfirmCard exibido para validação visual
        ↓
POST /api/chat/confirm  →  Prisma.create() no PostgreSQL
        ↓
Dashboard atualizado em tempo real via onRefresh()
```

---

## 🚀 Atualizações Recentes (Fase Beta)

Durante a fase de testes (Beta), o projeto tem recebido melhorias contínuas focadas na estabilidade e segurança corporativa:
- **Landing Page Dinâmica**: Criação do novo website promocional altamente otimizado, com animações fluidas na *Hero section* e componentes interativos como o *Voice Engine*, rodando lisos até em celulares antigos.
- **Auditoria de Segurança (P0)**: Varredura profunda em todo o código que mapeou e planejou a mitigação de vulnerabilidades (ex: ausência de *rate limit*, falhas no fluxo de 2FA e manipulação de sessão em rotas da API).
- **Transparência Legal**: Inclusão de **Termos de Uso** e aviso da fase Beta na tela de criação de conta, alertando os usuários sobre instabilidades temporárias e bugs, com base na legislação brasileira, além de *opt-in* para novidades.
- **Otimizações Mobile-First**: Resolução de gargalos de renderização e travamentos de scroll causados por excesso de listeners e animações complexas em viewports reduzidos.
- **Polimento de UI/UX**: Inúmeras correções visuais e de lógica no Dashboard (como navegação em lote de transações, filtros e ordenação visual).

---

## 💡 Reflexão sobre o Processo

### ✅ O que funcionou bem

- **Vibe Coding acelerou muito o desenvolvimento**: descrever a intenção em linguagem natural e deixar a IA gerar a estrutura base poupou horas de scaffolding e boilerplate.
- **Prompt Engineering com JSON restritivo**: forçar o LLM a sempre retornar um JSON estruturado (ao invés de texto livre) foi a chave para tornar a IA confiável como "controller" da aplicação.
- **Design mobile-first de verdade**: pensar primeiro no polegar e na tela pequena resultou numa UX muito mais fluida do que adaptar um layout desktop depois.
- **Transcrição híbrida de voz**: combinar a Web Speech API local (para feedback visual imediato) com o Whisper da Groq (para alta precisão) foi uma solução elegante de latência zero para o usuário.

### ⚠️ O que não funcionou como esperado

- **LLaMA 3.3 com function calling**: o modelo Groq, apesar de extremamente rápido, não é tão confiável quanto GPT-4 em tool calling estruturado. Foi necessário adicionar uma camada de fallback com Regex para limpar marcadores de código markdown que vazavam no JSON.
- **Timezone**: a data dos lançamentos fica presa no UTC do servidor Vercel, o que pode causar divergências para usuários em fusos horários diferentes. É um débito técnico conhecido para v2.

### 📚 O que aprendi sobre conversar com IAs

1. **Contexto é tudo**: quanto mais contexto estruturado você fornece (a stack, o modelo de dados, os exemplos de entrada/saída esperados), menos retrabalho você tem com as respostas da IA.
2. **A IA é melhor como "acelerador" do que como "substituição"**: as decisões de arquitetura (JWT próprio vs Auth0, esquema do banco, fluxo de confirmação) precisaram de raciocínio humano. A IA acelerou a execução, não a decisão.
3. **Iterar rápido é fundamental**: testar os prompts como "conversas curtas e diretas" e refinar incrementalmente funciona muito melhor do que tentar escrever o prompt perfeito de uma vez.

---

*Desenvolvido com ☕, muito Vibe Coding por **Samuel Ramos** para o Bootcamp DIO.*  
*Construído e otimizado com o auxílio do **Antigravity** e ferramentas da suite **Google**.*
