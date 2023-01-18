[Início](https://github.com/Thalyalm/rocketseat-trilha-fundamentar) /
[Módulos](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/readme.md) /
[Certificado](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/certificado)

---

:ballot_box_with_check: Font-variant e font-stretch

Font Variant

Faz variações na apresentação da fonte

Script:

    p {
        font-variant: small-caps;
    }

Referência: https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant

Font Stretch

Alargamento ou encolhimento da fonte

Aceita palavras-chaves como: expanded, condensed, normal

Aceita porcentagens de 50% a 200%

Essa propriedade não vai funcionar em todas as fontes

Script:

    p {
        font-stretch: expanded;
    }

Referência: https://developer.mozilla.org/en-US/docs/Web/CSS/font-stretch

Referência: https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals

---

:ballot_box_with_check: Letter e word-spacing

Letter spacing

Define o espaçamento entre os caracteres

Script:

    p {
        letter-spacing: 4px;
    }

Referência: https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing

Word spacing

Define o espaçamento entre palavras

Script:

    p {
        word-spacing: 1em;
    }

Referência: https://developer.mozilla.org/en-US/docs/Web/CSS/word-spacing

---

:ballot_box_with_check: Line-height e text-transform

Line height

Define os espaços entre linhas

Pode ser com unidades ou sem unidades de medida

Valores comuns: 1.5 ou 2

Script:

    p {
        line-height: 1.5;
    }

Referência: https://developer.mozilla.org/en-US/docs/Web/CSS/line-height

Text transform

Transformação do texto

Valores podem ser: none | capitalize | uppercase | lowercase | full-width | full-size-kana

Script:

    p {
        text-transform: uppercase;
    }

Referência: https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform

---

:ballot_box_with_check: Text-decoration

Aparência decorativa de um texto

Line:
    
    underline | overline | line-through

Podemos aplicar mais de 1 valor

Style:

    wavy | dotted | double | dashed | solid

Color:

    <color> values

Script:

    h1 {
        text-decoration: underline; /* shorthand */
    }

    p {
    text-decoration: wavy overline blue; /* shorthand */
    }

Referência: https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration

---

:ballot_box_with_check: Text-align

Alinhamento de um texto

Valores:
    start | end | left | right | center | justify | match-parent

Script:

    p {
        text-align: center;
    }

Referência: https://developer.mozilla.org/en-US/docs/Web/CSS/text-align

---

:ballot_box_with_check: Text-shadow

Sombra aplicada a um texto

Permite múltiplos valores

Script:

    p {
    text-shadow: 1px 1px 1px red,
            2px 2px 1px green; /* offset-x | offset-y | blur-radius | color */
    }

Referência: https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow

---

- [ ] Shorthand

---

[Voltar](https://github.com/Thalyalm/rocketseat-trilha-fundamentar/tree/main/modulos/app-bonito-ate-nos-textos/readme.md)