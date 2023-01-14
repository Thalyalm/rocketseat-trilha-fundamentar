[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos) /
[Certificado](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/certificado)

---

:ballot_box_with_check: Tabelas

Estaremos vendo agora sobre o elemento &lt;table&gt;, que ajuda na organização de dados, criando tabelas.

Prós
    
    Visualização de dados via linhas e colunas.
    Boa acessibilidade para leitura dos dados 

Contras
    
    Pouco flexível
    Precisa de estilização para melhor visualização 

Não usar
    
    Para criar seu layout

---

:ballot_box_with_check: Organizando Tabelas

Agora vamos dar uma melhor organizada na nossa tabela.

Colocaremos o nosso cabeçalho, na tag &lt;thead&gt;&lt;/thead&gt; e o nosso corpo no &lt;tbody&gt;&lt;/tbody&gt; e criaremos o rodapé usando &lt;tfoot&gt;&lt;/tfoot&gt; colocando os dados total.

Por fim poderemos colocar a tag &lt;caption&gt;&lt;/caption&gt; para descrever sobre o que a nossa tabela é, ficando mais ou menos assim:

    <table>

        <caption>Pessoas por idade</caption>

        <thead>
            <tr>
                <th>Nome</th>
                <th>Idade</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Mayk</td>
                <td>35</td>
            </tr>
            <tr>
                <td>Diego</td>
                <td>25</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td>Total:</td>
                <td>2 Pessoas</td>
            </tr>
        </tfoot>

    </table>

---

:ballot_box_with_check: Tabela básica

Para fazer uma tabela básica, apenas precisaremos da tag &lt;table&gt;&lt;/table>, dentro dela iremos usar a tag &lt;tr&gt;&lt;/tr&gt;(table row) para criar uma linha na tabela, e dentro dela usaremos a tag &lt;th&gt;&lt;/th&gt; para o cabeçalho.

Depois faremos o tr novamente, só que agora não sendo o cabeçalho, e sim o td.

Ficará da seguinte foram:

    <table>
        <tr>
            <th>Nome</th>
            <th>Idade</th>
        </tr>
        <tr>
            <td>Mayk</td>
            <td>35</td>
        </tr>
        <tr>
            <td>Diego</td>
            <td>25</td>
        </tr>
    </table>

Pronto tabela básica.

---

:ballot_box_with_check: Tabela complexa

Estaremos criando uma tabela bem mais complexa, com alguns atributos a mais e uma acessibilidade a mais para tabelas complexas.

Faremos uma tabela que contém 2 lojas, onde estaremos vendo quantos produtos foram vendidos e produzidos e agruparemos por nome dos produtos.

---

:ballot_box_with_check: THead complexa

Veremos como fazer um thead complexo.

    <table>
        <caption>Produzidos x Vendidos por Loja</caption>
        <thead>
            <tr>
                <th rowspan="2"></th>
                <th colspan="2">Afonso Pena</th>
                <th colspan="2">Antônia Pereira</th>
            </tr>
            <tr>
                <th>Produzidos</th>
                <th>Vendidos</th>
                <th>Produzidos</th>
                <th>Vendidos</th>
            </tr>
    </thead>
    </table>

Primeiro de tudo iremos criar o nosso table, colocando a descrição com o caption.

Criaremos o thead para começarmos o nosso cabeçalho, abrimos o tr dentro para linha e colocamos dentro deste tr 3 th, o primeiro sendo vazio.

Na próxima linha já temos os produzidos e vendidos, com o auxilio do emmet, criamos direto 4 th e colocamos os produzidos e vendidos.

Notamos que ainda está desorganizado, então usaremos o atributo rowspan="2", na primeira linha, para ocupar 2 linhas, empurrando os elementos para o lado.

Agora vemos que sobrou 2 colunas vazias, então usaremos o atributo de coluna colspan="2" nas 2 lojas.

---

:ballot_box_with_check: TBody complexo

Veremos como fazer um tbody complexo.

    <table>
        <caption>Produzidos x Vendidos por Loja</caption>

        <thead>
            <tr>
                <th rowspan="2"></th>
                <th colspan="2">Afonso Pena</th>
                <th colspan="2">Antônia Pereira</th>
            </tr>
            <tr>
                <th>Produzidos</th>
                <th>Vendidos</th>
                <th>Produzidos</th>
                <th>Vendidos</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>Vassouras</th>
                <td>50</td>
                <td>30</td>
                <td>20</td>
                <td>20</td>
            </tr>
            <tr>
                <th>Baldes</th>
                <td>10</td>
                <td>10</td>
                <td>30</td>
                <td>25</td>
            </tr>
        </tbody>
    </table>

Dando continuidade a nossa tabela, iremos criar o tbody, abrir uma linha com o tr, colocar o nome do produto, porém ele será um th, ou seja um cabeçalho, e com a ajuda do emmet criaremos 4 td, para colocarmos o tanto de produtos produzidos e vendidos, e repetiremos, mas para outro produto.

---

:ballot_box_with_check: Melhorando o aspecto com colgroup

Colocamos a tag &lt;colgroup&gt;&lt;/colgroup&gt;, dentro colocamos 3 &lt;col&gt;, onde na segunda colocamos o atibuto style="background-color: red" e na terceira style="background-color: blue", porém ainda está desorganizado por isso colocaremos span="2" para alinharmos a cor com a coluna.

    <table>
        <caption>Produzidos x Vendidos por Loja</caption>
    
        <colgroup>
            <col>
            <col span="2" style="background-color: red">
            <col span="2" style="background-color: blue;">
        </colgroup>
        
        <thead>
            <tr>
                <th rowspan="2"></th>
                <th colspan="2">Afonso Pena</th>
                <th colspan="2">Antônia Pereira</th>
            </tr>
            <tr>
                <th>Produzidos</th>
                <th>Vendidos</th>
                <th>Produzidos</th>
                <th>Vendidos</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>Vassouras</th>
                <td>50</td>
                <td>30</td>
                <td>20</td>
                <td>20</td>
            </tr>
            <tr>
                <th>Baldes</th>
                <td>10</td>
                <td>10</td>
                <td>30</td>
                <td>25</td>
            </tr>
        </tbody>
    </table>

---

:ballot_box_with_check: Melhorando acessibilidade

Estaremos usando o atributo scope, que serve permitir que essa acessibilidade saiba que o escopo do cabeçalho é relacionado com, o agrupamento, ou a coluna, ou a linha, o atributo é escrito scope="" .

    <table>
        <caption>Produzidos x Vendidos por Loja</caption>
    
        <colgroup>
            <col>
            <col span="2" style="background-color: red">
            <col span="2" style="background-color: blue;">
        </colgroup>
        
        <thead>
            <tr>
                <th rowspan="2"></th>
                <th colspan="2" scope="colgroup">Afonso Pena</th>
                <th colspan="2" scope="colgroup">Antônia Pereira</th>
            </tr>
            <tr>
                <th scope="col">Produzidos</th>
                <th scope="col">Vendidos</th>
                <th scope="col">Produzidos</th>
                <th scope="col">Vendidos</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th scope="row">Vassouras</th>
                <td>50</td>
                <td>30</td>
                <td>20</td>
                <td>20</td>
            </tr>
            <tr>
                <th scope="row">Baldes</th>
                <td>10</td>
                <td>10</td>
                <td>30</td>
                <td>25</td>
            </tr>
        </tbody>
    </table>

---

[Voltar](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/guia-estelar-de-html)