<p align="center">
  <img src="docs/screenshots/logo.png" width="120" alt="Mira Logo" />
</p>

# 💸 Mira — AI Financial Assistant
> O projeto nasceu durante o Desafio de Vibe Coding da DIO e continuou evoluindo depois do primeiro MVP, passando por ciclos de melhoria visual, revisão das regras financeiras, testes e estabilização dos fluxos críticos.

[![Next.js](https://img.shields.io/badge/Next.js-16.2-black?logo=next.js)](https://nextjs.org/)
[![Prisma](https://img.shields.io/badge/Prisma-6.0-2D3748?logo=prisma)](https://www.prisma.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Supabase-3ECF8E?logo=supabase)](https://supabase.com/)
[![Groq](https://img.shields.io/badge/AI-openai%2Fgpt--oss--120b-orange)](https://groq.com/)
[![Vercel](https://img.shields.io/badge/Vercel-Hospedado-black?logo=vercel)](https://mira-finance-one.vercel.app/)
[![Remotion](https://img.shields.io/badge/Video-Remotion-blue?logo=react)](https://www.remotion.dev/)

🔗 **Acesse o App online:** [https://mira-finance-one.vercel.app/](https://mira-finance-one.vercel.app/)
*(A aplicação está em beta. Uma conta demonstrativa pode ser fornecida separadamente. Utilize somente dados fictícios na demonstração.)*

---

## 🌐 Website Promocional

O projeto conta com uma **Landing Page Promocional** moderna e de alta performance. Ela foi construída com animações dinâmicas, *glassmorphism* e design "True Mobile" (fluido e sem travamentos no scroll), focada na conversão e apresentação do produto, com seções detalhadas de features e chamada para ação integrada à plataforma.

---

## 🧠 O que é a Mira?

A **Mira** é um Web App de finanças pessoais que reduz o atrito do controle financeiro tradicional através de **Inteligência Artificial conversacional**.

![Mira Intro](docs/screenshots/intro.gif)

Em vez de preencher formulários, o usuário simplesmente fala (ou digita):

> *"Gastei 45 reais no Uber hoje."*<br>
> *"Quero juntar 2.000 reais para viajar até dezembro."*

A IA identifica a intenção, extrai e estrutura as informações e apresenta uma confirmação para revisão. A operação só é registrada depois da aprovação do usuário.

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
* **Componentes Fluídos**: Gráficos do Recharts, modais de confirmação e tabelas de lançamentos reorganizam-se dinamicamente via Flexbox/Grid CSS nativos para caber perfeitamente de telas pequenas a telas grandes de desktop.
* **Micro-interações Otimizadas**: Gavetas deslizantes (*Drawers*) e transações animadas garantem que a navegação pareça um app nativo de smartphone.

---

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 💬 **Chat financeiro com IA** | Registre despesas, receitas e metas em linguagem natural. A IA identifica a intenção, extrai e estrutura as informações e apresenta uma confirmação para revisão. A operação só é registrada depois da aprovação do usuário. |
| 🎙️ **Entrada por voz** | Fale e a aplicação transcreve sua intenção de forma natural. |
| 📊 **Dashboard** | Acompanhe saldo, balanço mensal e gráficos dinâmicos. |
| 💳 **Múltiplos cartões** | Gerencie contas diferentes com moedas diferentes, conversão e transferências internas. |
| 🎯 **Metas e aportes** | Defina objetivos financeiros e registre aportes para acompanhar seu progresso. |
| 💡 **Insights** | Visualizações e dados agregados sobre sua vida financeira. |
| 📤 **Exportação CSV** | Exporte facilmente seus lançamentos. |
| 🔐 **Segurança e acesso** | Conta com verificação de e-mail, recuperação de senha, autenticação JWT stateless com cookies HttpOnly e 2FA (TOTP). |
| 📱 **Responsividade** | Experiência focada no uso mobile, adaptável para qualquer tela. |

---

## 🛠️ Tech Stack

| Camada | Tecnologia |
|---|---|
| **Framework** | Next.js 16.2 |
| **UI** | React 19 + Framer Motion + CSS Nativo |
| **Banco de Dados** | PostgreSQL via Supabase + Prisma ORM 6 |
| **Inteligência Artificial** | Vercel AI SDK + openai/gpt-oss-120b via Groq |
| **Voz** | Whisper via Groq |
| **Autenticação** | JWT com jose, cookies HttpOnly, bcryptjs e TOTP |
| **Deploy** | Vercel |

---

## 📋 Briefing inicial e comportamento da IA

Este foi o briefing inicial usado para guiar o desenvolvimento do produto:

```txt
# Contexto
Criar um aplicativo web de organização de finanças pessoais que funcione
por meio de conversas com o usuário via chat de IA.
A ideia é reduzir o atrito do controle financeiro tradicional,
sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem
muita entrada manual e pouca personalização.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem
complicação.

# Experiência Desejada e Funcionalidades
1. Registrar gastos via chat em linguagem natural (ex: "Gastei 30 no iFood ontem").
2. Confirmação antes de persistir os dados (perguntas quando faltarem informações e tratamento de falhas).
3. Respostas estruturadas validadas pela aplicação.
4. Entrada por voz.
5. Dashboard dinâmico com saldo e gráficos.
6. Gestão de metas financeiras.
7. Suporte a múltiplos cartões e carteiras.
8. Experiência responsiva e focada no celular.

# Stack Técnica
- Next.js, React, CSS Nativo
- Prisma + PostgreSQL
- Vercel AI SDK + Groq
- Deploy na Vercel
```

Com o amadurecimento do projeto, as instruções da IA evoluíram através de engenharia de prompt, definindo o contexto, objetivo, intenções reconhecidas, campos obrigatórios, comportamento de fazer perguntas para informações ausentes, formato estruturado da resposta e comportamentos proibidos, sempre reforçando a necessidade de confirmação e reação a respostas inválidas, até a conclusão efetiva da operação.

---

## 🙋 Meu papel no projeto

Fui responsável pela concepção do produto, definição dos fluxos, regras de negócio, experiência e critérios de validação. As ferramentas de IA participaram como aceleradoras da exploração, implementação e revisão, enquanto as decisões, restrições e aprovações permaneceram sob supervisão humana.

---

## 🏗️ Arquitetura do Projeto

A arquitetura do projeto foi estruturada para suportar as necessidades do domínio de negócio:

* **Ações financeiras**: Módulos para gerenciar despesas, receitas e transferências.
* **Autenticação e segurança**: Fluxos seguros de verificação, recuperação e 2FA.
* **Chat e confirmação**: Interação em linguagem natural com validação e confirmação rigorosa antes de persistir.
* **Voz**: Processamento de transcrições de áudio.
* **Metas e insights**: Cálculos, agregações e acompanhamento de progresso.
* **Validações e câmbio**: Validação de consistência, regras financeiras e conversão de valores.
* **Prisma schema e migrações**: Estruturação dos dados e histórico de evolução do banco.
* **Testes e componentes**: Estrutura base de UI e testes para garantir a integridade dos fluxos.

---

## 🔄 Como a IA Funciona no App

```
Usuário escreve ou fala
        ↓
API de chat
        ↓
openai/gpt-oss-120b via Groq
        ↓
Resposta estruturada
        ↓
Validação
        ↓
Cartão de confirmação
        ↓
Confirmação do usuário
        ↓
Validação server-side
        ↓
Persistência
        ↓
Atualização do dashboard
```

A IA identifica a intenção, extrai e estrutura as informações e apresenta uma confirmação para revisão. A operação só é registrada depois da aprovação do usuário.
A aplicação continua responsável por validar dados, validar propriedade dos recursos, impedir intenções incompatíveis, aplicar regras financeiras, persistir informações, impedir duplicidade e comunicar sucesso ou falha.

---

## 🚀 Atualizações e estabilização

A Mira está em beta funcional. Depois da construção do MVP, o projeto passou por uma etapa ampla de estabilização dos fluxos principais e agora se encontra em validação integrada e refinamento da experiência.

Os principais fluxos passaram por um processo de fortalecimento:
- Padronização do runtime em Node.js 24.
- Fortalecimento de cadastro, verificação de e-mail, recuperação de senha e 2FA.
- Validações server-side reforçadas de valores, datas, tipos, moedas e propriedade de recursos.
- Garantia de atomicidade em operações financeiras relacionadas e consistência de transferências entre cartões de moedas diferentes.
- Incrementos atômicos robustos em metas financeiras.
- Proteção contra confirmações repetidas e mensagens de sucesso apenas após resposta válida do servidor.
- Melhoria na recuperação da interface depois de falhas.
- Testes comportamentais e estruturais dos principais invariantes financeiros.

Não existe regressão crítica ou alta confirmada aberta dentro do escopo auditado. A fase atual foca na consistência técnica e polimento antes de novas features.

---

## 💡 Reflexão sobre o processo

- **IA acelera a execução, mas não substitui decisões**: A IA auxiliou na ideação e implementação inicial, mas as regras de arquitetura e decisões de negócio continuaram sob supervisão humana.
- **Contexto e restrições reduzem retrabalho**: Instruções precisas com exemplos de saída estruturada minimizam ciclos perdidos.
- **Saídas estruturadas ainda precisam de validação**: Mesmo com instruções rígidas, os dados provenientes da IA exigem validação rigorosa na camada da aplicação.
- **Caminhos de falha também precisam ser especificados**: É fundamental preparar a aplicação para lidar com respostas incorretas, instabilidades ou estados não previstos pela IA.
- **Revisão humana e testes continuam necessários**: A validação manual integrada continua sendo essencial para assegurar que a experiência seja coesa.
- **Frontend e backend precisam concordar sobre quando uma operação terminou**: A sincronização entre confirmação do usuário e persistência final exige fluxos cuidadosos e proteção contra repetição.

---

Desenvolvido por Samuel Ramos como um projeto de produto, engenharia e interação com IA.

<br><br>
<div align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Inter&weight=600&size=24&color=000000&center=true&vCenter=true&width=200&height=40&lines=fase" alt="fase" />
  <br>
  <img src="https://readme-typing-svg.demolab.com/?font=Inter&weight=900&size=80&color=FF0000&center=true&vCenter=true&width=400&height=120&lines=BETA" alt="BETA" />
</div>
