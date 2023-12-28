## Parágrafos HTML

Parágrafos são definidos com a tag `<p>`.

Um parágrafo sempre começa em uma nova linha, e os navegadores adicionam automaticamente um espaço em branco (uma margem) antes e
depois de um parágrafo.

```html
<p>Este é um parágrafo.</p>
<p>Este é outro parágrafo.</p>
```

## Como o HTML é exibido

Você pode não ter certeza de como o HTML é exibido.

Telas grandes e pequenas, e janelas de tamanhos diferentes irão criar resultados diferentes.

Com HTML, você não pode alterar o tamanho da tela adicionando espaços e linhas extras no seu código.

O navegador removerá espaços e linhas extras quando a página for exibida:

```html
<p>
Este parágrafo
contém uma linha em branco

no código fonte.
</p>
```

## Regras Horizontais

A tag `<hr>` define uma quebra temática em uma página HTML, e é mais usada para separar conteúdo (como em um livro).

```html
<p>Este é um parágrafo.</p>
<hr>
<p>Este é outro parágrafo.</p>
```

A tag `<hr>` é uma tag vazia, o que significa que ela não possui tag de fechamento.

## Quebras de Linha

A tag `<br>` define uma quebra de linha.

Use `<br>` se você quiser adicionar uma quebra de linha (uma nova linha) em um texto, sem começar um novo parágrafo:

```html
<p>Este é<br>um parágrafo<br>com quebras<br>de linha.</p>
```

A tag `<br>` é uma tag vazia, o que significa que ela não possui tag de fechamento.

## O problema do poema

Este poema será exibido em uma unica linha:

```html
<p>
    Nosso céu tem mais estrelas,
    Nossas várzeas têm mais flores,
    Nossos bosques têm mais vida,
    Nossa vida mais amores.
</p>
```

## O problema do poema resolvido

O elemento `<pre>` define texto pré-formatado.

O texto dentro deste elemento é exibido em uma fonte de largura fixa (geralmente Courier), e ele preserva espaços e quebras de linha:

```html
<pre>
    Nosso céu tem mais estrelas,
    Nossas várzeas têm mais flores,
    Nossos bosques têm mais vida,
    Nossa vida mais amores.
</pre>
```

Outra solução é usar a tag `<br>`:

```html
<p>
    Nosso céu tem mais estrelas,<br>
    Nossas várzeas têm mais flores,<br>
    Nossos bosques têm mais vida,<br>
    Nossa vida mais amores.
</p>
```