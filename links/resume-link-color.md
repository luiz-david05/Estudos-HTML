## HTML Links - Cores diferentes

Por padrão, um link parece isso (em todos os navegadores):

- Um link não visitado é exibido em azul
- Um link visitado é exibido em roxo
- Um link ativo é exibido em vermelho

Para alterar a cor de um link, use a propriedade de cor CSS.

```html
<style>
    a:link {
        color: green;
        background-color: transparent;
        text-decoration: none;
    }

    a:visited {
        color: hotpink;
        background-color: transparent;
        text-decoration: none;
    }

    a:hover {
        color: red;
        background-color: transparent;
        text-decoration: underline;
    }

    a:active {
        color: blue;
        background-color: transparent;
        text-decoration: underline;
    }
</style>
```

## Link Buttons

Para transformar um link em um botão, use a propriedade de exibição CSS.

```html
<!DOCTYPE html>
<html>
<head>
<style>
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 15px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
</style>
</head>
<body>

<h2>Link Button</h2>
<p>Um link estilizado como um botão:</p>
<a href="" target="_blank">Isso é um link</a>

</body>
</html>
```
