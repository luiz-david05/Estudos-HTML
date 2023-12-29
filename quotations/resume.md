## Elementos de citação

## Blockquote 

O elemento `<blockquote>` define uma seção que é citada de outra fonte.

```html
<p>Este é um parágrafo.</p>

<blockquote cite="http://www.sitedeorigem.org">
  <p>Este é um bloco de citação.</p>
</blockquote>
```

O atributo `cite` é usado para indicar a fonte da citação.

## Elemento `<q>`
O elemento `<q>` define uma citação curta.

```html
<p>Este é um parágrafo.</p>

<p>Este é um <q>citação curta</q>.</p>
```

## Elemento `<abbr>`

O elemento `<abbr>` define uma abreviação ou um acrônimo.

```html
<p>Este é um parágrafo.</p>

<p>O <abbr title="Fundo de Equilíbrio Fiscal do Rio Grande do Norte">FUDERN</abbr> foi criado em 2017</p>
```

O atributo `title` é usado para especificar o título completo da abreviação.

## Elemento `<address>`

O elemento `<address>` define informações de contato para o autor/proprietário de um documento ou artigo.

```html
<address>
  <p>Escrito por <a href="mailto:

">Jailson Mendes</a>.</p>
    <p>Visite-nos em:<br>
    <a href="https://www.youtube.com/@canalquedelicia-oretorno235">canal da delicia</a><br>
    </p>
</address>
```

## Elemento `<cite>`

O elemento `<cite>` define o título de um trabalho criativo (por exemplo, um livro, um poema, uma música, um filme, uma pintura, uma escultura ou uma obra de arquitetura).

```html
<p>Em meu livro favorito, <cite>O Retorno</cite>, o autor diz que <q>a vida é uma delicia.</q></p>
```

## Elemento `<bdo>`

O elemento `<bdo>` define a direção do texto.

```html
<bdo dir="rtl">Este é um parágrafo com texto da direita para a esquerda.</bdo>
```

O atributo `dir` pode ter os seguintes valores:

- `ltr` - Texto da esquerda para a direita. Este é o padrão
- `rtl` - Texto da direita para a esquerda

## Elemento `<bdi>`

O elemento `<bdi>` isola uma parte do texto que pode ser formatada de forma diferente do texto que está fora dela.

```html
<p>Este é um parágrafo com texto em árabe: <bdi>السلام عليكم</bdi></p>
```