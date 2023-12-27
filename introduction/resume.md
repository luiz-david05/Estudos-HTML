## O que é HTML?

HTML é uma linguagem de marcação, ou seja, um conjunto de tags que definem o conteúdo de uma página web. A estrutura básica de um documento HTML é a seguinte:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Minha primeira página</title>
  </head>
  <body>
    <h1>Olá mundo!</h1>
  </body>
</html>
```

Explicações:

O `<!DOCTYPE html>` define que este documento é um documento HTML5.

O elemento `<html>` é o elemento raiz de uma página HTML.

O elemento `<head>` contém informações sobre a página.

O elemento `<title>` especifica um título para a página (que é mostrado na aba do navegador).

O elemento `<body>` contém o conteúdo da página, e é um container para todos os elementos visíveis, como headings, parágrafos, imagens, hyperlinks, tabelas, listas, etc.

O elemento `<h1>` define um titulo de primeiro nível.

O elemento `<p>` define um parágrafo.


## O que é um elemento HTML?

Um elemento HTML é definido por uma tag inicial, um conteúdo e uma tag final. Por exemplo:

```html
<p>Este é um parágrafo</p>
```

A tag inicial é `<p>` e a tag final é `</p>`. O conteúdo é o texto "Este é um parágrafo".

Nota: Alguns elementos HTML não possuem tag final, como por exemplo a tag `<br>`.


## Navegadores

Navegadores são programas que interpretam o código HTML e mostram o conteúdo de uma página web. Um navegador não mostra as tags HTML, mas usa elas para determinar como mostrar o conteúdo da página.

## Estrutura de uma página HTML

A estrutura de uma página HTML é a seguinte:

```html
<html>
    <head>
        <title>Título da página</title>
    </head>
    <body>
        <h1>Isso é um título</h1>
        <p>Isso é um parágrafo</p>
        <p>Isso é outro parágrafo</p>
    </body>
</html>
```