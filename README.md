# Info

Esse repositório foi criado para treinar markdown e para criar um material de apoio para pessoas que queiram aprender também

## Materiais utilizados

* Curso Udemy
    * [Aprenda Markdown](https://www.udemy.com/course/aprenda-markdown/learn/lecture/12217290?start=0#overview)
    
* Sites
    * [Guia basico](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)
    * [Documentation](https://www.markdownguide.org/basic-syntax/)
* Videos
    * [Código Fonte TV](https://www.youtube.com/watch?v=gFJfyHRKaE0)
    * [Cria jogo](https://www.youtube.com/watch?v=vZaldeUg6D0)

# Apreendendo MARKDOWN

Aprendendo MARKDOWN para descrever seus projetos e para profissionalizar seu perfil no GitHub.

# Títulos

Para adicionar titulos basta apenas acresentar um # na frente

## Sub-Títulos

Para adicionar subtitulos basta por 2 # na frente e assim vai até por exemplo o h6 no html. 

# Paragrafos
Para adicionar paragrafos, conteudos ou texto deve-se apenas escrever.

**OPS:** Para pular de linha pressione duas vezes o **Space** e para separar paragrafos pressione duas vezes o **Enter**

# Ênfase

## Negrito

Para aplicar a propriedade **negrito** basta por 2 *(Asteristico) ou 2 _(underline)  no começo e no fim da palavra ou frase

## Itálico

Para aplicar a propriedade *itálico*  basta por 1 *(Asteristico) ou 1 _(underline)  no começo e no fim da palavra ou frase

# Linha horizontal

Para adiconar linhas horizontais basta por 3 *(Asteristico), 3 _(underline) ou 3 -(traço)

Exemplo:

***

# Listas Não-ordenadas

coloque apenas 1 -(traço), +(sinal de adição) ou *(asteristico), caso deseje por um subitem selecione e pressiione tab e assim por diante.

Exemplo:

* Item1
    * SubItem1
        * OutroItem
    * SubItem2
    * SubItem3
* Item2
* Item3
* Item4

# Listas ordenadas

coloque apenas os numeros seguindos de um ponto, lembrando que o numero segue a ordem do primeiro numero adicionado

Exemplo:

1. Item
    1. Sub Item
    1. Sub Item
    1. Sub Item
1. Item
1. Item
1. Item

# Links

Para adicionar Link basta por o texto entre [ ] e a url da pagina entre ( )

exemplo:

[markdown documentation](https://www.markdownguide.org/basic-syntax/)

# Imagens

Para adicionar images segue a mesma logica do link porem ponha um sinal de ! na frente do [ ] e dentro dele ponha a descrição da imagem

Exemplo:

[![markdown](markdown.png)](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)

# Tabelas

utiliza-se | para separar as colunas e na linha de baixo ponha --- para indicar que a linha de cima são os títulos da tabela

Exemplo:

linguagens mais populares:

Linguaguem | posição
-----------|--------|
Python | 1
Java | 2
Javascript | 3

[Fonte](http://pypl.github.io/PYPL.html)

# Blocos de código

Para inserir bloco de codigos ponha 3 ~ no começo e no final, e para por a sintaxe do codigo ponha o nome da linguagem na frente dos primeiros 3 ~

Exemplo:
~~~js
//mensagem feliz

function saudacao() = {
    var data = new date;
    return data.getHours() <= 12? "Bom dia": data.getHours() <= 18? "Boa tarde": "Boa noite";
}

console.log(saudacao());

~~~




