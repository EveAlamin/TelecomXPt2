# 📊 Predição de Evasão de Clientes - Telecom X (Parte 2)

Este projeto é a segunda parte da análise de **evasão de clientes (churn)** da empresa fictícia **Telecom X**.  
Enquanto a **Parte 1** focou em análise exploratória e identificação de padrões, aqui o objetivo foi **construir modelos preditivos de Machine Learning** para prever quais clientes têm maior chance de cancelar os serviços.

---

## 🚀 Tecnologias Utilizadas
- Python 3.x  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 🔧 Etapas do Projeto

### 1. Preparação dos Dados
- Normalização e limpeza das variáveis.  
- Transformação de variáveis categóricas em numéricas.  
- Seleção de atributos relevantes para modelagem.  

### 2. Modelagem Preditiva 🤖
Foram testados dois modelos:  
- **Regressão Logística** → Melhor desempenho, com **~80% de acurácia** e bom equilíbrio entre precisão e recall.  
- **Árvore de Decisão** → Funcionou bem, mas apresentou risco maior de **overfitting**.  

➡️ **Regressão Logística** escolhida como modelo principal.  

### 3. Fatores Mais Influentes
Principais variáveis associadas ao **churn**:  
- **Contrato Mês a Mês** → Maior risco de evasão.  
- **Serviço de Internet Fibra Óptica** → Clientes cancelam mais nesse plano.  
- **Tempo de Contrato** → Quanto mais tempo, menor o risco de saída.  
- **Método de Pagamento (Cheque Eletrônico)** → Fortemente ligado ao churn.  
- **Fatura Mensal Alta** → Aumenta a evasão, embora com menor impacto.  

### 4. Estratégias de Retenção
- Reestruturar planos mensais, incentivando contratos anuais/bianuais.  
- Criar **programa de onboarding** para os primeiros 90 dias de contrato.  
- Auditar e melhorar qualidade do serviço de fibra óptica.  
- Incentivar **pagamentos automáticos** com benefícios financeiros.  

---

## 📊 Resultados
- Modelo preditivo robusto para identificar clientes em risco.  
- Insights acionáveis para estratégias de retenção.  
- Base para implementação de campanhas de marketing direcionadas.  

