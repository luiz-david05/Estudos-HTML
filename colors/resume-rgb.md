## Cores RGB 

Uma valor RGB representa a quantidade de vermelho, verde e azul em uma cor.

O valor é representado como: rgb(red, green, blue).

Cada parâmetro (red, green e blue) define a intensidade da cor como um número entre 0 e 255.

Isso quer dizer que isso tem 256 X 256 X 256 = 16.777.216 cores possíveis.

Por exemplo, rgb(255, 0, 0) é exibido como vermelho, porque o red é definido como 255, o green e o blue são definidos como 0.

## Cores RGBA

RGBA é uma extensão de RGB que inclui o canal alfa - que especifica a opacidade da cor.

Um valor RGBA é definido com: rgba(red, green, blue, alpha).

O parâmetro alpha é um número entre 0.0 (totalmente transparente) e 1.0 (totalmente opaco).

Por exemplo, rgba(255, 0, 0, 0.3) é exibido como vermelho com 30% de opacidade.

## Tons de Cinza

Os tons de cinza são definidos usando valores iguais para todos os parâmetros RGB:

```html
<p style="color:rgb(0,0,0);">Texto preto</p>
<p style="color:rgb(128,128,128);">Texto cinza</p>
<p style="color:rgb(255,255,255);">Texto branco</p>
```
