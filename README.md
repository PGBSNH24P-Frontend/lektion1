---
author: Lektion 1
date: MMMM dd, YYYY
paging: "%d / %d"
---

# Lektion 1

Hej och välkommen!

## Dagens agenda

1. Introduktion till kurs
   - Kursplan
   - Omniway och GitHub upplägg
   - Uppgifter
2. Introduktion till HTML
3. Introduktion till CSS
4. Övning med handledning
5. Genomgång av övningar
6. Quiz frågor

---

# Webben och webbsidor

En webbsida är ett dokument med HTML, CSS och JavaScript. När du besöker en webbsida laddar du ned ett HTML dokument.

Alla datorer som erbjuder eller hämtar HTML dokument är uppkopplade på 'webben'.

---

# Live Server

Live Server är ett verktyg som hjälper dig att utveckla webbsidor. När du gör en ändring i HTML, CSS eller JavaScript laddas webbsidan om automatiskt.

Det finns som VSCode extension och det finns även självstående verktyg.

Om man använder Live Share kan live servern öppnas och delas med andra.

# Webbläsare och inspektering

Inspekera vilken webbsida som helst direkt i webbläsaren — ofta genom att högerklicka och välja "Inspect" eller liknande.

---

# Vad är HTML?

- Står för 'Hypertext Markup Language'
- Strukturera innehåll på webbsidor
- Används tillsammans med CSS och JavaScript

---

# Exempel HTML dokument

```html
<html>
  <head>
    <title>Min hemsida</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <section>
      <h1>Hej!</h1>
      <p>Mitt namn är William och jag gillar programmering.</p>
    </section>
    <section>
      <h2>Länkar</h2>
      <a href="https://github.com/">GitHub</a>
      <button>Say hi</button>
    </section>
  </body>
</html>
```

---

# HTML Kommentarer

```html
<!-- Detta är en kommentar -->
<!--
Detta
är
också
en
kommentar
-->
```

---

# Taggar och element

Taggar är de minste byggstenarna i HTML.

```html
<tag>
</span>
<div>
</button>
```

Element består av en start tag, slut tag, valfritt innehåll och valfria attributer.

```html
<p id="paragraph">
  Detta är innehållet för p-elementet.
</p>

<div>
  <p>Här ligger ett element innanför ett annat element.</p>
</div>

<tag attribute1="a" attribute2="b">
  Hejsan!
</tag>
```

---

# Vanligt förekommande tags

Vissa tags kommer med funktionalitet och styling utan CSS och JavaScript.

- div
- span
- p
- button
- a
- br
- code
- img
- input
- label
- ul
- li
- script
- style
- section

---

# Innehåll i element

Element kan innehålla text och andra element. Innehållet ligger mellan start- och sluttaggarna.

```html
<div>Detta visar på textinnehåll</div>

<section>
    Denna text, tillsammans med 'span' och 'p’
    elementen, är innehåll till 'div' elementet.
    <span>
        Denna text är innehåll till 'span' elementet.
    </span>
    <p>
        Denna text är innehåll till 'p' elementet.
    </p>
</section>
```

---

# Elementrelationer och hierarkier

Element som ligger innanför andra element bildar relationer:

```html
<parent>
    <child></child>
</parent>
```

---

# Element attributer

Attributer består av information och inställningar på element. Det finns inbyggda attributer och man kan skapa sina egna.

```html
<p id="paragraph"></p>
<img width="100" height="50">
```

---

# Vanligt förekommande attributer

Alla attributer kommer med funktionalitet och/eller styling.

- id
- class
- width
- height
- src
- disabled
- href
- label
- onclick
- onchange
- name

---

# Basfil för HTML

Alla HTML filer består av:

```html
<html>
  <head>
    <!-- Här inne ligger meta information som titeln på webbsidan, styles, skript och mer. -->
  </head>
  <body>
    <!-- Här inne ligger innehållet på sidan som element och text -->
  </body>
</html>
```

---

# Vad är CSS?

- Står för 'Cascading Style Sheets'
- Designa innehåll på webbsidor (storlek, position, färg m.m)
- Används tillsammans med HTML och JavaScript

```html
<html>
  <head>
    <title>Min hemsida</title>
    <style></style>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body></body>
</html>
```

---

# Exempel CSS dokument

```css
h1 {
  margin-left: 50px;
}

.primary-button {
  border: 5px solid green;
  border-radius: 4px;
}

#github {
  font-size: xx-small;
}

div .shop {
  background-color: red;
}
```

---

# CSS Kommentarer

```css
/* Detta är en kommentar */
/*
Detta
är
också
en
kommentar
*/
```

---

# CSS egenskaper

Egenskaper bestämmer färg, storlek, position och mer på HTML element.

```css
div {
  background-color: red;
  margin: 10px;
  padding: 1px;
  display: block;
}
```

---

# Vanligt förekommande egenskaper

- margin
- padding
- border
- background
- background-color
- color
- display
- scale
- flex
- translate
- width
- height

---

# CSS selectors

- Applicerar egenskaper på element
- Typer
  - type selector
  - class selector
  - id selector

```css
div {} /* Type selector */
.divs {} /* Class selector */
#my-div {} /* Id selector */
```

```html
<div>Hej</div>
<div class="divs">Hej</div>
<div id="my-div">Hej</div>
```

---

# CSS selector ordning

Selectors appliceras i följande ordning:

1. Inline
2. Id
3. Class
4. Type/Tag/Element
5. Universal

Detta är relevant i de fall flera selectors har samma egenskap.

---

# Övning med handledning

Nu övar vi! Övningar ligger på GitHub.

Vi samlas och går igenom några av dem efteråt. Skriv ned övningar som är svåra eller som ni vill ha mer förklaring kring.

---

# Quiz frågor

- Vad är den minsta byggstenen i HTML?
- Vad är element?
- Vad är syntaxen för element-attributer?
- Vad gör CSS egenskaper?
- Ge två exempel på selectors med typ och syntax.
- Vilken tag används för knappar?
- Vilken tag används för titlar?
- Vilka tags används för listor?
- Vilken egenskap ändrar textfärg?
- Vilken egenskap ändrar bakgrundsfärg?
- Vilka egenskaper ändrar utrymme?
