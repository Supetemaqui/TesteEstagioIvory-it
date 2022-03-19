## Teste Técnico

## Dicas / Regras
1. Ao codificar matenha seu código limpo e coerente. Manter padronização ajuda a equipe entender o que foi codificado, além de ajudar nas manutenções futuras. Algumas dicas: [Padronização Códificação](https://github.com/ivory-it/ivoryit-testeestagio-detetive/wiki/Padroniza%C3%A7%C3%A3o-codifica%C3%A7%C3%A3o);
2. A classe `CampoMinado.cs` não pode ser modificada;
3. É permitido ter apenas uma instância da classe `CampoMinado.cs`;
4. O algoritimo deve realizar uma analise conforme a seção Objetivo do jogo e não um algoritmo de força bruta, abrindo todos as casas para se descobrir as minas terrestres para depois reabrir somente as que não tem minas terrestres;
5. O algoritimo deve analisar a string que representa o tabuleiro, não é valido fixar a abertura das posições que não possuem minas terrestres pela analise do algoritmo `CampoMinado.cs`;
6. Não é para criar uma aplicação onde o usuário escolha qual posição abrir, é para ser um algoritimo autonomo que realize as jogadas;
7. Qualquer duvida entre em contato: thiago.resende@ivoryit.com.br

## Como resolvi
O código atende a todas as regras impostas, usei o método 'Random()' para que o código funcione sozinho sem que os valores para
linhas e colunas sejam informadas anteriormente, fiz um laço de repetição para que os valores informados para linha e coluna nunca
repitam um valor já mostrado no jogo, criei uma mensagem final para quando o resultado de 'JogoStatus' for igual a 2, depois disso 
feito e incorporado no método apenas chamei na main.

## Considerações finais
Tenho bastante prática em Java/STS e SQL e muito interesse em iniciar meu primeiro estágio, tive prática em .NET quando desenvolvi um
chatbot para a BATERIAS MOURA, tenho muito interesse em novas linguagens/experiências.