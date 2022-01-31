# Introdução à lógica e a à programação

## 1.   Entendendo o que é lógica

### Objetivos da aula

**a)**   **Entender o que é lógica e lógica de programação**

Lógica é coerência de raciocínio, de ideias, é a sequência coerente, regular e necessária de acontecimentos;

Lógica de programação significa apenas contextualizar a lógica na programação de computadores, buscando a melhor sequência de ações (na programação chamamos de **algoritmo**), para solucionar um problema.

**b)**   **Entender e criar um mapa mental para resolução de problemas**

\- Metacognição: “pensar como você pensa”, vamos utilizá-la para criar o mapa mental e traçar o passo a passo para resolver o problema.

Ex: Você vai comprar uma blusa e descobre que se comprar duas camisetas, ganha 20% de desconto na compra, quanto vai pagar?

| Camiseta 1 | Camiseta 2 | Total  | Desconto | Desconto R$ | Preço a pagar |
| ---------- | ---------- | ------ | -------- | ----------- | ------------- |
| 50,00      | 50,00      | 100,00 | 20%      | 20,00       | 80,00         |

 

**c)**    **Entender o que é uma abstração**

Abstração é a habilidade de concentrar nos aspectos essenciais de um contexto qualquer, ignorando características menos importantes ou acidentais. 

 

## 2.   O que são algoritmos e pseudocódigos

### Objetivos da aula

**a)**   **Entender o que é um algoritmo**

É uma sequência de passos que resolve um problema. Ex.:

Início-dia: 

​        Acordei

​        Levantei da cama

​        Troquei de roupa

​        Escovei os dentes

​        Fui a padaria

​        Tomei café

...

​        Fim-dia

​        Todos os programas são uma sequência de passos e instruções. A ordem de passos é muito importante.

**b)**   **Entender o que é um pseudocódigo**

Pseudocódigo é uma forma genérica de escrever um algoritmo, utilizando uma linguagem simples (nativa, ou seja, em português a quem o escreve, de forma a ser entendida por qualquer pessoa).

https://studio.code.org/s/mc/stage/1/puzzle/1

https://rachacuca.com.br/jogos/pinguins-numa-fria/

 

## 3.   Aprendendo fluxograma, variáveis e constantes

### Objetivos da aula

**a)**   **Entender o que é fluxograma (**[**http://www.flowgorithm.org**](http://www.flowgorithm.org)**)**

Fluxograma é uma ferramenta utilizada para representar graficamente o algoritmo, isto é, a sequência lógica do **fluxo de dados**.

![Diagrama  Descrição gerada automaticamente com confiança média](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image001.png)

 

 

 

 

 

**NÃO EXISTE UM PADRÃO DE BLOCOS, MAS ELES SEGUEM O MESMO PADRÃO DENTRO DAQUELE FLUXOGRAMA PARA REPRESENTAR O MESMO MÉTODO.**

 

 

 

 

 

 

 

 

 

 

Também pode ser definido como um tipo de diagrama e pode ser entendido como uma representação esquemática de um processo. Podemos entendê-lo, na prática, como a documentação dos passos necessários para a execução de um **processo qualquer**.

 

**b)**   **Aprender sobre variáveis, constantes e tipos de dados**

a.    O que são variáveis?

“Na programação, uma variável é um objeto (uma posição, frequentemente localizada na memória) capaz de reter e representar um valor ou uma expressão”.

“Uma variável é um espaço na memória do computador destinado a um dado que é alterado **durante a execução do algoritmo**”.

​                                i.   Declaração de variáveis (não aceitam espaço; não podem iniciar com números; devem ser evitados acentos, alguns programas aceitam, mas a universalidade, não.)

As variáveis devem ser declaradas antes de serem chamadas na execução do programa. Devemos atribuir seu tipo, e, em seguida, atribuímos seu valor (através do usuário), executamos a função, e, em seguida, sua saída, se for a intenção.

​                               ii.   Tipos de variáveis: as variáveis podem ser classificadas basicamente de quatro tipos:

·     Numérica, que podem ser inteiras, pode ser decimal ou pode ser real;

·     Caracteres;

·     Alfanuméricas, podem receber letras e números (nomes); ou,

·     Lógicas (verdadeira ou falsa).

 

b.    O que é uma constante?

As constantes são valores imutáveis e não são alterados durante a vida útil do programa.

## 4.   Tomadas de decisões e expressões

### Objetivos da aula

**a)**   **Conhecer as expressões aritméticas, literais e as expressões relacionais**

