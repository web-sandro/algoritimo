aprenda casa :a
dt
tat
un
pd 90
pf :a*2
pd 90
pf :a*2
pd 90
ul
escreva [ fabricando linhas ]
linhas :a
un
pe 180
pf :a/2*7
pd 90
ul
escreva [ fabricando quadrado ]
quadrado :a
pf :a
pd 30
escreva [ fabricando triangulo ]
triangulo :a
escreva [ fabricando paralelogramo ]
paralelogramo :a
un
pf :a*0.33
pd 90
pf :a*1.125
pe 90
ul
retangulo  :a*0.20 :a*0.8 
pf :a*0.8
pe 90
pf :a*0.075
pd 90
pf :a*0.1
pd 90
pf :a*0.34
pd 90
pf :a*0.1
pd 90
pf :a*0.265
pe 90
pf :a*0.80
un
pd 90
pf :a*1.1245
pe 90
pf :a*0.33
pf :a
pd 180
ul
retangulo :a*2 :a
un
pd 90
pf :a*0.25
pe 90
pf :a*0.35
ul
pf :a*0.3
pd 90
pf :a*0.5
pd 90
pf :a*0.3
pd 90
pf :a *0.5
pd 180
un
pf :a
pe 90
ul
pf :a*0.3
pd 90
pf :a*0.5
pd 90
pf :a*0.3
pd 90
pf :a *0.5
pe 90
un
pf :a*0.35
pd 90
pf :a*1.58
pd 90
ul
pf :a*0.66
pe 90
pf :a*0.33 +1
pe 90
pf :a*0.66
fim

aprenda linhas :a
pf :a*4
pd 90
un
pf :a/100*4
ul
pd 90
pf :a*4
pe 90
un
pf :a/100*4
pe 90
ul
pf :a*4
pd 90
un
pf :a/100*4
pd 90
ul
pf :a*4
fim

aprenda paralelogramo :a
pd 60
pf :a
pd 120
pf :a*1.63
un
pf :a*0.20
ul
pf :a*0.17
pd 60
pf :a
pd 120
pf :a*2
pd 90
fim

aprenda quadrado :a
repita 4 [ pf :a pd 90 ]
fim

aprenda retangulo :base :altura
pf :altura
pd 90
pf :base
pd 90
pf :altura
pd 90
pf :base
pd 90
fim

aprenda triangulo :a
repita 2 [ pf :a pd 120 ]
fim



VisuAug

Algoritmo "Primeiro programa"
// inicio
Var
// Seção de Declarações das variáveis 


Inicio

escreval
escreval
escreval("Olá! mundo.")

Fimalgoritmo

LISTA 01

Faça um algoritmo que receba dois números e exiba o resultado da sua soma.

Algoritmo "Resultado da soma"
//   Faça um algoritmo que receba dois números e exiba o resultado da sua soma.

Var

   num1, num2, soma :inteiro


Inicio

      escreval("Digite o primeiro número numero")
      leia(num1)
      escreval("Digite o segundo numero")
      leia(num2)
      soma<-num1+num2
      escreval("Equação")
      escreva(num1," + ",num2, " = ", soma)

Fimalgoritmo

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

Faça um algoritmo que receba dois números e ao final mostre a 
soma, subtração, multiplicação e a divisão dos números lidos.


Algoritmo "Resultado da soma"
//   aça um algoritmo que receba dois números e ao final mostre a
//   soma, subtração, multiplicação e a divisão dos números lidos.

Var

   num1, num2, soma, subtracao, multiplicacao, divisao :real


Inicio

      escreval("Digite o primeiro número numero")
      leia(num1)
      escreval("Digite o segundo numero")
      leia(num2)
      soma<-num1+num2
      subtracao<-num1-num2
      multiplicacao<-num1*num2
      divisao<-num1/num2
      escreval("Equações")
      escreval(num1," + ",num2, " = ", soma)
      escreval(num1," + ",num2, " = ", subtracao)
      escreval(num1," + ",num2, " = ", multiplicacao)
      escreval(num1," + ",num2, " = ", divisao)

Fimalgoritmo

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

Escrever um algoritmo para determinar o consumo médio de um automóvel sendo fornecida 
a distância total percorrida pelo automóvel e o total de combustível gasto.

Escrever um algoritmo que leia o nome de um vendedor, o seu salário fixo e o total de vendas efetuadas por ele no mês (em dinheiro). Sabendo que este vendedor ganha 15% de comissão sobre suas vendas efetuadas, informar o seu nome, o salário fixo e salário no final do mês.

Escrever um algoritmo que leia o nome de um aluno e as notas das três provas que ele obteve no semestre. No final informar o nome do aluno e a sua média (aritmética).

Ler dois valores para as variáveis A e B, e efetuar as trocas dos valores de forma que a variável A passe a possuir o valor da variável B e a variável B passe a possuir o valor da variável A. Apresentar os valores trocados.

Ler uma temperatura em graus Celsius e apresentá-la convertida em graus Fahrenheit. A fórmula de conversão é: F=(9*C+160) / 5, sendo F a temperatura em Fahrenheit e C a temperatura em Celsius.


Elaborar um algoritmo que efetue a apresentação do valor da conversão em real (R$) de um valor lido em dólar (US$). O algoritmo deverá solicitar o valor da cotação do dólar e também a quantidade de dólares disponíveis com o usuário.


A Loja Mamão com Açúcar está vendendo seus produtos em 5 (cinco) prestações sem juros. Faça um algoritmo que receba um valor de uma compra e mostre o valor das prestações.


O custo ao consumidor de um carro novo é a soma do custo de fábrica com a percentagem do distribuidor e dos impostos (aplicados, primeiro os impostos sobre o custo de fábrica, e depois a percentagem do distribuidor sobre o resultado). Supondo que a percentagem do distribuidor seja de 28% e os impostos 45%. Escrever um algoritmo que leia o custo de fábrica de um carro e informe o custo ao consumidor do mesmo.