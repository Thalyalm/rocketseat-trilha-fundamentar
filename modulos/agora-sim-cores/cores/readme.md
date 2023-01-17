[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/readme.md) /
[Certificado](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/certificado)

---

:ballot_box_with_check: Abertura

Nesse curso vamos aprender a como trabalhar com cores e backgrounds nos nossos elementos. Adicionar cores é algo necessário para qualquer layout e saber como trabalhar com imagens e cores de fundo é essencial.

---

:ballot_box_with_check: Introdução

Cores
    
    Usamos CSS para alterar cores do nosso documento.

Tipos

    background-color (para caixas)
    color (para textos)
    border-color (para caixas)
    outros...

Valores
    
    Podemos definir valores por:

        palavra-chave (blue, transparent)
        hexadecimal (#990011)
        funções (rgb, rgba, hsl, hsla)

---

:ballot_box_with_check: Keyword named values

Nessa aula vamos entender as bases de como aplicar cores no CSS.

HTML

    <div>
        <h1>Um texto aqui</h1>
        <p>Mais texto</p>
    </div>

CSS

    div {
        color: blue;
    }

    h1 {
        color: red;
    }

---

:ballot_box_with_check: Hexadecimal

Nessa aula vamos aprender a trabalhar com valores hexadecimal

    /*<hex-color> values 0-9 e A-F*/
    color: #090; /* RED, GREEN, BLUE */
    color: #009900;
    color: #090a;
    color:#009900aa;

---

:ballot_box_with_check: RGB

RGB → Red, Green e Blue

O alpha representa a transparência da cor

    /*<rgb()> values */
    color: rgb(34, 12, 64, 0.6) /* 0-255 */
    color: rgba(34, 12, 64, 0.6)

---

:ballot_box_with_check: HSL

HSL → Hue - Saturation - Lightness

    color: hsl(180, 100%, 50%, 60%)
    color: hsla(180, 100%, 50%, 60%)

---

:ballot_box_with_check: Global values

Nessa aula vamos ver sobre os valores globais da propriedade color.

    /* Global values */
    color: inheritr; /* Herda a cor do elemento anterior */
    color: initial; /* Volta a sua cor inicial */
    color: unset; /* Pega a cor do contexto */

---

:ballot_box_with_check: Conclusão

Entendendo esses princípios e com a prática, fica cada vez mais fácil entender como aplicar cores no CSS.

Referência: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Ferramenta: https://convertacolor.com/

---

[Voltar](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/agora-sim-cores/readme.md)