# ATIVIDADE 07 - Maratona SENAI de Lógica
## 1.1.
Variável: É um espaço na memória que muda de valor. 

Constante: É um valor que permanece fixo
## 1.2.
O comando leia() serve para o programa receber dados externos (do teclado ou de um sensor).

o inteiro, real, cadeia é crucial porque o computador processa dados de formas diferentes. Se você ler a temperatura como Cadeia (texto), não poderá fazer cálculos matemáticos com ela. Se ler como Inteiro, perderá a precisão das casas decimais que um tipo Real forneceria.
## 1.3.
Eles funcionam como "portões" de decisão para evitar acidentes:

E (AND): A máquina só liga se (Porta Fechada E Botão Pressionado). Ambas devem ser verdadeiras.

OU (OR): O alarme soa se (Sensor de Fumaça Ativado OU Botão de Emergência Pressionado). Apenas uma precisa ser verdadeira.

NÃO (NOT): Inverte o estado. Se o sensor "Obstáculo" for Falso, o operador NÃO torna a condição Verdadeira para permitir o movimento.
## 1.4.
Uma estrutura de repetição executa o mesmo bloco de código várias vezes até que uma condição seja satisfeita.

Quando usar: Em uma linha de montagem, você a usa para processar peças. "Enquanto houver peças na esteira, execute o aperto do parafuso."
## 1.5. 
Para (For): Usado quando você sabe exatamente quantas vezes vai repetir. (Ex: Pintar 10 carros).

Enquanto (While): Usado quando a repetição depende de uma condição variável. (Ex: Encher um tanque até que o sensor de nível acuse "cheio").
## 1.6.
Um loop infinito ocorre quando a condição de parada nunca é atingida.

Risco: Em um sistema industrial, isso pode travar a interface de controle (IHM), impedindo que o operador desligue a máquina ou veja alertas críticos, o que pode causar danos físicos ou explosões por falta de resposta do sistema.
## 1.7.
Imagine que você tem 105 produtos e caixas que comportam 10 unidades:

Divisão Inteira (/): Diz quantas caixas completas você terá (105 / 10 = 10 caixas).

Módulo (%): Retorna o resto da divisão, ou seja, quantos produtos sobraram e não formaram um lote completo (105 \ 10 = 5 produtos avulsos).
## 1.8.
A indentação (o recuo do texto) serve para mostrar a hierarquia do código. Em projetos com várias pessoas, ela é essencial para que qualquer colega bata o olho e entenda rapidamente quais comandos pertencem a qual "se" ou "laço", evitando erros de lógica e facilitando a manutenção.
## 1.9.
Ela permite que o sistema tome dois caminhos distintos:

SE (Umidade < 30%) ENTÃO { Liga irrigação }
SENAO { Desliga irrigação }

Sem o "senao", o sistema poderia saber quando ligar, mas não saberia o que fazer quando a condição deixasse de ser real.
## 1.10.
 No ambiente profissional, o código que você escreve hoje será lido por outra pessoa (ou por você mesmo) daqui a meses.

Por que comentar? Para explicar o "porquê" de certas decisões técnicas complexas. Isso economiza horas de investigação em caso de falha no sistema e garante que a operação da fábrica não pare por falta de entendimento do software.



