# Guia básico para estilizar células de texto do Jupyter Notebook utilizando Markdown.

Este guia foi feito para ser uma referência rápida para a estilização de texto do Jupyter Notebook. Você encontra maiores detalhes na pagina do [John Gruber's](https://daringfireball.net/projects/markdown/), na página do [Github](https://docs.github.com/en/github/writing-on-github) ou nesta [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

**Disclaimer**: este notebook foi escrito utilizando o *Google colab* no navegador *Brave*. Você pode obter comportamentos diferentes em alguns tópicos caso utilize outros navegadores.

# Cabeçalhos

Podemos separar as células em seis níves diferentes de cabeçalhos, o que é feito para auxiliar na organização dos notebooks. O cabeçalho é renderizado a partir de um símbolo de hashtag (\#) no inicio de uma linha. 
<br>
<br>
Com apenas 1 hashtag (\#), temos um cabeçalho de nível 1. 

Com 2 hashtags (\#\#), temos um cabeçalho de nível 2.

Com 3 hashtags (\#\#\#), temos um cabeçalho de nível 3.

Com 4 hashtags (\#\#\#\#), temos um cabeçalho de nível 4.

Com 5 hashtags (\#\#\#\#\#), temos um cabeçalho de nível 5.

Com 6 hashtags (\#\#\#\#\#\#), temos um cabeçalho de nível 6.

A seguir temos exemplos de como são renderizados cada tipo de cabeçalho.

# Cabeçalho nível 1

\# Cabeçalho nível 1



## Cabeçalho nível 2

\## Cabeçalho nível 2

### Cabeçalho nível 3

\### Cabeçalho nível 3

#### Cabeçalho nível 4

\#### Cabeçalho nível 4

##### Cabeçalho nível 5

\##### Cabeçalho nível 5

###### Cabeçalho nível 6

\###### Cabeçalho nível 6

# Ênfase

## Itálico

Para deixar o texto em itálico, utiliza-se o asterisco (\*) ou o underline (\_):

Este texto \*em itálico\* utilizando asterisco:  *em itálico*

Este texto \_em itálico\_ utilizando underline:  _em itálico_

## Negrito 

Para deixar o texto em negrito, utiliza-se dois asteriscos (\**) ou dois o underlines (\__):

Este texto \*\*em negrito\*\* utilizando asterisco:  **em negrito**

Este texto \_\_em negrito\_\_ utilizando underline:  __em negrito__

## Itálico e negrito

Para deixar o texto em itálico e em negrito ao mesmo tempo tilize-se três asteriscos (\*\*\*) ou três o underlines (\_\_\_):

Este texto \*\*\*em itálico e negrito\*\*\* utilizando asterisco:  ***em itálico e negrito***

Este texto \_\_\_em itálico e negrito\_\_\_ utilizando underline:  ___em itálico e negrito___

## Tachado

Para deixar o texto tachado utiliza-se dois tils (\~\~):

Este texto \~\~ tachado\~\~:  ~~tachado~~


## Sublinhado

Não temos um código específico para escrever texto sublinhado utilizando a sintaxe de Markdown, mas podemos utilizar sintaxe `HTML`, através da tag `<ins></ins>`

Este texto \<ins>sublinhado\</ins>: <ins>sublinhado</ins>


# Listas

## Listas de itens (lista não ordenada)

Para criar uma lista não ordenada, podemos utilizar o asterisco (\*), o sinal de menos (\-) e/ou o sinal de mais (\+) para adicionar cada item da lista.

Por exemplo:

\- Mamão

\* Limão

\+ Maça

será renderizado dessa forma:

- Mamão

* Limão

+ Maça

Para inserir lista dentro de listas, basta adicionar um espaçamento (tab) em relação a margem esquerda. Por exemplo:

\* Maça

&emsp;\* Gala

&emsp;\* Fuji

Será renderizada da seguinte forma:

+ Maça

  + Gala

  + Fuji

E para adicionar novas listas dentro de listas (nested list), basta adicionar mais um espaçamento (tab). Por exemplo:


\- Maça

&emsp;\- Gala

&emsp;\- Fuji

&emsp;&emsp;\- verde

&emsp;&emsp;\- madura

Será renderizada da seguinte forma:

+ Maça

  + Gala

  + Fuji

    + verde

    + madura



## Listas numeradas (listas ordenadas)

Para inserir listas numeradas, basta iniciar a linha com um número qualquer e adicionar um ponto após o número, não importando qual número seja. Por exemplo:

1\. Item 1

2\. Item 2

3\. Item 3

Será renderizado dessa forma:

1. Item 1

2. Item 2

3. Item 3

Já esta forma

1\. Item 1

20\. Item 2

3100\. Item 3

será renderizado de forma igual a anterior:

1. Item 1

20. Item 2

3100. Item 3

Para iniciar em um número diferente de 1, basta utilizar alterar o primeiro número de lista. Por exemplo:

10\. Item 1

2\. Item 2

3100\. Item 3

Será rendezirado iniciando no número 10:

10. Item 1

2. Item 2

3100. Item 3

**Observação**: Este item apresenta comportamento diferente dependendo de onde é renderizado. No Google colab, o comportamento é o descrito acima. No GitHub, a numeração irá sempre iniciar em 1. Sempre verifique se o comportamento descrito corresponde ao obitido.

E para adicionar uma lista dentro desta lista, basta utilizar um tab. Por exemplo:

1\. Item 1

2\. Item 2

3\. Item 3

&emsp;1\. Item 1

&emsp;2\. Item 2

&emsp;3\. Item 3

Será renderizado da seguinte forma:

1\. Item 1

2\. Item 2

3\. Item 3

  1. Item 1

  2. Item 2

  3. Item 3


  Listas ordenadas e não ordenadas podem ser acopladas uma nas outras. Por exemplo:

1\. Item 1

2\. Item 2

3\. Item 3

&emsp;\- Item 1

&emsp;\- Item 2

&emsp;\- Item 3  

Será renderizado da seguinte forma:

1. Item 1

2. Item 2

3. Item 3

  - Item 1

  - Item 2

  - Item 3  


# Tabela

Para criar uma tabela, utilizamos a barra vertical (|) para indicar o inicio e o final de cada célula da tabela. A primeira linha da tabela sempre será interpretada como o cabeçalho da tabela, e o cabeçalho e o corpo da tabela deve ser separado por pelo menos um traço (-).

Por exemplo, 

\| Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3 |

\| - | - | - |

\| Linha 1 | Linha 2 | Linha 3 |

Será renderizado da seguinte forma:

| Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3 |
| - | - | - |
| Linha 1 | Linha 2 | Linha 3 |

Por padrão, o cabeçalho será centralizado, enquanto que as linhas serão alinhadas à esquerda. Para alterar o alinhamento das linhas para à direita, basta colocar o simbolo de dois pontos (:) após o traço que separa o cabeçalho das linhas da tabela. Por exemplo:

\| Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3 |

\| - | - | -: |

\| Linha 1 | Linha 2 | Direita |

Será renderizado destaforma:

| Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3 |
| - | - | -: |
| Linha 1 | Linha 2 | Direira |

Para centralizar o conteúdo da linha de uma coluna, basta colocar os dois pontos antes e depois do traço. Por exemplo,

\| Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3 |

\| - | :-: | - |

\| Linha 1 | Central | Linha 3 |

Será renderizado desta forma:

| Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3 |
| - | :-: | - |
| Linha 1 | Central | Linha 3 |

<br>

**Observação**: O alinhamento das células citado acima não funciona no GitHub.

# Código

É possível renderizar o texto para simular um código de programação em uma linguagem. Para inserir o texto dentro de uma linha, basta colocar o código entre duas crases (\`).

Por exemplo, para renderizar x = 10 como código, adiciona-se uma crase antes e outra após o código, dessa forma: \`x = 10\`.

Que será renderizado assim: ` x = 10`

Para inserir um bloco de código, adicionamos três crases (```) antes do bloco, e outras três crases após o bloco.

Por exemplo, para inserir um bloco de código que contém uma função que soma dois números, fazemos desta forma:

\```  
def soma(x, y):  
&emsp;return x + y  
\```

Que será renderizado assim:

```
def soma(x, y):
  return x + y
```

Para que o estilo de código seja aplicado, basta colocar o nome da linguagem após a primeira linha de crases. Por exemplo:


\```python  
def soma(x, y):  
&emsp;return x + y  
\```

Será renderizado destacando os elementos de código Python:

```python
def soma(x, y):
  return x + y
```

Observe que as palavras chaves do python `def` e `return` foram marcadas em azul, destacando o código Python.


# Outros

## Blockquote

Podemos inserir um paragráfo destacado, utilizando um símbolo de maior (\>) no início do paragráfo. Por exemplo,

\> Isto será destacado como uma citação direta

Será renderizado desta forma

> Isto irá ser destacado como uma citação direta

##Link

Podemos adicionar links ao longo do texto. Para fazer isto, utilizamos a estrutura \[nome que irá aparecer](link completo).

Por exemplo, para inserir um link que leva ao site da Google, utilizamos a seguinte notação:

Clique \[aqui](https://www.google.com/) para acessar o Google.

Que será renderizado da seguinte forma:

Clique [aqui](https://www.google.com/) para acessar o Google.

## Quebra de linha

Para separa dois parágrafos, basta deixa-los separados por um linha inteira, ou inserir dois espaços em branco após o final do primeiro paragráfo. Também podemos utilizar a TAG de `HTML` `<br>` para querar uma linha, adicionando esta TAG no final do parágrafo.

## Linha horizontal

Para adicionar uma linha horizontal, basta adicionar três traços (\---) em uma linha vazia.

Por exemplo,

\---

Será renderizado desta forma:

---


## Imagem

Para inserir uma imagem, basta utilizar a seguinte notação: 

\!\[alt text]\(link para a imagem "texto de titulo da imagem ao passar o mouse pela imagem").

Por exemplo,

\!\[alt text]\(https://raw.githubusercontent.com/andersonmdcanteli/matplotlib-course/main/logo/marca_puzzle.png
 "texto de titulo da imagem ao passar o mouse pela imagem").

 Será renderizado desta forma:

![alt text](https://raw.githubusercontent.com/andersonmdcanteli/matplotlib-course/main/logo/marca_puzzle.png 
 "texto de titulo da imagem ao passar o mouse pela imagem")


Passe o mouse por cima da imagem e observe o texto que será apresentado. 


Para alterar este texto para algo mais adequado, basta alterar o texto inserido entre aspas duplas:

![alt text](https://raw.githubusercontent.com/andersonmdcanteli/matplotlib-course/main/logo/marca_puzzle.png
 "logo do projeto The puZZle in a Mug").


Entretanto, ao utilizar a forma acima não é possível alterar o tamanho da imagem. 

Para poder alterar o tamanho da imagem é necessário utilizar a tag `HTML` `<img>`, da seguinte forma:

```HTML
<img src="link para a imagem" alt="texto de titulo da imagem ao passar o mouse pela imagem" width="pixels">
```

Onde `pixels` é o número de pixels que a imagem terá na largura. O valor da altura será proporcional ao valor passado em `width`, em relação ao tamanho original da imagem.

Exemplo:

\<img src="https://raw.githubusercontent.com/andersonmdcanteli/matplotlib-course/main/logo/marca_puzzle.png" alt="logo Puzzle in a Mug project" width="400">

<br>

Que é renderizado dessa forma:

<img src="https://raw.githubusercontent.com/andersonmdcanteli/matplotlib-course/main/logo/marca_puzzle.png" alt="logo Puzzle in a Mug project" width="400">


## Equações

É possível renderizar equações nos notebooks utilizando código Latex. Entretanto, é necessário envolver o código da equação com o simbolo do dólar ($).

Para inserir uma equação dentro de um paragráfo, utilizamos um (1) simbolo de dolar antes e outros após a equação. Por exemplo:

<br>

O volume de uma esfera refere-se ao seu espaço interno, sendo calculado através da fórmula \\$V_{esfera} = \frac{4}{3}\pi r^{3}\\$, onde \\$r\\$ é o raio da esfera.

<br>

O texto acima será renderizado da seguinte forma:


O volume de uma esfera refere-se ao seu espaço interno, sendo calculado através da fórmula $V_{esfera} = \frac{4}{3}\pi r^{3}$, onde $r$ é o raio da esfera.

<br>

Caso não contenha nenhum texto acompanhando a equação, ela será renderizada de forma justificada à esquerda. Por exemplo:

<br>

\\$V_{esfera} = \frac{4}{3}\pi r^{3}\$

<br>

Será renderizado desta forma:

$V_{esfera} = \frac{4}{3}\pi r^{3}$

<br>

Para que a equação seja renderizada no centro do notebook, utilize dois simbolos de dolar (\$\$) ao invés de apenas um. Por exemplo:

<br>

\\$\\$V_{esfera} = \frac{4}{3}\pi r^{3}\$\$

<br>

Será renderizado desta forma:

$$V_{esfera} = \frac{4}{3}\pi r^{3}$$

<br>

**Observação**: barras extras (\\) serão renderizadas no GitHub nas equações acima que propositalmente não são rederizadas. As remova para que a equação seja renderizada de forma correta.

<br>

Para gerar o código Latex para as equações você pode utilizar o site [mathurl.com](http://mathurl.com/), onde é possível desenhar as equações de forma bem simpes.

# Considerações finais

Como os notebooks funcionam em navegadores, eles também podem ser editados utilizando TAGs `HTML` e código `css`. Mas, a ideia dos notebooks é ser algo simples e rápido de utilizar, e portanto, é mais adequado utilizar o Markdown para estilizar o seu texto de forma rápida e eficiente.

# Sobre

**Author:** Anderson Marcos Dias Canteli, *PhD in Food Engineer*

**Last updated on:** 12/07/2021

### Interesting links:

- [GitPage](http://andersonmdcanteli.github.io/)

- [Blog](https://andersoncanteli.wordpress.com/)

- [YouTube channel](https://www.youtube.com/c/AndersonCanteli/)

- [Curriculum lattes](http://lattes.cnpq.br/6961242234529344)

<br>

<img style="float: right" src="https://raw.githubusercontent.com/andersonmdcanteli/matplotlib-course/main/logo/marca_puzzle.png" alt="logo Puzzle in a Mug project" width="400">
