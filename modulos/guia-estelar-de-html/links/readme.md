[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/readme.md) /
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

:ballot_box_with_check: Conteúdos dentro de elemento a

Estaremos vendo o que podemos colocar dentro do conteúdo do elemento &lt;a&gt;&lt;/a&gt;.

Qualquer coisa pode ser colocado, até mesmo outras tags, e mais de uma.

    <a href="http://google.com" title="Ir para google">
        <h1>Google</h1>
        <p>Claro que posso</p>
        <img src="https://source.unsplash.com/random" alt="">
    </a>

Neste exemplo há até imagens.

---

:ballot_box_with_check: Caminhos e URLS

Algo importante que precisamos saber ao criar links é como navegar neles, juntamente em como navegar no caminho dos arquivos.

No caso dos links são as URLs, que são sequencia de texto que define onde algo está localizado na web , por exemplo https://rocketseat.com.br, ela mostrando que esse endereço levará para algum lugar da web.

No caso dos arquivos, são os seus caminhos, onde, no explorador de arquivos, um recurso está localizado, podendo ser imagem, pdf, qualquer arquivo basicamente, abrindo alguns arquivos do nosso projeto no VSCode, usando o elemento a, iremos escrever ao invés de https://..., apenas o nome do arquivo, o próprio VSCode possui a inteligência de saber que o arquivo está lá, lembrando que também podemos usar os atributos que usamos nas URLs.

---

:ballot_box_with_check: Como navegar pelos diretórios

Estaremos vendo nesta aula como navegar pelos diretórios.

    <a href="hyperlinks.html">arquivo na pasta anterior</a>
    <br>
    <a href="./urls-caminhos.html">arquivo no diretório raiz</a>
    <br>
    <a href="urls-caminhos.html">arquivo na mesma pasta</a>
    <br>
    <a href="outros/conteudo-a-element.html">arquivo na pasta outros, que está na pasta anterior</a>

Para o mesmo diretório, local, raiz apenas colocamos o nome do arquivo no href.

Para entrar em um diretório colocamos o nome do diretório e /, como no exemplo "outros/conteudo-a-element.html"

Para sair de um diretório colocamos ../ ,ele sairá do diretório, semelhante a sair de uma caixa que está dentro de outro.

E por fim o diretório raiz especificamente, usamos apenas ./ , o próprio VSCode irá completar.

Caso você coloque um arquivo que não existe ou mesmo está no diretório errado, vai dar erro de não ter encontrado o arquivo.

---

:ballot_box_with_check: Caminhos absolutos vs relativos

No caminho absoluto inclui-se o protocolo e o nome de domínio e sempre apontará para o mesmo local, já que é absoluto. Como por exemplo esta URL http://www.rocketseat.com.br/projeto/index.html é absoluto(mesmo não levando a lugar nenhum, é apenas um exemplo).

No caminho relativo, é relativo à página, pasta aberta, ou seja, se não tiver irá consequentemente dar erro, apontará para lugares diferentes. Como por exemplo apenas google.com.

---

:ballot_box_with_check: Exercício de apresentação

Criando navegação entre os arquivos:

Crie um projeto contendo

        2 arquivos no diretório principal (index.html e contact.html)

        1 diretório de nome: files
            Dentro desse diretório adicione 2 imagens da sua preferência e 1 arquivo de nome images.html, que irá listar as imagens

Dentro de cada arquivo .html, você deverá colocar:

    1. Menu de navegação com uma lista <li></li> não ordenada <ul></ul>

    2. título <h1></h1> da página

    3. Um mais parágrafos <p></p> com informações da página

A Navegação:

Para o menu de navegação use a tag &lt;nav&gt;&lt;/nav&gt; e coloque a lista não ordenada como conteúdo da tag.

O conteúdo do link deverá ser o nome da página .html que existe no projeto, sendo que para cada página, iremos ter um link.

Ao clicarmos no link, deveremos ser direcionados à página clicada.

Páginas imagens.html:

Como conteúdo desta página, além do que foi pedido, adicionar também

    1. As duas imagens que você tem na pasta;

    2. Use a tag p para colocar a tag img.

Obs: Imagens de tamanho muito grande, poderão não se adaptar bem, mas não se preocupe com isso agora, pois logo aprenderemos a como melhorar isso.

Página contact.html:

Como conteúdo desta página, além do que foi pedido, adicionar também:

    1. Colocar suas informações de contato: email e telefone;

    2. Cada informação deverá estar dentro de um link que quando clicado, irá abrir a respectiva informação de contato (email ou telefone)
    Dicas

Para o conteúdo da tag &lt;p&gt;&lt;/p&gt;, se desejar, poderá fazer o uso do atalholorem que existe no Visual Studio Code.
Para isso digite lorem e em seguida aperte tab.

Atenção: Alguns computadores isso pode não funcionar, portanto, ão atenha a isso e continue o exercício sem essa dica.

---

:ballot_box_with_check: Exercício de resolução

Resolução da atividade

index.html

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Homepage</title>
    </head>
    <body>
        
        <nav>
            <ul>
                <li>
                    <a href="index.html">Homepage</a>
                </li>
                <li>
                    <a href="files/images.html">Minhas Imagens</a>
                </li>
                <li>
                    <a href="contact.html">Contato</a>
                </li>
            </ul>
        </nav>
      
        <h1>Homepage</h1>

        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas deleniti qui possimus eaque consectetur itaque animi. Pariatur voluptates illum deserunt assumenda! Doloribus in asperiores eos sapiente ea fugit perferendis repellat.</p>
    </body>
    </html>

contact.html

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Contato</title>
    </head>
    <body>
        <nav>
            <ul>
                <li>
                    <a href="index.html">Homepage</a>
                </li>
                <li>
                    <a href="files/images.html">Minhas Imagens</a>
                </li>
                <li>
                    <a href="contact.html">Contato</a>
                </li>
            </ul>
        </nav>

        <h1>Contato</h1>

        <p>Fale comigo</p>

        <ul>
            <li>
                <a href="mailto:meuemail.com">meuemail@email.com</a>
            </li>
            <li>
                <a href="tel:8877776666">(88) 7777 6666</a>
            </li>
        </ul>
    </body>
    </html>

imagens.html

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Imagens</title>
    </head>
    <body>
        <nav>
            <ul>
                <li>
                    <a href="../index.html">Homepage</a>
                </li>
                <li>
                    <a href="images.html">Minhas Imagens</a>
                </li>
                <li>
                    <a href="../contact.html">Contato</a>
                </li>
            </ul>
        </nav>

        <h1>Minhas imagens</h1>

        <p>Olha isso!</p>

        <p>
            <img src="./1.jpeg" alt="Imagem 1">
            <img src="./2.jpeg" alt="Imagem 2">
        </p>
        
    </body>
    </html>

---

[Voltar](/modulos/guia-estelar-de-html/readme.md)