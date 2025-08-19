# TelecomX – Projeto Final Oracle Next One + Alura

## Descrição do Projeto

Este projeto consiste em uma análise preditiva de **evasão de clientes (churn)** da empresa **TelecomX**, utilizando técnicas de Machine Learning para identificar quais clientes têm maior risco de cancelar serviços.  

O objetivo é **fornecer insights estratégicos** que permitam à empresa criar ações de retenção direcionadas e reduzir a perda de clientes.  

O projeto foi desenvolvido como **challenge final** do programa **Oracle Next One + Alura**, integrando conceitos de ciência de dados, pré-processamento de dados, balanceamento de classes, modelagem e análise de variáveis importantes.

---

## Tecnologias e Bibliotecas

O projeto foi desenvolvido em **Python** e utiliza as seguintes bibliotecas:

- `pandas` e `numpy` – manipulação e análise de dados  
- `seaborn` e `matplotlib` – visualização de dados  
- `scikit-learn` – machine learning, pré-processamento e métricas  
- `imbalanced-learn` – técnicas de oversampling (SMOTE) para lidar com desequilíbrio de classes  

---

## Estrutura do Projeto

---

## Objetivos

1. Limpar e preparar os dados para análise.  
2. Balancear o dataset utilizando SMOTE.  
3. Treinar modelos de machine learning para prever churn:  
   - **Regressão Logística**  
   - **Random Forest**  
4. Avaliar desempenho dos modelos com métricas: acurácia, precisão, recall e F1-score.  
5. Identificar **as variáveis mais relevantes** que influenciam a evasão de clientes.  
6. Propor **estratégias de retenção** com base nos resultados.

---

## Resultados dos Modelos

| Modelo                 | Acurácia | Precisão | Recall | F1 Score |
|------------------------|----------|----------|--------|----------|
| Regressão Logística    | 0.757    | 0.53     | 0.745  | 0.62     |
| Random Forest          | 0.779    | 0.596    | 0.526  | 0.559    |

- A Regressão Logística é melhor para identificar clientes em risco de churn (maior recall).  
- O Random Forest apresenta maior precisão e acurácia, sendo mais confiável para prever clientes que permanecem.

---

## Principais Variáveis de Influência

As variáveis mais importantes para prever churn foram:

- `Faturamento_Total`  
- `Meses_Cliente`  
- `Servico_Internet`  
- `TV_Streaming`  
- `Metodo_de_Pagamento`  
- `Servico_Celular`  
- `Backup_Online`  
- `Faturamento_Mensal`  
- `Linhas_Adicionais`  
- `Filmes_Streaming`  
