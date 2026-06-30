<p align="center">
  <a href="#-english">
    <img src="https://img.shields.io/badge/English-blue?style=for-the-badge" />
  </a>
  <a href="#-português">
    <img src="https://img.shields.io/badge/Português-green?style=for-the-badge" />
  </a>
</p>

---

# 🇺🇸 English
# Rafael Sodré Paschoal

Computer Science student @ UEPB (expected 2028)
📍 Brazil | Open to internships / junior backend roles

Backend Engineer focused on scalable, secure, and production-oriented systems.

I build backend applications using Java, Spring Boot, Python, and FastAPI, with emphasis on clean architecture, API design, data consistency, and real-world problem solving.

---

## Projects

### [whisp](https://github.com/rafaelsodrepsc/whisp) · Java · WIP

Real-time chat platform focused on backend architecture and distributed communication.

- Real-time messaging with WebSocket
- Authentication and authorization with JWT/OAuth2
- Event-driven persistence with Kafka and session state in Redis
- Health checks and metrics with Spring Actuator
- Unit test suite (16 tests) covering core domain logic
- Multistage Dockerfiles orchestrated with Docker Compose
- AI service layer integrating the Groq API via Java 21 native HttpClient
- Angular frontend (whisp-client) in progress, consuming the backend API

Focus: real-time communication, API security, distributed system design, and separating WebSocket delivery, Kafka persistence, and Redis session state.

`Java 21` `Spring Boot` `WebSocket` `JWT/OAuth2` `PostgreSQL` `Docker` `Kafka` `Redis` `Angular`

---

### [rag-java](https://github.com/rafaelsodrepsc/rag-java) · Java

RAG-based document Q&A API that:

- Processes PDF/TXT documents into semantic chunks
- Generates embeddings and stores them in pgvector
- Retrieves relevant context before answering
- Keeps answers grounded in source documents

Focus: retrieval accuracy, scalable ingestion, and reducing hallucinations.

`Java 21` `Spring Boot 3.5` `LangChain4j` `OpenAI` `PostgreSQL + pgvector` `Docker`

---

### [csv-analyst-api](https://github.com/rafaelsodrepsc/csv-analyst-api) · Python

API that allows users to query CSV data using natural language.

- Converts natural language questions into Pandas operations through an LLM
- Executes generated code in a restricted environment
- Uses AST validation, isolated namespace, and runtime limits to reduce unsafe execution risks

Focus: safe LLM code execution and data accessibility.

`FastAPI` `Pandas` `Groq API` `LLaMA 3.3 70B` `python-dotenv`

---

### [Ranker](https://github.com/rafaelsodrepsc/Ranker) · Java

Championship management system supporting multiple tournament formats.

- Round Robin with mirror pairing and odd-team handling
- Single-elimination brackets with power-of-2 validation
- Match scheduling across venues and dates
- Standings table with tie-breaker rules
- Optional JavaFX desktop interface branch

Focus: algorithm design, object-oriented modeling, and data consistency.

`Java 21` `OOP` `Streams & Lambdas` `Custom Exceptions` `Scheduling Algorithm` `JavaFX`

---

## What I'm focusing on

- Designing scalable backend systems
- Building secure and reliable APIs
- Applying AI and LLMs to practical backend problems
- Improving system design, performance, and observability
- Working with AI-assisted development workflows (Claude Code, code review agents)

---

## Stack

**Backend:** Java, Spring Boot, Python, FastAPI, Flask
**Frontend:** Angular
**Databases:** PostgreSQL (+ pgvector), MySQL
**Messaging & Cache:** Kafka, Redis
**AI & Data:** LLM APIs, RAG, Prompt Engineering, Pandas
**Infrastructure:** Docker, Docker Compose, AWS EC2, AWS S3
**Security:** OAuth2, JWT

---

## Contact

