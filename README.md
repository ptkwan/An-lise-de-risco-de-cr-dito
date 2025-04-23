<h1>🧠 Estudo de Caso – Patrick Kwan</h1>
<p><strong>📌 Objetivo:</strong> Desenvolver um modelo de admissão com base em dados históricos e análise exploratória.</p>

<hr>

<h2>📂 Sumário</h2>
<ol>
  <li><a href="#bibliotecas">📚 Bibliotecas Utilizadas</a></li>
  <li><a href="#leitura">📥 Leitura do Arquivo</a></li>
  <li><a href="#variavel">🎯 Análise da Variável Resposta</a></li>
  <li><a href="#exploratoria">🔍 Análise Exploratória</a>
    <ul>
      <li>4.1 🛠️ Tratamento de Valores Vazios</li>
      <li>4.2 📊 Visualizações</li>
      <li>4.3 ⏰ Compras em Horário Comercial</li>
    </ul>
  </li>
  <li><a href="#aprofundando">🔬 Aprofundando as Análises</a></li>
  <li><a href="#conclusao">✅ Conclusão</a></li>
</ol>

<hr>

<h2 id="bibliotecas">📚 Bibliotecas Utilizadas</h2>
<ul>
  <li><strong>Pandas:</strong> Manipulação e análise de dados tabulares.</li>
  <li><strong>NumPy:</strong> Operações numéricas e vetoriais.</li>
  <li><strong>Matplotlib / Seaborn:</strong> Visualizações gráficas.</li>
  <li><strong>Scikit-learn:</strong> Pré-processamento e modelos de machine learning.</li>
  <li><strong>Keras:</strong> Construção e treinamento de redes neurais artificiais.</li>
</ul>

<hr>

<h2 id="leitura">📥 Leitura do Arquivo</h2>
<p>Os dados foram carregados utilizando a biblioteca <code>pandas</code>, permitindo uma visualização inicial das colunas, tipos de dados e possíveis inconsistências.</p>

<hr>

<h2 id="variavel">🎯 Análise da Variável Resposta</h2>
<p>A variável <code>over30_mob3</code> foi definida como a variável dependente do modelo, sendo o foco das previsões a serem realizadas.</p>

<hr>

<h2 id="exploratoria">🔍 Análise Exploratória</h2>

<h3>4.1 – 🛠️ Tratamento de Valores Vazios</h3>
<p>Identificação de colunas com dados ausentes e aplicação de estratégias de limpeza ou imputação.</p>

<h3>4.2 – 📊 Visualizações</h3>
<ul>
  <li><strong>Tipo de Cliente:</strong> Distribuição dos clientes por categoria.</li>
  <li><strong>Renda:</strong> Análise da distribuição de renda entre os clientes.</li>
  <li><strong>Tempo até Utilização:</strong> Padrões temporais de comportamento do cliente.</li>
  <li><strong>Score Email:</strong> Distribuição e impacto do score de e-mail.</li>
  <li><strong>Score Pessoa:</strong> Análise do score de perfil individual.</li>
  <li><strong>Valor da Compra:</strong> Variação nos valores de compra dos clientes.</li>
  <li><strong>Análise Geral:</strong> Relação entre renda, score e valor de compra com o status de admissão.</li>
</ul>

<h3>4.3 – ⏰ Compras em Horário Comercial</h3>
<p>Exploração do comportamento de consumo durante o horário comercial.</p>

<hr>

<h2 id="aprofundando">🔬 Aprofundando as Análises</h2>

<h3>5.1 – 📏 Normalização da Base</h3>
<p>Padronização dos dados para garantir melhor performance nos modelos.</p>

<h3>5.2 – 🔗 Gráfico de Correlação</h3>
<p>Visualização da correlação entre variáveis para identificar padrões relevantes.</p>

<h3>5.3 – 🤖 Treinamento do Modelo</h3>
<p>Criação de modelos de machine learning tradicionais para previsão da variável resposta.</p>

<h3>5.4 – 🧠 Modelo com Rede Neural</h3>
<p>Construção e treinamento de um modelo de rede neural usando Keras.</p>

<h3>5.5 – 🧮 Avaliação com Matriz de Confusão</h3>
<p>Análise do desempenho do modelo com métricas de acurácia, precisão e recall.</p>

<h3>5.6 – 🌲 Floresta Aleatória</h3>
<p>Implementação de um modelo de <strong>Random Forest</strong> para comparação com a rede neural.</p>

<hr>

<h2 id="conclusao">✅ Conclusão</h2>
<p>A partir das análises realizadas, foi possível compreender os principais fatores que influenciam o status de admissão. Os modelos testados demonstraram boa performance, com oportunidades claras de melhoria no pré-processamento e balanceamento dos dados.</p>
