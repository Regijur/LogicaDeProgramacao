# Aprendendo Lógica de Programação
Autor: Reginaldo Mota (O Régis)

Tópicos que serão estudados:
- Algoritmos
- As Vantagens de Usar Computadores
- Linguagens de Programação
- Variáveis
- Operadores
- Coleções
- Controle de Fluxo
- Funções
- Classes

Bônus:
- Aprendendo o básico de Python
- O que um programador faz
- Passo a passo para estudar qualquer tecnologia

## Algoritmos

Todo passo a passo é um algoritmo, sempre que uma sequência lógica e padronizada de passos for descrita para a resolução de um problema, estamos lidando com um algortimo.

Exemplo de algoritmo:

Pense por exemplo em alguma ação que você faz diariamente, como comer:

1. Pegue um prato
2. Pegue uma colher
3. Coloque a comida no prato com a colher
4. Pegue os talheres de sua preferência
5. Pegue um pouco de comida com o talher
6. Abra a boca
7. Caso a comida esteja quente assopre até que a comida esfrie
8. Coloque a comida dentro da boca
9. Retire o talher da boca sem tirar a comida
10. Mastigue
11. Repita o passo 9 até que a comida esteja bem esmagada
12. Engula
13. Repita os passos 5 a 11 até que não reste mais comida no prato ou não haja mais fome ou vontade de comer

Isso é um algoritmo para comer, um passo a passo, note que caso você inverta a posição de um passo, já não vai funcionar, troque o 6 pelo 8 e você irá derramar comida na mesa, pois sua boca ainda estará aberta.

Sei que é um exemplo bobo, porém é exatamente isso, o conceito de algoritmo é bem simples, que até um exemplo bobo é completo para demonstrar o conceito

## As Vantagens de Usar Computadores

A capacidade do ser humano de processar informações é incrível, o cérebro humano é algo misterioso que funciona muito bem.

No entanto, ele é muito bom em fazer muitas coisas ao mesmo tempo, e muitas dessas coisas são cruciais para a nossa vida.

Já para tarefas relacionadas com cálculos, análises, coisas que lidam com muita informação simultâneamente e coisas muito específicas, o cérebro também consegue trabalhar, no entanto não de uma forma muito eficiente.

É nesse momento onde percebemos a grande utilidade dos computadores, ferramentas que são excelentes em trabalhar com situações onde a especificidade é um diferencial.

O computador é a ferramenta que utilizamos para resolver problemas específicos e padronizados. Facilitando a vida do ser humano.

## Linguagens de Programação

Uma linguagem de programação é a forma como dizemos ao computador o que ele deve fazer, todo algoritmo feito para um computador deve ser escrito em uma linguagem de programação.

Cada linguagem irá definir a sua sintaxe, igual em linguagens mesmo, inglês, português, alemão, italiano, russo, enfim, qualquer linguagem foi desenvolvida para resolver o mesmo problema que é o de traduzir o mundo em palavras.

Simplificar e retirar ambiguidades, permitindo que todos possam se comunicar e transmitir informações de uma forma rápida, clara e eficiente.

Linguagens de programação tem esse mesmo intuito, no entanto os agentes são diferentes, em vez da comunicação ser entre duas pessoas, se dá entre uma pessoa e uma máquina (computador).

Existem diversas linguagens:
- Python
- JavaScript
- TypeScript
- Java
- C#
- C++
- C
- PHP
- Ruby
- R
- Dart
- Pascal
- E várias outras

Porém, apesar da infinidade de linguagens existentes, todas elas possuem o mesmo objetivo, que é o de permitir a comunicação entre pessoa e máquina. E para isso todas possuem características em comum que formam a base das linguagens. E essas semelhanças é o que forma a base que chamamos de lógica de programação, que é o que realmente deve ser focado no início.

Não foque em aprender 100% de uma linguagem, foque na base, na lógica de programação, pois uma vez que você aprende a lógica você consegue facilmente compreender qualquer linguagem que quiser.

## Variáveis

> O grande foco de qualquer forma de comunicação é a transmissão de informações. 

Isso não é diferente nas linguagens de programação, troca de informações é o que faz com que tudo faça sentido.

Logo transmitir informações para o computador e manipular essas informações se torna o foco principal de qualquer programa.

