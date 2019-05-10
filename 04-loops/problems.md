# Exercícios: estrutura de repetição <!-- omit in toc -->

**Problemas**:

- [Qual a área da figura?](#qual-a-%C3%A1rea-da-figura)
- [Quero calcular área do quadrado](#quero-calcular-%C3%A1rea-do-quadrado)
- [Número primo](#n%C3%BAmero-primo)
- [Somar digitos](#somar-digitos)
- [Jogo dos números felizes](#jogo-dos-n%C3%BAmeros-felizes)

## Qual a área da figura?

**objetivo**

- Repetir 10 vezes o cálculo da área do quadrado

**descrição**

As figuras planas são: triângulo, quadrado, retângulo, losango, trapézio e círculo.
Informações sobre cálculo da [área de figuras planas](https://www.todamateria.com.br/areas-de-figuras-planas/).
Em específico, a área do quadrado é calculado pela fórmula `área = lado * lado` e o algoritmo inicial abaixo calcula a área de quadrado com tamanho de seu lado definido aleatoriamente.

```scala
var lado := aleatório(1,100)
var contador := 1

escreva "a área do {contador}º quadrado é {lado * lado}"
```

Complementar o algoritmo acima para que calcule `10` áreas de quadrados de lados com tamanhos aleatórios.
Por fim, imprima na tela o número, o tamanho do lado e da área de cada quadrado.

**solução 1**

```scala
para contador de 1 até 10 passo 1 faça
  var lado := aleatório(1,100)
  escreva "{contador}º quadrado lado={lado} área={lado * lado}"
fim
```

**solução 2**

```scala
var contador := 1

enquanto contador <= 10 faça
  var lado := aleatório(1,100)
  escreva "{contador}º quadrado lado={lado} área={lado * lado}"
  contador := contador + 1
fim
```

## Quero calcular área do quadrado

**objetivo**

- Perguntar ao usuário se deseja calcular área do quadrado

**descrição**

As figuras planas são: triângulo, quadrado, retângulo, losango, trapézio e círculo.
Informações sobre cálculo da [área de figuras planas](https://www.todamateria.com.br/areas-de-figuras-planas/).
Em específico, a área do quadrado é calculado pela fórmula `área = lado * lado` e o algoritmo inicial abaixo calcula a área de quadrado com tamanho de seu lado definido aleatoriamente.

```scala
var lado := aleatório(1,100)
var contador := 1

escreva "a área do {contador}º quadrado é {lado * lado}"
```

Complementar o algoritmo acima, calculando a área do 1º quadrado e para os demais perguntando se o usuário deseja calcular.
Para cada quadrado, imprima na tela o número, lado e área do quadrado.

**solução**

```scala
var contador := 1
var continuar := 0

enquanto continuar == 0 faça
  var lado := aleatório(1,100)
  escreva "{contador}º quadrado lado={lado} área={lado * lado}"
  contador := contador + 1
  escreva "digite 0 para continuar e outro valor para parar"
  continuar := leia_inteiro
fim
```

## Número primo

**objetivo**

- dado um número, verificar se ele é primo contando os algoritmos que fazem uma divisão com resto igual a `0`

**descrição**

Faça um algoritmo para identificar se um número (aleatório) é primo.

Lembre-se que número primo, é um número natural, maior que 1, apenas divisível por si próprio e pela unidade.

**Comentários**:

Os problemas (e as soluções) envolvendo os números primos são fascinantes e não é objetivo deste artigo esgotar o assunto, muito pelo contrário, o objetivo é simplesmente ser a porta de entrada, o primeiro degrau.

Outro ponto a comentar é a questão dos testes, você verá que é difícil determinar o quanto de testes seriam suficientes para garantir o correto funcionamento do algoritmo.

## Somar digitos

**objetivo**:

- fazer uma estrutura de repetição para calcular separar os digitos de um número
- fazer o somatório dos digitos

**descrição**:

Faça um algoritmo para somar os dígitos de um inteiro.
Não utilizar recursos de string, ou seja, trabalhe apenas com tipos numéricos.

**exemplo**

```
número 2015
digitos 2 0 1 5
a soma de 2015 é igual a 8
```

## Jogo dos números felizes

[fonte](http://dojopuzzles.com/problemas/exibe/numeros-felizes/)

_nível_: difícil

Para saber se um número é feliz, você deve obter o quadrado de cada dígito deste número, em seguida você faz a soma desses resultados.
A seguir o mesmo procedimento deve ser feito com o valor resultante desta soma.
Se ao repetir o procedimento diversas vezes e obtivermos o valor 1, o número inicial é considerado feliz.

Exemplo, tomemos o número 7, que é um número feliz:
7² = 49
4² + 9² = 97
9² + 7² = 130
1² + 3² + 0² = 10
1² + 0² = 1

Podemos observar nesse exemplo que os números 49, 97, 130 e 10 também são felizes.
Existem infinitos números felizes.

E um número triste? Como sabemos que um número não será feliz?
Desenvolva um programa que determine se um número é feliz ou triste.
