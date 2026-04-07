# conceitos-css
# Conceitos Margin, Padding e Border

## Margin
### O que é?
- O **CSS margin** é uma propriedade utilizada para adicionar um distanciamento na parte externa, ao redor do elemento.
- Ela pode ser definida com diferentes unidades de medidas e deve ser utilizada com atenção, pois como altera o posicionamento dos elementos, pode desestruturar o layout da página HTML.
- A margin é uma área transparente, pois não recebe a propriedade background do elemento a que pertence. Trata-se de uma propriedade importante, pois ajuda a definir o layout e a centralizar os elementos em uma área sem a necessidade de realizar diversos cálculos.
### Ela deve ser usada da seguinte maneira:
- #elemento {
    margin-top: 15px;
    margin-right: 10px;
    margin-bottom: 25px;
    margin-left: 35px;
}

## Padding

### O que é?
- O **padding CSS** é uma propriedade relacionada com a distância de um elemento e a borda da página.
-  Para entender melhor, basta pensar no elemento como uma caixa que precisa ser deslocada dentro do site. Você pode querer que ela fique mais para a esquerda, para direita, para cima ou para baixo.
- ### Como usar
- Para usar o **padding** do **CSS** não há muito segredo. Você só precisa entender exatamente qual parte da tela deseja alterar. Dessa forma, você pode fazer usar:

1. padding-top: para configurar do elemento ao topo;
2. padding-right: do elemento até a direita;
3. padding-left: do elemento até a esquerda;
4. padding-bottom: do elemento até a parte inferior.

## Border

### O que é?
- **Border CSS**, ou bordas aplicadas no estilo em cascatas, é uma propriedade que adiciona um contorno em volta de um elemento HTML.
- Localizada entre o **padding** e a **margin**, ela pode ser aplicada em todos os lados de um elemento da página e tem características diferentes, como tamanhos, cores e estilos.
### Como usar?
- Utilizando apenas a propriedade **border**, é possível aplicar três valores:

**border**: 30px solid blue;
O código acima é uma forma abreviada de escrever os mesmos valores abaixo:

border-width: 30px; // Estiliza a sua largura
border-style: solid; // Estiliza seu estilo
border-color:  blue; // Estiliza sua cor
