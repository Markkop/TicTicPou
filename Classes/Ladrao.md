# Ladrao/Trombadinha

O Ladrão possui as três ações básicas do jogo.
Além disso, ele pode usar a sua ação especial em alguém, fazendo com a mão como se estivesse pegando algo no ar e falando "Perdeu"  
Caso ele use "Perdeu" em alguém que esteja carregando uma ação especial, ele rouba aquele carregamento.  
Caso ele use "Perdeu" em alguém que esteja fazendo TicTic, ele ganha uma bala (com no máximo 1 bala)  

Exemplos:  
Usou "Perdeu" no "Uh!" de um Samurai: o Ladrão pode usar "Katchin" quando quiser e o Samurai perdeu o seu carregamento.  
O mesmo para o Mago e seu "Abra".  
  
No caso do Padre, o "Perdeu" não rouba a reza, apenas cancela ela.  
No caso do Cangaceiro, o "Perdeu" não faz com quem o Ladrão tenha 2 balas, apenas rouba/cancela a bala.  

Observações:  
O Ladrão não pode usar "Perdeu" novamente até usar a ação especial que roubou anteriormente. (com exceção do roubo de um TicTic)  
Ou seja, o Ladrão não pode acumular ações especiais.  
E também o Ladrão não pode ter mais que uma bala.  

## Em testes:

Essa classe está em testes e no momento o maior problema é a força que ele tem contra Magos e Samurais, enquanto que Padres e Cangaceiros são poucos afetados.  
Também é necessário verificar como que fica a sua interação com um Assassino no jogo.  
Nota-se que, dentro do conceito atual, o Ladrão não precisa carregar o "Perdeu".  


