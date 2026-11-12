## Olá, sou o Lucas 👋

Engenheiro backend em Fortaleza. Há seis anos coloco em produção APIs e microsserviços em **Java, Python e Go**, e hoje meu foco é **observabilidade**: entender por que os sistemas se comportam como se comportam, inclusive quando a saída é gerada por LLMs e agentes de IA.

Faço mestrado em Ciência da Computação na **UFC**, com pesquisa em *observabilidade inteligente em sistemas distribuídos com agentes de IA*.

### Em que trabalho

- **Observabilidade:** OpenTelemetry, Prometheus, Grafana, Loki, Jaeger, tracing distribuído, análise de causa-raiz
- **IA aplicada:** microsserviços com LLMs (AWS Bedrock, OpenAI), RAG sobre dados estruturados e grafos de conhecimento
- **Backend:** Spring Boot, microsserviços, pagamentos, RBAC, PostgreSQL, MongoDB, Neo4j, Redis
- **Infra:** Docker, AWS, Terraform, CI/CD

### Destaques

- 📄 **Quanto custa observar?** Artigo em coautoria (mestrado, UFC) que mede o overhead da stack Prometheus + Grafana + Loki + Jaeger via OpenTelemetry em microsserviços Spring Boot. Em 180 execuções num desenho fatorial 2×3, o overhead de latência foi significativo em todas as cargas e chegou a **+58,5% no p99 (+10 ms) sob carga alta**, com perda de vazão de no máximo 1,8%. [Código, dados e artigo](https://github.com/lucasameneses/observability-overhead-benchmark).
- 🏫 **Plataforma educacional em produção:** backend de uma plataforma de ensino adaptativo com ~10 mil usuários e mais de 670 mil respostas processadas. Trabalhei em microsserviços de IA, pagamentos, RBAC e na instrumentação para análise de causa-raiz.

### Projetos

| Projeto | Sobre |
|---|---|
| [microservices-failure-lab](https://github.com/lucasameneses/microservices-failure-lab) | Laboratório reproduzível do meu TCC (IFCE): quatro cenários de falha em microsserviços diagnosticados com métricas, logs e traces |
| [observability-overhead-benchmark](https://github.com/lucasameneses/observability-overhead-benchmark) | Avaliação de desempenho (mestrado, UFC): quanto a stack de observabilidade custa em latência, vazão, CPU e memória a microsserviços Spring Boot, em 180 execuções com testes estatísticos |
| llm-observability-lab *(em construção)* | Tracing de aplicações com LLMs e agentes usando as convenções GenAI do OpenTelemetry |

### Contato

[LinkedIn](https://www.linkedin.com/in/lucas-alves-b75430165/) · lucasalvesmnss@gmail.com
