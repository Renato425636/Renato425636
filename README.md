# Renato Assis Schiavon Parente

**Engenheiro de Dados & Plataforma** — GCP · AWS · 5+ anos

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)

Construo a camada entre o dado bruto e quem o consome: frameworks de segurança, serviços de acesso, qualidade de dados e orquestração em escala.

**→ [Portfólio completo](https://renato4256.github.io)** — arquitetura, decisões e trade-offs de cada projeto, folha por folha.

---

## Experiência

Atualmente **Engenheiro de Dados II** na Nio (GCP), onde projeto frameworks de segurança e governança de dados, serviços de acesso e pipelines de orquestração em escala. Antes disso, mais de 3 anos no Itaú Unibanco (AWS), passando por Analytics Engineering no maior app bancário da América Latina e modernização de pipelines legados para arquitetura serverless. 5+ anos de experiência ponta a ponta: arquitetura, ingestão, modelagem analítica e disponibilização de dados para BI e Data Science.

---

## Projetos Profissionais

Frameworks e serviços que espelham padrões usados em produção — segurança, qualidade e acesso a dados.

| Projeto | Descrição | Stack principal | Repositório | Documentação |
| :--- | :--- | :--- | :--- | :--- |
| **data-quality-checks** | Framework cross-source de qualidade de dados: três engines (BQ nativa, Soda Core, Flashback Oracle) sob uma interface YAML, resultado auditado no BigQuery | Python · PySpark · BigQuery · Oracle · Soda Core · Airflow | [Repositório](https://github.com/Renato425636/data-quality-checks) | [Docs](https://renato425636.github.io/data-quality-checks/) |
| **pipeline-observability** | Ciclo declarativo validate → plan → apply para recursos GCP de observabilidade; YAML como fonte de verdade, apply idempotente com audit trail | Python · Cloud Monitoring · Cloud Logging · JSON Schema · GitHub Actions | [Repositório](https://github.com/Renato425636/pipeline-observability) | [Docs](https://renato425636.github.io/pipeline-observability/) |
| **data-protection-toolkit** | Toolkit de inspeção de PII, mascaramento e classificação de dados sensíveis em GCP e GCS, exposto como microsserviço via FastAPI | Python · FastAPI · Cloud DLP · GCS · BigQuery | [Repositório](https://github.com/Renato425636/data-protection-toolkit) | [Docs](https://renato425636.github.io/data-protection-toolkit/) |
| **datalake-access-layer** | API de concessão e revogação de acesso ao datalake com núcleo de decisão versionado; separação entre decisão e aplicação, prazo por padrão | Python · FastAPI · GCP IAM · BigQuery | [Repositório](https://github.com/Renato425636/datalake-access-layer) | [Docs](https://renato425636.github.io/datalake-access-layer/) |

---

## Estudos & Exploração

Provas de conceito e exercícios de tuning para validar técnica antes de levar a produção.

| Projeto | Descrição | Stack principal | Repositório | Documentação |
| :--- | :--- | :--- | :--- | :--- |
| **etl_dados_olist_optmization** | Tuning de pipeline: efeito de broadcast join e cache no plano de execução e no custo de um ETL pesado | PySpark · Python | [Repositório](https://github.com/Renato425636/etl_dados_olist_optmization) | — |
| **etl_dados_olist** | Modelagem dimensional: ETL de dados transacionais brutos para star schema pronto para consumo analítico | PySpark · SQL · Python | [Repositório](https://github.com/Renato425636/etl_dados_olist) | [Docs](https://renato425636.github.io/etl_dados_olist/) |
| **user_sessions** | Sessões de usuário com window functions: agrupamento de logs em sessões com tratamento de intervalo ocioso e evento fora de ordem | PySpark · Python | [Repositório](https://github.com/Renato425636/user_sessions) | [Docs](https://renato425636.github.io/user_sessions/) |
| **etl_pyspark_countries** | Normalização de JSON aninhado: ingestão de payloads semiestruturados de API com achatamento em tabelas consultáveis e esquema explícito | PySpark · Python | [Repositório](https://github.com/Renato425636/etl_pyspark_countries) | [Docs](https://renato425636.github.io/etl_pyspark_countries/) |

---

## Contato

- Portfólio: [renato4256.github.io](https://renato4256.github.io)
- LinkedIn: [renato-assis-schiavon-parente](https://www.linkedin.com/in/renato-assis-schiavon-parente-a323011b3/)
- GitHub: [@Renato425636](https://github.com/Renato425636)
- E-mail: renatoassisparente@gmail.com
