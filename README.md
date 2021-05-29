## **PROJETO USANDO GRÁFICO DE NETWORK - TRANSAÇÕES DE TIMES EUROPEUS** :chart_with_upwards_trend:

Com intuito de aprender Gráficos de Rede e Análise de Cesta de Compras, busquei um projeto* com dados que me trariam interesse, assim ficando mais fácil assimilar a técnica, e para isso, nada melhor que o futebol.

As informações do esporte bretão foram obtidas do <a href="https://www.kaggle.com/hugomathien/soccer">Kaggle</a>. Onde foi possível encontrar um banco de dados com mais +25.000 partidas, +10.000 jogadores e 11 ligas diferentes, coletados entre as temporadas de 2008 e 2016.

Sobre as técnicas empregadas: A Análise de Cesta de Compras, conhecida como MBA - Market Basket Analysis, desenvolvida para encontrar padrões, principalmente utilizada em lojas (de onde vem seu nome), sendo possível estudar e até prever quais compras serão feitas por seus clientes e em qual ordem elas acontecem. Aproveito o conceito, pois como não tenho a informação das transações, utilizarei esta técnica para conectar os dados das partidas e assim confrontar em qual clube o jogador esteva em cada jogo e assim detectar as trocas das agremiações. A outra técnica será utilizada para a visualização dessas transações, onde será mais fácil observar o comportamento e ligação destes dados tratados na *basket case*.

Para o início foi necessário combinar cinco tabelas do *database*, já que no banco de dados do Kaggle ele estava subdividido em Países, Ligas, Partidas, Jogadores e Times. Logo em seguida foi realizado as importações, análises e limpeza dos dados. Assim foi possível reunir e agrupar toda a informação para ser possível criar a Análise de Cesta de Compras e posteriormente o Gráfico de Rede.

![Cesta de Compras](https://media-exp1.licdn.com/dms/image/C4D12AQGDrHqmu_E7SQ/article-inline_image-shrink_1000_1488/0/1621817663969?e=1627516800&v=beta&t=LPJDkF9M99TI8XCQaL2Xmw2U-irfAg2xVE-sgFBNEmM)

Ao criar a cesta de compra, conforme figura ao lado, pode-se calcular quais jogadores em comum os clubes tiveram e, com isso, deduzir as transações feitas. Ou seja, é importante salientar que não se pode afirmar que houve troca entre os clubes, mas que, entre as diversas partidas analisadas, um determinado jogador participou por uma agremiação e que em um próximo jogo, atuou por outra.

![Grafico de Rede](https://media-exp1.licdn.com/dms/image/C4D12AQFNjfTTX3hPSA/article-inline_image-shrink_1000_1488/0/1621817709169?e=1627516800&v=beta&t=F-yxVv-OUqQZsiPVQY9YDS7Gne7Lcl3X_KWeb4QEuPc)

Após inferências realizadas, consegui programar, conforme imagem acima, o Gráfico de Rede, que é uma apresentação interessante para representar essas transações, sendo fácil visualizar as ligações de trocas entre os clubes, conforme mostrado no esquema abaixo. Porém, a melhor maneira de aproveitar esse recurso, já que ele é interativo, é acessar este <a href="https://jeffguerra.github.io/Projeto-Transacoes-no-Futebol/">link</a>, onde pode-se interagir com o gráfico, aproximar, clicar e obter informações mais detalhadas.

![Grafico de Rede](https://media-exp1.licdn.com/dms/image/C4D12AQE_1py-ZTsDtg/article-inline_image-shrink_1000_1488/0/1621818289681?e=1627516800&v=beta&t=FTAktyPSVec268Q-va--fQuRR5toFSr67BdR7gk4_nU)

Acesse o <a href="https://github.com/jeffguerra/Projeto-Transacoes-no-Futebol">**gráfico**</a> e o <a href="https://jeffguerra.github.io/Projeto-Transacoes-no-Futebol/">**github**</a> deste projeto.

*baseado em projeto do Data Science Academy (em R)
