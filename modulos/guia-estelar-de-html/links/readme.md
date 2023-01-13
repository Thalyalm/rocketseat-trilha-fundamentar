[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos) /
[Certificado](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/certificado)

---

:ballot_box_with_check: Conhecendo a tag âncora

São os famosos hyperlinks, e a tag usada para se criar um é a &lt;a href=""&gt;&lt;/a&gt;, responsável por ligar várias páginas.

Em sua anatomia ele recebe atributos globais (title, id ,class,...) e o mais importante href, a referência, podendo ser url completa, fragmento, email, telefone e mais diversos outros. há também o atributo de download, que é download="", usado junto do href="",por exemplo, se você colocar o link de uma imagem no href="" com o atributo de download, a imagem será baixada ao invés de irmos até a página e se colocarmos um valor no atributo de download, ele irá dizer como você vai salvar o arquivo.

Por fim temos o atributo target="", que irá dizer qual o alvo do nosso disparo, ou seja, se não tivermos o target, quando clicarmos no link, ele vai pegar o mesmo alvo, a mesma página e apenas vai trocar o conteúdo, mas se usarmos o atributo, por exemplo target="_blank", ele vai abrir uma página com o conteúdo.

---

:ballot_box_with_check: Utilizando a tag âncora

Nesta aula estaremos aprendendo um pouco mais sobre a tag âncora utilizando ela.

    <p>Saiba mais</p>

    <ul>
        <li><a href="#about">Sobre mim</a></li>
        <li><a href="#history">História</a></li>
        <li><a href="#works">Trabalhos</a></li>
    </ul>

    <h1 id="about">Sobre mim</h1>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis eius harum quos similique. Debitis, itaque sit veniam quam recusandae eligendi aspernatur neque deleniti adipisci provident excepturi voluptate, amet corporis laborum.

    <h2 id="history">História</h2>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore velit ab nisi sit quam quis ea provident. Sequi numquam modi, voluptatem velit nulla harum vel quasi nesciunt doloribus est aspernatur.
    Lorem ipsum dolor sit amet consectetur adipisicing elit. A, earum incidunt. Explicabo debitis in quae voluptatem rerum, laborum iste illum dolore vel quidem exercitationem nesciunt eligendi deserunt, quos velit <possimus class="lore"></possimus>

    <h2 id="works">Trabalhos</h2>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci nostrum aspernatur rerum aliquid quae aliquam et harum, vero quibusdam porro. Iusto architecto soluta reprehenderit dolores enim. Earum provident perferendis sapiente.

Neste exemplo temos os fragmentos, com o navegador aberto, se clicarmos em qualquer um deles, será adicionado uma # e o nome do respectivo fragmento, mas como faremos a ligação entre o fragmento e a sua respectiva parte? adicionamos o atributo global id="" e colocamos o nome do fragmento dentro dele, o que faz com que sejamos levados até onde está o id na página.

---

- [ ] Conteúdos dentro de elemento a

---

- [ ] Caminhos e URLS

---

- [ ] Como navegar pelos diretórios

---

- [ ] Caminhos absolutos vs relativos

---

- [ ] Exercício de apresentação

---

- [ ] Exercício de resolução

---

[Voltar](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/guia-estelar-de-html)