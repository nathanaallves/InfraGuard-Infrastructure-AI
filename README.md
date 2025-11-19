# InfraGuard – Gestão Inteligente de Infraestrutura
## *Repositório: `InfraGuard-Infrastructure-AI`*  
## *Projeto desenvolvido para o Challenge **Infra Frontier Girls***  

Monitoramento automatizado, análise inteligente e geração de relatórios mensais utilizando AI Foundry e Microsoft Azure.

---

## 📌 Sobre o Challenge

Este projeto foi criado especialmente para o **Challenge Infra Frontier Girls**, com foco em automação, engenharia de infraestrutura e uso de IA aplicada à observabilidade e governança de ambientes de TI.

O desafio exige:
- Criação de um agente funcional no AI Foundry  
- Integração com serviços do Azure  
- Ação real funcionando  
- Arquitetura documentada  
- Relatório automatizado  
- Repositório público completo  

Este README segue exatamente as exigências do Challenge.

---

## 📌 Descrição do Projeto

O **InfraGuard** é um agente inteligente desenvolvido no **AI Foundry**, integrado ao ecossistema **Microsoft Azure**, criado para automatizar o monitoramento e a gestão de infraestrutura.

Ele coleta métricas, analisa anomalias, executa automações e envia um **relatório mensal em PDF** ao responsável técnico — incluindo custos, consumo e alertas críticos.

---

## 🚀 Funcionalidades

- Coleta automática de métricas de VMs, storage e rede  
- Análise inteligente de anomalias  
- Recomendações automáticas da IA  
- Relatório mensal em PDF  
- Envio por e-mail via Logic Apps  
- Consulta a métricas e custos via Azure Functions  
- Integração direta ao agente no AI Foundry  
- Arquitetura segura, modular e escalável  

---

## 🏗️ Arquitetura da Solução

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

---


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

---

## 🧠 Passo a Passo – AI Foundry

### 1. Criar o Agente
- Nome: **InfraGuard**
- Tipo: *Standard – Developer*
- Descrição: “Agente inteligente para automação e observabilidade de infraestrutura.”

### 2. Criar a Ação
- Nome: **ConsultarInfraAzure**
- Método: POST  
- Endpoint: API Management  
- JSON de entrada:
```json
{
  "resource": "vm",
  "periodo": "mensal"
}
