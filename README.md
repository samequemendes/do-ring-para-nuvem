# 🥊 Curso: Do Ringue para a Nuvem – Um Knockout na Carreira em TI

Formação prática e direta para novos profissionais de TI, com foco em **DevOps**, **Cloud AWS**, **Engenharia de Plataforma** e **Infraestrutura como Código (IaC)**. A proposta é ensinar de forma acessível, utilizando a metáfora do **boxe** como inspiração para disciplina, evolução contínua e resiliência.

---

## 🎯 Objetivo do Curso

Entregar 2 produtos reais e aplicáveis:
1. 🚀 **App Base do Projeto (MVP funcional)** – Infra + Front + Back + Pipelines.
2. 🛠️ **Internal Developer Portal (IDP)** – Portal de provisionamento, documentação e Developer Experience (DevEx) para evolução do projeto.

---

## 📚 Estrutura Completa do Curso

---

### 🔥 Módulo 0 – Aquecimento (Setup Inicial)

- Introdução ao curso e à metáfora do boxe.
- Requisitos básicos: Git, terminal, curiosidade.
- Setup do ambiente:
  - Linux/WSL.
  - AWS CLI.
  - Terraform.
  - VS Code.

---

### 🔥 Módulo 1 – Fundamentos (Jab de Conhecimento)

- Conceitos base: Cloud, AWS, DevOps.
- Diferença entre DevOps e Engenharia de Plataforma.
- Introdução à IaC (Infraestrutura como Código).
- Git + GitFlow (controle de versionamento).

---

### 🔥 Módulo 2 – Entrando no Octógono (Pipeline Orquestradora)

- Estrutura de um projeto real.
- Criação da pipeline orquestradora (Azure DevOps).
- Organização dos repositórios:
  - Infraestrutura
  - Frontend
  - Backend
- Pipeline por stages: **infra ➔ backend ➔ frontend**.
- Conceitos:
  - `resources.repositories`
  - `variable groups`

---

### 🔥 Módulo 3 – Infraestrutura AWS com Terraform

- Padrão de projeto:
  - `backend.tf`
  - `provider.tf`
  - `main.tf`
  - `outputs.tf`
  - `variables.tf`
- Multiambiente: `hml`, `prd`.
- Deploy de:
  - S3
  - DynamoDB
  - ACM
  - Route 53
- Segurança:
  - IAM Roles
  - Assume Role
  - AWS Provider com aliases.
- Boas práticas: tags, backend remoto, separação de arquivos.

---

### 🔥 Módulo 4 – Frontend na Nuvem

- Hosting estático (S3 + CloudFront).
- HTTPS via ACM.
- Integração de domínio (Route 53).
- Pipeline de build + deploy com:
  - Compressão.
  - Cache busting.

---

### 🔥 Módulo 5 – Backend Serverless

- Lambda + API Gateway + Cognito.
- API RESTful segura.
- Deploy via Terraform.
- CRUD com DynamoDB ou DocumentDB.
- Roles mínimas e boas práticas de segurança.

---

### 🔥 Módulo 6 – Observabilidade e Monitoramento

- Monitoramento com CloudWatch.
- Logging estruturado (JSON).
- Health Checks com ALB.
- Alertas básicos de Lambda e CloudFront.

---

### 🔥 Módulo 7 – Projeto Final: App Base do Projeto

- Montagem do projeto completo:
  - Infraestrutura + Backend + Frontend + Segurança + Observabilidade.
- Apresentação do case: **It’s On Fight**.
- Publicação no GitHub.
- Desafio final:
  - Criar um mini projeto autoral com tudo aprendido.

---

## 🛠️ Módulo 8 – Internal Developer Portal (IDP) & Entrega DevEx

### 🎯 Objetivo

Construir um **Developer Portal** funcional, permitindo:
- Consulta da documentação técnica.
- Provisionamento self-service de novos recursos.
- Acesso ao catálogo de serviços.
- Continuidade do projeto através do IDP.

### 🛠️ Stack Recomendada

- [Backstage (Spotify)](https://backstage.io/) – Framework IDP.
- Terraform – Infraestrutura como Código.
- Azure DevOps Pipelines.
- Docker ou ECS para deploy do portal.

### 📦 Conteúdos do Módulo

1. Conceitos de **DevEx** e **IDP**.
2. Instalação e configuração do Backstage.
3. Deploy do portal no ambiente cloud.
4. Criação do **Catálogo de Serviços**:
   - Frontend
   - Backend
   - Pipelines
   - Infraestrutura
5. Templates para novos repositórios e pipelines.
6. Integração **GitOps** (provisionamento via PR).
7. Documentação viva:
   - Conexão com Markdown dos repositórios.
8. IDP como porta de entrada do time de desenvolvimento.

---

## ✅ Produtos Finais do Curso

1. 🚀 **App Base do Projeto (MVP)**:
   - Backend Serverless + Frontend + Infraestrutura AWS.
   - Segurança e Observabilidade.
   - Pipelines automatizadas.

2. 🛠️ **Internal Developer Portal (IDP)**:
   - Portal de gestão técnica, documentação e provisionamento.
   - Foco em Developer Experience (DevEx).
   - Plataforma para continuidade e evolução da aplicação.

---

> Este curso forma profissionais prontos para o mercado, entregando projetos reais desde o primeiro deploy.
