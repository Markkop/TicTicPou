# Mago
  
Mago é uma classe cuja origem se deu pela implementação da Granada no jogo base original. Granada era uma arma que podia ser armada e utilizada apenas uma vez por partida, mas todos os jogadores podiam utilizá-la. A Granada, assim como a explosão do Mago, ataca todos os jogadores ao mesmo tempo e caso o jogador receba um tiro durante o lançamento da Granada, a ação é anulada.

No Tic Tic Pou com Classes, Magos carregam a sua ação especial abrindo um livro em sua frente e anunciando "Abra". Uma vez carregada, o jogador pode executar sua ação especial em qualquer rodada simbolizando uma explosão que cai dos céus ao som de "Kadabra!". A Explosão ataca todos os jogadores da roda e quem não estiver se defendendo, morre.

Caso o Mago seja atacado durante o Kadabra, seja por um tiro, por outra explosão ou por um contra-ataque, o Mago morre e sua ação é anulada.

Nota-se aqui que o Samurai é uma classe quase counter de Mago, pois ele pode tentar coordenar seu contra-ataque para o momento que o Mago for usar sua explosão, matando o Mago e salvando demais jogadores que fossem morrer para a ação.

Resoluções:
- Caso 2 magos executem a Explosão ao mesmo tempo, ambos os magos morrem, mas ninguém mais é atacado.
- Caso o Mago seja atacado por um Assassino, o Mago não morre (pois não estaria defendendo) e o Assassino morre (pois estava vulnerável).