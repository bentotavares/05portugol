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


## 2.1.
```
programa {
  funcao inicio() {
    cadeia nome
    escreva("Digite o nome do colaborador: ")
    leia(nome)
    escreva("Olá ", nome, ", seu turno de 8h na Indústria 4.0 começou. Bom trabalho!")
  }
}
```
## 2.2.
```
programa {
  funcao inicio() {
    inteiro r1, r2, total
		escreva("Quantidade da 1ª remessa: ")
		leia(r1)
		escreva("Quantidade da 2ª remessa: ")
		leia(r2)
		total = r1 + r2
		escreva("Estoque total disponível: ", total)
  }
}
```
## 2.3.
```
programa {
  funcao inicio() {
    real valorHora, horas, total
		escreva("Valor da hora técnica: ")
		leia(valorHora)
		escreva("Quantidade de horas: ")
		leia(horas)
		total = valorHora * horas
		escreva("Valor total a ser pago: R$ ", total)
  }
}
```
## 2.4.
```
programa {
  funcao inicio() {
    real metros, milimetros
		escreva("Medida em metros: ")
		leia(metros)
		milimetros = metros * 1000
		escreva("Configuração da máquina: ", milimetros, " mm")
  }
}
```
## 2.5.
```
programa {
  funcao inicio() {
    real m1, m2, m3, media
		escreva("Consumo da Máquina 1 (kWh): ")
		leia(m1)
		escreva("Consumo da Máquina 2 (kWh): ")
		leia(m2)
		escreva("Consumo da Máquina 3 (kWh): ")
		leia(m3)
		media = (m1 + m2 + m3) / 3
		escreva("Média de consumo: ", media, " kWh")
  }
}
```
## 2.6.
```
programa {
  funcao inicio() {
    real largura, comprimento, area
		escreva("Largura do galpão: ")
		leia(largura)
		escreva("Comprimento do galpão: ")
		leia(comprimento)
		area = largura * comprimento
		escreva("Área total: ", area, " m²")
  }
}
```
## 2.7.
```
programa {
  funcao inicio() {
    real custo, venda
		escreva("Preço de custo da engrenagem: ")
		leia(custo)
		venda = custo * 1.15
		escreva("Preço de venda para 15% de lucro: R$ ", venda)
  }
}
```
## 2.8.
```
programa {
  funcao inicio() {
    real celsius, fahrenheit
		escreva("Temperatura em Celsius: ")
		leia(celsius)
		fahrenheit = celsius * 1.8 + 32
		escreva("Temperatura em Fahrenheit: ", fahrenheit, "°F")
  }
}
```
## 2.9.
```
programa {
  funcao inicio() {
    real distancia, litros
		escreva("Distância da entrega (km): ")
		leia(distancia)
		litros = distancia / 12
		escreva("Litros de diesel necessários: ", litros, "L")
  }
}
```
## 2.10.
```
programa {
  funcao inicio() {
    inteiro id
		escreva("Digite o ID da peça: ")
		leia(id)
		escreva("Anterior: ", id - 1, " | Atual: ", id, " | Próximo: ", id + 1)
  }
}
```
## 2.11.
```
programa {
  funcao inicio() {
    real temp
		escreva("Temperatura da caldeira: ")
		leia(temp)
		se (temp > 100) {
			escreva("ALERTA: RISCO DE EXPLOSÃO")
		} senao {
			escreva("Temperatura Estável")
		}
  }
}
```
## 2.12.
```
programa {
  funcao inicio() {
    inteiro idade
		escreva("Idade do colaborador: ")
		leia(idade)
		se (idade >= 18) {
			escreva("Autorizado")
		} senao {
			escreva("Não Autorizado")
		}
  }
}
```
## 2.13.
```
programa {
  funcao inicio() {
    inteiro prodA, prodB
		escreva("Produção Setor A: ")
		leia(prodA)
		escreva("Produção Setor B: ")
		leia(prodB)
		se (prodA > prodB) {
			escreva("Setor A produziu mais.")
		} senao se (prodB > prodA) {
			escreva("Setor B produziu mais.")
		} senao {
			escreva("Empate na produção.")
		}
  }
}
```
## 2.14.
```
programa {
  funcao inicio() {
    inteiro id
		escreva("ID da peça: ")
		leia(id)
		se (id % 2 == 0) {
			escreva("Esteira Esquerda (Par)")
		} senao {
			escreva("Esteira Direita (Ímpar)")
		}
  }
}
```
## 2.15.
```
programa {
  funcao inicio() {
    cadeia usuario, senha
		escreva("Usuário: ")
		leia(usuario)
		escreva("Senha: ")
		leia(senha)
		se (usuario == "admin" e senha == "1234") {
			escreva("Acesso Concedido")
		} senao {
			escreva("Acesso Negado")
		}
  }
}
```
## 2.16.
```
programa {
  funcao inicio() {
    real peso
		escreva("Peso da carga (kg): ")
		leia(peso)
		se (peso <= 500) {
			escreva("Transporte autorizado.")
		} senao {
			escreva("Excesso de peso!")
		}
  }
}
```
## 2.17.
```
programa {
  funcao inicio() {
    real atual, novo
		escreva("Salário atual: ")
		leia(atual)
		se (atual < 2500) {
			novo = atual * 1.10
		} senao {
			novo = atual * 1.05
		}
		escreva("Novo salário: R$ ", novo)
  }
}
```
## 2.18.
```
programa {
  funcao inicio() {
    real comp
		escreva("Comprimento da peça (cm): ")
		leia(comp)
		se (comp < 15) {
			escreva("Refugo")
		} senao se (comp <= 20) {
			escreva("Padrão")
		} senao {
			escreva("Premium")
		}
  }
}
```
## 2.19.
```
programa {
  funcao inicio() {
    real t1, t2, t3, media
		escreva("Nota teste 1: ")
		leia(t1)
		escreva("Nota teste 2: ")
		leia(t2)
		escreva("Nota teste 3: ")
		leia(t3)
		media = (t1 + t2 + t3) / 3
		se (media >= 7) {
			escreva("Operador Ouro")
		} senao {
			escreva("Reciclagem")
		}
  }
}
```
## 2.20.
```
programa {
  funcao inicio() {
   inteiro ano
		escreva("Digite o ano: ")
		leia(ano)
		se ((ano % 4 == 0 e ano % 100 != 0) ou (ano % 400 == 0)) {
			escreva("Ano bissexto: Manutenção Geral!")
		} senao {
			escreva("Ano comum.")
		} 
  }
}
```
## 2.21.
```
programa {
  funcao inicio() {
    para (inteiro i = 1; i <= 50; i++) {
			escreva("Sensor ID: ", i, "\n")}
  }
}
```
## 2.22.
```
programa {
  funcao inicio() {
    para (inteiro i = 2; i <= 100; i += 2) {
			escreva("Testando sensor: ", i, "\n")
		}
  }
}
```
## 2.23.
```
programa {
  funcao inicio() {
    para (inteiro i = 10; i >= 0; i--) {
			escreva(i, "... ")
		}
		escreva("IGNIÇÃO!")
  }
}
```
## 2.24.
```
programa {
  funcao inicio() {
    inteiro soma = 0, prod
		para (inteiro i = 1; i <= 7; i++) {
			escreva("Produção dia ", i, ": ")
			leia(prod)
			soma += prod
		}
		escreva("Total produzido na semana: ", soma)
  }
}
```
## 2.25.
```
programa {
  funcao inicio() {
    inteiro n, fat = 1
		escreva("Calcular fatorial de: ")
		leia(n)
		para (inteiro i = 1; i <= n; i++) {
			fat *= i
		}
		escreva("Fatorial: ", fat)
  }
}
```
## 2.26. 
```
programa {
  funcao inicio() {
    inteiro prodHora
		escreva("Produção por hora: ")
		leia(prodHora)
		para (inteiro i = 1; i <= 10; i++) {
			escreva(i, "h: ", i * prodHora, " peças\n")
		}
  }
}
```
## 2.27. 
```
programa {
  funcao inicio() {
    real temp, soma = 0.0
		para (inteiro i = 1; i <= 10; i++) {
			escreva("Temperatura ponto ", i, ": ")
			leia(temp)
			soma += temp
		}
		escreva("Média térmica do ambiente: ", soma / 10)
  }
}
```
## 2.28.
```
programa {
	funcao inicio() {
		cadeia senha = ""
		enquanto (senha != "1234") {
			escreva("Digite a senha da porta: ")
			leia(senha)
			se (senha != "1234") escreva("Incorreta! ")
		}
		escreva("Acesso Liberado!")
	}
}
```
## 2.29
```
programa {
	funcao inicio() {
		para (inteiro i = 0; i <= 200; i += 5) {
			escreva("Marca: ", i, "mm\n")
		}
	}
}
```
## 2.30.
```
programa {
	funcao inicio() {
		inteiro a = 0, b = 1, prox
		escreva(a, " ", b, " ")
		para (inteiro i = 3; i <= 10; i++) {
			prox = a + b
			escreva(prox, " ")
			a = b
			b = prox
		}
	}
}
```
## 2.31.
```
programa {
	funcao inicio() {
		inteiro n
		real prod, soma = 0.0
		escreva("Quantas máquinas analisar? ")
		leia(n)
		para (inteiro i = 1; i <= n; i++) {
			escreva("Produção máquina ", i, ": ")
			leia(prod)
			soma += prod
		}
		escreva("Média final: ", soma / n)
	}
}
```
## 2.32.
```
programa {
	funcao inicio() {
		inteiro descarte = 0, aprovado = 0
		real peso
		para (inteiro i = 1; i <= 10; i++) {
			escreva("Peso da peça ", i, "(g): ")
			leia(peso)
			se (peso < 50) { descarte++ } senao { aprovado++ }
		}
		escreva("Aprovadas: ", aprovado, " | Descarte: ", descarte)
	}
}
```
## 2.33.
```
programa {
	funcao inicio() {
		cadeia nome
		real bruto, liquido
		para (inteiro i = 1; i <= 5; i++) {
			escreva("Nome: ") leia(nome)
			escreva("Salário Bruto: ") leia(bruto)
			liquido = bruto * 0.89 
			escreva("Funcionário: ", nome, " | Líquido: R$ ", liquido, "\n")
		}
	}
}
```
## 2.34.
```
programa {
	funcao inicio() {
		real pressao = -1.0, maior = 0.0
		enquanto (pressao != 0) {
			escreva("Digite a pressão (ou 0 p/ sair): ")
			leia(pressao)
			se (pressao > maior) { maior = pressao }
		}
		escreva("Maior pressão registrada: ", maior)
	}
}
```
## 2.35.
```
programa {
	funcao inicio() {
		inteiro opcao = -1
		enquanto (opcao != 0) {
			escreva("\n(1) Ligar (2) Desligar (3) Status (0) Sair: ")
			leia(opcao)
			escolha(opcao) {
				caso 1: escreva("Máquina Ligada") pare
				caso 2: escreva("Máquina Desligada") pare
				caso 3: escreva("Sistema Operacional") pare
				caso 0: escreva("Saindo...") pare
				caso contrario: escreva("Opção Inválida")
			}
		}
	}
}
```
## 2.36.
```
programa {
	funcao inicio() {
		inteiro meta, prod, bateram = 0
		escreva("Meta do dia: ") leia(meta)
		para (inteiro i = 1; i <= 5; i++) {
			escreva("Produção funcionário ", i, ": ") leia(prod)
			se (prod >= meta) { bateram++ }
		}
		escreva(bateram, " funcionários bateram a meta.")
	}
}
```
## 2.37
```
programa {
	funcao inicio() {
		real estoque = 1000.0, retirada
		enquanto (estoque > 0) {
			escreva("Saldo: ", estoque, "kg. Quanto retirar? ")
			leia(retirada)
			estoque -= retirada
			se (estoque < 0) estoque = 0.0
		}
		escreva("Silo vazio.")
	}
}
```
## 2.38.
```
programa {
	funcao inicio() {
		inteiro nota, notaDez = 0
		para (inteiro i = 1; i <= 10; i++) {
			escreva("Voto funcionário ", i, " (0-10): ")
			leia(nota)
			se (nota == 10) { notaDez++ }
		}
		escreva("Funcionários que deram nota máxima: ", notaDez)
	}
}
```
## 2.39.
```
programa {
	funcao inicio() {
		real pol
		para (inteiro i = 1; i <= 5; i++) {
			escreva("Medida em polegadas: ")
			leia(pol)
			escreva(pol, " pol = ", pol * 2.54, " cm\n")
		}
	}
}
```
## 2.40.
```
programa {
	funcao inicio() {
		cadeia nome, destaque = "", setor
		inteiro prod, total = 0, maiorProd = 0
		para (inteiro i = 1; i <= 5; i++) {
			escreva("Nome: ") leia(nome)
			escreva("Setor (A/B/C): ") leia(setor)
			escreva("Produção: ") leia(prod)
			total += prod
			se (prod > maiorProd) {
				maiorProd = prod
				destaque = nome
			}
		}
		escreva("\n--- DASHBOARD ---")
		escreva("\nTotal Fábrica: ", total)
		escreva("\nMédia: ", total / 5.0)
		escreva("\nDestaque: ", destaque)
	}
}
```


