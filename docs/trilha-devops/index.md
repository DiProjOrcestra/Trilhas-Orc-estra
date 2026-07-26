# Trilha de DevOps

---

## 1. Visão Geral e Objetivos

Este documento padroniza a capacitação interna da **Orc’estra Gamificação** para a área de **DevOps**.

O objetivo é oferecer um caminho de aprendizado direcionado e eficiente, levando em consideração o tempo dos membros para focar direto nas tecnologias essenciais. Ao final da trilha, o membro estará apto a gerenciar ambientes de infraestrutura, automatizar esteiras de entrega (CI/CD) e suportar as aplicações da Orc'estra com alta disponibilidade e segurança.

---

## Módulos de Aprendizado

### Módulo 1: Linux
Conhecer o sistema de diretórios do Linux, editar arquivos no console, gerenciar processos, variáveis de ambiente, PATH, pacotes e comunicação remota via SSH e SCP.

### 1.1 Downloads & Instalação
- 🌐 [Download Ubuntu Oficial](https://ubuntu.com/download)
- 🌐 [Artigo: Linux — Download, Instalação e Comandos Básicos (Alura)](https://www.alura.com.br/artigos/linux-download-instalacao-distribuicoes-e-principais-comandos)

### 1.2 Guias & Artigos de Apoio
- 🌐 [Guia: Comandos Básicos no Linux](https://medium.com/linkapi-solutions/comandos-b%C3%A1sicos-no-linux-95079363ab0e)
- 🌐 [Artigo: Entendendo Permissões no Linux (Alura)](https://www.alura.com.br/artigos/entendendo-as-permissoes-no-linux)
- 🌐 [Artigo: Compactando e Descompactando Arquivos com TAR (Alura)](https://www.alura.com.br/artigos/linux-compactando-e-descompactando-arquivos-com-o-tar)
- 🌐 [Artigo: Como Acessar Servidores Remotamente com SSH (Alura)](https://www.alura.com.br/artigos/como-acessar-servidores-remotamente-com-ssh)

### 1.3 Cursos & Prática
- 🎥 [Vídeo: Dual Boot e Configuração do Linux](https://www.youtube.com/watch?v=UTqDuWHbZkw&t=187s)
- 🎥 [Curso Completo de Linux no YouTube](https://www.youtube.com/watch?v=epiyExCyb2s)
- 🌐 [Curso Prático: Linux Basic Commands (LabEx)](https://labex.io/courses/linux-basic-commands-practice-online)
- 🌐 [Curso Gratuito: Linux Unhatched (Cisco NetAcad)](https://www.netacad.com/courses/linux-unhatched?courseLang=en-US)
- 🌐 [Curso Gratuito: Linux Essentials (Cisco NetAcad)](https://www.netacad.com/courses/linux-essentials?courseLang=en-US)
- 🌐 [Guia Interativo: Linux Journey (LabEx)](https://labex.io/linuxjourney)
- 🌐 [Curso Gratuito: Linux Essentials (4Linux)](https://4linux.com.br/cursos/produto/linux-essentials/)

---

### Módulo 2: Redes
Compreender o modelo OSI e a pilha TCP/IP. Configurar e diagnosticar a resolução de nomes (DNS).

### 2.1 Cursos Recomendados
- 🌐 [Curso Gratuito: Networking Basics (Cisco NetAcad)](https://www.netacad.com/pt/courses/networking-basics?courseLang=pt-BR)
- 🎥 [freeCodeCamp: Aulas de Redes de Computadores](https://www.youtube.com/@freecodecamp/search?query=computer%20networking)

---

### Módulo 3: Git & Versionamento
Dominar o versionamento de código, resolução de conflitos em branches, integração de repositórios remotos e uso do Git como gatilho central para automações (CI/CD) e GitOps.

### 3.1 Fundamentos de Git & GitHub
- 🎥 [Vídeo: O que é Git e GitHub #01](https://www.youtube.com/watch?v=DqTITcMq68k)
- 🎥 [Vídeo: O que é Git e GitHub #02](https://www.youtube.com/watch?v=UBAX-13g8OM)
- 🌐 [Artigo: Guia de Git e GitHub (Alura)](https://www.alura.com.br/artigos/o-que-e-git-github)
- 🌐 [Curso Interativo: GitHub Skills](https://learn.github.com/skills)

### 3.2 Automação & GitOps
- 🎥 [Vídeo: O que é CI/CD?](https://youtu.be/F51HlrEeedw?si=z3BqDgY4IUnc0wsI)
- 🎥 [Vídeo: Entendendo o Conceito de GitOps](https://www.youtube.com/watch?v=E_jIbfix1JE)

---

### Módulo 4: Arquitetura (Monólito & Microsserviços)
Entender o ciclo de vida de aplicações monólitas vs microsserviços. Estruturar comunicação entre serviços via APIs RESTful e protocolos HTTP.

### 4.1 Conceitos de Microsserviços & Web
- 🌐 [Guia: Arquitetura de Microsserviços (Google Cloud)](https://cloud.google.com/learn/what-is-microservices-architecture?hl=pt-BR)
- 🎥 [Vídeo: Monolitos vs Microsserviços](https://www.youtube.com/watch?v=ooJjxNsQnK4)
- 🌐 [Documentação: Visão Geral do Protocolo HTTP (MDN)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Overview)
- 🎥 [Vídeo: Como Funciona a Internet?](https://www.youtube.com/watch?v=A-hNZjcaS-Q&t=449s)

### 4.2 Design de APIs
- 🌐 [Guia: Boas Práticas de Design de APIs RESTful (Microsoft)](https://learn.microsoft.com/pt-br/azure/architecture/best-practices/api-design)

---

### Módulo 5: Docker & Kubernetes
Escrever Dockerfiles otimizados para empacotar aplicações, isolar processos, gerenciar redes de contêineres e escrever manifestos de Kubernetes.

### 5.1 Cursos Recomendados
- 🌐 [Curso Gratuito: Containers Fundamentals (4Linux)](https://4linux.com.br/cursos/produto/containers-fundamentals/)
- 🎥 [freeCodeCamp: Aulas de Docker no YouTube](https://www.youtube.com/@freecodecamp/search?query=docker)

---

### Módulo 6: Monitoramento & Segurança (DevSecOps)
Instrumentar sistemas para coletar logs, métricas e traces. Criar dashboards, configurar alertas e integrar varreduras de segurança diretamente na esteira de entrega.

### 6.1 Cibersegurança & DevSecOps
- 🌐 [Curso Gratuito: Introdução à Cibersegurança (Cisco NetAcad)](https://www.netacad.com/pt/courses/introduction-to-cybersecurity?courseLang=pt-BR)
- 🌐 [Curso Gratuito: CyberOps Associate (Cisco NetAcad)](https://www.netacad.com/courses/cyberops-associate?courseLang=en-US)
- 🌐 [Curso Gratuito: Security Essentials (4Linux)](https://4linux.com.br/cursos/produto/security-essentials/)
- 🎥 [freeCodeCamp: Aulas de Cibersegurança](https://www.youtube.com/@freecodecamp/search?query=cybersecurity)

### 6.2 Observabilidade & Monitoramento
- 🌐 [Curso Gratuito: Observabilidade e Monitoramento (4Linux)](https://4linux.com.br/cursos/produto/observability-and-monitoring-fundamentals/)
- 🌐 [Curso em Vídeo: Network+ N10-009 (Professor Messer)](https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-training-course/)
- 🎥 [freeCodeCamp: Prometheus e Grafana](https://www.youtube.com/@freecodecamp/search?query=prometheus%20grafana)

---

### Módulo 7: Cloud & Infraestrutura como Código (IaC)
Alocar recursos computacionais em provedores de nuvem (AWS, GCP, Azure) e escrever infraestrutura automatizada com ferramentas de IaC como Terraform.

### 7.1 Cursos Recomendados
- 🌐 [Curso Gratuito: Cloud Fundamentals (4Linux)](https://4linux.com.br/cursos/produto/cloud-fundamentals/)
- 🌐 [Trilha de Aprendizado: Azure Fundamentals (Microsoft)](https://learn.microsoft.com/pt-br/training/paths/azure-fundamentals-describe-azure-architecture-services/)

---

### Módulo 8: Troubleshooting
Conduzir análises de causa raiz (Root Cause Analysis), correlacionar métricas e logs em sistemas distribuídos e utilizar ferramentas de console para restaurar serviços.

### 8.1 Cursos & Recursos
- 🌐 [Curso Gratuito: Network Troubleshooting (Cisco NetAcad)](https://www.netacad.com/courses/network-addressing-and-basic-troubleshooting?courseLang=en-US)
- 🌐 [Portal de Treinamentos: Professor Messer](https://www.professormesser.com/)
- 🌐 [Curso Gratuito: Soft Skills e Carreiras de TI (4Linux)](https://4linux.com.br/cursos/produto/soft-skills-carreiras-de-ti/)

---

### Módulo 9: Formações e Cursos Completos de DevOps
Cursos e especializações recomendadas para aprofundamento na carreira de Engenharia de DevOps.

### 9.1 Cursos & Guias Gratuitos
- 🌐 [Curso Gratuito: DevOps Essentials (4Linux)](https://4linux.com.br/cursos/produto/devops-essentials/)
- 🌐 [Trilha de Carreira: Engenheiro DevOps (Microsoft)](https://learn.microsoft.com/en-gb/training/career-paths/devops-engineer)
- 🌐 [Módulo de Aprendizado: Entregar com DevOps (Microsoft)](https://learn.microsoft.com/en-us/training/modules/deliver-with-devops/)
- 📁 [Planilha de Recursos & Cursos Guia DevOps](https://docs.google.com/spreadsheets/d/1sP9ynQNBIe3NgnQL65YN6Fe0fuUxN2g0fslLrJsyEFQ/htmlview)
- 🌐 [Roadmap Completo de Carreira DevOps (Roadmap.sh)](https://roadmap.sh/devops)

### 9.2 Cursos Pagos Recomendados
- 🌐 [Formação DevOps (Alura)](https://www.alura.com.br/cursos-online-devops)
- 🌐 [Formação DevOps (4Linux)](https://4linux.com.br/cursos/devops/)

---

## Próximo Passo: Projeto Integrador

Concluiu os estudos teóricos dos módulos? Agora é hora de colocar a mão na massa no **Projeto Integrador Site Orc**!

[Ir para o Projeto Integrador: Site Orc ➔](desafio.md){ .md-button .md-button--primary }