E essas informações devem ser armazenadas para que possam ser utilizadas, pois de outra forma toda vez que fosse necessário utilizar essa informação a pessoa precisaria fornecer novamente, o que acaba com a vantagem dos computadores de serem independentes de nós durante o processamento das informações.

Para isso que existem as variáveis, que são apelidos que nós fornecemos para endereços de memória que irão armazenar uma informação específica.

Com essa informação armazenada e relacionada a um apelido, sempre que chamarmos esse apelido durante a conversa com o computador ele entederá do que estamos falando.

### Nomeando variáveis

Um ponto importante que deve ser dada a devida atenção é na nomenclatura dessas variáveis, pois como é um apelido, o computador entende qualquer coisa, então colocar o nome de uma variável de ***a1234*** é totalmente possível no entanto é uma péssima prática, pois quando uma outra ler esse código ela não conseguirá compreender do que se trata essa variável de forma fácil.

Já variáveis denominadas ***media_final_do_aluno***, ***nome_do_usuario***, ***email_do_professor*** e ***posicao_do_jogador***, são exemplos de nomes que descrevem bem o que essas variáveis estão armazenando.

Lembre-se:
> “Qualquer um pode escrever um código que o computador entenda. Bons programadores escrevem códigos que os humanos entendam.” – Martin Fowler

### Tipos de Variáveis

Essas variáveis por sua vez, podem armazenar tipos de dados diferentes. E esses tipos são justamente o que elas estão armazenando, e certas linguagens que possuem o que chamamos de tipagem forte possuem formas específicas de declarar cada um dos tipos de variáveis.

Os tipos existentes:
- Char (caracteres)
- Int (números inteiros)
- Float (números ponto flutuante / decimais)
- Double (números decimais)
- Bool* (booleanos / verdadeiro e falso)
- Strings* (texto)
- Structs* (tipo abstrato de dado)
- Uint* (números inteiros positivos)
- Entre outros

> Os tópicos com * (asterístico) existem em algumas linguagens e em outras não

As linguagens variam em quais tipos existem, e como é feita a manipulação desses tipos. Existem linguagem com tipagem dinâmica, como Python e JavaScript, que no caso do Python nem precisam de uma palavra reservada para serem declaradas. Já em JavaScript ainda existem os declaradores ***var, let e const*** que são utilizados para todos os tipos de variáveis e sua diferença se encontra na maneira de manipular essas informações.

## Operadores
Operadores nada mais são do que ferramentas no código que manipulam as variáveis, ou informações no geral. E se dividem em três tipos principais, os operadores:

- Aritméticos
- Atribuição
- Comparação
- Lógicos
- Identidade*
- Associação*

> Os marcados com * não são obrigatoriedade em todas as linguagens.

### Operadores Aritméticos

São todos os operadores relacionados com cálculos, somar, subtrair, dividir, multiplicar, todos os operadores relacionados com cálculos matemáticos de manipulação de números.

#### Tabela de Operadores Aritméticos em Python
|Símbolo|Função|Exemplo|Retorno|
|:---:|:-:|:-:|:-:|
|+|Soma dois valores|2 + 5 |7|
|-|Subtrai dois valores| 2 - 5 ou -1|-3 ou -1|
|*|Multiplica dois valores| 2 * 5|10|
|/|Divide dois valores| 10 / 2 | 5|
|//|Divisão inteira| 5 // 2 | 2 |
|%| Resto da divisão | 5 % 2 | 1 |
|**| Exponenciação | 5**2| 25|

### Operadores de Atribuição
São aqueles operadores responsáveis por atribuir valores para variáveis.

#### Tabela de Operadores de Atribuição em Python
|Símbolo|Função|Exemplo|
|:-:|:-:|:-:|
|=|Atribui um valor a uma variável, reescrevendo o valor da mesma|media_final = 10.0|
|+=|Soma um valor ao que já existe na variável e atribui para a variável original| ciclo += 1|
|-=|Subtrai um valor ao que já existe na variável e atribui para a variável original| tempo_do_cronometro += 1|
|*=|Multiplica o valor da variável por um outro valor e atribui para a variável original|capital *= 1.08|
|/=|Divide o valor da variável por um outro valor e atribui para a variável original|tempo_total /= 2|
|%=|Retorna o resto da divisão do valor da variável por um outro valor e atribui para a variável original|par_ou_impar %= 2|

### Operadores de Comparação

Responsáveis por comparar dois valores

