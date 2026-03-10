# Telecom Churn Prediction

Projeto de Ciência de Dados focado na previsão de evasão de clientes em uma empresa de telecomunicações.

## Objetivo

Desenvolver modelos de Machine Learning capazes de identificar clientes com maior probabilidade de cancelar seus serviços, permitindo ações estratégicas de retenção.

## Dataset

O dataset contém informações sobre:

- perfil dos clientes
- serviços contratados
- tipo de contrato
- forma de pagamento
- histórico de gastos
- tempo de relacionamento com a empresa

Total de registros: 7032

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

## Etapas do Projeto

1. Limpeza e preparação dos dados
2. Análise exploratória (EDA)
3. Engenharia de atributos
4. Divisão treino/teste
5. Treinamento de modelos
6. Avaliação de desempenho
7. Identificação de fatores de churn

## Modelos Utilizados

- Regressão Logística
- Random Forest

## Resultados

A Regressão Logística apresentou melhor desempenho geral:

Acurácia: 80%

Principais fatores de churn:

- contratos mensais
- baixo tempo de cliente
- ausência de serviços adicionais
- gasto mensal elevado

## Possíveis Melhorias

- aplicação de SMOTE
- otimização de hiperparâmetros
- teste com XGBoost ou LightGBM
- feature engineering adicional
