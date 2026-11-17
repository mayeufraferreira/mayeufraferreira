# Olá, eu sou a Mayara Karoline! 👋
### Engenheira de Software Full Stack & Backend Pleno
**Java (8, 17, 21) • Spring Boot • Angular • Apache Kafka • Arquitetura de Microsserviços**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayara-karoline)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mayeufraferreira@gmail.com)

---

### ⚡ Sobre Mim


- 🏗️ **Foco em Engenharia & Arquitetura:** Microsserviços orientados a eventos (**Apache Kafka**), **APIs RESTful (API First / OpenAPI)**, **Clean Code, SOLID** e alta disponibilidade.
- 🏆 **Destaque Recente:** **1º Lugar no Hack Garanhuns Tech 2026** com o desenvolvimento da plataforma RiskTech **Radar Jus** (análise preditiva de risco trabalhista e solvência corporativa/bancária).
- 🔬 **Pesquisa Aplicada (UFAPE):** Bacharelanda em Ciência da Computação, pesquisando Visão Computacional e Deep Learning (**YOLOv8 / TensorFlow Lite**) embarcados em dispositivos de borda (Edge Computing) e Engenharia de Dados Geoespaciais (**PostgreSQL / PostGIS**).

---

### 🛠️ Stack Tecnológica & Ferramentas

| Domínio | Tecnologias & Ferramentas |
| :--- | :--- |
| **Backend & Arquitetura** | ![Java](https://img.shields.io/badge/Java_8_%2F_17_%2F_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Spring](https://img.shields.io/badge/Spring_Framework-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Hibernate](https://img.shields.io/badge/JPA_%2F_Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) |
| **Mensageria & Integração** | ![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white) ![Swagger](https://img.shields.io/badge/OpenAPI_%2F_Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black) ![REST](https://img.shields.io/badge/RESTful_APIs-02569B?style=flat-square) |
| **Frontend Web** | ![Angular](https://img.shields.io/badge/Angular_12+-DD0031?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Bancos de Dados** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL_%26_PostGIS-316192?style=flat-square&logo=postgresql&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle_%2F_PLSQL-F80000?style=flat-square&logo=oracle&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white) |
| **DevOps, QA & Observabilidade** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Pytest](https://img.shields.io/badge/JUnit_%26_Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) |

---

### 🚀 Projetos em Destaque (Arquitetura & Engenharia)

#### 🏆 1. [Radar Jus — Plataforma Preditiva RiskTech (1º Lugar Hack Garanhuns Tech 2026)](https://github.com/mayeufraferreira)
> **Problema resolvido:** Avaliação automatizada de risco de responsabilidade subsidiária trabalhista (Súmula 331 TST) e solvência financeira de empresas e grandes instituições bancárias.
- **Arquitetura & Engenharia:** Processamento assíncrono em duas camadas (*Fast-Scan* e *Deep-Scan* em background via `ThreadPoolExecutor`), consolidação de capital social multi-filiais por CNPJ e motor de inferência probabilística Bayesiana.
- **Integrações:** Consumo resiliente das APIs públicas **DataJud (CNJ)**, **Comunica PJe**, **TST** e **BrasilAPI**.
- **Stack:** `Python` • `Flask` • `SQLAlchemy` • `Pytest` • `REST APIs`

#### 🎓 2. [CertifAI — Plataforma EdTech de Treinamento, Cursos e Preparação](https://github.com/mayeufraferreira)
> **Problema resolvido:** Plataforma completa de ensino e preparação de alto desempenho (modelo EdTech / preparatório para provas e certificações), estruturando trilhas de aprendizagem, gestão de cursos, resolução de questões e acompanhamento de desempenho do aluno.
- **Backend (`certifai-backend`):** API RESTful com arquitetura em camadas, modelagem relacional de domínio educacional (cursos, módulos, matrículas e progresso), tratamento global de exceções (RFC 7807), documentação **OpenAPI/Swagger** e testes automatizados.
- **Frontend (`certifai-frontend`):** SPA modularizada com experiência fluida de estudo, gerenciamento explícito de *loading/error states*, interceptadores HTTP, HTML5 semântico e servidor de produção **Nginx** conteinerizado.
- **DevOps:** Pipeline completo de **CI/CD com GitHub Actions** e orquestração multi-container via **Docker Compose**[cite: 1].

#### 📊 3. Engenharia de Dados & Análise Epidemiológica (Pesquisa UFAPE)
> **Problema resolvido:** Criação de indicadores socioeconômicos normalizados (escala 0 a 1) por setor censitário para otimizar a alocação de serviços públicos de saúde.
- **Engenharia de Dados (ETL):** Extração, saneamento e normalização de grandes volumes de dados brutos do IBGE utilizando `Python (Pandas, Matplotlib)` e consultas espaciais em `PostgreSQL / PostGIS`.
