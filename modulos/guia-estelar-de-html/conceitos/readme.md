[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/readme.md) /
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

:ballot_box_with_check: Aninhamento Hierarquia

Aninhamento em HTML significa colocar uma tag dentro da outra, porém não é qualquer tag que podemos colocar dentro de outra, existe uma hierarquia por trás delas, por exemplo:

    <p> 
        <em>texto<em>
        <p> texto2</p> 
    </p>

Podemos ver no exemplo acima que a tag  &lt;em&gt; &lt;/em&gt;(usada para dar enfase em um texto) é pertencente a Tag &lt;p&gt; &lt;/p&gt;(usada para criar um parágrafo).

Também é possível notar que há um fluxo, onde as tags são lidas por ordem de cima para baixo.

Por fim o posicionamento de elementos, podemos ver que a tag &lt;em&gt; &lt;/em&gt; não está em uma outra linha como na tag &lt;p&gt; &lt;/p&gt;, existem tags que quebram a linha, então mesmo que colocarmos a tag &lt;p&gt; &lt;/p&gt; uma do lado da outra, visualmente vai dar quebra de linha.

---

:ballot_box_with_check: Praticando

Vamos colocar em prática o que aprendemos nessas ultimas aulas.

Escreva 2 parágrafos, dando ênfase e importância para algumas palavras , e adicione um link de saiba mais.

— use a tag &lt;em&gt; &lt;/em&gt; para ênfase

— use a tag &lt;strong&gt; &gt;/strong&gt; para importância

— o link pode levar para o google.

ex:

    <p>
        Lorem <em>ipsum</em> dolor sit amet consectetur
        <strong>adipisicing</strong>  elit. A eligendi nesciunt mollitia <strong>provident </strong> explicabo cum, adipisci magnam? <b>Itaque</b> quae suscipit pariatur sit? Tempore odio autem repellat, voluptate eius perspiciatis similique.
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. A eligendi nesciunt mollitia provident explicabo cum, adipisci magnam? Itaque quae suscipit pariatur sit? Tempore odio autem repellat, voluptate eius perspiciatis similique.
    </p>

    <a href="https://google.com">Saiba mais</a>

---

:ballot_box_with_check: Caracteres Reservados

Caracteres reservado são caracteres usados no próprio HTML, como < > & " " ' ', não podemos usar nas tags, pois dão erro, mesmo aparecendo na preview o navegador vai tentar ler esses caracteres de alguma forma que faça sentido. Para usarmos precisamos troca-los por outras formas de escrever.

    <p>
        &lt;
        os espaços 
        &gt;
        &amp;
        
        <br>
        &quot; que colocamos    
        &quot;
        <br>
        &apos; além das quebras de linha são
        ignorados

    </p> 

---

:ballot_box_with_check: Anatomia Documento

Estaremos vendo nesta aula sobre a Anatomia do documento HTML e como ver o nosso HTML, além do preview.

Se abrirmos o documento .html pelo navegador estaremos vendo a nossa página e se clicarmos em ver o código fonte dela, estaremos vendo o HTML que escrevemos no VSCode.

Agora na parte de anatomia de um documento HTML, temos este exemplo.

    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title>Anatomia do Documento</title>
        </head>

        <body>
            <h1>Título</h1>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis saepe similique perferendis mollitia a assumenda doloribus omnis, quidem tempore accusamus repudiandae. Accusamus, rem dolorum ad repellendus distinctio blanditiis praesentium nulla?
            </p>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis saepe similique perferendis mollitia a assumenda doloribus omnis, quidem tempore accusamus repudiandae. Accusamus, rem dolorum ad repellendus distinctio blanditiis praesentium nulla?
            </p>
        </body>
    </html>

O padrão seria esta forma.

&lt;!DOCTYPE html&gt; — diz ao navegador que estamos a trabalhar com HTML 5.

&lt;html&gt;&lt;/html&gt; — o próprio HTML, elemento raiz, o inicio da cadeia.

&lt;head&gt;&lt;/head&gt; — contém configurações importantes para página, mas não ainda o que o usuário vai ver.

&lt;meta&gt; — onde vai representar vários tipos de metadados da página.

&lt;title&gt;&lt;/title&gt; — título da página.

&lt;body&gt;&lt;/body&gt; — onde haverá conteúdo visual da página.

Se quiser facilitar tudo digitando ! o emmet irá completar automaticamente.

---

:ballot_box_with_check: Criando Projetos

Estaremos vendo como criar um projeto html.

Abrindo o explorador de arquivos do seu computador, indo na parte de usuário > documentos e criará a pasta do projeto, e arrastará para o VSCode.

Você pode criar arquivos, por exemplo: index.html, ou criar pastas.

---

[Voltar](/modulos/guia-estelar-de-html/readme.md)