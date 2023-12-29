## Cores HSL

Um valor HSL é definido com: hsl(hue, saturation, lightness).

A hue (matiz) é um grau no círculo de cores, de 0 a 360. 0 (ou 360) é vermelho, 120 é verde e 240 é azul.

A saturation (saturação) é um valor percentual, de 0% a 100%. 0% significa uma cor sem saturação (cinza), e 100% é a cor total.

A lightness (luminosidade) é um valor percentual, de 0% a 100%, onde 0% é preto, 50% é normal e 100% é branco.

Por exemplo, hsl(0, 100%, 50%) é exibido como vermelho, porque o grau é 0, a saturação é 100% e a luminosidade é 50%.

Outro exemplo, hsl(120, 100%, 50%) é exibido como verde, porque o grau é 120, a saturação é 100% e a luminosidade é 50%.

## Saturação

A saturação é a intensidade ou pureza de uma cor.

100% é a saturação total, sem tons de cinza.

50% é 50% cinza, mas você ainda pode ver a cor.

0% é completamente cinza, e você pode não ver a cor.

## Luminosidade

A luminosidade é a quantidade de branco (luz) ou preto (sombra) em uma cor.

100% é branco, 0% é preto e 50% é normal.

## Tons de Cinza

Os tons de cinza são definidos usando valores iguais para todos os parâmetros HSL:

```html
<p style="color:hsl(0,0%,0%);">Texto preto</p>
<p style="color:hsl(0,0%,50%);">Texto cinza</p>
<p style="color:hsl(0,0%,100%);">Texto branco</p>
```

## Cores HSLA

HSLA é uma extensão de HSL que inclui o canal alfa - que especifica a opacidade da cor.

Um valor HSLA é definido com: hsla(hue, saturation, lightness, alpha).

O parâmetro alpha é um número entre 0.0 (totalmente transparente) e 1.0 (totalmente opaco).

Por exemplo, hsla(0, 100%, 50%, 0.3) é exibido como vermelho com 30% de opacidade.