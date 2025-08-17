# Análise de Churn de Clientes (Teleco)

Este repositório contém uma análise exploratória de dados (EDA) focada no comportamento de clientes de uma empresa de telecomunicações, com o objetivo de identificar os principais fatores que levam ao abandono do serviço (`Churn`).

---

## Propósito do Projeto

O objetivo principal desta análise é entender a relação entre as características dos clientes (como tempo de permanência, gastos mensais e serviços contratados) e a probabilidade de `Churn`. O estudo visa fornecer insights valiosos para a equipe de negócios, permitindo a criação de estratégias mais eficazes de retenção de clientes.

---

## Análise e Insights

A análise, realizada em um notebook Jupyter, revelou os seguintes pontos principais:

* **Relação entre `Tenure` e `Churn`**: O tempo de permanência (`Tenure`) é um dos preditores mais fortes de abandono. A taxa de `Churn` é significativamente mais alta entre os clientes novos (com baixo `tenure`) e diminui drasticamente à medida que o tempo de permanência aumenta.
* **Impacto de `MonthlyCharges`**: A média de gastos mensais dos clientes que cancelam é superior àqueles que permanecem, indicando que a empresa está perdendo clientes de alto valor.
* **Análise Financeira**: Uma projeção com uma redução de 25% na taxa de `Churn` demonstra um potencial substancial de receita salva, ressaltando o valor financeiro direto da retenção de clientes.
* **Correlações entre Variáveis**: Foi identificada uma forte correlação entre as variáveis `tenure` e `TotalCharges`, o que faz sentido, já que o valor total pago se acumula ao longo do tempo.

---

## Estrutura do Repositório

O repositório contém o arquivo `A3_Data.ipynb`, que inclui:

* Limpeza e pré-processamento de dados.
* Análise de correlação entre as variáveis numéricas.
* Visualizações gráficas para explorar a distribuição de `tenure` por `churn`.
* Cálculo e visualização do impacto financeiro do `churn`.

---

## Tecnologias Utilizadas

* **Python**: Linguagem de programação.
* **Pandas**: Para manipulação e análise de dados.
* **NumPy**: Para operações numéricas.
* **Matplotlib** e **Seaborn**: Para visualização de dados.
* **Jupyter**: Ambiente de desenvolvimento interativo.
