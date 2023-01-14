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

- [ ] Tabela básica

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

- [ ] Tabela complexa

---

- [ ] THead complexa

---

- [ ] TBody complexo

---

- [ ] Melhorando o aspecto com colgroup

---

- [ ] Melhorando acessibilidade

---

[Voltar](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/guia-estelar-de-html)