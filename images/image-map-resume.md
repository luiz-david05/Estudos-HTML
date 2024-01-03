## Image Maps 

A tag `<map>` define um mapa de imagem. Um mapa de imagem é uma imagem com áreas clicáveis. As áreas são definidas com a tag `<area>`.

```html
<img src="planets.gif" width="145" height="126" alt="Planets" usemap="#planetmap">

<map name="planetmap">
  <area shape="rect" coords="0,0,82,126" alt="Sun" href="sun.htm">
  <area shape="circle" coords="90,58,3" alt="Mercury" href="mercur.htm">
  <area shape="circle" coords="124,58,8" alt="Venus" href="venus.htm">
</map>
```

## Como isso funciona?

A ideia é que você tenha uma imagem e queira que as pessoas possam clicar em partes diferentes da imagem. Por exemplo, você pode ter um mapa do mundo e deseja que as pessoas possam clicar em cada país para obter mais informações sobre ele.

Para fazer isso, você precisa de uma imagem e de um mapa de imagem. O mapa de imagem é um arquivo separado que define as áreas clicáveis da imagem. O mapa de imagem é vinculado à imagem usando o atributo `usemap`.

## A imagem

A imagem é inserida usando a tag `<img>`. A única diferença é que você precisa adicionar o atributo `usemap`:

```html
<img src="planets.gif" width="145" height="126" alt="Planets" usemap="#planetmap">
```
O valor do `usemap` começa com um caractere `#` e deve corresponder ao valor do atributo `name` do mapa de imagem.

## Criando um mapa de imagem

Um mapa de imagem é criado com a tag `<map>`. O atributo `name` é usado para vincular o mapa de imagem à imagem:

```html
<map name="planetmap">
```	
O atributo `name` deve ter o mesmo valor que o atributo `usemap` da imagem.

## As áreas clicáveis

As áreas clicáveis são definidas com a tag `<area>`. 

# Shape

O atributo `shape` define a forma da área clicável. Os valores possíveis são:

* `rect` - define um retângulo
* `circle` - define um círculo
* `poly` - define uma forma poligonal
* `default` - define todo o elemento

# Shape="rect"

As coordenadas para `shape="rect"` vem em pares, representando o canto superior esquerdo e o canto inferior direito do retângulo (x1, y1, x2, y2):

Então, as coordenadas `0,0` são localizadas 0 pixels da esquerda da margim e 0 pixels do topo.

As coordenadas `82,126` são localizadas 82 pixels da esquerda da margim e 126 pixels do topo.

```html
<area shape="rect" coords="0, 0, 82, 126" alt="Sun" href="sun.htm">
```

# Shape="circle"

As coordenadas para `shape="circle"` vem em três valores: as coordenadas x e y do centro do círculo e o raio do círculo (x, y, raio):

```html
<area shape="circle" coords="90, 58, 3" alt="Mercury" href="mercur.htm">
```

# Shape="poly"

As coordenadas para `shape="poly"` vem em pares, representando os pontos x e y de cada vértice do polígono:

```html
<area shape="poly" coords="124,58, 118,63, 118,70, 124,73, 130,70, 130,63" alt="Venus" href="venus.htm">
```

# Shape="default"

O valor `default` define todo o elemento:

```html
<area shape="default" coords="0,0,82,126" alt="Sun" href="sun.htm">
```

## Image map e javascript

Você pode usar o mapa de imagem para executar uma função JavaScript quando o usuário clicar em uma área clicável. Para fazer isso, adicione o atributo `onclick` à tag `<area>`:

```html
<area shape="rect" coords="0,0,82,126" alt="Sun" onclick="sun()">
```