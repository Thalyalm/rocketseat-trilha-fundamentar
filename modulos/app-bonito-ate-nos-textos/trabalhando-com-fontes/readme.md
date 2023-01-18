[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/readme.md) /
[Certificado](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/certificado)

---

:ballot_box_with_check: Abertura

Nesse curso vamos aprender aplicar estilos CSS nos textos para deixar nossos layouts mais interessantes.

---

:ballot_box_with_check: Introdução font-properties

A tipografia transmite uma mensagem, por exemplo, quando queremos dar uma ênfase no texto nós podemos escrever o mesmo em negrito.

Nós podemos transmitir uma mensagem diferente dependendo do estilo que escrevemos o texto.

Algumas das propriedades de fonts do CSS que podem nos ajudar a transmitir uma mensagem através dos textos da página são:

    font-family
    font-weight
    font-style
    font-size

---

:ballot_box_with_check: Font-family

Tipo de fonte de um elemento

Lista de fontes e ordem de prioridade

inclui fallback font
    
    p {
    font-family: "Times New Roman", Times, serif;
    }

Alguns tipos de fonts:
    
    serif (com serifa)
    sans-serif (sem serifa)

---

:ballot_box_with_check: Font-weight

Peso da fonte

Valores: normal | bold | bolder | lighter | 100 | 200 | 300 | 400 | 500 | 600 | 700 | 800 | 900

Dependendo da família da fonte não conseguimos utilizar todos os pesos de fonte

    p {
        font-weight: bold;
    }

Referência: https://www.w3.org/TR/css-fonts-3/

---

:ballot_box_with_check: Font-style

É o estilo da fonte

Valores: normal | italic | oblique

Os valores que podem ser aplicados dependem da fonte usada
    
    span {
        font-style: italic;
    }

---

:ballot_box_with_check: Font-size

Tamanho da fonte

p {
	font-size: 18px;
}

---

:ballot_box_with_check: Web-fonts

Fontes do sistema x Fontes da web

Fontes do sistema são as fontes que estão instaladas na máquina do usuário e nem sempre o cliente vai ter instalado as fontes usadas no projeto e isso pode fazer com que os estilos dos textos não sejam aplicados corretamente, mas para resolver esses casos podemos preparar nossas fonts para web ou usar fontes da web.

Como usar fontes para web?
    @font-face
    @import
    link

Referência: https://fonts.google.com/

---

[Voltar](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/app-bonito-ate-nos-textos/readme.md)