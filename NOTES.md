# HTML Canvas Graphics

A tag `<canvas>` nada mais é do que um container para gráficos. Basicamente, é uma tela, uma região definida no código HTML com atributos de altura e largura.
Canvas usa vários métodos para desenhar formas personalizadas (círculo, semicírculo, Retângulo e Quadrado) caracteres, e adicionar imagens. Também podemos usar CSS para a tag .

###### Exemplo:

```
<canvas width="600" height="600"></canvas>
    <script>
        let canvas = document.querySelector('canvas');
        let context = canvas.getContext('2d')

        context.fillRect(100, 100, 400, 400);
    </script>
```

##### fillRect()

`fillRect()` é uma função que leva quatro parâmetros, eixo X, eixo Y, Largura e altura.
No exemplo acima, os valores `(100, 100, 400, 400)`, começando pelos eixos x e y (100 e 100), determinam onde na tela(`<body></body>`) se posicionará o elemento canvas, começando em 0, se moverá 100 pixels no eixo x(para a direita), após, 100 pixels para baixo, no eixo y. Prosseguindo, neste ponto começamos a desenhar a forma, os parâmetros de largura e altura ( 400 e 400 ) ocuparão o espaço de deslocamento de 400 pixels para a direita e 400 pixels para baixo.

Neste link, encontrarei as referências do canvas, Propriedades e Metodos https://www.w3schools.com/tags/ref_canvas.asp
Obs: Quando observamos "method", na documentação, estamos falando de funções.

### Canvas sketch

###### Comandos:

canvas-sketch nome-projeto.js --new --open / Cria e abre o projeto canvas-sketch

canvas-sketch nome-projeto.js --output=output/01

https://github.com/mattdesl/canvas-sketch/blob/master/docs/api.md
https://github.com/mattdesl/canvas-sketch/blob/master/docs/README.md

https://www.devmedia.com.br/html5-a-tag-canvas/25413
https://www.w3schools.com/html/html5_canvas.asp
Read more: http://www.linhadecodigo.com.br/artigo/3488/entendendo-a-tag-canvas-no-html-5.aspx#ixzz7DHaE7I3z
