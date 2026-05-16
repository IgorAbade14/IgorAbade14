# Hi there, I'm Igor Abade! 👋

### 👨‍💻 DevOps & Infrastructure Engineer
Como acadêmico de Engenharia de Software e profissional focado em cultura DevOps, dedico meu trabalho ao provisionamento de infraestrutura como código (IaC), automação de pipelines de entrega e orquestração de containers. Desenvolvo arquiteturas resilientes e monitoráveis, com foco em alta disponibilidade e eliminação de trabalho repetitivo (*toil*).

---

### 🛠️ Tech Stack & Ecosystem

| Categoria | Tecnologias e Ferramentas |
| :--- | :--- |
| **Cloud Computing** | AWS (EC2, VPC, S3, IAM, ALB, EKS) |
| **Infraestrutura como Código** | Terraform (Modules, State Management, S3 Remote Backend) & HCL |
| **Containers & Orquestração** | Docker, Docker Compose, Kubernetes (K8s) & Minikube |
| **CI/CD & Automação** | GitHub Actions, Bash Scripting & Python |
| **Sistemas & Servidores** | Linux (Debian, Ubuntu, Mint), NGINX & Apache |
| **Observabilidade & Redes** | Prometheus, Grafana, Protocolos TCP/IP, DNS & SSH |

---

### 🚀 Projetos Técnicos em Destaque

#### 🌐 [Mint-Orchestrator](https://github.com/IgorAbade14/Mint-Orchestrator)
> **Status do Projeto:** ![CI/CD Status](https://github.com/IgorAbade14/Mint-Orchestrator/actions/workflows/main.yml/badge.svg)

Aplicação Python/Flask orquestrada em ambiente Kubernetes (Minikube). Conta com um pipeline de CI/CD automatizado via GitHub Actions que realiza validação sintática e testes de integridade estrutural offline dos manifestos de `Deployment` e `Service` antes do build da imagem Docker.

#### 📡 [Status-Pulse](https://github.com/IgorAbade14/Status-Pulse)
Arquitetura de Nuvem 100% gerenciada via **Terraform**, utilizando módulos reutilizáveis para segregação de camadas de rede, segurança e aplicação na **AWS**. Conta com persistência de estado (`tfstate`) via S3 Remote Backend e automação de deploys com GitHub Actions.
> **Status do Projeto:** (https://github.com/IgorAbade14/Status-Pulse/actions/workflows/terraform.yaml)

#### ⚖️ [Load Balanced Web Stack](https://github.com/IgorAbade14/load-balanced-web-stack)
Provisionamento de uma infraestrutura resiliente e tolerante a falhas distribuída em múltiplas Zonas de Disponibilidade (**Multi-AZ**) na AWS via Terraform. Implementação de **Application Load Balancer (ALB)** para distribuição inteligente de tráfego e regras de firewall em cascata via Security Groups.

#### 📦 [SerraStack v2.0](https://github.com/IgorAbade14/SerraStack)
Provisionamento automatizado de uma stack LEMP completa utilizando **Docker Compose** para isolamento de serviços. Implementação de scripts em Bash para *Auto-Healing* (limpeza de recursos órfãos, reconstrução de ambiente e validação de `Healthchecks`).

#### ⚙️ [UpKeeper v1.0](https://github.com/IgorAbade14/UpKeeper-Version-1.0)
Desenvolvimento de scripts robustos em **Bash** para gerenciamento de manutenção preventiva em sistemas baseados em Debian/Ubuntu. Implementação de conceitos de idempotência e gestão de janelas de manutenção crítica baseada em lógica condicional.

---

### 📫 Conecte-se comigo:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/igorabade14)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/IgorAbade14)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abadeti123@gmail.com)

---
*"Automating the boring stuff to build resilient and scalable futures."*
