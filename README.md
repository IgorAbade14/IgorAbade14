# Hi there, I'm Igor Abade! 👋

👨‍💻 **DevOps & Infrastructure Engineer**

Como acadêmico de Engenharia de Software e profissional focado em cultura DevOps, dedico meu trabalho ao provisionamento de infraestrutura como código (IaC), automação de pipelines de entrega e orquestração de containers. Desenvolvo arquiteturas resilientes, seguras e monitoráveis, com foco em alta disponibilidade e eliminação de trabalho repetitivo (toil) sob os princípios de SRE.

---

## 🛠️ Tech Stack & Ecosystem

| Categoria | Tecnologias e Ferramentas |
| :--- | :--- |
| **Cloud Computing** | AWS (EC2, VPC, S3, IAM, ALB, EKS) & LocalStack (Cloud Simulation)[cite: 1] |
| **Infraestrutura como Código** | Terraform (Modules, State Management, S3 Remote Backend) & HCL[cite: 1] |
| **Containers & Orquestração** | Docker, Docker Compose (Multi-stage builds) & Kubernetes (K8s / Minikube)[cite: 1] |
| **CI/CD & Versionamento** | Git, GitHub & GitHub Actions (Automação de workflows e deploys)[cite: 1] |
| **Sistemas & Automação** | Linux (Debian, Ubuntu, Mint), Bash Scripting & Python[cite: 1] |
| **Observabilidade & Redes** | Prometheus, Grafana, NGINX (Proxy Reverso, Load Balancing), TCP/IP, DNS & SSH[cite: 1] |
| **Formatos de Configuração** | YAML, JSON & XML[cite: 1] |

---

## 🚀 Projetos Técnicos em Destaque

### 🧪 [Sandbox-Zero](https://github.com/IgorAbade14/Sandbox-Zero) | Nuvem Simulada & Engenharia de Confiabilidade (SRE)
* **Simulação & Orquestração:** Provisionamento via Terraform de uma infraestrutura local utilizando LocalStack para emulação de S3 integrado a um cluster Kubernetes (Minikube)[cite: 1].
* **Observabilidade Avançada:** Coleta de métricas via Prometheus e criação de dashboards personalizados no Grafana cruzando fronteiras de isolamento através do DNS interno (CoreDNS)[cite: 1].
* **Inteligência de Alertas:** Regras rígidas de alertas temporais (*Evaluate every 10s / For 10s*) mitigando comportamentos matemáticos de borda (divisão por zero) em cenários de ausência de dados[cite: 1].
* **Esteira CI/CD:** Pipeline no GitHub Actions para checagem sintática de código (`terraform fmt/validate`), validação estrutural de Docker Compose e testes estáticos de scripts Bash[cite: 1].

### 📡 [Status-Pulse](https://github.com/IgorAbade14/Status-Pulse) | Infrastructure as Code & Cloud Automation
* **Provisionamento Modularizado (IaC):** Arquitetura 100% gerenciada via Terraform, utilizando módulos reutilizáveis para segregação de camadas de rede, segurança e aplicação na AWS[cite: 1].
* **Persistência de Estado e CI/CD:** Implementação de S3 Remote Backend para gestão de estado (`tfstate`) e automação de fluxos de deploy através de pipelines no GitHub Actions[cite: 1].
* **Segurança e Networking:** Configuração de VPC customizada com regras rígidas de firewall (Security Groups em cascata) e controle de acesso via chaves SSH[cite: 1].
* **Bootstrap Dinâmico:** Automação de instâncias EC2 com Docker Engine via scripts de `user_data`, incluindo seleção dinâmica de recursos baseada no ambiente (Dev/Prod)[cite: 1].

### 🌐 [Mint-Orchestrator](https://github.com/IgorAbade14/Mint-Orchestrator) | Container Orchestration & CI/CD Pipelines
* **Orquestração e Resiliência (K8s):** Implantação de aplicação Python/Flask em Kubernetes (Minikube) utilizando objetos nativos (Deployments com múltiplas réplicas e Services para Load Balancing) e Probes de Liveness/Readiness para Self-Healing[cite: 1].
* **Automação de Build:** Scripts robustos em Bash para automação de builds Docker utilizando um sistema de versionamento dinâmico baseado em timestamps, mitigando falhas de cache do cluster (`ImagePullBackOff`)[cite: 1].
* **Pipeline de Integração Contínua:** Criação de esteiras automatizadas via GitHub Actions focadas na validação sintática do código fonte e em testes de integridade estrutural offline dos manifestos de infraestrutura[cite: 1].

## 📫 Conecte-se comigo:

🤝 [LinkedIn](https://linkedin.com/in/igorabade14) | ✉️ [E-mail](mailto:abadeti123@gmail.com)[cite: 1]

---

> "Automating the boring stuff to build resilient and scalable futures."
