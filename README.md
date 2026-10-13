# 🏋️‍♂️ Gym Churn & Retention Analysis - Model Fitness

Projeto desenvolvido no bootcamp da **TripleTen** focado na previsão de rotatividade de clientes (*churn*), identificação de fatores de risco através de análise exploratória e matriz de correlação, desenvolvimento de modelos de Machine Learning supervisionado (Regressão Logística e Random Forest) e segmentação não supervisionada de clientes por meio de agrupamento hierárquico (*dendrograma*) e *K-Means*.

## 🚀 Tecnologias Utilizadas
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Machine Learning (Scikit-Learn):** LogisticRegression, RandomForestClassifier, StandardScaler, train_test_split, métricas de avaliação (Accuracy, Precision, Recall).
- **Clusterização (Scikit-Learn & SciPy):** KMeans, linkage, dendrogram.
- **Jupyter Notebook**

## 🎯 Objetivos do Projeto
- **Análise Exploratória (EDA):** Identificação de perfis médios de clientes que abandonam o serviço versus os que permanecem, com destaque para variáveis cruciais como tempo de vida (*lifetime*), frequência de treinos no mês atual e período de contrato.
- **Modelagem Preditiva:** Construção e avaliação comparativa de clasificadores para prever o risco de *churn* de cada membro, validando a estabilidade do modelo face à multicolinearidade.
- **Segmentação de Clientes (Clustering):** Padronização de dados, construção de dendrograma para determinar o número ideal de grupos e aplicação do algoritmo K-Means para definir 5 personas distintas (desde o grupo de lealdade até ao grupo de altíssimo risco).
- **Recomendações Estratégicas:** Formulação de ações práticas para a retenção de clientes (como incentivo a contratos de longo prazo, alertas automáticos para quedas de frequência e expansão de parcerias corporativas e campanhas de indicação).

## 💡 Principais Conclusões
A análise comprovou que o principal fator de retenção é o hábito de treino consistente aliado a contratos mais longos e ao vínculo comunitário (aulas em grupo ou parcerias). A Regressão Logística obteve o melhor desempenho preditivo global (92.25% de acurácia), permitindo à gestão antecipar o abandono de clientes e direcionar campanhas de retenção de forma altamente eficiente.
