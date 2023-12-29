## Formatação de texto

O HTML contém vários elementos para definir texto com um significado especial.

```html	
<p><b>Este texto é importante</b></p>
<p><i>Este texto é um texto alternativo</i></p>
<p>Este é <sub>texto subscrito</sub> e <sup>texto sobrescrito</sup></p>
```

## Elementos de formatação de texto

<ul>
    <li>`<b>` - Negrito</li>
    <li>`<strong>` - Importante</li>
    <li>`<i>` - Itálico</li>
    <li>`<em>` - Texto alternativo</li>
    <li>`<mark>` - Marcado</li>
    <li>`<small>` - Pequeno</li>
    <li>`<del>` - Deletado</li>
    <li>`<ins>` - Inserido</li>
    <li>`<sub>` - Subscrito</li>
    <li>`<sup>` - Sobrescrito</li>
</ul>

## Elementos `<b>` e `<strong>` 

O elemento `<b>` especifica texto em negrito, sem qualquer significado especial.

O elemento `<strong>` é usado para definir texto importante.

```html
<p>Este é um <b>texto importante</b></p>
<p>Este é um <strong>texto importante</strong></p>
```

## Elementos `<i>` e `<em>`

O elemento `<i>` especifica texto em itálico, sem qualquer significado especial.

O elemento `<i>` é tipicamente usado para indicar termos técnicos, palavras estrangeiras, pensamentos, ou outros textos que são diferentes do texto ao redor.

O elemento `<em>` é usado para definir ênfase. O conteúdo do elemento `<em>` é tipicamente exibido em itálico.

```html
<p>Este é um <i>texto alternativo</i></p>
<p>Este é um <em>texto alternativo</em></p>
```
Um leitor de tela geralmente pronuncia o conteúdo do elemento `<em>` com ênfase.

## Elemento `<mark>`

O elemento `<mark>` define texto marcado.

O texto marcado tipicamente é exibido com uma cor amarela brilhante.

```html
<p>Este é um <mark>texto marcado</mark></p>
```

## Elemento `<small>`

O elemento `<small>` define um texto pequeno.

```html
<p>Este é um <small>texto pequeno</small></p>
```

## Elementos `<del>` e `<ins>`

O elemento `<del>` define texto deletado.

O texto deletado é tipicamente exibido com uma linha riscada.

O elemento `<ins>` define texto inserido.

O texto inserido é tipicamente exibido sublinhado.

```html
<p>Este é um <del>texto deletado</del></p>
<p>Este é um <ins>texto inserido</ins></p>
```

## Elementos `<sub>` e `<sup>`

O elemento `<sub>` define texto subscrito.

O texto subscrito é tipicamente exibido ligeiramente menor, e um pouco abaixo do texto normal.

O elemento `<sup>` define texto sobrescrito.

O texto sobrescrito é tipicamente exibido ligeiramente menor, e um pouco acima do texto normal.

```html

<p>Este é um <sub>texto subscrito</sub> e <sup>texto sobrescrito</sup></p>
```