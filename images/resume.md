## Imagens

Imagens são definidas com a tag `<img>`. O nome do arquivo da imagem é especificado no atributo `src`. O texto alternativo da imagem é especificado no atributo `alt`.

```html
<img src="imagem.jpg" alt="descrição da imagem">
```
## Width e Height

A tag `<img>` também vem com dois atributos opcionais: width e height. Estes atributos especificam a largura e a altura da imagem(em pixels):

```html
<img src="imagem.jpg" width="500" height="600">
```

## Width e Height, ou Style ?

É preferível usar o atributo style para especificar a largura e a altura de uma imagem:

```html
<style>
    img {
        width: 100%;
        height: auto;
    }
</style>
```

## Imagens em um outro diretório

Se a imagem estiver em um diretório diferente, você deve especificar o caminho para a imagem no atributo src:

```html
<img src="/images/imagem.jpg" alt="descrição da imagem">
```

## Imagens em um outro site

Se a imagem estiver em um outro site, você deve especificar o caminho completo para a imagem no atributo src:

```html
<img src="url" alt="descrição da imagem">
```

## Imagens animadas

```html
<img src="imagem.gif" alt="descrição da imagem">
```

## Imagens como links

```html
<a href="https://www.youtube.com/watch?v=ZxGiEoczryg&t=795s">
    <img src="https://i.ytimg.com/vi/ZxGiEoczryg/maxresdefault.jpg" alt="All of me - Masayoshi Takanaka">
</a>

## Image Floating

A propriedade CSS float é usada para definir o alinhamento horizontal de um elemento. Ele move o elemento flutuante para a esquerda ou para a direita de seu contêiner.

```html
<img src="imagem.jpg" alt="descrição da imagem" style="float:right;width:42px;height:42px;">
```