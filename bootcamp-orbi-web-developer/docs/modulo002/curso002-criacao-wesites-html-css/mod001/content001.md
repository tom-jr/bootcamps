Tim Berners-Lee

- HTML 1 1991
- HTML 2 1995
- HTML 3 1997
- HTML 4 1997
- HTML 5 2014

![](/docs/assets/img/intro_criacao_website_01.png)

# HTML5
## Definição e estrutura básica
Em 1991 Tim Berners-Lee criou essa linguagem de marcação para melhorar a comunicação entre ele e seus colegas de trabalho no CERN,
 desde então já surgiram 5 versões e o HTML se tornou a base da web.

Com o HTML definimos o significado e a estrutura do conteúdo da web e, além de texto, nossas páginas precisam de imagens, 
vídeos e vários outros formatos e para isso temos os elementos HTML.

Um elemento HTML é formado pela tag de abertura e seus atributos, o conteúdo e uma tag de fechamento. E mais a frente veremos
 que existem elementos que não tem tag de fechamento.

Com esses elementos podemos agrupar tipos de conteúdo, alterar tamanho e forma de fontes e adicionar diferentes mídias ao nossa página na web.

E agora podemos ver como é a estrutura básica de um arquivo HTML.

A primeira linha do documento deve ser o \<!DOCTYPE html\>, apesar de parecer um elemento HTML ela apenas diz 
ao navegador que ele está lidando com um arquivo do tipo HTML5. Os elementos HTML vem logo abaixo.

**\<html\>**

A tag html é a raiz do seu documento, todos os elementos HTML devem estar dentro dela. E nela nós informamos ao navegador 
qual é o idioma desse nosso documento, através do atributo lang, para o português brasileiro usamos pt-BR.

**\<head\>**

A tag head contém elementos que serão lidos pelo navegador, como os metadados - um exemplo é o charset, que é a codificação
 de caracteres e a mais comum é a UTF-8, o JavaScript com a tag script, o CSS através das tags style e link - veremos a
  diferença quando falarmos sobre CSS - e o título da página com a tag title.

**\<body\>**

E dentro da tag body colocamos todo o conteúdo visível ao usuário: textos, imagens, vídeos.
