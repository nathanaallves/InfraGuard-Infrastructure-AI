# InfraGuard – Gestão Inteligente de Infraestrutura
---
Repositório: InfraGuard-Infrastructure-AI  
Projeto desenvolvido para o Challenge ***Infra Frontier Girls*** 
Monitoramento automatizado, análise inteligente e geração de relatórios mensais utilizando AI Foundry e Microsoft Azure.

---

## 📌 Objetivo do Challenge

O objetivo é criar uma solução real, prática e aplicável para equipes de infraestrutura, utilizando IA para previsão, automação e insights operacionais.

Repositório público GitHub com README completo
Prints do passo a passo
Agente funcional no Foundry
Ação personalizada de cálculo
Fluxo final funcionando no Azure
Entrega dentro do prazo

Este README segue exatamente as exigências do Challenge.

---

## 📌 Descrição do Projeto

O InfraGuard é um agente inteligente desenvolvido no Azure AI Foundry com foco em monitoramento, análise e gestão de infraestrutura de TI. Ele calcula automaticamente o Índice de Saúde da Infraestrutura (IHI), gera recomendações técnicas, armazena dados no Azure e envia um relatório mensal automático ao gestor.

```text
InfraGuard-Infrastructure-AI
│
├── README.md
│
├── docs/
│   ├── arquitetura.md
│   ├── fluxos.md
│   └── referencias.md
│
├── Scripts/
│   ├── automacoes.ps1
│   └── consumo.py
│
└── agent/
    ├── agent.json
    └── actions/
        └── calcular_consumo.yaml
```


---

## 🚀 Funcionalidades

- Cálculo automático do Índice de Saúde da Infraestrutura (IHI)
- Diagnóstico inteligente baseado em métricas fornecidas
- Classificação de criticidade
- Recomendações técnicas automáticas
- Armazenamento dos dados no Azure
- Relatório mensal automático via e-mail com insights

---

## 🏗️ Arquitetura da Solução
```text
Usuário → AI Foundry Agent → Azure API Management
↓
Azure Function (Python)
↓
Azure Monitor / Log Analytics / Cost Management
↓
Processamento e Análise
↓
Azure Storage → Geração de PDF
↓
Logic Apps → E-mail
```

---

## 🛠️ Componentes Utilizados

| Componente | Função |
|-----------|--------|
| **AI Foundry Agent** | Inteligência e interface |
| **Azure API Management** | Segurança e gateway |
| **Azure Functions** | Processamento e coleta de métricas |
| **Azure Monitor / Log Analytics** | Observabilidade |
| **Azure Cost Management** | Dados financeiros |
| **Azure Storage** | Armazenamento do relatório |
| **Logic Apps** | Envio de e-mails |

---

## 📘 Requisitos do Challenge (Atendidos)

- Repositório público com README.md ✔  
- Prints do agente funcionando ✔  
- Azure Function ativa ✔  
- Lógica de automação configurada ✔  
- Fluxo no Foundry com ação funcional ✔  
- Relatório mensal automatizado ✔  
- Arquitetura documentada ✔  


