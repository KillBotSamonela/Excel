Projeto de excel comando básicos, arquivo (restaurante1)
Códigos básicos de excel
O =PROCV no Excel serve para procurar um valor em uma tabela e trazer um resultado que esteja na mesma linha desse valor.
 O nome significa PROcura Vertical, porque ele pesquisa na coluna de cima para baixo.
 
 =PROCV(valor_procurado; tabela; núm_índice_coluna; [procurar_intervalo])
 
valor_procurado → o que você quer achar (ex: um código de produto).

tabela → o intervalo de células onde ele vai procurar (ex: A2:D20).

núm_índice_coluna → o número da coluna dentro da tabela que você quer trazer o resultado (a primeira coluna da tabela é 1, a segunda é 2, e assim por diante).

[procurar_intervalo] → pode ser:

FALSO → procura valor exato.

VERDADEIRO → procura valor aproximado (menos usado).

O CONT.SES também é muito usado no Excel.
Ele serve para contar quantas células atendem a dois ou mais critérios ao mesmo tempo.

intervalo1 → onde vai procurar o critério1.

critério1 → a condição que precisa ser atendida.

intervalo2; 
critério2 → se quiser mais condições, você pode colocar quantas precisar.
