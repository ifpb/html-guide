# Table Content

## Basic Table
---

[table-simple/index.html](table-simple/index.html):
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

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
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

## Table Section
---

[table-section/index.html](table-section/index.html):
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

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
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

## Table Span
---

[table-span/index.html](table-span/index.html):
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

<div style="border-radius: 0.3rem;background-color: #f3f6fa;border: solid 1px #dce6f0; padding: 0.8rem">
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

## References
---

* [HTML table basics \| MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
* Elements: [`<table>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table),
  [`<thead>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/thead),
  [`<tbody>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tbody),
  [`<tfoot>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tfoot),
  [`<tr>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tr),
  [`<th>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th),
  [`<td>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td)
* Attributes: 
  * [`<table>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table#Attributes): `border`
  * [`<td>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td#Attributes): `colspan`, `rowspan`
