## Atributos HTML

<ol>
    <li>Todos os elementos HTML podem ter atributos</li>
    <li>Os atributos fornecem informações adicionais sobre os elementos</li>
    <li>Os atributos são sempre especificados na tag de início</li>
    <li>Os atributos geralmente vêm em pares nome / valor como: <strong>nome = "valor"</strong></li>
</ol>

## O atributo href

O atributo href especifica o URL da página para a qual o link vai.

```html
<a href="www.youtube.com">link youtube</a>
```

## O atributo src

A tag `<img>` é usada para incorporar uma imagem em uma página HTML. O atributo src especifica o URL (endereço da web) da imagem:

```html
<img src="imagem.jpg">
```

Há duas formas de especificar o URL no atributo src:

1. Um caminho absoluto - aponta para outro site (como src="https://www.google.com/imagem.jpg")

Imagens externas podem conter copyright. E se você não tiver permissão para usar, estará violando as leis de direitos autorais. Além disso, 
você não controla imagens externas; elas podem ser removidas ou alteradas.

2. Um caminho relativo - aponta para um arquivo no site atual (como src="imagem.jpg"). Aqui, o URL não inclue o nome do domínio. Se o URL 
começar sem uma barra (/), ele será relativo a página atual. Exemplo: `src="imagem.jpg"`. Se o URL começar com uma barra (/), ele será relativo ao domínio. Exemplo: `src="/images/imagem.jpg"`.

Caminhos relativos são preferíveis porque o site pode ser movido para outro domínio ou para um servidor seguro (HTTPS) sem quebrar os links.

## Os atributos width e height

A tag `<img>` também vem com dois atributos opcionais: width e height. Estes atributos especificam a largura e a altura da imagem(em pixels):

```html
<img src="imagem.jpg" width="500" height="600">
```

## O atributo alt

O atributo alt especifica um texto alternativo para uma imagem, se a imagem por alguma razão não puder ser exibida. Por causa de uma conexão lenta, ou se o usuário não puder ver a imagem, ou se o usuário usar um leitor de tela, o texto alternativo é exibido:

```html
<img src="imagem.jpg" alt="descrição da imagem">
```

## O atributo style

O atributo style é usado para adicionar estilos a um elemento, como cor, fonte, tamanho e muito mais.

```html
<p style="color:blue;">Este é um parágrafo azul.</p>
```

## O atributo lang

O atributo lang especifica o idioma de um elemento:

```html
<!DOCTYPE html>
<html lang="pt-br">
<body>
    <h1>Este é um título</h1>
    <p>Este é um parágrafo.</p>
</body>
```

## O atributo title

O atributo title especifica informações adicionais sobre um elemento. O valor do atributo title será exibido como uma dica de ferramenta quando você passar o mouse sobre o elemento:

```html
<p title="Eu sou uma dica de ferramenta">Este é um parágrafo.</p>
```