[rafaelsodrepaschoal@gmail.com](mailto:rafaelsodrepaschoal@gmail.com) · [linkedin.com/in/rafaelsodrepsc](https://linkedin.com/in/rafaelsodrepsc)

---

# 🇧🇷 Português
# Rafael Sodré Paschoal

Estudante de Ciência da Computação na UEPB, com previsão de formação em 2028.
📍 Brasil | Aberto a estágios e vagas júnior em backend

Desenvolvedor Backend com foco em sistemas escaláveis, seguros e orientados a produção.

Construo aplicações backend usando Java, Spring Boot, Python e FastAPI, com ênfase em arquitetura limpa, design de APIs, consistência de dados e resolução de problemas reais.

---

## Projetos

### [whisp](https://github.com/rafaelsodrepsc/whisp) · Java · WIP

Plataforma de chat em tempo real focada em arquitetura backend e comunicação distribuída.

- Mensagens em tempo real com WebSocket
- Autenticação e autorização com JWT/OAuth2
- Persistência orientada a eventos com Kafka e estado de sessão em Redis
- Health checks e métricas com Spring Actuator
- Suíte de testes unitários (16 testes) cobrindo a lógica de domínio
- Dockerfiles multistage orquestrados com Docker Compose
- Camada de IA integrando a API da Groq via HttpClient nativo do Java 21
- Frontend em Angular (whisp-client) em desenvolvimento, consumindo a API do backend

Foco: comunicação em tempo real, segurança de APIs, design de sistemas distribuídos e separação entre entrega via WebSocket, persistência via Kafka e estado de sessão via Redis.

`Java 21` `Spring Boot` `WebSocket` `JWT/OAuth2` `PostgreSQL` `Docker` `Kafka` `Redis` `Angular`

---

### [rag-java](https://github.com/rafaelsodrepsc/rag-java) · Java

API de perguntas e respostas sobre documentos usando RAG.

- Processa documentos PDF/TXT em chunks semânticos
- Gera embeddings e armazena em pgvector
- Recupera contexto relevante antes de responder
- Mantém as respostas baseadas nos documentos de origem

Foco: precisão na recuperação, ingestão escalável e redução de alucinações.

`Java 21` `Spring Boot 3.5` `LangChain4j` `OpenAI` `PostgreSQL + pgvector` `Docker`

---

### [csv-analyst-api](https://github.com/rafaelsodrepsc/csv-analyst-api) · Python

API que permite consultar dados CSV usando linguagem natural.

- Converte perguntas em linguagem natural para operações Pandas usando LLM
- Executa código gerado em ambiente restrito
- Usa validação por AST, namespace isolado e limite de execução para reduzir riscos

Foco: execução segura de código gerado por LLM e acessibilidade de dados.

`FastAPI` `Pandas` `Groq API` `LLaMA 3.3 70B` `python-dotenv`

---

### [Ranker](https://github.com/rafaelsodrepsc/Ranker) · Java

Sistema de gerenciamento de campeonatos com suporte a múltiplos formatos.

- Round Robin com espelhamento e tratamento de quantidade ímpar de times
- Eliminatória simples com validação de potência de 2
- Agendamento de partidas por locais e datas
- Tabela de classificação com critérios de desempate
- Branch opcional com interface desktop em JavaFX

Foco: algoritmos, modelagem orientada a objetos e consistência de dados.

`Java 21` `OOP` `Streams & Lambdas` `Custom Exceptions` `Scheduling Algorithm` `JavaFX`

---

## Foco atual

- Projetar sistemas backend escaláveis
- Construir APIs seguras e confiáveis
- Aplicar IA e LLMs em problemas reais de backend
- Melhorar design de sistemas, performance e observabilidade
- Trabalhar com workflows de desenvolvimento assistido por IA (Claude Code, agentes de code review)

---

## Stack

**Backend:** Java, Spring Boot, Python, FastAPI, Flask
**Frontend:** Angular
**Bancos de dados:** PostgreSQL (+ pgvector), MySQL
**Mensageria e Cache:** Kafka, Redis
**IA e Dados:** LLM APIs, RAG, Prompt Engineering, Pandas
**Infraestrutura:** Docker, Docker Compose, AWS EC2, AWS S3
**Segurança:** OAuth2, JWT

---

## Contato

[rafaelsodrepaschoal@gmail.com](mailto:rafaelsodrepaschoal@gmail.com) · [linkedin.com/in/rafaelsodrepsc](https://linkedin.com/in/rafaelsodrepsc)