# topGearMemorial
Uma simplificação dos jogos de corrida (ex: Top Gear, SNES) que será desenvolvido unicamente em Java para a Unidade Curricular de Programação Orientada à Objetos (POO) do Curso de Análise e Desenvolvimento de Sistemas (ADS) do Instituto Federal de Santa Catarina (IFSC).

## Objetivo do jogo
Completar o circuito o mais rápido possível. Pensar em adicionar mais circuitos ou não.

## Infos gerais
2D, pista rolando de cima para baixo, movimentação no A ou D (só vai para a esquerda ou para a direita).

## Movimentação

### Carro
O eixo y é fixo, só se movimenta da esquerda para a direita.
- [ ] Definir o tamanho do carro, linkado com definir o tamanho da faixa.
- [ ] Definir velocidade do carro, o que na verdade é a velocidade da pista.

### Pista
Limites à esquerda e à direita, o movimento é de cima para baixo, tem uma largura fixa de 3 faixas (pode ser modificado o número de faixas).
- [ ] Definir o tamanho da faixa e o tamanho da pista
- [ ] Definir a velocidade em que a pista se movimenta/velocidade do carro.
- [ ] Definir se ela faz curvas

### Obstáculos
Carros, cones, pedras (pode ser modificado o que esses obstáculos serão).

### Cronômetro
Conta o tempo do início da volta até o seu fim. Seja o mais rápido possível.

## Timeline do jogo

### Menu inicial
Novo jogo > press start with logo > animação indo para o lado

### Início do jogo
- Contagem regressiva 3 2 1 GO
- Animação de fumaça

### Finish Line
- carro diminui a velocidade e mostra o tempo percorrido na volta

### Bucket de ideias aleatórias que talvez implemente ou não
- Tipos de carros diferentes
- Música
- Sons: acelerar carro, batida etc
- Aumentar ou diminuir a velocidade manualmente
- Aumentar a velocidade na borda da pista
- Diminuir a velocidade ao sair da pista no limite dela
- threads (java) https://docs.oracle.com/javase/8/docs/api/java/lang/Thread.html
- GUI JFrame and JPanel https://www.javaprogressivo.net/2012/11/JFrame-e-JPanelDesenhando-em-Java.html, https://docs.oracle.com/en/java/javase/21/docs/api/java.desktop/javax/swing/JFrame.html
  
## Referências:
- https://www.retrogames.cz/play_910-SNES.php
- https://pt.wikipedia.org/wiki/Top_Gear_(s%C3%A9rie_de_jogos_eletr%C3%B4nicos)
