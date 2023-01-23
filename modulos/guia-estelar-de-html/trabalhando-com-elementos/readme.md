[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/readme.md) /
[Certificado](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/certificado)

---

:ballot_box_with_check: Semântica

Vamos falar de semântica em HTML.

Um dos principais objetivos é dar uma estruturação para o texto, para que haja significado e também uma melhor leitura e para isso usamos elementos semânticos, são mais de 100, mas todos muito importantes, são apenas benefícios.

---

:ballot_box_with_check: Títulos e Parágrafos

Nesta aula estaremos aprendendo a como fazer títulos e parágrafos, para uma melhor leitura, uma melhor semântica.

    <h1>Sobre mim</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. </p>
    <p>Voluptates tempora iusto at provident soluta distinctio fugit ratione consectetur deleniti vel quisquam deserunt architecto quas, possimus quos molestias maiores iste officia?
    </p>

    <h2>Nascimento</h2>
    <h3>Infância</h3>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Qui officiis consequuntur corrupti nisi cumque esse dolorum fugit, rem suscipit cum laudantium expedita itaque odio a explicabo ex illo illum libero?
    </p>
    <h3>Adolescência</h3>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Qui officiis consequuntur corrupti nisi cumque esse dolorum fugit, rem suscipit cum laudantium expedita itaque odio a explicabo ex illo illum libero?
    </p>

    <h2>Trabalho</h2>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus ad vel explicabo consequatur, ut magni doloremque sapiente, perspiciatis excepturi esse ea neque sed! Blanditiis mollitia assumenda ipsum harum consequuntur. Veritatis.

    <a href="">Saiba mais</a>


&lt;hx&gt;&lt;/hx&gt; — indo de 1 à 6 é a tag para título, 1 sendo o maior e 6 sendo o menor, a hierarquia indo de título, subtítulo e etc.

&lt;p&gt;&lt;/p&gt; — este sendo a tag de parágrafo.

---

:ballot_box_with_check: Listas

Listas no HTML são feitas da seguinte forma:

&lt;li&gt;&lt;/li&gt; — colocar os elementos da lista. &lt;ul&gt;&lt;/ul&gt; — para uma lista não ordenada.&lt;ol&gt;&lt;/ol&gt; — para uma lista ordenada.

    <h1>Suco detox</h1>
    <h2>Ingredientes:</h2>

    <ul>
        <li>3 folhas de couve;</li>
        <li>1 laranjas;</li>
        <li>1 pedacinho gengibre;</li>
        <li>300 ml de água;</li>
        <li>Adoçante a gosto;</li>
        <li>Gelo a gosto.</li>
    </ul>

---

:ballot_box_with_check: Citações

&lt;blockquote&gt;&lt;/blockquote&gt; — para uma citação que você queira deixa maior, tendo uma estilização mais diferente.
&lt;code&gt;&lt;/code&gt; — mostra que é um código

cite — atributo usado para citar a url.

&lt;cite&gt;&lt;/cite&gt; — tag usada para colocar o citar link direto no texto.

&lt;q&gt;&lt;/q&gt; — citação curtas com aspas.

    <blockquote cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">
        O <strong>Elemento HTML <code>&lt;blockquote&gt;</code> </strong> (ou <em>HTML Block
        Quotation Element</em>) indica que um texto externo foi citado.
    </blockquote>

    <p>De acordo com <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">
        <cite>página MDN blockquote</cite></a>:
    </p>

    <p>O elemento quote — <code>&lt;q&gt;</code> — é <q cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q">usado para citações curtas que não precisam de parágrafos ou quebras de linha.</q> -- <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q">
    <cite>MDN q page</cite></a>.</p>

---

:ballot_box_with_check: Abreviações

Elemento muito comum encontrado na web é a de abreviação, mas de alguma forma queremos mostrar a palavra inteira.

    <p>Usamos <abbr title="Hypertext Markup Language">HTML</abbr>  para estruturar nossos documentos da web.</p>

Se colocarmos o mouse em cima da abreviação, teremos a palavra inteira.

---

:ballot_box_with_check: Detalhes de contato

A tag usada para apenas colocar detalhes de contato é a tag &lt;address&gt;&lt;/address&gt;, não endereço em si, mas por exemplo o autor da página.

    <address>
        <p>Mayk Brito <br>
        <strong>Campo Grande, MS</strong>
        </p>
    </address>

---

:ballot_box_with_check: Lista de descrição

Usado para marcar uma lista de itens e suas descrições.

    <h2>Glossário</h2>
    <dl>
        <dt>Hypertext</dt>
        <dd>É um hiper texto com possibilidades...</dd>

        <dt>Markup</dt>
        <dd>Marcação do texto</dd>

        <dt>Languague</dt>
        <dd>Linguagem com sua semântica e sintaxe....</dd>
    </dl>

&lt;dl&gt;&lt;/dl&gt; — tag para lista de descrições.&lt;dt&gt;&lt;/dt&gt; — tag para o termo da descrição.&lt;dd&gt;&lt;/dd&gt; — tag para descrição.

---

:ballot_box_with_check: Representação de código

Para representar códigos usamos as tags:

&lt;code&gt;&lt;/code&gt; — muda a cor do conteúdo para representar código.

&lt;pre&gt;&lt;/pre&gt; — tag para criar um bloco de código, mantém os espaços em branco.

    <pre>
        <code>
            &lt;
        </code>
    </pre>

---

:ballot_box_with_check: Elementos Genéricos

&lt;div&gt;&lt;/div&gt; — tag usada para agrupar conteúdo.

&lt;span&gt;&lt;/span&gt; — tag usada para agrupar texto, em uma ideia mais de linha.

    <div class="cart">
        <span>Camiseta</span>
        <span>r$ 99,00</span>
    </div>

---

[Voltar](/modulos/guia-estelar-de-html/readme.md)