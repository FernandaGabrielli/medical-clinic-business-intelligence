# Clínica Médica — Análise de Dados, ETL e Dashboard

## Sobre o Projeto

Projeto desenvolvido para a disciplina de Ciência de Dados.

O objetivo foi realizar o processo de ETL (Extração, Transformação e Carga) em uma base de dados de uma clínica médica e construir um dashboard gerencial para apoiar a tomada de decisões.

## Perguntas de Negócio

- Qual faixa etária concentra mais atendimentos?
- Qual convênio gera mais receita para a clínica?

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Google Colab
- Looker Studio
- Google Sheets

## Processo ETL

### Extração
- Leitura do arquivo CSV
- Inspeção inicial dos dados

### Transformação
- Tratamento de valores nulos
- Remoção de duplicatas
- Padronização de categorias
- Conversão de tipos de dados
- Criação de colunas calculadas

### Carga
- Exportação do dataset limpo
- Integração com Google Sheets
- Construção do dashboard no Looker Studio

## Colunas Calculadas

- faixa_etaria
- mes_atendimento
- categoria_duracao

## Dashboard

O dashboard apresenta:

- Total de atendimentos
- Receita total
- Ticket médio
- Taxa de retorno
- Atendimentos por faixa etária
- Receita por convênio
- Atendimentos por especialidade
- Evolução mensal dos atendimentos

## Estrutura do Projeto

```text
 ├── Notebook_ETL.ipynb

📁 data
 ├── grupo2_clinica.csv
 └── dataset_limpo.csv

📁 docs
 └── Etapa1_Exploracao.pdf

README.md
```
