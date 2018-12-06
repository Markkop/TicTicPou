# Pacificador (em testes)
  
Pacificador é uma classe que ainda está sendo desenvolvida em conjunto com todos os jogadores que compreendem as demais classes do jogo e contribuem com novas ideais.  
  
Em um primeiro momento, o Pacificador tinha, além das 3 ações básicas, uma ação especial que cancelava todas as ações de carregamentos. Esta ação não necessitava de carregamento.  
A ação era interessante pois modificava o ritmo do jogo, mas não era suficiente para deixá-lo competitivo.  
  
Houve duas ideias de mecânicas adicionais para a classe para deixar seu "gameplay" mais dinâmico:  
- Caso o Pacificador cancelasse o carregamento de metade ou mais jogadores, ele ganha uma vida extra.  
Dessa forma ele tentaria anular o carregamento de mais pessoas enquanto os demais jogadores tentam não ser anulados para não conceder uma vida ao Pacificador.  
O problema aqui foi que contar o número de jogadores afetados durante uma partida se demonstrou inviável.  
  
- O Pacificador não pode mais cancelar duas vezes seguidas, mas os jogadores afetados não podem repetir o mesmo carregamento no próximo turno.
Dessa forma as ações seriam mais estratégicas, mas também não muda muito a dinâmica da classe.  
  
## Estado atual  
  
Atualmente, a ação de cancelar do Pacificador cancela todas as ações daquela rodada, mas é necessário carregá-la assim como as demais classes.
Caso o Pacificador salve alguém da morte por ter cancelado, ele ganha uma vida extra (com no máximo uma).   
  
Recarregar ação especial: o Pacificador cruza seus braços para o alto, formando um X e anunciando "Prepara".  
Usar ação especial: o Pacificador descruza os braços num movimento como se fosse um juiz de futebol encerrando uma partida e anunciando "Cancela!"  
  
Esta mecânica parece ser a mais interessante até o momento, mas ainda carece de testes para avaliar a viabilidade.  
  
Resoluções:  
Caso o Pacificador seja atacado enquanto Cancela, seu cancelamento não é ativado de forma similar ao Mago. (E se tiver uma vida extra? A definir)  
  
A prioridade é sempre verificar se o Pacificador é morto durante a rodada. Caso seja, seu cancelamento não é ativado, mesmo que sua vida teria sido salva.  