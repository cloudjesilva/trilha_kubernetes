# Trilha Kubernetes — Monorepo de Projetos Cloud Native

Este repositório reúne três módulos complementares desenvolvidos durante minha trilha de estudos em **Kubernetes**, **Istio**, **Helm** e **observabilidade**.  
O objetivo é demonstrar, de forma prática, minha experiência com arquitetura de microsserviços, service mesh, roteamento avançado, deploy progressivo e boas práticas de infraestrutura moderna.

---

## 📂 Estrutura do Repositório

trilha_kubernetes/
├── microservices-app/     # Aplicação Node.js em arquitetura de microsserviços
├── charts-helm/           # Pacotes Helm para deploy automatizado
└── istio/                 # Configurações de Service Mesh, Canary, Rolling e Gateway

---

## 🚀 Módulos do Projeto

### **1. microservices-app**
Aplicação em Node.js estruturada em microsserviços, utilizada como base para testes de deploy, roteamento e observabilidade.

**Principais pontos:**
- Comunicação entre serviços
- Deploy em cluster Kubernetes
- Testes de resiliência e falhas

---

### **2. charts-helm**
Pacotes Helm criados para automatizar deploys e padronizar configurações no cluster.

**Inclui:**
- Templates Helm
- Values configuráveis
- Estrutura para CI/CD
- Deploy simplificado via `helm install`

---

### **3. istio**
Configurações completas de **Service Mesh** utilizando Istio.

**Conteúdo:**
- Sidecar injection automático
- DestinationRules com subsets (prod / canary)
- VirtualServices com roteamento avançado
- Retries automáticos e timeouts
- Ingress Gateway configurado
- ServiceEntry para controle de saída
- Canary Release baseado em headers
- Rolling Release baseado em weight
- Observabilidade com Kiali, Prometheus e Grafana

---

## 🧠 Habilidades Demonstradas

- Kubernetes (deploy, services, ingress, namespaces)
- Istio (service mesh, roteamento, segurança, observabilidade)
- Helm (templates, values, deploy automatizado)
- Canary Release e Rolling Update
- Kiali para visualização de tráfego
- Prometheus e Grafana para métricas
- Boas práticas de arquitetura cloud native
- Git e GitHub (monorepo, versionamento, organização)

---

## 🛠️ Tecnologias Utilizadas

- **Kubernetes**
- **Istio**
- **Helm**
- **Node.js**
- **Prometheus**
- **Grafana**
- **Kiali**
- **Minikube**

---

## 📈 Objetivo do Repositório

Este monorepo foi criado para demonstrar minha evolução prática na trilha de Kubernetes e Service Mesh, consolidando conhecimentos essenciais para atuar como:

- DevOps Engineer  
- SRE (Site Reliability Engineer)  
- Cloud Engineer  
- Platform Engineer  

---

## 📬 Contato

Se quiser saber mais sobre o projeto ou conversar sobre oportunidades:

**👤 Jefferson Silva**  
**GitHub:** https://github.com/cloudjesilva  
**LinkedIn:** *((https://www.linkedin.com/in/jeffersonanalistacloudaws/))*

---