a.         Expressões aritméticas: São expressões que utilizam operadores aritméticos e funções aritméticas envolvendo constantes e variáveis. Seguem os principais **operadores aritméticos**:

| Soma          | +    |
| ------------- | ---- |
| Subtração     | -    |
| Multiplicação | *    |
| Divisão       | /    |
| Potenciação   | ^    |
| Porcentagem   | %    |

 

b.         Expressões literais: São expressões com constantes e/ou variáveis que tem como resultados valores literais. Iremos utilizar as expressões literais na atribuição de valor para uma variável ou constante. Exemplos:

Nome = “José da Silva”

nome ← “José da Silva”

media=(nota1+nota2+nota3+nota4)/4]

*Exemplo de expressões aritméticas e literais*

| **Variáveis** | **Comando de atribuição / operação** | **Procedimento**                                       |       |                                    |
| ------------- | ------------------------------------ | ------------------------------------------------------ | ----- | ---------------------------------- |
| A             | B                                    | C                                                      | A = 2 | Armazenar o  valor 2 na variável A |
|               | B = A + 3                            | Somar o valor  de A (2) com 3 e armazenar em B (5)     |       |                                    |
|               | C = A + B                            | Somar o valor  de A (2) com B (5) e armazenar em C (7) |       |                                    |
|               |                                      |                                                        |       |                                    |

 

c.         Expressões relacionais: São expressões compostas por outras expressões ou variáveis numéricas com operadores relacionais (maior, menor, igual, diferente). As expressões relacionais retornam valores lógicos (verdadeiro / falso). 

Ex. 2 = 1 Falso // 7 < 10 Verdadeiro

| **Operadores relacionais** |                      |                    |                         |
| -------------------------- | -------------------- | ------------------ | ----------------------- |
| **Símbolo**                | **Nome do operador** | **Exemplo**        | **Significado**         |
| >                          | Maior que            | x > y              | x é maior que y?        |
| >=                         | Maior ou  igual      | x >= y             | x é maior ou igual a y? |
| <                          | Menor                | x < y              | x é menor que y?        |
| <=                         | Menor que            | x <= y             | x é menor ou igual a y? |
| **==**                     | **Igualdade\***      | x == y             | x é igual a y?          |
| != ou <>                   | Diferente de         | x != y ou   x <> y | x é diferente de y?     |

*** Um só sinal de igual ( = ) é atribuição de valor a uma variável.**

**b)**   **Entender e aplicar as tomadas de decisões em um algoritmo** 

“Quando escrevemos programas, geralmente ocorre a necessidade de decidir o que fazer dependendo de alguma condição encontrada durante a execução.”

## 5.   Como utilizar a concatenação

### Objetivos da aula

**a)**   **Aprender o que é uma concatenação e como utilizá-la na prática**

Concatenação é um termo usado em computação para designar a operação de unir o conteúdo de duas strings (string é uma sequência de caracteres).

Agrupamento de duas ou mais células que, incluindo fórmulas, textos ou outras informações contidas no seu interior, dá origem a um **único resultado**. 

É muito útil para criar uma exibição para o usuário.

 

# Introdução ao Portugol

## 1.   Aprenda como utilizar uma estrutural de repetição

### Objetivos da aula

**a)**   **Aprender o que é uma estrutura de repetição e como utilizá-la na prática**

Dentro da lógica de programação, é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, **de acordo com uma condição ou com um contador.**

## 2.   O que são linguagens de programação?

### Objetivos da aula

**a)**   **Aprender o que são linguagens de programação**

“Linguagem de Programação é uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para gerar programas (software). Um software pode ser desenvolvido para rodar em um computador, um dispositivo móvel ou em qualquer equipamento que permita sua execução.”

“O que é óbvio para você, certamente não é óbvio para uma máquina. E se você quer que a máquina faça algo para você, você precisa ‘falar com ela’.”

A função das linguagens de programação é servir de um meio de comunicação entre computadores e humanos.

​        *- Linguagem de programação de baixo e alto nível:*

