## Links HTML - Hyperlinks

Links HTML são hiperlinks. Você pode clicar em um link e saltar para outro documento. Quando você move o mouse sobre um link, o ponteiro do mouse mudará para uma pequena mão.

Um link não precisa ser texto. Um link pode ser uma imagem ou qualquer outro elemento HTML.

## Sintaxe de Links HTML

A tag `<a>` define um hyperlink. 

```html
<a href="url">link text</a>
```

O atributo mais importante do elemento `<a>` é o atributo href, que indica o destino do link.

O <em>link text</em> é o texto que será exibido para o usuário.

```html	
<a href="https://www.youtube.com/watch?v=ZxGiEoczryg&t=795s">All of me - Masayoshi Takanaka</a>
```
Por padrão, os links aparecem como isso (em todos os navegadores):

<ol>
    <li>Um link não visitado é exibido em azul</li>
    <li>Um link visitado é exibido em roxo</li>
    <li>Um link ativo é exibido em vermelho</li>
</ol>

## O atributo target

O atributo target especifica onde abrir o documento vinculado.

O atributo target pode ter um dos seguintes valores:

<ol>
    <li>_self - Abre o documento vinculado no mesmo quadro / janela que foi clicado (este é o padrão)</li>
    <li>_blank - Abre o documento vinculado em uma nova janela ou guia</li>
    <li>_parent - Abre o documento vinculado no quadro pai</li>
    <li>_top - Abre o documento vinculado no corpo inteiro da janela</li>
</ol>

```html
<a href="https://www.youtube.com/watch?v=ZxGiEoczryg&t=795s" target="_blank">All of me - Masayoshi Takanaka</a>
```

## URls Relativas vs URLs Absolutas

Links podem ser absolutos ou relativos.

Um link absoluto é o endereço completo da página da web. Por exemplo: `https://www.youtube.com/watch?v=ZxGiEoczryg&t=795s`

Um link relativo é um link para uma página dentro do mesmo site. Por exemplo: `watch?v=ZxGiEoczryg&t=795s`

## Imagem como um link

Você pode usar imagens como links. Para fazer isso, coloque a tag `<img>` dentro da tag `<a>`:

```html
<a href="https://www.youtube.com/watch?v=ZxGiEoczryg&t=795s">
    <img src="https://i.ytimg.com/vi/ZxGiEoczryg/maxresdefault.jpg" alt="All of me - Masayoshi Takanaka">
</a>
```

## Links para um endereço de e-mail

Use o atributo `mailto:` para criar um link para um endereço de e-mail:

```html
<a href="mailto:email@exemplo.com">Enviar e-mail</a>
```

## Button como um link

Para usar um botão como um link, é preciso usar um pouco de JavaScript.

```html
<button onclick="window.location.href = 'https://www.youtube.com/watch?v=ZxGiEoczryg&t=795s';">All of me - Masayoshi Takanaka</button>
```

## Link titles

O atributo title especifica informações extras sobre um elemento.

A informação é mais frequentemente mostrada como uma dica de ferramenta quando o mouse se move sobre o elemento.

```html
<a href="https://www.youtube.com/watch?v=ZxGiEoczryg&t=795s" title="Melhor compilado do youtube">All of me - Masayoshi Takanaka</a>
```
## Remover underline de links

Por padrão, os links são sublinhados. Use o atributo `text-decoration:none` para remover sublinhado de links:

```html
<a href="https://www.youtube.com/watch?v=ZxGiEoczryg&t=795s" style="text-decoration:none;">All of me - Masayoshi Takanaka</a>
```