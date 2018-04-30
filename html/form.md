# Forms

## Components
---

### single-line text field

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="text" name="cpf">
</div>

```html
<input type="text" name="cpf">
```

### label field

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <label for="cpf">CPF:</label>
  <input type="text" name="cpf" id="cpf">
</div>

```html
<label for="cpf">CPF:</label>
<input type="text" name="cpf" id="cpf">
```

### required attribute

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <form>
    <input type="text" name="cpf" required>*
  </form>
</div>

```html
<input type="text" name="cpf" required>*
```

### placeholder attribute

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="text" name="cpf" placeholder="000.000.000-00">
</div>

```html      
<input type="text" name="cpf" placeholder="000.000.000-00">
```

### value attribute
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="text" name="cpf" value="000.000.000-00">
</div>

```html
<input type="text" name="cpf" value="000.000.000-00">
```

### password field

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="password" name="password">
</div>

```html
<input type="password" name="password">
```

### radio button field

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="radio" name="sexo" value="masculino" id="masculino">
  <label for="masculino">masculino</label>
</div>

```html
<input type="radio" name="sexo" value="masculino" id="masculino">
<label for="masculino">masculino</label>
```

### radio group
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="radio" name="sexo" value="masculino" id="masculino" checked>
  <label for="masculino">masculino</label>
  <input type="radio" name="sexo" value="feminino" id="feminino">
  <label for="feminino">feminino</label>
</div>

```html
<input type="radio" name="sexo" value="masculino" id="masculino" checked>
<label for="masculino">masculino</label>
<input type="radio" name="sexo" value="feminino" id="feminino">
<label for="feminino">feminino</label>
```

### checkbox field
      
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="checkbox" name="aceitaCondicoes" value="ok" id="condicoes">
  <label for="condicoes">Você concorda com os termos...</label>
</div>

```html
<input type="checkbox" name="aceitaCondicoes" value="ok" id="condicoes">
<label for="condicoes">Você concorda com os termos...</label>
```

### range field
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="range" name="number">
  <input type="text" name="number-value" value="20" size="2">
</div>

```html
<input type="range" name="number">
<input type="text" name="number-value" value="20" size="2">
```

### button field
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <button>Create</button>
</div>

```html
<input type="button" name="submit" value="Create">
<input type="submit" name="submit" value="Create">
<button>Create</button>
```

### date field  
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <input type="date" name="date">
</div>

```html
<input type="date" name="date">
```

### combobox field
  
<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <select name="place">
    <option value=""></option>
    <option value="PB">Paraíba</option>
    <option value="PE">Pernambuco</option>
  </select>
</div>

```html
<select name="place">
  <option value=""></option>
  <option value="PB">Paraíba</option>
  <option value="PE">Pernambuco</option>
</select>
```

### multi-line text field

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
  <textarea name="message" rows="3" cols="60">digite uma mensagem</textarea>
</div>

```html
<textarea name="message" rows="3" cols="60">digite uma mensagem</textarea>
```

## Simple Form
---

[form/index.html](form/index.html)
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