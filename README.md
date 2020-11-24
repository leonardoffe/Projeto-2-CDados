# Projeto 2 CDados

***Algoritmo de vendas de video games***
Bruno Paiva, 
Leonardo Elias, 
Luiz Eduardo Santoro, 
Paulo Chade

***Introdução***
O principal objetivo do nosso 2° projeto de Ciências dos Dados é prever o total de vendas de um jogo levando em consideração a plataforma, o ano de lançamento, o gênero do jogo e o autor. Usamos como base as plataformas do Xbox, PS3 e Wii. 

No primeiro passo do projeto, tivemos que buscar um banco de dados que permitiria responder os interesses levantados no tema escolhido. Utilizamos a plataforma Kaggle para buscarmos nosso banco de dados sobre as vendas antigas dos jogos e suas respectivas plataformas. O banco de dados, em um primeiro momento, estava aparentemente muito bem estruturado, o que facilitou a escolha de uma forma imediata. Mas conforme fomos avançando com o projeto reparamos que deveríamos utilizar filtros e excluir determinados dados. Usamos os 10 maiores autores (Electronic Arts, Activision, Ubisoft, Namco Bandai Games, THQ, Konami Digital Entertainment, Take-Two Interactive, Sega, Sony Computer Entertainment, Capcom) para facilitar a construção do nosso algoritmo.

Depois de realizar algumas comparações entre as três plataformas Xbox, PS3 e Wii, começamos a utilizar métodos diferentes para testá-los no trabalho. Utilizamos o modelo de regressão linear e Random Forest.

***GitHub***
Nosso GitHub contém dois arquivos principais: o *vgsales.csv*, que apresenta os dados de nosso modelo e o *Projeto 2.ipynb*, que é o nosso próprio modelo implementado.
