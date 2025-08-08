Projeto TelecomX: Previsão de Evasão de Clientes
📋 Descrição
Este projeto tem como objetivo analisar dados de clientes de uma empresa de telecomunicações para entender os fatores que influenciam a evasão (cancelamento) e construir modelos preditivos que possam antecipar quais clientes têm maior probabilidade de cancelar o serviço.

A análise inclui:

Exploração e visualização dos dados.

Engenharia de features e pré-processamento.

Criação e avaliação de modelos preditivos (Regressão Logística e Random Forest).

Interpretação dos modelos para identificar variáveis relevantes.

Estratégias para retenção de clientes baseadas nos resultados.

🗂️ Estrutura do Projeto
telecomx_limpo.csv — Base de dados original já limpa.

notebooks/ — Scripts em Jupyter Notebook contendo todo o passo a passo da análise e modelagem.

scripts/ — Scripts Python para pré-processamento, modelagem e avaliação.

README.md — Este arquivo com a documentação do projeto.

📌 Etapas do Projeto
1. Pré-processamento e Engenharia de Features
Remoção de colunas irrelevantes (customerID).

Tratamento de valores faltantes.

Codificação de variáveis categóricas (One-Hot Encoding).

Normalização dos dados para modelos que requerem (ex: Regressão Logística).

2. Análise Exploratória
Visualização da matriz de correlação para identificar variáveis relacionadas à evasão.

Análise específica de variáveis como Tempo de Contrato e Total Gasto com gráficos de boxplot e dispersão para detectar padrões.

3. Modelagem Preditiva
Divisão dos dados em treino (70%) e teste (30%) com estratificação da variável alvo.

Treinamento de dois modelos:

Regressão Logística (modelo linear que exige normalização)

Random Forest (modelo de árvore que não exige normalização)

Avaliação com métricas: acurácia, precisão, recall, F1-score e matriz de confusão.

4. Interpretação e Conclusões
Análise dos coeficientes da Regressão Logística para entender o impacto das variáveis.

Análise da importância das variáveis no Random Forest.

Identificação dos principais fatores que influenciam a evasão.

Propostas de estratégias para retenção de clientes baseadas nos insights obtidos.

🛠️ Tecnologias Utilizadas
Python 3.x

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook
