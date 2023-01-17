[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/readme.md) /
[Certificado](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/certificado)

---

:ballot_box_with_check: Abertura

Nesse curso vamos aprender como funciona o Box Model, espaçamentos, preenchimentos, bordas, além dos display-block e display-inline. Esses são conceitos base que vão te ajudar a evoluir muito no CSS.

---

:ballot_box_with_check: Introdução

O Box Model é fundamental para fazer layouts para web porque ele vai te dar maior facilidade na hora de aplicar o CSS. Ao entender os conceitos do Box Model muitas questões do CSS começam a fazer sentido.

O que é o Box Model?

Cada elemento é representado como uma caixa retangular
Essa caixa possui propriedades de uma caixa em 2 dimensões (largura x altura)

Propriedades da caixa

    Tamanho (largura x altura) → width | height
    Conteúdo → content
    Bordas → border
    Preenchimento interno → padding
    Espaços fora da caixa → margin

---

:ballot_box_with_check: Box Sizing

Nessa aula vamos ver sobre o box-sizing que é o responsável pelo calculo do tamanho total da caixa (box).

Podemos usar a ferramenta de desenvolvedor do próprio navegador para visualizar as especificações dos elementos da página

Quando o padding é adicionado (padding: 0 20px;) faz com que aumente a largura da caixa, deixando de respeitar os 100px de largura.

E é por isso que é tão importante conhecer a propriedade do box-sizing.

Por padrão o navegador vai calcular o tamanho da caixa pelo content-box e vai somar com os outros boxes, no exemplo acima no lugar de 100px a caixa vai ficar com uma largura de 140px. Para que isso não aconteça, é possível mudar qual vai ser a referência para o calculo do tamanho da caixa adicionando a propriedade box-sizing: border-box;.

Dessa forma o elemento vai ficar com a largura (width) determinado, que no caso do exemplo citado é de 100px.

Normalmente usa-se o código abaixo como forma de "resetar" o box-sizing que vem por padrão nos navegadores.

    * {
    box-sizing: border-box;
    }

O seletor * seleciona todos os elementos da página.

---

:ballot_box_with_check: Display-block-inline

display: block; vs display: inline;

Como as caixas se comportam em relação as outras caixas

Comportamento externo das caixas

Display Block

    Ocupa toda a linha, colocando o próximo elemento abaixo desse

    width e height são respeitados

    padding, margin, border irão funcionar normalmente

Exemplo

    <p> <div> <section>, todos os headings <h1> <h2>...

Display Inline

    Os elementos ficam ao lado do outro e não empurram outros elementos para baixo

    width e height não funcionam

    Somente valores horizontais de margin

Exemplo

    <a> <strong> <span> <em>

---

:ballot_box_with_check: Margin

Margin, é o espaço (margem) entre os elementos

Podemos dividir o margin em 4 valores:

    margin-top | margin-right | margin-bottom | margin-left */

    values: <length> | <percentage> | auto

Geralmente usamos uma forma abreviada (shorthand) para escrever o margin. Esse formato segue o sentido horário iniciando pelo top, seguindo para right, bottom e left.

    margin: 12px 16px 10px 4px; /* TOP = 12px | RIGHT = 16px | BOTTOM = 10px | LEFT = 4px */
    margin: 12px 16px 0; /* TOP = 12px | RIGHT = 16px | BOTTOM = 0px | LEFT = 16px */
    margin: 8px 16px; /* TOP = 8px | RIGHT = 16px | BOTTOM = 8px | LEFT = 16px */
    margin: 8px; /* TOP = 8px | RIGHT = 8px | BOTTOM = 8px | LEFT = 8px */

O margin é aplicado em elementos com display block

Cuidado com o margin collapsing que é quando o top se junta ao bottom

---

- [ ] Padding

---

- [ ] Border-outline

---

[Voltar](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/uma-caixa-dentro-da-outra/readme.md)