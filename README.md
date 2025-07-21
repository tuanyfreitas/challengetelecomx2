# Previsão de Evasão de Clientes - Telecom X

Este repositório contém a solução da Parte 2 do desafio Telecom X, que tem como objetivo construir um pipeline de **Machine Learning** para prever a **evasão de clientes (churn)** com base em dados comportamentais e contratuais.

---

##  Objetivo do Projeto

Desenvolver modelos preditivos capazes de identificar clientes com maior probabilidade de cancelarem seus serviços, auxiliando a empresa a tomar decisões estratégicas de retenção.

---

##  Habilidades Aplicadas

- Pré-processamento de dados
- Codificação de variáveis categóricas
- Análise de desbalanceamento de classes
- Normalização e transformação
- Criação e avaliação de modelos preditivos
- Interpretação de variáveis importantes
- Comunicação técnica com foco estratégico

---

##  Estrutura do Projeto


---

##  Tecnologias Utilizadas

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

##  Pipeline Desenvolvido

1. **Carregamento dos dados tratados** da Parte 1
2. **Codificação** das variáveis categóricas com `get_dummies`
3. **Análise de desbalanceamento de classes**
4. **Aplicação de SMOTE** para balancear os dados de treino
5. **Normalização dos dados** para modelos baseados em distância
6. **Análise de correlação** com a variável-alvo (`Churn`)
7. **Treinamento de dois modelos:**
   - Regressão Logística (com dados normalizados)
   - Random Forest (sem normalização)
8. **Avaliação com métricas:**
   - Acurácia, Precisão, Recall, F1-score
   - Matriz de confusão
9. **Visualização da importância das variáveis**
10. **Conclusão estratégica com recomendações de retenção**

---

##  Principais Resultados

- A **Random Forest** apresentou melhor desempenho geral.
- As variáveis mais importantes foram:
  - Tipo de contrato (`Contract`)
  - Valor mensal (`MonthlyCharges`)
  - Tempo de permanência (`Tenure`)
  - Serviços como `TechSupport` e `OnlineSecurity`
- Clientes com contratos mensais e cobrança elevada nos primeiros meses têm maior risco de evasão.


---

 Desafio fictício baseado em projeto educacional da plataforma Alura - *Desenvolvido para fins de aprendizagem*.
