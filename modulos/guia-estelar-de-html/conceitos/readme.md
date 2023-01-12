[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos) /
[Certificado](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/certificado)

---

:ballot_box_with_check: Abertura

Nesse curso iremos aprender o que é HTML, seus conceitos essenciais, tags, atributos, aninhamentos, hierarquias de tags, elementos de diretórios.

---

:ballot_box_with_check: Instalando plugin de preview HTML

Nesta aula iremos aprender a instalar uma extensão no VSCode que irá nos permitir poder ver o HTML em tempo real enquanto digitamos.

Então você irá até a parte de extensões, que fica na esquerda, sendo o último ícone, digite "HTML Preview" e baixe a extensão.

---

:ballot_box_with_check: O que é HTML

HTML é um acrônimo para Hypertext (hipertexto) Markup (marcação) Language (linguagem), ela não é uma linguagem de programação em si, porém é uma linguagem na forma de escrever, tendo sintaxe e semântica, Hypertext é uma marcação especifica que nos leva a outro texto, isso mais no passado, agora sendo relacionado a imagens, a videos. Bastante simples usar o HTML, podemos ver ele clicando com o botão direito na pagina e selecionar a opção "view Page Source". Agora vamos ver mais sobre o HTML.

---

:ballot_box_with_check: Comentários

Comentários servem para nos ajudar a não nos perder em nossos códigos, sendo bem simples abrir um comentário, dessa forma:
    
    <!-- comentários -->
    
O que há em um comentário não afetará o código.

---

:ballot_box_with_check: Anatomia das Tags

Estaremos vendo a parte que constitui o Markup do HTML, as Tags.

As Tags funcionam da seguinte forma:

    <h1> TÍTULO </h1>

Você faz a abertura delas, coloca o nome da Tag e as fecha como no exemplo. No caso dessa Tag, seu conteúdo é a de título, juntando a abertura, fechamento e o conteúdo, teremos um Elemento HTML.

Há também Elementos vazios que diferente do exemplo acima não se fecha daquela forma, mas assim:

    <img src=" " alt=" ">

Essa sendo para imagem possuindo atributos, que veremos mais tarde seu funcionamento.

---

:ballot_box_with_check: Atributos

Há também os atributos booleanos, que não precisam de conteúdo, booleano significando que apenas possuem dois tipos de valores, sendo eles verdadeiro ou falso, não havendo texto, apenas essas duas opções.

    <input type="text" disabled>

Outro fator que devemos levar em consideração são as aspas, recomendado apenas o uso das aspas duplas, para não desencadear problemas no código.

---

:ballot_box_with_check: Atributos Globais

Atributos globais são atributos aplicáveis em todas as Tags, sendo as principais:

class — além de classificar as Tags, é usada para aplicar estilo css e também para acessar com o Java Script.
    
    <div class="conteúdo">
        Conteúdo
    </div>

contenteditable — usado para editar o conteúdo da página, porém não é mantido após salvar.
   
    <div contentedtable="true">
        Conteúdo
    </div>

data-* — usado para expandir os tipos de atributos que podemos usar para fazer mais tarde lógica no Java Script , utilizado em css também.
    
    <div data-qualquercoisaaqui="">
        Conteúdo
    </div>
   
   Escrito com "-" ou tudo junto.

hidden — usado para esconder uma Tag.
    
    <div class="carrinho" hidden>
        Conteúdo
    </div>

id — usado apenas 1 por Tag para identificação, para também mais tarde usar no Java Script e css.

    <div id="texto">
        Conteúdo
    </div>

    <div id="texto2">
        Conteúdo
    </div>

style — aplica a estilização na Tag, normalmente não se usa "style" dentro da Tag, mas sim em arquivos externos.

    <div style="color: red">
        Conteúdo
     </div>

tabindex — usado para ordenar o Tab na página.

    <div tabindex="3">
        Conteúdo
    </div>

    <div tabindex="1">
        Conteúdo
    </div>

    <div tabindex="2">
        Conteúdo
    </div>

title — serve para definir um título para a Tag, quando colocamos o mouse descansando em cima do conteúdo da página.

    <di title="Definir um título">
        Conteúdo
    </div>

Se você quiser estudar outros Atributos Globais vá ao site https://developer.mozilla.org/pt-BR/ .

---

- [ ] Aninhamento Hierarquia

---

- [ ] Praticando

---

- [ ] Caracteres Reservados

---

- [ ] Anatomia Documento

---

- [ ] Criando Projetos

---

[Voltar](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/guia-estelar-de-html)