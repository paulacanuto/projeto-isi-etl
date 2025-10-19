# projeto-isi-etl
Trabalho de Integração de Sistemas de Informação - ETL com Pentaho Data Integration (Kettle)
# 🎬 Projeto ETL com Pentaho e Power BI - TMDB API

## 📘 Descrição
Este projeto foi desenvolvido como parte da disciplina **Integração de Sistemas de Informação (ISI)**, com o objetivo de demonstrar um processo completo de **ETL (Extração, Transformação e Carga)** utilizando o **Pentaho Data Integration (PDI)** e análise visual no **Power BI**.

---

## 🛠️ Tecnologias Utilizadas
- **Pentaho Data Integration (PDI)** — versão 10.2.0.0-222  
- **SQLite** — banco local para armazenamento dos dados transformados  
- **API TMDB** — extração de dados reais de filmes  
- **Power BI** — criação de dashboards e relatórios visuais  
- **GitHub** — versionamento e entrega do projeto  

---
---

## ⚙️ Processo ETL

1. **Extração** — Consumo da API TMDB via REST Client no Pentaho  
2. **Transformação** — Tratamento com JavaScript Values e Filtros:
   - Normalização de datas
   - Remoção de registros inválidos
   - Criação de campos derivados
3. **Carga (Load)** — Armazenamento:
   - Dados válidos → SQLite / CSV
   - Dados excluídos → CSV separado
   - Dados originais → JSON backup

---

## 📈 Dashboard Power BI

O Power BI consome os dados transformados e apresenta:

- Tabela interativa com filmes, idiomas e descrição  
- Gráfico de barras: **Popularidade por Filme**  
- Gráfico de pizza: **Distribuição percentual de popularidade**

![Dashboard Power BI](https://github.com/paulacanuto/projeto-isi-etl/blob/main/Trabalho/PowerBI/dashboard_export.png)

---

## 🧩 Adicionar futuramento ao Pentaho: Resumo Automático

Para o Pentaho também gerar um arquivo resumo_final.csv com a contagem de:
- Filmes extraídos
- Filmes transformados
- Filmes excluídos  

---
## 💻 Trabalhos futuros:

- Expandir para múltiplos endpoints (gêneros, trending, atores);

- Implementar predições de popularidade com Machine Learning;

- Migrar o armazenamento para um banco de dados em nuvem;

- Deixar o dashboard em Power BI mais interativo.

---
## 👩‍💻 Autor(a)
**Ana Paula Canuto da Silva**  
Curso: Licenciatura em Engenharia de Sistemas Informáticos  
Disciplina: Integração de Sistemas de Informação  
Prof(a).: Luís Ferreira & Óscar Ribeiro 

---

## 📅 Data
Outubro de 2025

