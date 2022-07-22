
# Escrevendo como Machado de Assis

## Descrição do projeto

Este programa realiza a mimesis do trabalho de Machado, escrevendo frases que estatisticamente se assemelham com as frases escritas por ele. 

Tomamos uma palavra inicial como, por exemplo, 'olá'. Em seguida, olhamos toda a obra de Machado e em cada ocorrência da palavra 'olá', nós pegamos o item, palavra ou sinais de pontuação, que aparece logo em seguida e colocamos este item em uma lista. Vamos chamar essa lista de lista (de itens) sucessores de 'olá'. Suponha que tenhamos feito isso para toda palavra que Machado já escreveu.

Voltemos para a palavra 'olá'. Agora, escolhemos aleatoriamente um item na lista sucessores de 'olá'. Vamos supor que esse item seja a palavra 'mundo'. Escolhemos, aleatoriamente, um item na lista de sucessores de 'mundo'. Continuamos este processo aleatório até chegarmos em um '.' ou '!' ou '?'. Neste momento, teremos gerado uma frase utilizando como base as listas de sucessores obtidos da obra de Machado.

## Demonstração

<div align="center"> <img src="https://user-images.githubusercontent.com/101532054/180483225-e03f60cf-5026-4cad-9a97-f14c46cdf8f2.png" width="700px"> </div>
<br>

Ao rodar o programa, é pedido ao usuário que digite o nome do arquivo que será usado como base, neste caso, o usuário escolheu a obra Memórias Póstumas. Em seguida o usuário escolhe quantas frases serão geradas, e em cada uma delas ele escolhe a palavra inicial da frase.

Outros exemplos a seguir, o primeiro tomando como base a obra Quincas Borba, e o segundo exemplo tendo como base as obras Memórias Póstumas de Brás Cubas, Quincas Borba, O Almada e Dom Casmurro, condensadas em um único arquivo de texto.

<br>

<div align="center"> <img src="https://user-images.githubusercontent.com/101532054/180483246-f143b246-2d83-4b9d-aacd-debb9d90c016.png" width="700px"> </div>

<br>

<div align="center"> <img src="https://user-images.githubusercontent.com/101532054/180483264-b86423d8-ea9f-4c3b-85d6-9077d1a01161.png" width="700px"> </div>

<br>
<br>

> Este programa foi realizado como exercício de programação para a disciplina de Introdução à Computação (MAC0110) oferecida pela Universidade de São Paulo em 2021, ministrada pelos professores Jose Coelho de Pina Junior e Carlos Hitoshi Morimoto


