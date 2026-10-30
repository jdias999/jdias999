<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0078D4,100:FF3621&height=200&section=header&text=João%20Dias&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38" alt="Header Banner" />
</p>

<p align="center">
  <b>Data Engineering | Python | PySpark | SQL | Azure | Databricks</b><br>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/joaovpdias/">
    <img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
 
---

## Sobre mim

Sou estudante de **Análise e Desenvolvimento de Sistemas** com foco em **Engenharia de Dados**.

Minha base vem do desenvolvimento de software, e hoje direciono meus estudos e projetos para arquitetar todo o ciclo de vida do dado: desde a ingestão de dados de api e bancos relacionais, passando por processamento distribuído, controle de qualidade e cargas incrementais, até a modelagem dimensional em arquitetura Lakehouse.

---

## Foco técnico e conceitos que aplico

- **Processamento e Transformação:** Python, SQL, PySpark e Pandas;
- **Arquitetura Lakehouse & Medallion:** Construção das camadas Landing, Bronze, Silver e Gold com **Delta Lake** e governança no **Unity Catalog**;
- **Cargas Incrementais:** Ingestão incremental com **Databricks Auto Loader**, controle de **Watermark**, evolução de schema (*Schema Evolution*) e garantia de idempotência com `MERGE INTO` (Upsert);
- **Cloud & Orquestração:** **Azure Data Factory (ADF)**, **Azure Data Lake Storage Gen2 (ADLS Gen2)**, configuração de permissões (IAM / Access Connector) e **Apache Airflow**;
- **Modelagem e Qualidade de Dados:** Modelagem Dimensional (Star / Galaxy Schema), validação de séries temporais, deduplicação com *Window Functions* e Data Quality;
- **Bancos de Dados & Infra Local:** PostgreSQL, DuckDB, Docker e Docker Compose.

---

## Tech Stack

### Linguagens, Bancos e Infra

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,postgres,docker,git,github&theme=dark" alt="Python, PostgreSQL, SQL, Git e GitHub" />
</p>

### Data Engineering & Lakehouse

<p align="center">
  <img src="https://img.shields.io/badge/Apache_Spark-FFFFFF?style=for-the-badge&logo=apachespark&logoColor=%23E35A16" alt="Apache Spark" />
  <img src="https://img.shields.io/badge/PySpark-E35A16?style=for-the-badge&logo=apachespark&logoColor=white" alt="PySpark" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks" />
  <img src="https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge&logo=deltalake&logoColor=white" alt="Delta Lake" />
  <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Apache Airflow" />
    <img src="https://skillicons.dev/icons?i=azure,powerbi&theme=dark" alt="Azure e Power BI" />
</p>

---

## Projetos em Destaque

### [Data Center Infrastructure, Energy & Environmental Impact — Lakehouse](https://github.com/jdias999/https://github.com/jdias999/datacenter-energy-lakehouse)

Pipeline de Engenharia de Dados ponta a ponta na nuvem (**Microsoft Azure**) construído para analisar a relação entre a infraestrutura global de Data Centers, a demanda por eletricidade, a intensidade de carbono da matriz energética e indicadores socioeconômicos dos países.

- **Extração & Ingestão Incremental:** Consumo de 3 APIs REST (*Datacenters.world, Ember Energy e World Bank*) com paginação, controle de **Watermark** dinâmico e ingestão incremental na camada Bronze via **Databricks Auto Loader**.
- **Tratamento & Qualidade (Silver):** Padronização em **PySpark**, validação de lacunas em séries históricas, deduplicação com `ROW_NUMBER()` e atualização idempotente com `MERGE INTO`.
- **Modelagem & Orquestração (Gold & Cloud):** Modelagem dimensional em **Spark SQL** (Fatos, Dimensões e Views analíticas), governança de dados e permissões com **Unity Catalog + ADLS Gen2**, orquestração paralela no **Azure Data Factory** e visualização de insights com **Seaborn**.

---

### [SAC ANAC — Pipeline ETL & Análise](https://github.com/jdias999/aviation-complaints-analytics-pipeline)

Pipeline de dados construído a partir de dados públicos da ANAC e do SAC.

O projeto envolve ingestão, limpeza, transformação e análise de mais de 100 mil registros utilizando **Python, Pandas, SQL e DuckDB**, transformando dados brutos em indicadores estruturados para avaliação de reclamações e atendimento no setor aéreo.

---

### [Data Engineering Lab](https://github.com/jdias999/data_engineer_lab)

Repositório onde concentro estudos práticos, laboratórios e implementações voltadas para Engenharia de Dados.

Reúne scripts e experimentos com **SQL, Python, consumo de APIs, PySpark, Databricks, Docker e modelagem de dados**.

---