#### Tabela de Operadores de Comparação em Python
|Nome|Símbolo|Função|Exemplo|Retorno|
|:-:|:-:|:-:|:-:|:-:|
|Maior que|>|Verifica se um valor é maior que outro|2 > 7|False|
|Menor que|<|Verifica se um valor é menor que outro|2 < 7|True|
|Igual a|==|Verifica se um valor é igual a outro|2 == 7|False|
|Diferente de|!=|Verifica se um valor é diferente de outro|2 != 7|True|
|Maior ou igual a|>=|Verifica se um valor é maior ou igual a outro|2 >= 2|True|
|Menor ou igual a|<=|Verifica se um valor é menor ou igual a outro|2 <= 7|True|

### Operadores Lógicos
Responsáveis por executar funções lógicas booleanas, por exemplo saber se duas condições são verdadeiras simultâneamente, ou pelo menos uma das duas é verdadeira, ou falsa.

#### Tabela de Operadores Lógicos em Python
|Nome|Símbolo|Função|Exemplo|Retorno|
|:-:|:-:|:-:|:-:|:-:
|Operador E|and|	Retorna True se todas as condições forem verdadeiras, caso contrário retorna False|	3 > 1 and 3 < 5| True|
|Operador Ou|or|	Retorna True se uma das condições for verdadeiras, caso contrário retorna False	|1 < 3 or 1 > 5| True|
|Operador de negação|not|	Inverte o resultado: se o resultado da expressão for True, o operador retorna False	|not (3 > 1 and 3 < 5)| False|

### Operadores de Identidade
São operadores da linguagem Python que permitem que seja feita uma verificação de identidade.
```python
#autor: Reginaldo Mota (O Régis)

class Pessoa:
    def __init__(self, nome, idade):
        self.nome = nome
        self.idade = idade

Reginaldo1 = Pessoa('Reginaldo', 19)
Reginaldo2 = Pessoa('Reginaldo', 19)

print(Reginaldo1 is Reginaldo2) # retorna False
print(Reginaldo1 is not Reginaldo2) # retorna True
print(Reginaldo1.nome == Reginaldo2.nome) # retorna True
print(Reginaldo1.idade == Reginaldo2.idade) # retorna True
```

A identidade funciona da maneira apresentada no bloco acima, veja que apesar dos objetos Reginaldo1 e Reginaldo2 possuírem as mesmas informações de nome e idade, elas são instâncias diferentes e independentes uma da outra.

#### Tabela de Operadores de Identidade em Python
|Nome|Símbolo|Função|Exemplo|
|:-:|:-:|:-:|:-:
|Operador É|is|	Retorna True se as variáveis comparadas forem o mesmo objeto|	nome is ‘Reginaldo’
|Operador Não é|is not|	Retorna True se as variáveis comparadas não forem o mesmo objeto	|nome is not ‘Régis’

### Operadores de Associação
São operadores da linguagem Python que permitem que seja verificado o pertencimento de elementos a uma coleção.
```python
#autor: Reginaldo Mota (O Régis)

nome = 'O Régis'

print('O' in nome) #imprime: True
print('Régis' in nome) #imprime: True
print('A' in nome) #imprime: False
print('F' not in nome) #imprime:True
```

Perceba que in e not in são os dois operadores de associação da linguagem, e eles representam o pertence e não pertence.

No primeiro teste por exemplo `'O' in nome` é o mesmo que perguntar se a letra `O` pertence ao nome `O Régis`.

#### Tabela de Operadores de Associação em Python
|Nome|Símbolo|Função|Exemplo|
|:-:|:-:|:-:|:-:
|Pertence|in|	Retorna True caso o valor seja encontrado na sequência|	'a' in 'amora'
|Não Pertence|not in|	Retorna True caso o valor não seja encontrado na sequência|	'a' not in 'Régis'

## Coleções
Agora que já conhecemos as variáveis e as formas de manipular elas, é importante conhecermos as coleções.

Coleções são conjuntos de informações, e todas linguagem de programação tem pelo menos um tipo coleção chamado de array (vetor) que é como se fosse um tipo de variável que armazena várias variáveis.

Em algumas linguagens, que são fortemente tipadas, os arrays também são tipados e armazenam dados do mesmo tipo.

Em outras linguagens com tipagem dinâmica como JavaScript e Python existem arrays ou listas que podem armazenar valores de tipos diferentes também, apesar de não ser tão comum assim.

