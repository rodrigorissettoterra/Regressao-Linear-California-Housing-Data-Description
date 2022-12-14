<strong>REGRESSÃO LINEAR: CALIFORNIA HOUSING DATA DESCRIPTION</strong>
<ul>
 	<li>Conhecendo o Dataset
<ul>
 	<li>Importando bibliotecas</li>
 	<li>O Dataset e o Projeto</li>
 	<li>Leitura dos dados</li>
 	<li>Visualizar os dados</li>
 	<li>Traduzindo o nome das colunas</li>
 	<li>Verificando o tamanho do dataset</li>
</ul>
</li>
 	<li>Análises Preliminares
<ul>
 	<li>Estatísticas descritivas</li>
 	<li>Matriz de correlação</li>
</ul>
</li>
 	<li>Comportamento da Variável Dependente (Y)</li>
 	<li>Análises gráficas
<ul>
 	<li>Importando biblioteca seaborn
<ul>
 	<li>Estilizando os gráficos</li>
</ul>
</li>
 	<li>Distribuição de frequência</li>
 	<li>Gráficos de dispersão entre as variáveis do dataset
<ul>
 	<li>Plotando o pairplot fixando somente uma variável no eixo y</li>
</ul>
</li>
</ul>
</li>
 	<li>Estimando um Modelo de Regressão Linear
<ul>
 	<li>Importando o train_test_split da biblioteca scikit-learn</li>
 	<li>Criando uma Series (pandas) para armazenar a variável dependente (y)</li>
 	<li>Criando um DataFrame (pandas) para armazenar as variáveis explicativas (X)</li>
 	<li>Criando os datasets de treino e de teste</li>
 	<li>Importando LinearRegression e metrics da biblioteca scikit-learn</li>
 	<li>Instanciando a classe LinearRegression()</li>
 	<li>Utilizando o método fit() para estimar o modelo linear utilizando os dados de TREINO (y_train e X_train)</li>
 	<li>Obtendo o coeficiente de determinação (R²) do modelo estimado com os dados de TREINO</li>
 	<li>Gerando previsões para os dados de TESTE (X_test) utilizando o método predict()</li>
 	<li>Obtendo o coeficiente de determinação (R²) para as previsões do nosso modelo</li>
</ul>
</li>
 	<li>Obtendo Previsões Pontuais
<ul>
 	<li>Criando um simulador simples</li>
</ul>
</li>
 	<li>Métricas de Regressão
<ul>
 	<li>Métricas da regressão</li>
 	<li>Obtendo métricas para o modelo com Temperatura Máxima</li>
</ul>
</li>
 	<li>Salvando e Carregando o Modelo Estimado
<ul>
 	<li>Importando a biblioteca pickle</li>
 	<li>Salvando o modelo estimado</li>
</ul>
</li>
 	<li>Simulador</li>
</ul>
