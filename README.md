# 🤖 MatchCV AI

> **Plataforma Inteligente para Otimização de Currículos ATS com Inteligência Artificial**

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-orange)
![React](https://img.shields.io/badge/React-19-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue)
![Supabase](https://img.shields.io/badge/Supabase-Backend-green)
![OpenAI](https://img.shields.io/badge/AI-OpenAI-purple)
![License](https://img.shields.io/badge/license-MIT-green)

---

# 📖 Sobre o Projeto

O **MatchCV AI** é uma aplicação web que utiliza Inteligência Artificial para analisar a compatibilidade entre um currículo e uma vaga de emprego, gerando automaticamente uma versão otimizada para sistemas **ATS (Applicant Tracking System)**.

O objetivo é aumentar as chances do candidato ser aprovado na triagem automática realizada por empresas e plataformas de recrutamento.

Além do cálculo de compatibilidade, a plataforma identifica palavras-chave, sugere melhorias no currículo, gera uma versão ATS Friendly e oferece uma visão analítica da evolução das candidaturas.

---

# ✨ Funcionalidades

## 📄 Upload de Currículo

* Upload de PDF
* Upload de DOCX
* Upload de TXT
* Upload de Markdown

---

## 💼 Análise da Vaga

* Colar descrição da vaga
* Upload do anúncio
* Extração automática de requisitos
* Identificação de palavras-chave

---

## 🤖 Inteligência Artificial

A IA é responsável por:

* Interpretar currículos
* Interpretar vagas
* Comparar competências
* Identificar Hard Skills
* Identificar Soft Skills
* Detectar palavras-chave
* Sugerir melhorias
* Reescrever experiências profissionais
* Gerar currículo ATS Friendly

---

## 📊 Match Score

A plataforma calcula automaticamente a compatibilidade entre currículo e vaga.

Exemplo:

```
Match Geral

91%
```

---

## 🎯 ATS Score

Avalia a qualidade do currículo para sistemas ATS considerando:

* Estrutura
* Organização
* Palavras-chave
* Formatação
* Legibilidade
* Compatibilidade

Exemplo:

```
ATS Score

95%
```

---

## 📝 Geração Automática de Currículo

A IA cria automaticamente um currículo otimizado contendo:

* Resumo Profissional
* Experiência
* Formação
* Hard Skills
* Soft Skills
* Certificações
* Idiomas
* Projetos

---

## 📨 Carta de Apresentação

Geração automática de uma carta personalizada para cada vaga.

---

## 📈 Dashboard

O sistema apresenta indicadores como:

* Match médio
* ATS médio
* Histórico de candidaturas
* Empresas analisadas
* Competências mais solicitadas
* Evolução das análises

---

## 📤 Exportação

Exportação para:

* PDF
* DOCX
* Markdown
* TXT

---

# 🖥️ Interface

O projeto possui uma interface moderna inspirada em plataformas SaaS.

Principais telas:

* Login
* Dashboard
* Upload do currículo
* Inserção da vaga
* Resultado da análise
* Sugestões da IA
* Editor do currículo
* Histórico
* Configurações

---

# 🏗️ Arquitetura

```
Usuário

        │

        ▼

Frontend (React + TypeScript)

        │

        ▼

Supabase

├── Authentication

├── PostgreSQL

├── Storage

└── Edge Functions

        │

        ▼

OpenAI / LLM

        │

        ▼

Análise Inteligente

        │

        ▼

Currículo ATS Friendly
```

---

# 🛠️ Tecnologias

## Front-end

* React
* TypeScript
* Vite
* Tailwind CSS
* shadcn/ui
* React Router

## Backend

* Supabase
* PostgreSQL
* Edge Functions

## Inteligência Artificial

* OpenAI API
* ChatGPT
* Gemini
* Lovable

## Exportação

* PDF
* DOCX
* Markdown

---

# 📂 Estrutura do Projeto

```
matchcv-ai/

│

├── Video do APP de Currículos ATS

│   
```

---

# 🔄 Fluxo da Aplicação

```
Usuário

↓

Upload do Currículo

↓

Inserção da Vaga

↓

IA Analisa os Dados

↓

Match Score

↓

ATS Score

↓

Sugestões Inteligentes

↓

Novo Currículo

↓

Exportação

↓

Histórico
```

---

# 🎯 Objetivos do Projeto

* Demonstrar aplicação prática de Inteligência Artificial.
* Automatizar a personalização de currículos.
* Auxiliar candidatos a aumentarem sua taxa de aprovação em processos seletivos.
* Explorar conceitos de IA Generativa, análise textual e experiência do usuário.
* Servir como projeto de portfólio para as áreas de Desenvolvimento Full Stack, IA e Produtos Digitais.

---

# 👩‍💻 Desenvolvido por

**Camila Silva dos Santos**

Economista | Desenvolvedora em formação | IA Generativa | Análise de Dados


---

# 📄 Licença

Este projeto está licenciado sob a licença **MIT**.

Sinta-se à vontade para estudar, utilizar como referência e contribuir com melhorias.

---

## ⭐ Se este projeto foi útil para você

Considere deixar uma **⭐** no repositório. Isso ajuda a dar visibilidade ao projeto e incentiva futuras melhorias.
