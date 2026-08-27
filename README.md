# 📊 Estudo de Dados Demográficos

Grupo: Ana e Anderson (Tema: Demografia)


Miniprojeto desenvolvido na disciplina de **Arquitetura e Processamento de Dados**, com foco na análise do **envelhecimento da população brasileira** e suas possíveis relações com a população em idade potencialmente ativa e a Previdência Social.

## 🎯 Objetivo

Analisar a evolução da estrutura etária da população brasileira, identificando tendências de envelhecimento populacional e discutindo os desafios que essa transformação pode representar para as próximas gerações.

## 🔎 Questões de análise

O projeto busca responder principalmente:

- Como a estrutura etária da população brasileira está mudando?
- Como evoluem indicadores como fecundidade, longevidade e envelhecimento?
- Como está mudando a relação entre idosos e população em idade potencialmente ativa?
- Qual é o perfil etário dos contribuintes da Previdência Social?
- Quais reflexões essas mudanças trazem para o planejamento das novas gerações?

## 🗂️ Fontes de dados

Serão utilizadas bases públicas e oficiais:

- **IBGE — Projeções da População 2000–2070**
- **Ministério da Previdência Social — AEPS 2024**

## 🏗️ Arquitetura dos dados

O processamento será estruturado utilizando os conceitos da **Arquitetura Medalhão**:

**🥉 Bronze → 🥈 Silver → 🥇 Gold**

- **Bronze:** preservação dos dados provenientes das fontes originais;
- **Silver:** limpeza, padronização e tratamento dos dados;
- **Gold:** dados preparados e organizados para análise, indicadores e visualizações.

## 🛠️ Tecnologias

- Python
- Pandas
- Jupyter Notebook
- Git / GitHub

## 📁 Estrutura inicial

    Demografia_Previdencia/
    ├── dados/
    │   ├── projecoes_2024_tab3_grupos_etarios_especificos.xlsx
    │   ├── projecoes_2024_tab4_indicadores.xlsx
    │   └── Número_Contribuintes_2022_2024_24C32_03.xlsx
    │
    └── demografia_previdencia.ipynb

> O projeto está em desenvolvimento e será atualizado conforme a evolução das etapas de processamento e análise dos dados.
