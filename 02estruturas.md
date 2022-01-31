# Conceitos iniciais sobre estrutura de dados, arrays e registro

## 1.   O que é estrutura de dados

​        Estrutura de Dados é uma estrutura organizada de dados na memória de um computador ou em qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados de forma correta.

​        Essas estruturas encontram muitas aplicações no desenvolvimento de sistemas, sendo que algumas são altamente especializadas e utilizadas em tarefas específicas.

​        Usando as estruturas adequadas através de algoritmos, podemos trabalhar com uma grande quantidade de dados, como aplicações em bancos de dados ou serviços de busca.

### Algoritmo

​        Um algoritmo é um conjunto de **instruções estruturadas e ordenadas**, seu objetivo é **realizar uma tarefa ou operação específica**.

​        Os algoritmos são utilizados para manipular dados nas estruturas de várias formas, como por exemplo: inserir, excluir, procurar e ordenar dados.

​        Em uma estrutura de dados devemos saber como realizar um determinado conjunto de operações básicas, como por exemplo:

·     Inserir dados

·     Excluir dados

·     Localizar um elemento

·     Percorrer todos os itens constituintes da estrutura para visualização

·     Classificar, que se resume em colocar os itens de dados em uma determinada ordem (numérica, alfabética etc.)

### Principais Estruturas de Dados

§ Vetores e Matrizes (também chamada de Arrays)

§ Registro

§ Lista

§ Pilha

§ Fila

§ Árvore

§ Tabela Hash

§ Grafos

## 2.   Vetores e matrizes (Também conhecida como Arrays)

​        Vetores e Matrizes ou Arrays são estruturas de dados simples que podem auxiliar quando há muitas variáveis do mesmo tipo em um algoritmo.

*Ao invés de criar uma variável para cada nome (nome1, nome2, nome3), você cria uma variável nomes e coloca dentro dela esses valores, através de um vetor*.

 

### Vetores

​        Vetor ou array uni-dimensional é uma variável que armazena várias variáveis do mesmo tipo.

​        O vetor é uma estrutura de dados indexada (possuí índice do 0 até onde você limitar), que pode armazenar uma determinada quantidade de valores do mesmo tipo.

*Declaramos o tipo da variável (inteiro), damos o nome, e entre colchetes [3] colocar quantas posições vamos ter, ou então, deixar em branco, e em seguida, já começar a declarar seus elementos, p.ex: inteiro números [] = {1, 2, 3}, teriam 3 posições.*

 

### Matriz

​        Matriz ou array multi-dimensional é um vetor de vetores.

​        Uma matriz é um vetor que possui duas ou mais dimensões. *É uma tabela.*

 

## 3.   O que são registros

Um Registro é uma estrutura que fornece um formato especializado para armazenar informações em memória. **Os registros são diferentes dos Arrays**. Enquanto Arrays nos permitem armazenar **vários dados de um único tipo de dados**, o recurso de Registro nos permite armazenar **mais de um tipo de dado**.

Um Registro é composto por campos que especificam cada uma das informações que o compõem. Ex.:

| CPF      |      |
| -------- | ---- |
| Nome     |      |
| Endereço |      |
| Contato  |      |

 

Toda estrutura de registro tem um nome (ex: livro), e seus campos podem ser acessados por meio do uso do operador ponto (.). Por exemplo, para acessar o preço de um livro, poderíamos utilizar a seguinte declaração: livro.preço

# Entenda o que são Listas, Pilhas e Filas

## 1.   O que são listas

Estrutura de Dados do tipo Lista, armazena dados de um determinado tipo em uma ordem específica. A diferença entre Listas e Arrays é que as Listas possuem tamanho ajustável, enquanto os Arrays possuem tamanho fixo. Na Lista você pode ir inserindo dados, diferente da Array.

Existem dois tipos de estruturas de lista: Ligadas e Duplamente Ligadas

**- Lista Ligada:** Na estrutura do tipo lista existem os nós (índices) onde cada um dos nós conhece o valor que está sendo armazenado em seu interior além de conhecer o elemento posterior a ele: por isso ela é chamada de “lista ligada”, pois os nós são amarrados com essa indicação de qual é o próximo nó.

