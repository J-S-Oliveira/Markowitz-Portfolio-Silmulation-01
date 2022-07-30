# Markowitz-Portfolio-Silmulation-01
Aplicação da Teoria Moderna do Portfolio (TMP), com a identificação da fronteira de eficiência, portfolio de menor risco, de maior Sharpe e da linha de mercado de capitais.

# Roteiro

 1.Colete os preços e volumes de um conjunto de ativos durante o período de 10 (dez) anos, pertencentes a no mínimo 5 (cinco) Índices de Segmentos e Setoriais diferentes na B3, e separe os ativos mais líquidos;

2.Construa amostras de treinamento e outras de teste, sendo a primeira com os 3 (três) anos e a segunda com o último ano, e desloque as janelas anualmente (walk forward analysis);

3.Na amostra de treinamento, aplique uma clusterização não supervisionada (K-Means ou DBSCAN) e separe um ativo para cada clusters, com o critério que desejar (sugestão maior índice Sharpe);

4.Aplique a Teoria do Portfolio Moderno de Markowitz nos ativos escolhidos no passo anterior, no sentido de alocar um capital de R$100.000,00;

5.Verifique o resultado da alocação de capital com Markowitz nos ativos separados, na fase de treinamento, na amostra de teste que representa o último ano da aquisição e compare com o índice Bovespa;

6.Descreva suas impressores relativas ao processo, baseado em números, e resultados encontrado

# Classificação Setorial | B3

![Setorial-B3-24-06-2022-_português_](https://user-images.githubusercontent.com/70406366/181828809-89799192-d632-4edb-9970-57c5034dc88e.png)

# Clusterização

Foram escolhidos por serem os principais ativos listado eem bolsa e também por serem os mais apresentarem liquidez ,e serem frequentemente recomendados por analistas:

  <li> <b>     AGRO3            </b> </li>
  <li> <b>     ABEV3            </b> </li>
  <li> <b>     MGLU3            </b> </li>
  <li> <b>     ITUB4            </b> </li>
  <li> <b>     VALE3            </b> </li>
  <li> <b>     PETR3            </b> </li>

### Movimento Geometrico Browniano AGRO3   


### Movimento Geometrico Browniano ABEV3   


### Movimento Geometrico Browniano MGLU3    


### Movimento Geometrico Browniano ITUB4  

### Movimento Geometrico Browniano VALE3 


### Movimento Geometrico Browniano PETR3  

# Matriz de Covariância e Correlação 

# Método K-means

# Portfolio Markowitz

# Testes e Resultados





