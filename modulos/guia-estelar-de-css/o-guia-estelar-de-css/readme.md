[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos) /
[Certificado](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/certificado)

---

:ballot_box_with_check: Abertura

Nestas próximas aulas, vamos ver os fundamentos do CSS, como funciona, o que é o CSS afinal de contas, conceitos básicos como cascatas, especificidade, box model e muito mais.

Para consumir esse curso, é interessante que você já tenha um conhecimento de HTML.

Vamos embarcar nessa jornada?

---

:ballot_box_with_check: Conhecendo o CSS

Começaremos nossa introdução pelo que exatamente quer dizer CSS, que é um acrônimo para Cascading Style Sheet, uma forma de escrever uma folha de estilos em cascata, mas ainda precisamos saber o que exatamente é uma folha de estilos e uma cascata, mas falaremos disso mais pra frente.

O CSS é um código para criar estilos no HTML, que como vimos, é a estrutura de todo o documento, já o CSS seria a beleza, a parte bonita.

CSS não é uma linguagem de programação, é uma linguagem style sheet, pois mesmo não sendo de programação, ainda possui uma ideia de sintaxe, e assim, precisamos aprender a forma correta de se escrever.

---

:ballot_box_with_check: Comentários

Os comentários no css não irão afetar seu código, mas pode nos ajudar a lembrar de blocos de códigos ou agrupar e organizar nosso código, deixa dicas para a leitura e ajuda os outros a entenderem nosso código.

Apenas não esqueça de fechar um comentário aberto.

Os comentários abrem com /* e terminam com */ .

Você também pode usar um comentário para desabilitar partes do seu código, o que possibilitaria um debug mais fácil, ou caso deseje fazer alguma alteração sem quebrar todo o seu código.

---

:ballot_box_with_check: Anatomia

Nesta aula, falaremos sobre a anatomia do CSS, como criar esse CSS para poder alterar algum elemento do HTML.

Na verdade, é bem simples, temos o nome de algum elemento, uma chave aberta e uma fechada embaixo, e no meio vamos ter propriedades e seus valores.

Toda propriedade é seguida de : (dois pontos) e um valor e um ; (ponto e vírgula) para encerrar essa ideia de valor.

Abaixo um exemplo de CSS:

    h1 {
        color: blue;
        font-size: 60px;
        background: gray;
    }

Os elementos do CSS são então:

Selectors: Nesse caso o h1, que vai buscar no HTML a tag h1 e aplicar as mudanças.

Declaration: As chaves e tudo dentro delas.

Properties: As coisas a serem alteradas.

Property values: Os novos valores que estamos atribuindo a tais propriedades.

---

:ballot_box_with_check: Seletores

Os seletores são o que conectam um elemento HTML com o CSS, existem vários tipos, inclusive, nós vimos um na última aula, o Element/Type selector, mas também temos o seletor global, que é um * (asterisco), ID selector, que é # (cerquilha, cardinal) e o ID do elemento HTML, class selector, que é um . (ponto) e o nome da classe, e mais alguns que podemos entender mais tarde no curso.

Os seletores que mais usaremos serão realmente apenas os anteriormente citados, e vamos entrar em exemplos de como usá-los:

HTML

    <div id="container" class="m-40">
        <h1>Título</h1>
        <h2>Subtitulo</h2>
    </div>

CSS

    /* ID selector */
    #container {
        width: 200px;
    }

    /* Class selector */
    .m-40 {
        margin: 40px;
    }

    /* Element/Type selector + Agrupamento de seletores */
    h1, h2 {
        color: blue;
        font-size: 60px;
        background: gray;
    }

---

:ballot_box_with_check: Box model

Nesta aula falaremos sobre o conceito de caixas, já que o CSS trabalha com essa ideia de caixas, ou seja, o box model. Mas o quê exatamente é esse box model?

É uma caixa retangular. Essa caixa possui as mesmas propriedades de uma caixa 2D, e tem como propriedades:

    Tamanho (largura x altura): width e height, respectivamente
    Conteúdo: o content
    Bordas: o border
    Preenchimento interno: o padding
    Espaços fora da caixa: a margin

Quase todo elemento de uma página é considerado uma caixa: Posicionamentos, tamanhos, espaçamentos, bordas, cores, então, em suma, elementos HTML são caixas, assim como quase tudo no CSS.

---

:ballot_box_with_check: Origem do CSS

Vamos primeiro aprender a adicionar um estilo no nosso documento HTML, certo?

Começaremos pelo inline, que é dentro do próprio HTML, através da tag style, utilizada das seguintes formas:

    <h1 style="color: blue;">Título
        <strong style="color: red;">alo</strong>
    </h1>

Ou na head do HTML, assim:

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
        <style>
        h1 {
                color: blue;
                }
        
        strong {
                color: red;
                }
        </style>
    </head>

Porém, a forma mais comum, é através da tag link, onde vamos linkar um documento CSS externo, um outro arquivo para nosso documento HTML, feito da seguinte forma:

    <link rel="stylesheet" href="style.css">

Neste caso, o nosso documento CSS se chama style.css e sua relação com o HTML é de stylesheet.

A última forma é através do @import, que é na verdade uma regra do CSS, portanto, deve ser usada dentro do css, ao invés de dentro do HTML, como as duas primeiras formas, e seu uso é mostrado a seguir:

    @import 'https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap'

Não é recomendado seu uso, pois leva um pouco mais de tempo do que através da tag link, fazendo a página ficar menos responsiva, demorando mais para o carregamento da mesma.

---

- [ ] A Cascata

A escolha do browser de qual regra aplicar, caso haja muitas regras para o mesmo elemento.

Seu estilo é lido de cima para baixo, ou seja, caso haja algum selector com informações conflitantes, o mais embaixo é o que será atribuído.
São levados em consideração 3 fatores:

    A origem do estilo;

    A especificidade;

    A importância;

---

- [ ] Especificidade

---

- [ ] Regra important

---

- [ ] At rules

---

- [ ] Shorthand

---

- [ ] Funções

---

- [ ] DevTools

---

- [ ] Cuidados com a escrita

---

- [ ] Vendor prefixes

---

[Voltar](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/guia-estelar-de-css)