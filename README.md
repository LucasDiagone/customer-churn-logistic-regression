# 📊 Previsão de Churn com Regressão Logística

Projeto de **Machine Learning** para previsão de **cancelamento de clientes (churn)** utilizando **Regressão Logística** e o dataset **Telco Customer Churn**.

O objetivo é identificar **quais clientes possuem maior probabilidade de cancelar o serviço**, permitindo que empresas criem **estratégias de retenção mais eficazes**.

---

# 🎯 Objetivo do Projeto

Desenvolver um modelo de classificação capaz de prever **churn de clientes** com base em características como:

- tempo de relacionamento com a empresa
- tipo de contrato
- tipo de internet
- valor da mensalidade
- método de pagamento
- suporte técnico

A partir dessas variáveis, o modelo estima a **probabilidade de cancelamento** para cada cliente.

---

# 📂 Dataset

Dataset utilizado:

**Telco Customer Churn**

Disponível em:

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

O dataset contém informações de **clientes de uma empresa de telecomunicações**, incluindo dados demográficos, serviços contratados e histórico de pagamentos.

---

# 📊 Principais Variáveis

| Variável | Descrição |
|--------|--------|
| `tenure` | Tempo (em meses) que o cliente permanece na empresa |
| `MonthlyCharges` | Valor da mensalidade |
| `Contract` | Tipo de contrato |
| `InternetService` | Tipo de serviço de internet |
| `TechSupport` | Indica se o cliente possui suporte técnico |
| `PaymentMethod` | Método de pagamento |
| `SeniorCitizen` | Indica se o cliente é idoso |
| `Churn` | Variável alvo (cancelou ou não) |

---

# 🧠 Metodologia

O projeto segue um fluxo padrão de **Machine Learning supervisionado**.

## Etapas do Projeto

1️⃣ Imports das bibliotecas  
2️⃣ Carregamento do dataset  
3️⃣ Limpeza e preparação dos dados  
4️⃣ Conversão da variável alvo  
5️⃣ Análise exploratória dos dados (EDA)  
6️⃣ Análise das variáveis categóricas  
7️⃣ Seleção das variáveis mais relevantes  
8️⃣ Criação das variáveis do modelo  
9️⃣ Divisão treino / teste  
🔟 Treinamento do modelo de Regressão Logística  
1️⃣1️⃣ Avaliação do modelo  
1️⃣2️⃣ Matriz de confusão  
1️⃣3️⃣ Curva ROC  
1️⃣4️⃣ Teste de previsão para novos clientes  

---

# 🤖 Modelo Utilizado

O modelo utilizado foi **Regressão Logística**, um algoritmo amplamente utilizado em problemas de **classificação binária**.

A regressão logística estima a **probabilidade de um cliente cancelar ou não o serviço**, com base nas variáveis explicativas.

Biblioteca utilizada:
**scikit-learn**

---

# 📊 Avaliação do Modelo

O desempenho do modelo foi avaliado utilizando:

- **Accuracy**
- **Classification Report**
- **Matriz de Confusão**
- **Curva ROC**
- **AUC (Area Under the Curve)**

Resultado obtido:
**AUC ≈ 0.82**

Esse valor indica que o modelo possui **boa capacidade de distinguir clientes que cancelam daqueles que permanecem**.

---

# 📉 Principais Insights

A análise exploratória e o modelo indicam alguns padrões importantes:

- Clientes com **contrato mensal** apresentam maior taxa de churn.
- Clientes com **internet fibra óptica** apresentam maior probabilidade de cancelamento.
- Clientes com **baixo tempo de relacionamento (tenure)** tendem a cancelar mais.
- Clientes com **suporte técnico ativo** apresentam menor probabilidade de churn.
- **Contratos de longo prazo** estão associados a maior retenção.

---

# 🔮 Simulação de Previsão

O projeto também inclui **simulação de previsão para novos clientes**, estimando a probabilidade de churn com base em suas características.

Exemplo:
**Previsão de churn: 1
Probabilidade de churn: 0.63**

Isso indica que o cliente possui **63% de probabilidade de cancelar o serviço**.

---

# 🛠 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📁 Estrutura do Projeto
churn-logistic-regression
│
├── data
│ └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebook
│ └── churn_projeto_regressao_logistica.ipynb
│
└── README.md

---

# 📌 Conclusão

O modelo desenvolvido demonstra que **variáveis relacionadas ao tipo de contrato, tempo de relacionamento e serviços contratados** possuem forte influência no cancelamento de clientes.

Essas informações podem ser utilizadas para:

- identificar clientes com maior risco de churn
- criar estratégias de retenção
- melhorar programas de fidelização

---

# 👨‍💻 Autor

**Lucas**

Estudante de **Data Science** com foco em **Machine Learning, Estatística e Análise de Dados**.
🔗 LinkedIn:  
https://www.linkedin.com/in/lucas-diagone-691285104/
