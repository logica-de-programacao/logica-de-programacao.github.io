# Exercícios: estrutura de decisão <!-- omit in toc -->

- [Qual a área da figura?](#qual-a-%C3%A1rea-da-figura)
- [O ano é bissexto?](#o-ano-%C3%A9-bissexto)
- [Qual o intervalo em dias de uma data?](#qual-o-intervalo-em-dias-de-uma-data)


## Qual a área da figura?

**objetivo**

- Calcular área de figuras planas

**descrição**

As figuras planas são: triângulo, quadrado, retângulo, losango, trapézio e círculo.
Informações sobre cálculo da [área de figuras planas](https://www.todamateria.com.br/areas-de-figuras-planas/).

Faça um algoritmo que receba do teclado um texto e armazene na variável `figura`, informando qual a figura plana usada para calcular a área.
De acordo com a figura, receba do teclado os valores correspondentes para calcular a área da figura e armazene em variáveis.
Exemplo, uma vez informado `quadrado` para a figura, receber do teclado o valor do lado do quadrado e armazenar o valor na variável `lado`. 
Calcular a àrea pela equação `lado * lado` e armazenar o valor na variável `área`.

Por fim, imprima na tela a equação e a área, usando as variáveis.

**exemplo**

```
qual a figura plana deseja calcular a área
quadrado
informe o lado do quadrado
12

-> área do quadrado é 144 = 12 * 12 
```

## O ano é bissexto?

**objetivo**

- Calcular se um ano é [bissexto](https://pt.wikipedia.org/wiki/Ano_bissexto)

**descrição**

Faça um algoritmo que receba do teclado o ano e armazene na variável `ano`.
Calcule se o ano informado é bissexto e armazene na variável lógica `bissexto`.

Imprima no final se o ano é bissexto ou não.

**exemplo**

```
informe o ano
2019
-> 2019 não é bissexto
```

```
informe o ano
2020
-> 2020 é bissexto
```

## Qual o intervalo em dias de uma data?

**objetivo**

- Dado uma data de aniversário e a data atual, calcular a idade em dias.

**descrição**

Construa um algoritmo que: 
1. receba do teclado o ano, mês e dia da data atual e armazene nas variáveis `data_atual_ano`, `data_atual_mês`, e `data_atual_dia`.
2. recebe do teclado o ano, mês e dia de nascimento e armazene nas variáveis `data_nascimento_ano`, `data_nascimento_mês`, e `data_nascimento_dia`.
3. Calcule o número de dias e armazene na variável `idade_em_dias`.

Para efeito de simplificação, considere que todo mês tem 30 dias e portanto o ano tem 360 dias.
Imprima na tela a idade.

**variação**

para cálculo dos números de dias, considere: 
1. meses de 31, 30, 28 e 29 dias.
2. [anos bissextos](https://pt.wikipedia.org/wiki/Ano_bissexto).

Imprima na tela a idade.

**exemplo**

```
informe o ano da data de hoje
2019
informe o número mês da data de hoje
4
informe o dia da data de hoje
10
informe o ano do nascimento
1975
informe o número mês do nascimento
5
informe o dia do nascimento
1
 
-> você tem dias 
```
 