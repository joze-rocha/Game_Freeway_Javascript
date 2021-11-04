Olá, Seja bem vindo!

Estudo da Linguagem Javascript - Recriamos o jogo Freeway de cartucho da Atari 2600 - Freeway.

- Cada carro passa em uma velocidade diferente em forma de loop.
- Inclusão de trilha sonora, personagem e os carros passando na rua.
- Poderemos tentar atravessar a rua, e no caso de conseguirmos, marcaremos um ponto, 
se houver colisão com algum carro ao atravessar a rua, voltaremos a posição original e perderemos pontos.

- Dividimos nosso projeto em outros arquivos .js:
	- ator
	- imagens
	- carro

Através da palavra-chave let declaramos as variáveis com escopo de bloco.
Entenda a diferença entre var, let e const no JavaScript acessando os links do artigo.
	https://www.alura.com.br/artigos/entenda-diferenca-entre-var-let-e-const-no-javascript?gclid=CjwKCAjwiY6MBhBqEiwARFSCPqGuRMHW3ddmeEDaBnLztpzss3XdR9RZOlsDyiWb4R75yk44wA9E5hoCWhwQAvD_BwE

No lugar de usar 9 variáveis, 3 para cada carro, criamos 3 listas: xCarros, yCarros e velocidadeCarros;
Trabalhamos com listas evitando diversas variáveis e com laços de repetição usando o for, removemos os códigos duplicados, utilizando laços de repetição e contadores em cada iteração;

Utilizamos a regra camelCase.

	- function preload()
	- function draw()
	- upload das imagens
	- image()
	- function mostraAtor()
	- function mostraCarro()
	- movimentaCarro()
	- movimentaAtor()
	- if (keyIsDown(UP_ARROW)))
	- if (keyIsDown(DOWN_ARROW))

A implementação da colisão, foi do https://editor.p5js.org/, clicamos em Help & Feedback > Reference > Libraries. 
Scrollando um pouco a página de bibliotecas, achamos o link para "p5.collide2d" pegamos a solução no GitHub e incorporamos ao projeto.

read for remember, tks for coming here. by @Joze-rocha