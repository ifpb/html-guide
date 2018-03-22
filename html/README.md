# HTML

<!-- Summary -->

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
  * [Dialog Element \| Can I Use](https://caniuse.com/#feat=dialog)

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

**Examples**

> [first-web-page](first-web-page/)

## Hyperlink

* Elements:
  * [`<a>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)
* Attributes:
  * [`<a>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#Attributes): `href`, `target`

### Example

```
hyperlink = content + url

content = text, image...

<a href="url">content</a>
```

```html
<a href="http://www.ifpb.edu.br/">ifpb</a>
<a href="http://www.ifpb.edu.br/" target="_blank">ifpb</a>
```

### Absolute URL

#### Desktop

```
/
└── home
    └── username
        └── site
            └── pages
                ├── contact.html
                └── index.html
```

**index.html**

```html
<a href="/home/username/site/pages/index.html">home</a>
<a href="file:///home/username/site/pages/index.html">home</a>
```

**contact.html**

```html
<a href="/home/username/site/pages/contact.html">contact</a>
<a href="file:///home/username/site/pages/contact.html">contact</a>
```

#### Server

```
/
└── var
    └── www
        └── site
            └── pages
                ├── contact.html
                └── index.html
```

> (/var/www/site/ = http://site.com/)

**index.html**

```html
<a href="/var/www/site/pages/index.html">home</a>
<a href="http://site.com/pages/index.html">home</a>
<a href="http://site.com/pages/">home</a>
```

**contact.html**

```html
<a href="/var/www/site/pages/contact.html">contact</a>
<a href="http://site.com/pages/contact.html">contact</a> 
<a href="/pages/contact.html">contact</a>
```

#### Examples
```
http://www.ifpb.edu.br
http://www.ifpb.edu.br/institucional/sobre-o-ifpb
file://C:/WINDOWS/image.png
C:/WINDOWS/image.png
ftp://ftp.gnu.org/pub/
```

### Relative URL

```
/
└── var
    └── www
        └── site
            └── pages
                ├── contact.html
                └── index.html
```

**index.html -> contact.html**
```html
<a href="contact.html">contact</a>
<a href="./contact.html">contact</a>
```

```
/
└── var
    └── www
        └── site
            ├── pages
            │   └── contact.html
            └── index.html
```

**index.html -> contact.html**
```html
<a href="pages/contact.html">contact</a>
<a href="./pages/contact.html">contact</a>
```

```
/
└── var
    └── www
        └── site
            ├── pages
            │   └── html
            │       └── contact.html
            └── index.html
```

**index.html -> contact.html**
```html
<a href="pages/html/contact.html">contact</a>
<a href="./pages/html/contact.html">contact</a>
```

```
/
└── var
    └── www
        └── site
            ├── pages
            │   └── contact.html
            └── public
                └── index.html
```

**index.html -> contact.html**
```html
<a href="../pages/contact.html">contact</a>
```

```
/
└── var
    └── www
        └── site
            ├── pages
            │   └── contact.html
            └── public
                └── html
                    └── index.html
```

**index.html -> contact.html**
```html
<a href="../../pages/contact.html">contact</a>
```

#### Examples

```html
<a href="home.html">home</a>
<a href="./home.html">home</a>
<a href="pages/home.html">home</a>
<a href="./pages/home.html">home</a>
<a href="../page/home.html">home</a>
```

### URL#ID

```html 
<a href="https://en.wikipedia.org/wiki/HTML#History">HTML History</a>
```

<a href="https://en.wikipedia.org/wiki/HTML#History">HTML History</a>

```html
<h1>Sumário</h1>

<ul>
  <li>Dolor ipsum</li>
  <li>Ipsum dolor</li>
</ul>

<h1>Dolor ipsum</h1>
<p>…</p>
<h1>Ipsum dolor</h1>
<p>…</p>
```

```html
<h1>Sumário</h1>

<ul>
  <li>
    <a href="#dolor_ipsum">Dolor ipsum</a>          
  </li>
  <li>
    <a href="#ipsum_dolor">Ipsum dolor</a>
  </li>
</ul>

<h1 id="dolor_ipsum">Dolor ipsum</h1>
<p>…</p>
<h1 id="ipsum_dolor">Ipsum dolor</h1>
<p>…</p>
```

### App links

```html
<a target="_blank" href="mailto:cstsi@ifpb.edu.br">cstsi@ifpb.edu.br</a>
<a target="_blank" href="sms:83999999999">(83) 9.9999-9999</a>
<a target="_blank" href="tel:83999999999">(83) 9.9999-9999</a>
<a target="_blank" href="whatsapp://send?text=Solu%C3%A7%C3%A3o%20Tempor%C3%A1ria%20https%3A%2F%2Fvidadesuporte.com.br%2Fsuporte-a-serie%2Fsolucao-temporaria%2F">whatsapp</a>
```

## Image and multimedia

* Elements:
  * [`<img>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)
* Attributes
  * [`<img>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#Attributes): `src`, `alt`, `title`, `width`, `height`

### Examples

```html
<img src="url" alt="text alternative">
```

### Image URL

```
/
└── var
    └── www
        └── site
            └── pages
                ├── home.html
                └── image.png
```

**home.html -> image.png**
```html
<img src="image.png" alt="Image Description">
<img src="./image.png" alt="Image Description">
<img src="/pages/image.png" alt="Image Description">
<img src="http://site.com/pages/image.png" alt="Image Description">
<img src="/var/www/site/pages/image.png" alt="Image Description">
```

```
/
└── var
    └── www
        └── site
            └── pages
                ├── home.html
                └── img
                    └── image.png
```

**home.html -> image.png**
```html
<img src="img/image.png" alt="Image Description">
<img src="./img/image.png" alt="Image Description">
<img src="/pages/img/image.png" alt="Image Description">
<img src="http://site.com/pages/img/image.png" alt="Image Description">
```

```
/
└── var
    └── www
        └── site
            ├── pages
            |   └── home.html
            └── img
                └── image.png
```

```html
<img src="../img/image.png" alt="Image Description">
<img src="/img/image.png" alt="Image Description">
<img src="http://site.com/img/image.png" alt="Image Description">
```

```
(/var/www/site = http://site.com/)
/
└── var
    └── www
        └── site
            └── home.html

(/var/www/site = http://site2.com/)
/
└── var
    └── www
        └── site
            └── img
                └── image.png
```

**home.html -> image.png**

```html
<img src="http://site2.com/img/image.png" alt="Image Description">
```

### Raster vs Vector

#### PNG (Raster)
**150px**<br>
<img src="assets/ifpb-logo.png" alt="logo ifpb" width="150px">

**2000px**
<div style="width: 200px; height: 200px; background-image: url('assets/ifpb-logo.png'); background-size: 2000px;"></div>

#### SVG (Vector)
**150px**<br>
<img src="assets/ifpb-logo.svg" alt="logo ifpb" width="150px">

**2000px**
<div style="width: 200px; height: 200px; background-image: url('assets/ifpb-logo.svg'); background-size: 2000px;"></div>

### Data URI

* [Image Data URI](https://css-tricks.com/data-uris/)
* [Data URI Generator](https://dopiaza.org/tools/datauri/index.php)

![logo ifpb](assets/ifpb.png)

```html
<img src="data uri" alt="text alternative">
```

**data:image/png;base64**
```
data:image/png;base64,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
```

### Image + Hyperlink

```html
<a href="url">
  <img src="url" alt="text alternative">
</a>
```

```html
<a href="http://ifpb.edu.br/">
  <img src="ifpb.png" alt="logo IFPB">
</a>
```

Output:<br>
[![logo ifpb](assets/ifpb.png)](http://ifpb.edu.br/)

## Table content

### `<table>`

- Elements: 
  - `<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`
- Attributes: 
  - `border`, `colspan`, `rowspan`

#### `<table>`, `<tr>`, `<th>`, `<td>`

```html
<table>
  <tr>
    <th>Language</th>
    <th>Creator</th>
  </tr>
  <tr>
    <td>Python</td>
    <td>Guido van Rossum</td>
  </tr>
  <tr>
    <td>Javascript</td>
    <td>Brendan Eich</td>
  </tr>
</table>
```

Output:
<div>
  <table>
    <tr>
      <th>Language</th>
      <th>Creator</th>
    </tr>
    <tr>
      <td>Python</td>
      <td>Guido van Rossum</td>
    </tr>
    <tr>
      <td>Javascript</td>
      <td>Brendan Eich</td>
    </tr>
  </table>
</div>

#### `<thead>`, `<tbody>`, `<tfoot>`

```html
<table>
  <thead>
    <tr>
      <th>Language</th>
      <th>Creator</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Python</td>
      <td>Guido van Rossum</td>
    </tr>
    <tr>
      <td>Javascript</td>
      <td>Brendan Eich</td>
    </tr>
  </tbody>
</table>
```

Output:
<div>
  <table>
    <thead>
      <tr>
        <th>Language</th>
        <th>Creator</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Python</td>
        <td>Guido van Rossum</td>
      </tr>
      <tr>
        <td>Javascript</td>
        <td>Brendan Eich</td>
      </tr>
    </tbody>
  </table>
</div>

#### `<thead>`, `<tbody>`, `<tfoot>`

```html
<table>
  <thead>
    <tr>
      <th>Language</th>
      <th>Creator</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Python</td>
      <td>Guido van Rossum</td>
    </tr>
    <tr>
      <td>Javascript</td>
      <td>Brendan Eich</td>
    </tr>
    <tr>
      <td>C</td>
      <td rowspan="2">Dennis Ritchie</td>
    </tr>
    <tr>
      <td>B</td>
    </tr>
  </tbody>
</table>
```

Output:
<div>
  <table>
    <thead>
      <tr>
        <th>Language</th>
        <th>Creator</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Python</td>
        <td>Guido van Rossum</td>
      </tr>
      <tr>
        <td>Javascript</td>
        <td>Brendan Eich</td>
      </tr>
      <tr>
        <td>C</td>
        <td rowspan="2">Dennis Ritchie</td>
      </tr>
      <tr>
        <td>B</td>
      </tr>
    </tbody>
  </table>
</div>

## Forms

- Elements:
  - `<form>`, `<input>`, `<label>`
- Attributes
  - `action`, `method`
- [HTML5 forms introduction and new attributes](http://html5doctor.com/html5-forms-introduction-and-new-attributes/)
- [HTML Form \| W3C](https://www.w3.org/TR/html5/forms.html)

### Components

#### single-line text field
```html
<input type="text" name="cpf">
```

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="text" name="cpf">
</div>

#### label field

```html
<label for="cpf">CPF:</label>
<input type="text" name="cpf" id="cpf">
```    

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <label for="cpf">CPF:</label>
  <input type="text" name="cpf" id="cpf">
</div>

#### required attribute

```html
<input type="text" name="cpf" required>*
```

<form>
  <input type="text" name="cpf" required>*
<form>

#### placeholder attribute

```html      
<input type="text" name="cpf" placeholder="000.000.000-00">
```

<input type="text" name="cpf" placeholder="000.000.000-00">

#### value attribute
  
```html
<input type="text" name="cpf" value="000.000.000-00">
```
  
<input type="text" name="cpf" value="000.000.000-00">

#### password field

```html
<input type="password" name="password">
```

<input type="password" name="password">

#### radio button field

```html
<input type="radio" name="sexo" value="masculino" id="masculino">
<label for="masculino">masculino</label>
```

<input type="radio" name="sexo" value="masculino" id="masculino">
<label for="masculino">masculino</label>

#### radio group
  
```html
<input type="radio" name="sexo" value="masculino" id="masculino" checked>
<label for="masculino">masculino</label>
<input type="radio" name="sexo" value="feminino" id="feminino">
<label for="feminino">feminino</label>
```

<input type="radio" name="sexo" value="masculino" id="masculino" checked>
<label for="masculino">masculino</label>
<input type="radio" name="sexo" value="feminino" id="feminino">
<label for="feminino">feminino</label>

#### checkbox field
    
```html
<input type="checkbox" name="aceitaCondicoes" value="ok" id="condicoes">
<label for="condicoes">Você concorda com os termos...</label>
```
  
<input type="checkbox" name="aceitaCondicoes" value="ok" id="condicoes">
<label for="condicoes">Você concorda com os termos...</label>

#### range field
  
```html
<input type="range" name="number">
<input type="text" name="number-value" value="20" size="2">
```

<input type="range" name="number">
<input type="text" name="number-value" value="20" size="2">

#### button field
  
```html
<input type="button" name="submit" value="Create">
<input type="submit" name="submit" value="Create">
<button>Create</button>
```

<button>Create</button>

#### date field  
  
```html
<input type="date" name="date">
```

<input type="date" name="date">

#### combobox field
  
```html
<select name="place">
  <option value=""></option>
  <option value="PB">Paraíba</option>
  <option value="PE">Pernambuco</option>
</select>
```

<select name="place">
  <option value=""></option>
  <option value="PB">Paraíba</option>
  <option value="PE">Pernambuco</option>
</select>

#### multi-line text field

```html
<textarea name="message" rows="3" cols="60">digite uma mensagem</textarea>
```

<textarea name="message" rows="3" cols="60">digite uma mensagem</textarea>

### Example

```html
<main>
  <h1>Contato</h1>
  <form action="sucesso.html" method="post">
    <fieldset>
      <div>
        <label for="nome">Nome</label>
        <input type="text" id="nome" name="nome" required> *
      </div>
      <div>
        Sexo
        <input type="radio" name="sexo" id="masculino" value="m" checked>
        <label for="masculino">Masculino</label>
        <input type="radio" name="sexo" id="feminino" value="f">
        <label for="feminino">Feminino</label>
      </div>
      <div>
        <label for="curso">Curso</label>
        <select name="curso" id="curso">
          <option value="" selected="">escolha um curso</option>
          <option value="TSI">Sistemas para Internet</option>
          <option value="RC">Redes de Computadores</option>
        </select>
      </div>
      <div>
        <label for="email">Email</label>
        <input type="text" id="email" name="email">
      </div>
      <div>
        <label for="titulo">Título</label>
        <input type="text" id="titulo" name="titulo">
      </div>
      <div>
        <label for="mensagem">Mensagem</label>
        <textarea id="mensagem" name="mensagem"></textarea>
      </div>
    </fieldset>
    <input type="submit" value="Enviar">
  </form>
</main>
```

Output:
<main>
  <b style="font-size: 2em;">Contato</b>
  <form action="sucesso.html" method="post">
    <fieldset>
      <div>
        <label for="nome">Nome</label>
        <input type="text" id="nome" name="nome" required> *
      </div>
      <div>
        Sexo
        <input type="radio" name="sexo" id="masculino" value="m" checked>
        <label for="masculino">Masculino</label>
        <input type="radio" name="sexo" id="feminino" value="f">
        <label for="feminino">Feminino</label>
      </div>
      <div>
        <label for="curso">Curso</label>
        <select name="curso" id="curso">
          <option value="" selected="">escolha um curso</option>
          <option value="TSI">Sistemas para Internet</option>
          <option value="RC">Redes de Computadores</option>
        </select>
      </div>
      <div>
        <label for="email">Email</label>
        <input type="text" id="email" name="email">
      </div>
      <div>
        <label for="titulo">Título</label>
        <input type="text" id="titulo" name="titulo">
      </div>
      <div>
        <label for="mensagem">Mensagem</label>
        <textarea id="mensagem" name="mensagem"></textarea>
      </div>
    </fieldset>
    <input type="submit" value="Enviar">
  </form>
</main>

## Web Resourses

### Google Maps

#### Static Map

Reference: https://staticmapmaker.com/google/

```
<img width="600" src="https://maps.googleapis.com/maps/api/staticmap?center=ifpb+av+primeiro+de+maio&zoom=16&scale=1&size=600x300&maptype=roadmap&format=png&visual_refresh=true" alt="Google Map of ifpb av primeiro de maio">
```


Output:

![IFPB](assets/ifpbstaticmap.png)

#### Dynamic Map

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1979.4582707790096!2d-34.87499884397443!3d-7.135649594847398!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7ace810852ae4f1%3A0xaf5445223401f2bb!2sIFPB!5e0!3m2!1sen!2sbr!4v1521749915692" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
```

Output:

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1979.4582707790096!2d-34.87499884397443!3d-7.135649594847398!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7ace810852ae4f1%3A0xaf5445223401f2bb!2sIFPB!5e0!3m2!1sen!2sbr!4v1521749915692" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

### Youtube

- Reference:
  - https://developers.google.com/youtube/subscribe/

```html
<iframe 
  width="560" 
  height="315" 
  src="https://www.youtube.com/embed/guvsH5OFizE" 
  frameborder="0" 
  allow="autoplay; encrypted-media" 
  allowfullscreen>
</iframe>
```

Output:
<iframe width="560" height="315" src="https://www.youtube.com/embed/guvsH5OFizE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### Google Drive

### Facebook

Reference: [Facebook - Social Plugins](https://developers.facebook.com/docs/plugins)

[Share Button](https://developers.facebook.com/docs/plugins/share-button)

```html
<iframe 
  src="https://www.facebook.com/plugins/share_button.php?href=https%3A%2F%2Fwww.ifpb.edu.br%2F&layout=button_count&size=small&mobile_iframe=true&width=118&height=20&appId" 
  width="118" 
  height="20" 
  style="border:none;overflow:hidden" 
  scrolling="no" 
  frameborder="0" 
  allowTransparency="true">
</iframe>
```

Output:

<iframe src="https://www.facebook.com/plugins/share_button.php?href=https%3A%2F%2Fwww.ifpb.edu.br%2F&layout=button_count&size=small&mobile_iframe=true&width=118&height=20&appId" width="118" height="20" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>

[Like Button](https://developers.facebook.com/docs/plugins/like-button)


```html
<iframe 
  src="https://www.facebook.com/plugins/like.php?href=http%3A%2F%2Fwww.ifpb.edu.br%2F&width=450&layout=standard&action=like&size=large&show_faces=true&share=true&height=80&appId" 
  width="450" 
  height="80" 
  style="border:none;overflow:hidden" 
  scrolling="no" 
  frameborder="0" 
  allowTransparency="true">
</iframe>
```

Output:

<iframe src="https://www.facebook.com/plugins/like.php?href=http%3A%2F%2Fwww.ifpb.edu.br%2F&width=450&layout=standard&action=like&size=large&show_faces=true&share=true&height=80&appId" width="450" height="80" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>

[Facebook Pages](https://developers.facebook.com/docs/plugins/page-plugin)

```html
<iframe 
  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fifpb.si%2F&tabs=timeline&width=340&height=500&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=false&appId" 
  width="340" 
  height="500" 
  style="border:none;overflow:hidden" 
  scrolling="no" 
  frameborder="0" 
  allowTransparency="true">
</iframe>
```

Output:
<iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fifpb.si%2F&tabs=timeline&width=340&height=500&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=false&appId" width="340" height="500" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>

### Twitter

- Reference
  - https://dev.twitter.com/web/overview

<!-- 
  TODO
  Robots.txt: [robots](http://www.robotstxt.org/robotstxt.html) e [robots do g1.com](http://g1.globo.com/robots.txt)
 -->

