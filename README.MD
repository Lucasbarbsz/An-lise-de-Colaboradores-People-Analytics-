# Análise de Turnover e Produtividade de Colaboradores

Este projeto apresenta uma análise exploratória de dados focada em indicadores de turnover, perfil de colaboradores e métricas de retenção, utilizando um conjunto de dados de RH (HR Analytics) para identificar padrões relevantes e apoiar decisões de pessoas.

## Objetivo

- Avaliar a rotatividade de colaboradores por departamento, tempo de empresa e faixa salarial.
- Identificar os principais fatores relacionados à saída de funcionários.
- Fornecer insights acionáveis para áreas de RH e gestão de pessoas.

## Escopo do projeto

A análise inclui:

- Visão geral do dataset: tamanho, tipos de variáveis e presença de valores faltantes.
- Limpeza básica dos dados e tratamento de valores nulos.
- Distribuição de colaboradores por departamento e faixa etária.
- Cálculo das taxas de turnover por departamento.
- Análise de turnover por tempo de empresa (`YearsAtCompany`).
- Avaliação de turnover por faixa salarial (`MonthlyIncome`).

## Fonte dos dados

O conjunto de dados utilizado é o `HR_Analytics.csv`, originado de um dataset público de RH disponível no Kaggle. O notebook faz download automático usando `kagglehub` para obter a versão mais recente do dataset.

## Estrutura do repositório

- `README.MD` - documentação do projeto.
- `notebooks/analise_exploratoria.ipynb` - notebook principal com toda a análise, visualizações e comentários.

## Tecnologias e bibliotecas

- Python
- Pandas
- Matplotlib
- KaggleHub (para download do dataset)

## Como executar

1. Abra o notebook `notebooks/analise_exploratoria.ipynb` no Jupyter ou VS Code.
2. Garanta que as bibliotecas necessárias estejam instaladas:

```bash
pip install pandas matplotlib kagglehub
```

3. Execute as células na ordem apresentada.

## Principais análises realizadas

- Distribuição de colaboradores por departamento e faixa etária.
- Cálculo de turnover em porcentagem por departamento.
- Análise de turnover por tempo de empresa, mostrando os anos com maior taxa de saída.
- Avaliação de turnover por faixas de renda para identificar se há correlação entre salário e saída.

## Insights esperados

- Determinar se o turnover é mais concentrado nos primeiros anos de empresa ou em anos intermediários.
- Detectar departamentos com maior risco de rotatividade.
- Entender se faixas salariais específicas apresentam maior taxa de saída.
- Apoiar recomendações de ações de retenção, como melhora do onboarding, desenvolvimento de carreira e políticas salariais.

## Próximos passos recomendados

- Cruzar o turnover com indicadores de satisfação no trabalho (`JobSatisfaction`) e avaliação de performance.
- Analisar o impacto de promoções e tempo na função (`YearsSinceLastPromotion`, `YearsInCurrentRole`).
- Construir um modelo simples de classificação para prever turnover e priorizar variáveis explicativas.

## Observações finais

O notebook contém a análise detalhada e as visualizações necessárias para comunicar os resultados.
