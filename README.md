🧠 Estudo de Caso – Patrick Kwan
📌 Objetivo: Desenvolver um modelo de admissão com base em dados históricos e análise exploratória.

📂 Sumário
📚 Bibliotecas Utilizadas

📥 Leitura do Arquivo

🎯 Análise da Variável Resposta

🔍 Análise Exploratória

4.1 🛠️ Tratamento de Valores Vazios

4.2 📊 Visualizações

4.3 ⏰ Compras em Horário Comercial

🔬 Aprofundando as Análises

✅ Conclusão

📚 Bibliotecas Utilizadas
Pandas: Manipulação e análise de dados tabulares.

NumPy: Operações numéricas e vetoriais.

Matplotlib / Seaborn: Visualizações gráficas.

Scikit-learn: Pré-processamento e modelos de machine learning.

Keras: Construção e treinamento de redes neurais artificiais.

📥 Leitura do Arquivo
Os dados foram carregados utilizando a biblioteca pandas, permitindo uma visualização inicial das colunas, tipos de dados e possíveis inconsistências.

🎯 Análise da Variável Resposta
A variável over30_mob3 foi definida como a variável dependente do modelo, sendo o foco das previsões a serem realizadas.

🔍 Análise Exploratória
4.1 – 🛠️ Tratamento de Valores Vazios
Identificação de colunas com dados ausentes e aplicação de estratégias de limpeza ou imputação.

4.2 – 📊 Visualizações
4.2.1 – Tipo de Cliente: Distribuição dos clientes por categoria.

4.2.2 – Renda: Análise da distribuição de renda entre os clientes.

4.2.3 – Tempo até Utilização: Padrões temporais de comportamento do cliente.

4.2.4 – Score Email: Distribuição e impacto do score de e-mail.

4.2.5 – Score Pessoa: Análise do score de perfil individual.

4.2.6 – Valor da Compra: Variação nos valores de compra dos clientes.

4.2.7 – Análise Geral: Relação entre renda, score e valor de compra com o status de admissão.

4.3 – ⏰ Compras em Horário Comercial
Exploração do comportamento de consumo durante o horário comercial.

🔬 Aprofundando as Análises
5.1 – 📏 Normalização da Base
Padronização dos dados para garantir melhor performance nos modelos.

5.2 – 🔗 Gráfico de Correlação
Visualização da correlação entre variáveis para identificar padrões relevantes.

5.3 – 🤖 Treinamento do Modelo
Criação de modelos de machine learning tradicionais para previsão da variável resposta.

5.4 – 🧠 Modelo com Rede Neural
Construção e treinamento de um modelo de rede neural usando Keras.

5.5 – 🧮 Avaliação com Matriz de Confusão
Análise do desempenho do modelo com métricas de acurácia, precisão e recall.

5.6 – 🌲 Floresta Aleatória
Implementação de um modelo de Random Forest para comparação com a rede neural.

✅ Conclusão
A partir das análises realizadas, foi possível compreender os principais fatores que influenciam o status de admissão.
Os modelos testados demonstraram boa performance, com oportunidades claras de melhoria no pré-processamento e balanceamento dos dados.
