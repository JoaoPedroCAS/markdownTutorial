
# GUIA DE MARKDOWN (MD)

Este guia pode ser utilzado como um tutorial para aqueles que não tem conhecimento na linguagem de marcação .md  

## Titulos

Assim como o HTML a linguagem markdown possui seis estilos diferentes de titulos. Estes titulos são utilizados atraves do caracter especial #. Quanto mais '#' um titulo possuir, menor a importancia dele.  

# Título com 1 '#'

## Título com 2 '#'

### Título com 3 '#'

#### Título com 4 '#'

##### Título com 5 '#'

###### Título com 6 '#'
 
Assim como em toda linguagem, o markdown possui medidas para tornar seus arquivos mais legíveis
para terceiros. Algumas medidas de boas práticas que podem ser tomadas quando escrever um título
em .md são: 
- Utilizar uma linha em branco antes e depois do titulo
- Acrescenter um espaço entre o caracter '#' e o primeiro caracter do título.

## Parágrafos

Para criar um parágrafo, devemos utilizar uma linha em branco entre uma frase e outra

## Quebra de linha

Para adicionar uma quebra de linha basta acrescentar dois ou mais espaços após a ultima palavra da frase e então dar um enter.  
Isso faz com que você continue no mesmo paragrado que antes, apenas uma linha abaixo.

## Negrito  

Para utilizar o negrito em markdown devemos colocar a parte a ser destacada entre dois '*'.  
**Negrito**

## Italico

Já para o ittálico, utilizamos apenas um '*'.  
*Itálico*

## Italico e Negrito

Para itálico e negrito iremos utilizar três '*'.  
***Italico e Negrito***

## Citação

Para fazer uma citação utilizaremos o caracter '>'

> Exemplo de citação

## Lista Ordenada

Para fazer uma lista ordenada basta digitar 'x.' sendo x o elemento a ser listado

1. Primeiro Item
2. Segundo Item

Tambem existe a possibilidade de fazer uma lista dentro da lista
1. Primeiro Item
2. Segundo Item
    1. Segundo Item A
    2. Segundo Item B
3. Terceiro Item

## Lista Sem Ordem

Para fazer uma lista sem ordem basta acrescentar o caracter '-' antes dos elementos a serem listados

- Primeiro Item
- Segundo Item

## Blocos de Código

Para acrescentar um bloco de código em markdown basta identar o código, dando 4 espaços ou um tab.  
O trecho de código deve possuir uma linha em branco antes e após sua utilização.

Exemplo de codigo abaixo

    include<stdio.h>
    include<stdlib.h>
    int main(){
        printf("Hello World");
        return 0;
    }
    
## Imagens

Para acrescentar uma imagem ao seu arquivo markdown basta acrescentar o caracter '!'

![nome da imagem](Seu_caminho/imagens/img.png)

## Código

Para denotar uma palavra como código devemos colocala entre crases '``'
`Exemplo`

## Linha Horizontal

Para criar uma linho horizontal devemos usar três '*' em uma linha em branco  

***
Exemplo acima

## Link

A forma correta de acrescentar um link é colocando o nome do site entre colchetes '[' e a URL do site entre parênteses '(', por exemplo:

[Google](https://google.com)

# Fim

Esse é um guia geral para uso pessoal, se em algum momento isso te ajudou a entender os comandos basicos de markdown, fico feliz :)  
Lembrando que a maioria dos comandos podem ser usados em conjunto então voce pode ter um link que  faz parte de uma lista e este link está em negrito e italico.
