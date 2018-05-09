# [Forms](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)

* [Components](#components)
* [Simple Form](#simple-form)

## Components
---

### [single-line text field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/text)

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="text" name="cpf">
</div>

```html
<input type="text" name="cpf">
```

### [required attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#Attributes)

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <form>
    <input type="text" name="cpf" required>*
  </form>
</div>

```html
<input type="text" name="cpf" required>*
```

### [placeholder attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#Attributes)

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="text" name="cpf" placeholder="000.000.000-00">
</div>

```html      
<input type="text" name="cpf" placeholder="000.000.000-00">
```

### [value attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#Attributes)
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="text" name="cpf" value="000.000.000-00">
</div>

```html
<input type="text" name="cpf" value="000.000.000-00">
```

### [label field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label)

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <label for="cpf">CPF:</label>
  <input type="text" name="cpf" id="cpf">
</div>

```html
<label for="cpf">CPF:</label>
<input type="text" name="cpf" id="cpf">
```

### [password field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/password)

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="password" name="password">
</div>

```html
<input type="password" name="password">
```

### [radio button field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/radio)

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="radio" name="sexo_value" value="masculino" id="masculino">
  <label for="masculino">masculino</label>
</div>

```html
<input type="radio" name="sexo" value="masculino" id="masculino">
<label for="masculino">masculino</label>
```

### [radio group](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/radio)
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  Sexo:
  <input type="radio" name="sexo" value="masculino" id="masculino" checked>
  <label for="masculino">masculino</label>
  <input type="radio" name="sexo" value="feminino" id="feminino">
  <label for="feminino">feminino</label>
</div>

```html
Sexo:
<input type="radio" name="sexo" value="masculino" id="masculino" checked>
<label for="masculino">masculino</label>
<input type="radio" name="sexo" value="feminino" id="feminino">
<label for="feminino">feminino</label>
```

### [checkbox field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/checkbox)
      
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="checkbox" name="aceitaCondicoes" value="ok" id="condicoes">
  <label for="condicoes">Você concorda com os termos...</label>
</div>

```html
<input type="checkbox" name="aceitaCondicoes" value="ok" id="condicoes">
<label for="condicoes">Você concorda com os termos...</label>
```

### [checkbox group](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/checkbox)

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  Linguagens:
  <input type="checkbox" name="linguagens" value="javascript" id="javascript">
  <label for="javascript">Javascript</label>
  <input type="checkbox" name="linguagens" value="c" id="c">
  <label for="c">C</label>
  <input type="checkbox" name="linguagens" value="java" id="java">
  <label for="java">Java</label>
  <input type="checkbox" name="linguagens" value="python" id="python">
  <label for="python">Python</label>
</div>

```html
Linguagens:
<input type="checkbox" name="linguagens" value="javascript" id="javascript">
<label for="javascript">Javascript</label>
<input type="checkbox" name="linguagens" value="c" id="c">
<label for="c">C</label>
<input type="checkbox" name="linguagens" value="java" id="java">
<label for="java">Java</label>
<input type="checkbox" name="linguagens" value="python" id="python">
<label for="python">Python</label>
```

### [range field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/range)
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="range" name="number" min="1" max="100" step="1">
  <input type="text" name="number-value" value="20" size="2">
</div>

```html
<input type="range" name="number" min="1" max="100" step="1">
<input type="text" name="number-value" value="20" size="2">
```

### [button field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/button)
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <button>Create</button>
</div>

```html
<input type="button" name="submit" value="Create">
<input type="submit" name="submit" value="Create">
<button>Create</button>
```

### [date field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/date)
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="date" name="date">
</div>

```html
<input type="date" name="date">
```

### [email field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/email)
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="email" name="email">
</div>

```html
<input type="email" name="email">
```

### [file field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/file)
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="file" name="file">
</div>

```html
<input type="file" name="file">
```

### [combobox field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select)
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <label for="place">Estado: </label>
  <select name="place" id="place">
    <option value=""></option>
    <option value="PB">Paraíba</option>
    <option value="PE">Pernambuco</option>
  </select>
</div>

```html
<label for="place">Estado</label>
<select name="place" id="place">
  <option value=""></option>
  <option value="PB">Paraíba</option>
  <option value="PE">Pernambuco</option>
</select>
```

### [multi-line text field](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea)

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <label for="message">Mensagem:</label><br>
  <textarea name="message" id="message" rows="3" cols="60">digite uma mensagem</textarea>
</div>

```html
<label for="message">Mensagem:</label><br>
<textarea name="message" id="message" rows="3" cols="60">digite uma mensagem</textarea>
```

## Simple Form
---

[simple-form/index.html](simple-form/index.html)
```html
<main>
  <h1 style="color: #606c71">Contato</h1>
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

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <main>
    <h1 style="color: 2em;">Contato</h1>
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
</div>

## References
---
* [HTML forms Guide \| MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms)
* [HTML5 forms introduction and new attributes](http://html5doctor.com/html5-forms-introduction-and-new-attributes/)
* [HTML Form \| W3C](https://www.w3.org/TR/html5/forms.html)
* Elements: [`<form>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form),
  [`<input>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input),
  [`<label>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label)
* Attributes
  * [`<form>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form#Attributes): `action`, `method`
  * [`<input>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#Attributes): `type`
  * [`<label>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label#Attributes): `for`