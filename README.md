# 🏥 Pipeline ETL de Internações Hospitalares do SUS

Este projeto coleta, transforma e armazena dados públicos de internações hospitalares do SUS. Automatizamos o processo com Apache Airflow e armazenamos os dados em um banco PostgreSQL. Ao final, visualizamos os principais insights sobre os municípios com maior número de internações.

## Tecnologias
- Python, Pandas
- PostgreSQL
- Apache Airflow
- Docker
- Jupyter / Dash

## Como executar
1. Clone o repositório
2. Execute `docker-compose up`
3. Acesse o Airflow em `localhost:8080`
4. Acesse o banco PostgreSQL em `localhost:5432`