![Diagrama  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg) 

O primeiro nó será o último nó até o surgimento do próximo nó, que passará a ser o último. Ela é **flexível**.

 

 

 

 

 

![Texto  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)

**- Lista Duplamente Ligada:** A grande diferença das listas duplamente ligadas para as listas ligadas é que elas são bidirecionais. Vimos que, naturalmente, não conseguimos “andar para trás” em listas ligadas, pois os nós de uma lista ligada sabem somente quem é o próximo elemento. Nas listas duplamente ligadas, os nós sabem quem é o próximo elemento e quem é o elemento anterior, o que **permite a navegação reversa**.

As listas duplamente ligadas constituem uma variação das listas ligadas. Você consegue fazer uma busca anterior ou normal.

![Diagrama  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image006.jpg)

 

## 2.   O que são pilhas

Uma Pilha é uma estrutura de dados que serve como uma coleção de elementos, e permite o acesso a somente um item de dados armazenado.

O acesso aos itens de uma Pilha é restrito – somente um item pode ser lido ou removido por vez.

Existem dois tipos de Pilhas: LIFO OU UEPS e FIFO OU PEPS

**- LIFO OU UEPS:** A estrutura do tipo PILHA LIFO (Last In First Out) ou UEPS (Último que Entra Primeiro que Sai), apresenta o seguinte critério: o primeiro elemento a ser retirado é o último que tiver sido inserido.

![Diagrama  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image008.jpg)

**- FIFO OU PEPS:** A estrutura do tipo PILHA FIFO (First In First Out) ou PEPS (Primeiro que Entra Primeiro que Sai), apresenta o seguinte critério: o primeiro elemento a ser retirado é o primeiro que tiver sido inserido na pilha, empilhamento ou stack.

![Uma imagem contendo Esquemático  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image010.jpg)

 

## 3.   O que são filas

A estrutura do tipo Fila admite remoção e inserção de novos de elementos sujeitos à seguinte regra de operação:

O elemento removido é o que está na estrutura há mais tempo, ou seja, o primeiro objeto inserido na fila é também o primeiro a ser removido seguido o conceito FIFO.

![Tabela  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image012.jpg)

 

 

# Estrutura de dados do tipo Árvore, Tabela Hash e Grafos

## 1.   O que são árvores

*É uma estrutura organizada de forma hierárquica.*

É uma estrutura de dados que organiza seus elementos de forma hierárquica, onde existe um elemento que fica no topo da árvore, chamado de raiz, e existem os elementos subordinados a ele, que são chamados de nós ou folhas.

*Na estrutura vetor, a busca procura o elemento em cada posição até encontra-lo, o que pode tornar a busca mais lenta.*

 

Ex.: Estrutura de Vetor

![Desenho de bandeira  Descrição gerada automaticamente com confiança média](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image014.jpg)

Estrutura de Árvore

![Mapa com ruas e árvores  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image016.jpg)

 

## 2.   O que são tabelas hash

Uma tabela hash, de dispersão ou espalhamento é uma estrutura de dados especial, que associa chaves de pesquisa a valores.

Uma tabela hash é uma generalização da ideia de array, porém utiliza uma função denominada Hashing para espalhar os elementos, fazendo com que os mesmos fiquem de forma não ordenada dento do “array” que define a tabela.

![Diagrama  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image018.jpg)

**- Por que espalhar?**

A tabela hash permite a associação de “valores” a “chaves”.

Valores: é a posição ou índice onde o elemento se encontra;

Chave: parte da informação que compõe o emento a ser manipulado.

 

​        Espalhar facilita a busca na estrutura de dados, pois a partir de uma chave podemos acessar de forma rápida uma posição do “array”.

 

## 3.   O que são grafos

Grafos são estruturas que permitem **programar a relação entre objetos**.

Os objetos são vértices ou “nós” do grafo.

Os relacionamentos são arestas.

 

![Forma  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image020.jpg) ![Forma  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image022.jpg)

![Diagrama, Forma  Descrição gerada automaticamente](file:///C:/Users/breno/AppData/Local/Temp/msohtmlclip1/01/clip_image024.jpg)

 

 