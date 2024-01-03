## CSS

Css significa Cascading Style Sheets (Folhas de Estilo em Cascata).

O CSS salva muito trabalho. Ele pode controlar o layout de várias páginas da web de uma vez.

## O que é CSS?

Cascading Style Sheets (CSS) é usado para formatar o layout de uma página da web.

Com CSS, você pode controlar a cor, a fonte, o tamanho, o espaçamento e a aparência do texto, bem como o espaçamento entre parágrafos, o espaçamento entre linhas, o plano de fundo etc.

A palavra cascata quer dizer que um estilo aplicado a um elemento parente será aplicado a todos os seus elementos filhos. Por exemplo, se você definir a cor de fonte para o elemento body, todos os elementos dentro do body herdarão essa cor de fonte (a menos que você substitua a cor de fonte de um elemento específico).

## Usando CSS

O CSS pode ser adicionado a documentos HTML de três maneiras diferentes:

<ol>
    <li><strong>Inline</strong> - usando o atributo style dentro de elementos HTML</li>
    <li><strong>Internal</strong> - usando o elemento style dentro da seção head </li>
    <li><strong>External</strong> - usando um link para um arquivo CSS externo</li>
</ol>

A forma mais comum de usar CSS é a externa, porque o CSS pode ser escrito uma vez e aplicado a muitas páginas HTML.


## CSS Inline

Para usar CSS inline, adicione o atributo style a um elemento:

```html
<h1 style="color:blue;">Um título azul</h1>
<p style="color:red;">Um parágrafo vermelho</p>
```

## CSS Interno

Para usar CSS interno, adicione um elemento style à seção head:

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
    <h1>Um título azul</h1>
    <p>Um parágrafo vermelho</p>
</body>
</html>
```

## CSS Externo

Para usar CSS externo, adicione um link para o arquivo CSS em um elemento head:

```html
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Um título azul</h1>
    <p>Um parágrafo vermelho</p>
</body>
</html>
```

## CSS Colors, Fonts and Sizes

Algumas propridedades comuns do CSS são:

- color: define a cor do texto
- font-family: define a fonte do texto
- font-size: define o tamanho do texto

```html	
<!DOCTYPE html>
<html>
<head>
<style>
    h1 {
        color: blue;
        font-family: verdana;
        font-size: 300%;
    }
    p {
        color: red;
        font-family: courier;
        font-size: 160%;
    }
</style>
</head>
<body>
    <h1>Um título azul</h1>
    <p>Um parágrafo vermelho</p>
</body>
</html>
```

## CSS Border

A propriedade border é usada para definir uma borda em um elemento.

A propriedade border é uma abreviação para as propriedades:

- border-width
- border-style (required)
- border-color

```html
<!DOCTYPE html>
<html>
<head>
<style>
    p {
        border: 1px solid powderblue;
    }
</style>
</head>
<body>
    <p>Um parágrafo com borda</p>
</body>
</html>
```

## CSS Padding

A propriedade padding define o espaço entre o conteúdo e a borda.

A propriedade padding é uma abreviação para as propriedades:

- padding-top
- padding-right
- padding-bottom
- padding-left

```html
<!DOCTYPE html>
<html>
<head>
<style>
    p {
        border: 1px solid powderblue;
        padding: 30px;
    }
</style>
</head>
<body>
    <p>Um parágrafo com borda</p>
</body>
</html>
```

## CSS Margin

A propriedade margin define o espaço entre os elementos.

A propriedade margin é uma abreviação para as propriedades:

- margin-top
- margin-right
- margin-bottom
- margin-left

```html
<!DOCTYPE html>
<html>
<head>
<style>
    p {
        border: 1px solid powderblue;
        margin: 50px;
    }
</style>
</head>
<body>
    <p>Um parágrafo com borda</p>
</body>
</html>
```
