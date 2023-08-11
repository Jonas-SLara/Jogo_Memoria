# Jogo_Memoria
em desenvolvimento inicial, isto será alterado mais tarde por enquanto é um teste não oficial para me situar com as ferramentas do GitHub

#etapas iniciais
-configurar o layout principal da página
-importar as imagens da web e separa-las em 3 pastas: um para cada tema, Bandeiras, Animais, Frutas
-no java script ler uma array de 12 elementos e as embaralhare, estas serão as posiçoes que serão distribuidas para as divs cards cada com uma imagem 
-12 cards sendo que na verdade serão 6 pares de cartas

#etapas construção
-um botaõ iniciar que chama a função de embaralhar anteriormente e verifica qual tema foi escolhido para pegar imagens deste tema e distribuir nos cards da esquerda para direita que não estara mais ordenada
-criar identificadores para imagens, imagens iguais terão mesmo identificadores
-efetuar as jogadas conforme haver cartas na mesa, varia de 2 em 2 com uma variavel
-enquanto esta variavel não estiver em 0 as cartas poderão ser clicadas, ao clicar chamar uma função para criar a animação de virada de carta,  e mudar o valor desta propiedade para ocupado
-cartas com valores: 'ocupado' não poderão ser clicadas novamente
-a primeira carta clicada retornara 1 a contagen de cartas viradas a segunda também, ao finalizar a segunda sera feito os testes condicionais
  Se Ambas possuirem os mesmos atributos elas serão iguais e sera chamado uma função para torna-las indisponiveis, 'ocupado' permanentemente e diminuira as cartas na mesa em -2
-a ideia é repetir os passos anteriores até que a primeira condição cartas na mesa seja 0, 

#ideias adicionais
