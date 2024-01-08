## Background Image

Para adicionar uma imagem de fundo em uma página HTML, use o atributo `<style>` e a propriedade `background-image`:

```html	
<p style="background-image: url('imagem.jpg');">
```

No elemento style, na seção head, você pode definir estilos para elementos HTML específicos:

```html
<style>
    p {
        background-image: url('imagem.jpg');
    }
</style>
```

## Background Image em uma página inteira

Para adicionar uma imagem de fundo em uma página inteira, você deve espicificar o background image no elemento `<body>`:

```html
<style>
    body {
        background-image: url('imagem.jpg');
    }
</style>
```

## Background Repeat

Se a imagem de fundo for menor que a tela, a imagem irá se repetir. Por padrão, a imagem se repete tanto na horizontal quanto na vertical até preencher a tela.

Para evitar a repetição da imagem, use a propriedade `background-repeat` com o valor `no-repeat`:

```html
<style>
    body {
        background-image: url('imagem.jpg');
        background-repeat: no-repeat;
    }
</style>
```

## Background Cover

Se quiser a imagem de fundo para cobrir toda a tela, use a propriedade `background-size` com o valor `cover`:

E, para ter certeza que o elemento inteiro está sempre coberto, use a propriedade `background-attachment` com o valor `fixed`:

```html
<style>
    body {
        background-image: url('imagem.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        background-attachment: fixed;
    }
</style>
```

## Background Stretch

Se quiser que a imagem de fundo se estique para cobrir toda a tela, use a propriedade `background-size` com o valor `100% 100%`:

```html
<style>
    body {
        background-image: url('imagem.jpg');
        background-repeat: no-repeat;
        background-size: 100% 100%;
    }
</style>