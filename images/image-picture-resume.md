## Element Picture

O elemento `<picture>` permite que você defina diferentes imagens para diferentes dispositivos ou tamanhos de tela.

Contém um ou mais elementos `<source>`, cada um se referindo a diferentes imagens com o atributo `srcset`. Dessa forma o navegador pode escolher a melhor imagem para o dispositivo ou tamanho de tela.

Cada `<source>` tem um atributo `media` que especifica o tamanho da tela para mostrar a imagem.

O elemento `<picture>` também contém um elemento `<img>` com um atributo `src` para navegadores que não suportam o elemento `<picture>`.

```html
<picture>
    <source media="(min-width: 650px)" srcset="img_tigre.jpg">
    <source media="(min-width: 465px)" srcset="img_gato.jpg">
    <img src="img_tigre.jpg" alt="Tigre">
</picture>
```