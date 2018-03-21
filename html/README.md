# HTML

## References

* HTML Awesome [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/diegocard/awesome-html5)
* Portais: [W3C](https://www.w3.org/standards/webdesign/htmlcss), [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML) e  [WP](https://docs.webplatform.org/wiki/html)
* Guias: [MDN](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML) e [WP](https://docs.webplatform.org/wiki/html/tutorials)
* Versões: [Draft](https://w3c.github.io/html/), [5.1](https://www.w3.org/TR/html51/), [5](https://www.w3.org/TR/html5/), [4.01](https://www.w3.org/TR/html4/), [outras versões](https://www.w3.org/QA/2002/04/valid-dtd-list.html); HTML5 ([Features](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) e [Demo](http://html5demos.com/))
* Cheat Sheet: [Websitesetup](https://websitesetup.org/html5-cheat-sheet/), [Frontend Cheat Sheets](https://github.com/logeshpaul/Frontend-Cheat-Sheets)

## HTML Elements

* Reference: [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element), [WP](https://docs.webplatform.org/wiki/html/elements) e [W3C](https://www.w3.org/TR/2014/REC-html5-20141028/index.html) (tabela comparativa: [w3school](http://www.w3schools.com/tags/ref_html_dtd.asp), [triin](http://www.triin.net/temp/html-elements.html))
* [Title Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title): (Description, Attributes, Usage, Example, Specifications, Browser compatibility)

[`hello/index.html`](hello/index.html):
```html
<!DOCTYPE html>
<html>
<head>
  <title>Bem-vindos</title>
</head>
<body>
  <h1>Olá, turma!</h1>
  <p>Meu primeiro parágrafo</p>
</body>
</html>
```

## HTML DOCTYPE

* Reference:
  * [Recommended Doctype Declarations to use in your Web document \| W3C](https://www.w3.org/QA/2002/04/valid-dtd-list.html)
  * [Doctypes and markup styles \| W3C](https://www.w3.org/wiki/Doctypes_and_markup_styles)
  * [Quirks Mode and Standards Mode \| MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Quirks_Mode_and_Standards_Mode)
  * [Obsolete and deprecated elements \| MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Obsolete_and_deprecated_elements)
  * [Dialog Element | Can I Use](https://caniuse.com/#feat=dialog)

### HTML5
```html
<!DOCTYPE html>
```

### HTML 4.01

#### Strict
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
   "http://www.w3.org/TR/html4/strict.dtd">
```

#### Transitional
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
   "http://www.w3.org/TR/html4/loose.dtd">
```

#### Frameset
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN"
   "http://www.w3.org/TR/html4/frameset.dtd">
```

### XHTML 1.0

#### Strict
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
   "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
```

#### Transitional
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
   "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

#### Frameset
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN"
   "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">
```

## HTML Attributes

* Reference: MDN([1](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes) e [2](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)), [WP](https://docs.webplatform.org/wiki/html/attributes) e [W3C](https://www.w3.org/TR/2014/REC-html5-20141028/index.html)
* [Global Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)
* [Meta attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#Attributes)
* [HTML attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html#Attributes)

[`hello-attr/index.html`](hello-attr/index.html):
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>
  <h1>Olá, turma!</h1>
  <p>Meu primeiro parágrafo</p>
</body>
</html>
```

## HTML Entities

* Reference: W3C ([1](https://dev.w3.org/html5/html-author/charref) e [2](https://www.w3.org/TR/html51/syntax.html#named-character-references))

| Char | Description | Unicode |Entity Name | Entity Code (Hex) |  Entity Code (Dec) |
|-|-|-|-|-|-|
| ! | EXCLAMATION MARK | U+00021 | &amp;excl; | &amp;#x00021; | &amp;#33; |
| & | AMPERSAND | U+00026 | &amp;amp; &amp;AMP; | &amp;#x00026; | &amp;#38; |
| < | LESS-THAN SIGN | U+0003C | &amp;lt; &amp;LT; | &amp;#x0003C; | &amp;#60; |
| > | GREATER-THAN SIGN | U+0003E | &amp;gt; &amp;GT; | &amp;#x0003E; | &amp;#62; |
| © | COPYRIGHT SIGN | U+000A9 | &amp;copy; &amp;COPY; | &amp;#x000A9; | &amp;#169; |
| á | LATIN SMALL LETTER A WITH ACUTE | U+000E1 | &amp;aacute; | &amp;#x000E1; | &amp;#225;|

**Examples**

[`entity/index.html`](entity/index.html):
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  <!-- Exemplos de Entidades -->
  <p>Para criar um parágrafo em HTML é necessário usar a tag &lt;p>.</p>
  <p>A entidade &amp;lt; no HTML cria o caracter <.</p>
  <p>Para exibir o © no HTML usamos a entidade &amp;copy;.</p>
</body>
</html>
```

## HTML Comments

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>
  <!-- Cabeçalho -->
  <h1>Olá, turma!</h1>
  
  <!-- Conteúdo -->
  <p>Meu primeiro parágrafo</p>
</body>
</html>
```

## [Document metadata](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Document_metadata)

* [Guide to <head> elements (Elements, Meta, Link, Icons, Social, Browsers, App Links, Other Resources)](https://gethead.info)
* [HTML5 Cheat sheet by Hackr.io](https://github.com/LeCoupa/awesome-cheatsheets/blob/master/frontend/html5.html)
* [Favicon](https://en.wikipedia.org/wiki/Favicon)

## [Content sectioning](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Content_sectioning), [Text content](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Text_content), [Inline text](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Inline_text_semantics)

* Elements:
  * [`<p>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)
  * [`<h1>`-`<h6>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)
  * [`<b>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/b)
  * [`<i>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/i)

## Lists

* Elements:
  * [`<ol>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
  * [`<ul>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
  * [`<dl>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl)
* Attributes:
  * [`<ol>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol#Attributes): `type`

### Ordered List

[`list`](list/):
```html
<p>Developer Roles:</p>
<ol>
  <li>Web developer</li>
  <li>Desktop applications developer</li>
  <li>Mobile developer</li>
</ol>
```

Output:
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0;">
  <p>Developer Roles:</p>
  <ol>
    <li>Web developer</li>
    <li>Desktop applications developer</li>
    <li>Mobile developer</li>
  </ol>
</div>

### Ordered List (type) 

[`list`](list/):
```html
<p>Developer Roles:</p>
<ol type="a">
  <li>Web developer</li>
  <li>Desktop applications developer</li>
  <li>Mobile developer</li>
</ol>
```
Output:
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0;">
  <p>Developer Roles:</p>
  <ol type="a">
    <li>Web developer</li>
    <li>Desktop applications developer</li>
    <li>Mobile developer</li>
  </ol>
</div>

### Unordered List 

[`list`](list/):
```html
<p>Cursos da UAI:</p>
<ul>
  <li>Redes de Computadores</li>
  <li>Sistemas para Internet</li>
</ul>
```

Output:
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0;">
  <p>Cursos da UAI:</p>
  <ul>
    <li>Redes de Computadores</li>
    <li>Sistemas para Internet</li>
  </ul>
</div>

### Unordered List (nested) 

[`list`](list/):
```html
<p>Conceitos do Front-End:</p>
  <ul>
    <li>HTML
      <ul>
        <li>Tag</li>
        <li>Atributo</li>
        <li>Entidade</li>
        <li>Comentário</li>
      </ul>
    </li>
    <li>CSS</li>
  </ul>
```
Output:
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0;">
<p>Conceitos do Front-End:</p>
  <ul>
    <li>HTML
      <ul>
        <li>Tag</li>
        <li>Atributo</li>
        <li>Entidade</li>
        <li>Comentário</li>
      </ul>
    </li>
    <li>CSS</li>
  </ul>
</div>

### Definition List 

[`list`](list/):
```html
  <p>Tecnologias do Front-End:</p>
  <dl>
    <dt>HTML</dt>
    <dd>Hyper Text Markup Language</dd>
    <dt>CSS</dt>
    <dd>Cascade Style Sheet</dd>
  </dl>
```
Output:
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0;">
  <p>Tecnologias do Front-End:</p>
  <dl>
    <dt>HTML</dt>
    <dd>Hyper Text Markup Language</dd>
    <dt>CSS</dt>
    <dd>Cascade Style Sheet</dd>
  </dl>
</div>

> [first-web-page](first-web-page/)

## Hyperlink

* Elements:
  * [`<a>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)
* Attributes:
  * [`<a>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#Attributes): `href`

<!-- <a href="http://www.ifpb.edu.br/">ifpb</a>
<a href="http://www.ifpb.edu.br/" target="_blank">ifpb</a>
<a href="sobre.html">sobre</a> -->

## Image and multimedia

* Elements:
  * [`<img>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)
* [Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#Attributes):
  * [`src`]()
  * [`alt`]()
* [Image Data URI](https://css-tricks.com/data-uris/)

### Examples

```
<img src="" alt="">
```

## Table content

### `<table>`

- Elements: 
  - `<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`
- Attributes: 
  - `border`, `colspan`, `rowspan`

## Forms

- Elements:
  - `<form>`
- Form HTML: [html5doctor](http://html5doctor.com/html5-forms-introduction-and-new-attributes/), [W3C](https://www.w3.org/TR/html5/forms.html)

<!-- TODO convert img2md -->
![widgets](form/form_elements.png)

<!-- 
  TODO
  Robots.txt: [robots](http://www.robotstxt.org/robotstxt.html) e [robots do g1.com](http://g1.globo.com/robots.txt)
 -->

 ## Web Resourses
