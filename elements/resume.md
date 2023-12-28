## Elementos HTML

Um elemento HTML é definido por uma tag de abertura, algum conteúdo e uma tag de fechamento:

```html
<p>Conteúdo do elemento</p>
```

## Elementos HTML aninhados

Os elementos HTML podem ser aninhados (elementos podem conter elementos).

Todos os documentos HTML consistem de elementos aninhados.

```html
<!DOCTYPE html>
<html>
    <body>
        <p>Meu primeiro parágrafo.</p>
    </body>
</html>
```

O elemento `<html>` é o elemento raiz e define todo o documento HTML.

O elemento `<body>` define o corpo do documento e é um elemento filho do elemento `<html>`.

O elemento `<p>` define um parágrafo e é um elemento filho do elemento `<body>`.

## Nunca esqueça a tag de fechamento

Alguns elementos irão exibir corretamente mesmo se você esquecer a tag de fechamento:

```html
<!DOCTYPE html>
<html>
    <body>
        <p>Este é um parágrafo.
        <p>Este é um parágrafo.
    </body>
</html>
```

No entanto, alguns navegadores podem adicionar uma tag de fechamento automaticamente.

Para uma melhor legibilidade e para evitar resultados inesperados e que erros ocorram: `<strong>sempre feche tags HTML.</strong>`

## Elementos HTML vazios

Alguns elementos HTML não possuem conteúdo. Estes são chamados de elementos vazios. `<br>` é um elemento vazio sem tag de fechamento (a tag `<br>` define uma quebra de linha).

```html
<!DOCTYPE html>
<html>
    <body>
        <p>Este é um parágrafo.<br>Este é um parágrafo.</p>
    </body>
</html>
```

## HTML não é case sensitive

A linguagem HTML não é case sensitive. A tag `<p>` é o mesmo que `<P>`.