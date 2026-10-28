# Dashboard de Salários na Área de Dados

Dashboard interativo para explorar a evolução dos salários na área de dados: filtros por ano, senioridade, tipo de contrato e tamanho da empresa, com indicadores e gráficos atualizados em tempo real.

**Demo online:** https://dashboard-salario-na-area-de-dados-2025.streamlit.app/

# Demonstração

![Demonstração do dashboard](demo/dashboard.gif)

## Funcionalidades

- Filtros por ano, senioridade, tipo de contrato e tamanho da empresa
- Indicadores de salário médio, salário máximo, total de registros e cargo mais frequente
- Ranking dos 10 cargos com maior salário médio
- Distribuição dos salários anuais
- Proporção entre trabalho presencial, remoto e híbrido
- Mapa com o salário médio de cientistas de dados por país
- Tabela com os dados filtrados

## Tecnologias

- Python
- Streamlit
- Pandas
- Plotly

## Estrutura do projeto

```
app.py                  # Aplicação Streamlit
base_de_dados.ipynb     # Análise exploratória da base
requirements.txt        # Dependências
demo/dashboard.gif      # Demonstração
```

## Como executar

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

## Fonte dos dados

A aplicação consome uma base pública de salários da área de dados publicada no repositório [vqrca/dashboard_salarios_dados](https://github.com/vqrca/dashboard_salarios_dados).

---

Autor: Gilvam Oliveira · [LinkedIn](https://www.linkedin.com/in/gilvam-oliveira/)
