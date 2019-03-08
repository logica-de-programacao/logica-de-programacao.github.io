---
layout: default
---

# [](#header-1) Aula 01 Meu primeiro jogo

## [](#header-2) Sumário

1. [Definição do problema](#problem)
2. [Objetivos](#goals)
3. [Solução](#solution)
4. [Códigos-fonte](#src)
5. [Avaliações](#exams)

## [](#problem) Definição do problema

O jogador deve acertar o número mágico do jogo.

## [](#goals) Objetivos

1. Meu primeiro jogo
   - entender a mecânica
2. Interação básica com usuário
   - leitura de dados pelo teclado, e
   - mostrar informações no monitor
3. Tipos e variáveis
   - Uso de tipo numérico inteiro

## [](#solution) Solução

Passos:

1. O jogo mostra texto informativo sobre o jogo.
2. O jogo solicita o nome do jogador e dá boas vindas.
3. O jogo gera um número aleatório do jogo.
4. O jogo solicita ao jogador um número.
5. O jogo compara os números do jogo e do jogador, informando quem ganhou o jogo.

## [](#src) Códigos-fonte

**1ª Versão** :: _1. O jogo mostra texto informativo sobre o jogo._

```potigol
escreva "Jogo adivinhe o número mágico"
escreva "Este jogo você tenta adivinar o número mágico"
```

**como executar**

```sh
potigol numero-magico.poti
```

**2ª Versão** :: _2. O jogo solicita o nome do jogador e dá boas vindas._

```potigol
escreva "Jogo adivinhe o número mágico"
escreva "Este jogo você tenta adivinar o número mágico"

escreva "Qual o seu nome?"
nome = leia_texto
escreva "Bem vindo {nome}"

```

**3ª Versão** :: _3. O jogo gera um número aleatório do jogo._

```potigol
escreva "Jogo adivinhe o número mágico"
escreva "Este jogo você tenta adivinar o número mágico"

escreva "Qual o seu nome?"
nome = leia_texto
escreva "Bem vindo {nome}"

magico = aleatório(minimo,maximo)

```

**4ª Versão** :: _4. O jogo solicita ao jogador um número._

```potigol
escreva "Jogo adivinhe o número mágico"
escreva "Este jogo você tenta adivinar o número mágico"

escreva "Qual o seu nome?"
nome = leia_texto
escreva "Bem vindo {nome}"

magico = aleatório(1,100)

escreva "Qual o seu palpite entre 1 e 100?"
numero = leia_inteiro
```

**5ª Versão** :: _5. O jogo compara os números do jogo e do jogador, informando quem ganhou o jogo._

```potigol
escreva "Jogo adivinhe o número mágico"
escreva "Este jogo você tenta adivinar o número mágico"

escreva "Qual o seu nome?"
nome = leia_texto
escreva "Bem vindo {nome}"

magico = aleatório(1,100)

escreva "Qual o seu palpite entre 1 e 100?"
numero = leia_inteiro

escreva "{nome}, seu número foi {numero}"
escreva "O meu número foi {magico}"
```

**Constantes** no lugar de valores literais

```potigol
escreva "Jogo adivinhe o número mágico"
escreva "Este jogo você tenta adivinar o número mágico"

escreva "Qual o seu nome?"
nome = leia_texto
escreva "Bem vindo {nome}"

minimo = 1
maximo = 100
magico = aleatório(minimo,maximo)

escreva "Qual o seu palpite entre {minimo} e {maximo}?"
numero = leia_inteiro

escreva "{nome}, seu número foi {numero}"
escreva "O meu número foi {magico}"
```

## [](#exams) Avaliações

**como entregar as avaliações**

1. Fazer o _fork_ do repositório https://github.com/logica-de-programacao/2019-potigol.git no Github
2. Criar um diretório pessoal com seu nome

### [](#exam-low) Avaliação fácil

**Tarefa**:

1. Ligar a máquina no Linux e entrar com a conta `aluno`
2. Exectuar o editor de código-fonte `Atom`
3. Criar um diretório local com seu nome
4. Dentro do diretório, criar um arquivo `numero-magico-v1.poti`
5. Digitar a 5ª versão do código-fonte acima
6. Executar o terminal (`gnome-terminal`)
7. Acessar diretório (comando `cd`)
8. Executar o arquivo criado (`potigol numero-magico-v1.poti`)
9. Salvar o arquivo no github (usando um navegador)
10. Salvar a tela do terminal no github (usando o navegador `numero-magico-v1.png`)

### [](#exam-med) Avaliação nível médio

**Tarefa** :

1. Executar o editor de código-fonte `Atom`
2. Se não existir, criar um diretório local com seu nome
3. Dentro do diretório, criar um arquivo `numero-magico-invertido.poti`
4. Implementar código-fonte para solução abaixo
5. Executar o terminal (`gnome-terminal`)
6. Acessar diretório (comando `cd`)
7. Executar o arquivo criado (`potigol numero-magico-invertido.poti`)
8. Salvar o arquivo no github (usando um navegador)
9. Salvar a tela do terminal no github (usando o navegador `numero-magico-invertido.png`)

**problema** : O jogo deve acertar o número do jogador.

**solução** :

1. O jogo mostra texto informativo sobre o jogo.
2. O jogo solicita o nome do jogador e dá boas vindas.
3. O jogo solicita ao jogador um número.
4. O jogo gera um número aleatório do jogo.
5. O jogo compara os números do jogo e do jogador, informando quem ganhou o jogo.

### [](#exam-med) Avaliação nível alto

**Tarefa** :

2. Executar o editor de código-fonte `Atom`
3. Se não existir, criar um diretório local com seu nome
4. Dentro do diretório, criar um arquivo `advinhar-caractere.poti`
5. Implementar código-fonte para solução abaixo
6. Executar o terminal (`gnome-terminal`)
7. Acessar diretório (comando `cd`)
8. Executar o arquivo criado (`potigol advinhar-caractere.poti`)
9. Salvar o arquivo no github (usando um navegador)
10. Salvar a tela do terminal no github (usando o navegador `advinhar-caractere.png`)

**problema** : O jogador deve acertar os 6 caracteres mágicos do jogo

**obs** como converter números em caracteres

```potigol
escreva 97.caractere # escreverá a letra a

letra_a = 97
letra_z = 122
escreva "{letra_a} na tabela ASCII corresponde a letra {letra_a.caractere}"
escreva "{letra_z} na tabela ASCII corresponde a letra {letra_z.caractere}"
```

[Sobre tabela ASCII](https://pt.wikipedia.org/wiki/ASCII)