a.         Alto nível: Essas são aquelas cuja sintaxe se aproxima mais da nossa linguagem e se distanciam mais da linguagem de máquina. Ex.: C, PHP, Javascript, C#, C++, Python, Java

b.         Baixo nível: É aquela que se aproxima mais da linguagem de máquina. Essas são as que você precisa ter o conhecimento direto da arquitetura do computador para fazer alguma coisa. Ex: Assembly

​        *- Linguagem de programação compiladas ou interpretadas:*

a.         Compiladas: É uma linguagem de programação em que o código fonte é executado diretamente pelo sistema operacional ou pelo processador, após ser traduzido por meio de um processo chamado compilação. Exemplo: C#, transforma em EXE

b.         Interpretadas: É uma linguagem de programação em que o código fonte é executado por um programa de computador chamado interpretador que em seguida é executado pelo sistema operacional ou processador. Ex: Javascript, e as linguagens de internet, os browsers fazer essa interpretação.

 

**b)**   **Introdução ao Portugol (Utilizando pseudocódigos na prática)**

“Portugol é uma pseudolinguagem que permite ao leitor desenvolver algoritmos estruturados em português de forma simples e intuitiva, independentemente de linguagem de programação.”

“É uma pseudolinguagem que permite ao programador pensar no problema em si, e não no equipamento que irá executar o algoritmo.”

https://github.com/UNIVALI-LITE/Portugol-Studio/releases/

Real – números com decimais

Caracter – recebe 1 letra

Cadeia – é a string, uma cadeia de caracteres

“Escreva” – é a saída de dados na tela; “Leia” recebe os dados na variável.

Para concatenar, aqui utilizamos o “+”

“\n”+ – para quebra de linhas

## 3.   Aprenda a utilizar desvios condicionais e boas práticas em programação

### Objetivos da aula

**a)**   **Aprender a utilizar os desvios condicionais (estruturas de decisão) no Portugol**

\- Desvio condicional

**- se**: é utilizada a palavra reservada (é utilizada para uma função do código) **se**, a condição a ser testada entre parênteses e as instruções que devem ser executadas entre chaves caso o desvio seja **verdadeiro**.

​        Exemplo: se (media>=7) {

​                        escreva(“Parabéns!! Você foi aprovado!!”)  Nesse caso, caso o retorno seja negativo, o programa encerrará.

**- se-senao**: agora vamos imaginar que se a condição for **falsa** um outro conjunto de comandos deve ser executado. Quando iremos encontrar esta situação?

Exemplo: se (media>=7) {

​                        escreva(“Parabéns!! Você foi aprovado!!”)

​                }

​                senao {

​                        escreva(“Infelizmente você foi reprovado!”)

 

​        **- caso:** este comando é similar aos comandos **se** e **senao**, e reduz a complexidade na escolha de diversas opções. Apesar de suas similaridades com o **se**, ele possui algumas diferenças. Neste comando não é possível o uso de operadores lógicos, ele apenas trabalha com valores definidos.

​                Este comando deve ser utilizado junto com a função **escolha**, a função **pare**, e, a função **caso contrário**.

**b)**   **Boas práticas de programação – Comentários**

No Portugol utilizamos o “//” para deixar comentários. Utilizamos para deixar um lembrete, uma mensagem para o programador. Ele não é exibido

## 4.   Trabalhando com laços de repetição em Portugol

### Objetivos da aula

**a)**   **Aprender a utilizar os laços de repetição no Portugol**

Dentro da lógica de programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou com um **contador**.

Ex:

funcao inicio ()

{

​        inteiro contador, limite, resultado

​        contador = 0

​        limite = 10

​        faca

​        {

​                resultado = 9 * contador

​                escreva (“9 X “ + contador + “=” + resultado + “\n”)

​                contador ++

​        } enquanto ( contador <= limite )

}

## 5.   Aplicação com matrizes e vetores

### Objetivos da aula

**a)**   **Aprender o que é uma matriz e um vetor e entender a sua aplicação prática**

Uma **matriz** é uma coleção de variáveis **de mesmo tipo (cadeia, inteiro, caracteres)**, acessíveis com um único nome e armazenados contiguamente na memória.

A individualização de cada variável de um vetor é feita através do uso de **índices**.

Os **Vetores** são matrizes de uma só dimensão.

 

Exemplo: Portugol Exemplo 4

## 6.   Certifique seu conhecimento