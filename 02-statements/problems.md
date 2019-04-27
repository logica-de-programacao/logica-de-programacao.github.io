# Exercícios: estrutura iniciais <!-- omit in toc -->

**sumário**

- [Trocar valor de 2 variáveis](#trocar-valor-de-2-vari%C3%A1veis)
- [Qual o dobro de um número?](#qual-o-dobro-de-um-n%C3%BAmero)
- [Qual a área da figura?](#qual-a-%C3%A1rea-da-figura)
- [Qual o antecessor e o sucessor de um número?](#qual-o-antecessor-e-o-sucessor-de-um-n%C3%BAmero)
- [Qual a média aritmética de 3 números?](#qual-a-m%C3%A9dia-aritm%C3%A9tica-de-3-n%C3%BAmeros)
- [Qual o intervalo em dias de uma data?](#qual-o-intervalo-em-dias-de-uma-data)
- [Conversor de medidas](#conversor-de-medidas)

## Trocar valor de 2 variáveis

**objetivo**

- Trocar o valor de 2 variáveis

**descrição**

Contrua um algoritmo que armazene o valor `999` na variável `primeiro` e o valor `555` na variável `segundo`.

A seguir, utilizando apenas atribuições entre variáveis, troque os seus valores fazendo com que o valor que está em `primeiro` passe para `segundo` e vice-versa.

Imprima na tela o nome das variáveis e seus respectivos valores antes e depois da permuta.

**variação**

Construa um algoritmo que receba do teclado 2 valores e armazene em 2 variáveis, `primeiro` e `segundo`.

A seguir, utilizando apenas atribuições entre variáveis, troque os seus valores fazendo com que o valor que está em `primeiro` passe para _segundo_ e vice-versa.

Imprima na tela o nome das variáveis e seus respectivos valores antes e depois da permuta.

**exemplo**

```
informe o primeiro valor
123
informe o segundo valor
321

-> primeiro = 123 e segundo = 321
-> primeiro = 321 e segundo = 123
```

## Qual o dobro de um número?

**objetivo**

- Calcular o dobro de um número

**descrição**

Contrua um algoritmo que armazene o valor `999` na variável `fator` e calcule o dobro desse valor na variável `produto`.

Imprima na tela, usando as variáveis, a equação e seu resultado.

**variação**

Contrua um algoritmo que receba do teclado um valor e armazene na variável `fator`. Calcule o dobro desse valor e armazene na variável `produto`.

Imprima na tela, usando as variáveis, a equação e seu resultado.

**exemplo**

```
informe o fator valor
123

-> 123 * 2  = 246
```

## Qual a área da figura?

**objetivo**

- Calcular área de figuras planas

**descrição**

Sabendo que a área de um quadrado é `lado * lado`.
Contrua um algoritmo que receba do teclado o tamanho do lado do quadrado e armazene na variável `lado` e calcule a área correspondente armazenando seu valor na variável `área`.

Imprima na tela a equação e a área, usando as variáveis.

**variação**

As figuras planas são: triângulo, quadrado, retângulo, losango, trapézio e círculo. O problema acima trata de um quadrado, faça 1 algoritmo para cada das outras figuras geométricas.

Informações sobre [área de figuras planas](https://www.todamateria.com.br/areas-de-figuras-planas/).

**exemplo**

```
informe o lado do quadrado
12

-> área do quadrado
-> 12 * 12 = 144
```

## Qual o antecessor e o sucessor de um número?

**objetivo**

- Calcular o antecessor e sucessor de um número.

**descrição**

Construa um algoritmo que armazene o valor `999` na variável `número_mágico` e calcule o número antecessor e sucessor desse número, armazenando respectivamente nas variáveis `antecessor` e `sucessor`.

Imprima na tela, usando as variáveis, os 3 números identificando-os.

**variação**

Construa um algoritmo que receba do declado um número e armazene na variável `número_mágico` e calcule o número antecessor e sucessor desse número, armazenando respectivamente nas variáveis `antecessor` e `sucessor`.

Imprima na tela, usando as variáveis, os 3 números identificando-os.

**exemplo**

```
informe um número
12

-> o antecessor de 12 é 11
-> o sucessor de 12 é 13
```

## Qual a média aritmética de 3 números?

**objetivo**

- Calcular a média aritmética de 3 números.

**descrição**

Construa um algoritmo que armazene 3 valores `999`, `998` e `997` nas variáveis `operando_1`, `operando_2` e `operando_3`. Calcule a média aritmética desses números armazenando na variável `média`.

Imprima na tela, usando as variáveis, a equação e a média.

**variação**

Construa um algoritmo que receba do teclado 3 valores e armazene nas variáveis `operando_1`, `operando_2` e `operando_3`. Calcule a média aritmética desses números armazenando na variável `média`.

Imprima na tela, usando as variáveis, a equação e a média.

**exemplo**

```
informe o 1o operando
15
informe o 2o operando
20
informe o 3o operando
10

-> (15 + 20 + 10) / 3 = 15
```

## Qual o intervalo em dias de uma data?

**objetivo**

- Dado uma data de aniversário e a data atual, calcular a idade em dias.

**descrição**

Construa um algoritmo que:

1. receba do teclado o ano atual e armazene na variável `data_atual_ano`.
2. receba do teclado o ano de nascimento e armazene na variável `data_nascimento_ano`.
3. Calcule o número de dias e armazene na variável `idade_em_dias`.

Considere que :

- todo mês tem 30 dias, consequentemente todo ano tem 360 dias.
- ano atual - ano de nascimento = idade em anos

Imprima na tela, usando as variáveis, a equação e a média.

**exemplo**

```
 informe o ano da data de hoje
 2019
 informe o ano do seu nascimento
 1975

 -> você tem 15840 dias
```

## Conversor de medidas

**objetivos**

- Converter temperatura em Fahrenheit em Celsius

**descrição**

Construa um algoritmo que:

1. receba do teclado a temperatura em Fahrenheit e armazene na variável `fahrenheit`.
2. Calcule o a temperatura em Celsius e armazene na variável `celcius`. `celcius = 5 * (fahrenheit - 32) / 9`.

Imprima na tela, usando as variáveis, tanto a temperatura em Fahrenheit quanto em Celcius.

**variação**

Existem diversas outras medidas que podem ser usadas para fazer conversão de valores. Alguns exemplos:

1. Conversão de Celcius em Fahrenheit;
2. [Conversão de Metros em Pés](https://www.metric-conversions.org/pt/comprimento/metros-em-pes.htm);
3. [Conversão de metros em polegadas](https://www.metric-conversions.org/pt/comprimento/metros-em-polegadas.htm)
4. [Conversão de metros quadrados em hectares](https://www.metric-conversions.org/pt/area/quadrado-medidores-em-hectares.htm)
5. [Quilôpmetro para milhas](https://www.metric-conversions.org/pt/comprimento/quilometros-em-milhas.htm)
6. [Quilômetro por hora em velocidade da luz](https://convertlive.com/pt/u/converter/velocidade-da-luz/em/quilômetro-por-hora)

**exemplo**

```
informe a temperatura em fahrenheit
100

-> 100 graus Fahrenheit corresponde a 37.78 graus Celcius
```
