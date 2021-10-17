# Conceitos de MarkDown

## Texto

````
Headers
=== faz uma linha embaixo 
--- faz uma linha embaixo 
# Este equivale à tag <h1></h1> Titulo;
## Este equivale à tag <h2></h2> Subtitulo
###### Este é o maximo de subtitulo equivale à tag <h6></h6>

Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
***You can combine them***

Quebra de linha é feito com dois enters 

````

## Listas 
````
Lista ordenada 
Geralemente se usa 1. ja aparece enumerado, mas também pode usar 1,2,3...
1. item 
1. item 2
  1. item 2a (endentação de lista, da dois espaços)
    1. item 2aa (endentação interna de lista, da mais dois espaços)

Lista não ordenada
Usa-se - para fazer pontinho
- item 1
- item 2
  - item 2a (endentação de lista, da dois espaços)
````
Código
````
`wilw do` mostra, o que esta entre as crases, em formato de codigo 

também pode ser feito uma caixa de código
``` indica qual linguagem é
escreve o codigo e ele formata em código
```
````
### Exemplo
 código `Wile do`

 ```js
 wile do
    print ("ola mundo")
 End
 ```

## Citação
````
Coloca o sinal de maior (>)
> Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

````

## Link
````
Para clicar na palavra e ser encaminhado a um link
[Texto do link](link)
````
### Exemplo
[Tutoreial da MarkDown](https://guides.github.com/features/mastering-markdown/)

## Referência de rodapé

````
[link do tutorial de MarkDown][MarkDown]

[MarkDown](https://guides.github.com/features/mastering-markdown/)

Facilita colocar no meio do texto quando preciso
````
### Exemplo

[link do tutorial de MarkDown][MarkDown]

[MarkDown]: https://guides.github.com/features/mastering-markdown/

## Imagem 

````
![foto](link da foto)
````
### Exemplo

![foto](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRddTGqPw1D-Zh0Pb1GZFBM0PXDe_2Q94Dp2g&usqp=CAU)

## Tabela
````
Para fazer tabela basta serapar os itens com barra vertical (|)
A tabela deve conter o mesmo numero de colunas 
Pra deixar mais alinhado pode usar o espaço
Alinhamento de texto:
: dois pontos a esquerda alinha a esquerda
: dois pontos a direita alinha a direita
: dois pontos a direita e esquerda alinha no meio:

| ID | Nome | Preço |
|:----|:------:|-------:|
|1   | iPad 2019 64GB | R$ 2000,00|
````

### Exemplo
| ID | Nome | Preço |
|:----|:------:|-------:|
|1   | iPad 2019 64GB | R$ 2000,00|

[Readme.md](https://github.com/LuanaGarcia/exercise-markdown/blob/master/README.md)


