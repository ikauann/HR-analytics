# HR Analytics: Explorando a Rotatividade de Funcionários

Este projeto explora os fatores que contribuem para a **rotatividade de funcionários** em uma empresa, usando um conjunto de dados público de [Kaggle](https://www.kaggle.com/datasets/anshika2301/hr-analytics-dataset).

## 🎯 **Objetivo do Projeto**
Identificar padrões que levam à rotatividade de funcionários (attrition) e fornecer insights acionáveis para ajudar a reduzir a taxa de desligamento, melhorando a retenção de talentos.

## 🛠️ **Metodologia**
1. **Análise Exploratória de Dados (EDA):**
   - Visualizações criadas com **Seaborn** e **Matplotlib**.
   - Cálculo de correlações usando **Cramer's V** e **Pearson** para identificar as variáveis mais relevantes.
   
2. **Feature Engineering:**
   - Criação de novas variáveis, como:
     - `age_last_promotion`: Idade na última promoção.
     - `hours_worked_per_week`: Cálculo das horas trabalhadas considerando horas extras.

3. **Modelagem:**
   - Modelos utilizados:
     - **Regressão Logística**

## 📊 **Resultados Obtidos**
### **Insights Importantes**
1. Funcionários **solteiros** têm maior probabilidade de rotatividade (coeficiente de **0.91** na Regressão Logística).
2. Funcionários **jovens** são mais propensos a sair (coeficiente de **0.82**).
3. A **falta de promoções recentes** está fortemente associada ao desligamento (coeficiente de **-1.08**).
4. O **tempo total de trabalho na empresa** tem impacto moderado na retenção.
5. Horas extras aumentam a chance de desligamento (correlação de **0.25** com `Attrition`).

## ✅ **Perguntas Respondidas**
1. **Quais departamentos têm maior rotatividade?**
   - **Resposta:** Os departamentos de **Vendas** e **Pesquisa & Desenvolvimento** apresentam maior rotatividade.

2. **Qual é a faixa etária mais propensa a sair?**
   - **Resposta:** Funcionários entre **20 e 30 anos** são os mais propensos.

3. **Como a carga de trabalho impacta a rotatividade?**
   - **Resposta:** Funcionários com **muitas horas extras** apresentam maior risco de desligamento.

4. **Por que pessoas com 1 ano de trabalho saem mais?**
   - **Resposta:** Fatores como expectativas desalinhadas e falta de crescimento inicial podem contribuir.
  
## 🔍 **Aprendizados**
1. **Perguntas Melhores:**
   - Aprendi que formular perguntas claras e específicas direciona análises mais eficazes.

2. **Visualizações Mais Impactantes:**
   - Utilizar gráficos adequados para cada tipo de dado ajuda a comunicar os insights de forma mais clara.

3. **Importância da Feature Engineering:**
   - Criar variáveis relevantes aumentou significativamente a capacidade preditiva dos modelos.