Em Python temos as seguintes coleções:
- Listas
- Tuplas
- Sets
- Dicionários

### Listas
É a coleção que armazena informações de maneira ordenada, indexável, mutável e permite duplicação de informação.

```python
#autor: Reginaldo Mota (O Régis)

lista_de_numeros = [ 1, 2, 3, 4, 5, 6, 7, 8, 9 ]

print(lista_de_numeros[3]) #imprime: 4

lista_de_numeros.append(10) 

print(lista_de_numeros) #imprime: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

lista_de_numeros[0] = 42

print(lista_de_numeros) #imprime: [42, 2, 3, 4, 5, 6, 7, 8, 9, 10]

lista_de_numeros.append(10)

print(lista_de_numeros) #imprime: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10]
```

Listas são criadas a partir dos colchetes `[ ]` e cada elemento é separado por meio de vírgulas.

Cada elemento pode ser acessado a partir do índice do mesmo, que é o número de sua posição menos 1, o menos um se dá pois a contagem começa pelo 0, isto é o primeiro elemento tem índice 0, o segundo indice 1, e assim por diante.

Perceba que a lista é uma estrutura expansível, e seus dados podem ser acessados diretamente, modificados, a lista pode ser expandida, e os permite que valores dobrados pertençam a mesma lista.

Portanto, as listas são muito utilizadas quando você quer trabalhar com dados em um mesmo local e manipular os mesmos.

### Tuplas
É o tipo de coleção que permite duplicação, é ordenável, porém é imutável e inexpansível.

```python
#autor: Reginaldo Mota (O Régis)

coordenadas_iniciais = (4,2)
coordenadas_finais = (8,3)

print(coordenadas_iniciais)
print(coordenadas_finais)

print(coordenadas_iniciais[0])
print(coordenadas_finais[1])

# As linhas abaixo retornam erros
# coordenadas_iniciais[0] = 3 # imutável
# coordenadas_iniciais[2] = 2 # inexpansível

# Tuplas podem ter vários elementos e duplicados

tupla_gigante = (1,2,3,4,5,6,7,8,9,0,1,2,3,45,7,2,6,9,3,1,1,1,1,1)

print(tupla_gigante) #imprime: (1, 2, 3, 4, 5, 6, 7, 8, 9, 0, 1, 2, 3, 45, 7, 2, 6, 9, 3, 1, 1, 1, 1, 1)
```

Tuplas são úteis quando os dados que você está manipulando são imutáveis e a quantidade de informações também é inalterável.

O símbolo de criação de tuplas são os parênteses `( )`!
### Sets
Os sets são coleções mais recentes, e são coleções não ordenáveis, não indexáveis, que não aceitam duplicação, seus elementos não podem ser modificados diretamente. No entanto é uma coleção expansível, isto é, elementos novos podem ser adicionados, desde que sejam diferentes dos já existentes.

```python
#autor: Reginaldo Mota (O Régis)

numeros_ordenados = { 2, 1, 3, 5, 4 } # ordena números automaticamente
vogais = { 'a', 'e', 'i', 'o', 'u'} # o mesmo não acontece com letras
numeros_decimais = {1.2,5.2,0.4,1.4,5.1} # ordena se diferença entre os números for maior ou igual a 0.2

print(numeros_ordenados) # imprime: {1, 2, 3, 4, 5}
print(vogais) # imprime: {'i', 'u', 'a', 'e', 'o'}
print(numeros_decimais) # imprime: {0.4, 1.2, 1.4, 5.2, 5.1}

numeros_ordenados.add(0) # expansível

print(numeros_ordenados) # imprime: {0, 1, 2, 3, 4, 5}

numeros_ordenados.add(0) # não permite duplicatas

print(numeros_ordenados) # imprime: {0, 1, 2, 3, 4, 5}

# As linhas abaixo retornam erros
# numeros_ordenados[0] = 3 # diretamente imutável
```

Os sets são boas opções para trabalhar com informações que não podem ser duplicadas, que não seja necessário modificar diretamente as informações e que a ordem dessas informações não é importante.

A ordenação automática também é bem útil, mas funciona perfeitamente somente nos casos em que estamos trabalhando com números inteiros, os demais existem imprecisões e até mesmo erros que podem acontecer.

O símbolo de criação de sets são as chaves `{ }`!

## Controle de Fluxo
## Funções
## Classes
