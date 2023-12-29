## HTML Styles

O style HTML é usado para adicionar estilos (cores, fontes, margens, etc.) para elementos.

```html	
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>Este é um cabeçalho</h1>
<p>Este é um parágrafo.</p>

</body>
</html>
```

## O atributo style

Adicionar o estilo de um elemento pode ser feito com o atributo `style`.

```html
<h1 style="color:blue;">Este é um cabeçalho</h1>
<p style="color:red;">Este é um parágrafo.</p>
```

`<tagname style="property:value;">`

O `property` é uma propriedade CSS, e o `value` é o valor CSS.

## Background Color

A propriedade CSS `background-color` define a cor de fundo de um elemento HTML.

```html
<body style="background-color:skyblue;">

<h1>Isto é um título</h1>
<p>Isto é um parágrafo.</p>

</body>
```

## Text Color

A propriedade CSS `color` define a cor do texto de um elemento.

```html
<h1 style="color:blue;">Este é um título</h1>
<p style="color:red;">Este é um parágrafo.</p>
```

## Font Family

A propriedade CSS `font-family` define a fonte de um elemento.

```html
<h1 style="font-family:sans-serif;">Este é um cabeçalho</h1>
<p style="font-family:courier;">Este é um parágrafo.
```

## Font Size

A propriedade CSS `font-size` define o tamanho da fonte de um elemento.

```html
<h1 style="font-size:300%;">Este é um título</h1>
<p style="font-size:160%;">Este é um parágrafo.</p>
```

## Text Align

A propriedade CSS `text-align` define o alinhamento horizontal do texto de um elemento.

```html
<h1 style="text-align:center;">Este é título no centro da página</h1>
<p style="text-align:center;">Este é um parágrafo.</p>
```