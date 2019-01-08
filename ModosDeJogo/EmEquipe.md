# Em Equipe  
  
É possível jogar TicTicPou em Equipes de 2x2, 3x3, 4x4 e assim por diante.  
Nota-se que algumas classes novas podem não ficar balanceadas em 2x2, recomendamos no mínimo 3x3.  
O TicTicPou em Equipe funciona igual ao normal, mas os times jogam um de frente para o outro em um formato oval (para que jogadores do mesmo time possam se ver e interagir).  
Fogo amigo é desativado, ou seja, um Kadabra não afeta jogadores do mesmo time.

Esse modo de jogo permite a elaboração de classes de suporte, algo que não era compatível com o TicTicPou normal uma vez que neste não cabe ações colaborativas.

## Nova Classe: Paramédico

O Paramédico possui as 3 ações básicas: Defesa, TicTic e Pou  
Além disso, ele pode carregar a sua ação especial arrastando as suas mãos umas nas outras de punhos fechados como se estivesse preparando para usar um **Desfibrilador**. Ao fazer isso ele emite o som de "**Zzz**".  
Para usar, ele encosta (ou aponta) as duas mãos de punhos fechados em um aliado morto ao som de **"Contato!"**, **revivendo o aliado**.  

O Paramédico **só pode carregar** sua ação especial **caso um aliado esteja morto**.  
Um jogador só pode reviver uma vez.  
  
Em testes:  
- número de carregamentos para reviver alguém (atualmente: 1)  
- número de vezes que o paramédio pode reviver (atualmente: não há)  
- número de vezes que um jogador pode reviver (atualmente: 1)  

# Em Desenvolvimento

Os seguintes conceitos estão em desenvolvimento e não são definitivos (inclusive os nomes).
Qualquer colaboração é apreciada.

## Conceito: Guardacostas
  
O Guardacostas também possui as três ações básicas.  
Além disso, ele pode carregar sua ação especial para usar e proteger algum aliado.  
Movimentos, sons e balanceamento ainda indefinidos.  

## Conceito: Apaixonado

O Apaixonado é um conceito que requer que ele e outro jogador do próprio time façam uma ação única juntos (consideremos apontar um para o outro por enquanto).
Caso ambos os jogadores se apontem, uma ação forte acontece.
Porém, caso um deles seja atacado no mesmo momento, a ação não acontece.
A ideia por trás é fazer com quem dois jogadores do mesmo time tentem se "sacarem" sem que o outro time perceba e contra-ataque.
Possíveis ações fortes:
- Todos do mesmo time recebem uma carga de sua ação especial
- O jogador que interagiu com o Apaixonado recebe uma vida extra
- Todos os inimigos perdem todos os carregamentos
- Todos os aliados ficam imunes naquela rodada, menos os jogadores que se apontaram

## Conceito: Carregador

O Carregador pode armar o TicTic e/ou a ação especial de um ou mais aliados.