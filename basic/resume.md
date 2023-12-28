## Documentos HTML

Todos os documentos HTML começam com uma declaração de tipo: `<!DOCTYPE html>`. Esta declaração não é uma tag HTML; é uma instrução para o navegador sobre qual versão do HTML a página está escrita. Em HTML5, esta declaração é apenas uma declaração de tipo e não requer nada mais do que `<!DOCTYPE html>`.

O documento HTML em si, começa com `<html>` e termina com `</html>`.

A parte visível do documento HTML é entre `<body>` e `</body>`.

```html
<!DOCTYPE html>
<html>
<body>
    <h1>Meu Primeiro Título</h1>
    <p>Meu primeiro parágrafo.</p>
</body>
</html>
```

## Títulos HTML

Os títulos HTML são definidos com as tags `<h1>` a `<h6>`.

`<h1>` define o título mais importante. `<h6>` define o título menos importante.

```html
<h1>Este é um título de nível 1</h1>
<h2>Este é um título de nível 2</h2>
<h3>Este é um título de nível 3</h3>
<h4>Este é um título de nível 4</h4>
<h5>Este é um título de nível 5</h5>
<h6>Este é um título de nível 6</h6>
```

## Parágrafos HTML

Parágrafos são definidos com a tag `<p>`.

```html
<p>Este é um parágrafo.</p>
<p>Este é outro parágrafo.</p>
```

## Links HTML

Links são definidos com a tag `<a>`. O endereço do link é especificado no atributo `href`:

```html
<p>Este é um link para o <a href="https://www.google.com">google</a>.</p>
```

## Imagens HTML

Imagens são definidas com a tag `<img>`. O nome do arquivo da imagem é especificado no atributo `src`. O texto alternativo da imagem é especificado no atributo `alt`.

```html
<img src="imagem.jpg" alt="descrição da imagem">
```