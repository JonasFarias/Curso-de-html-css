<h1>PROPRIEDADE POSITION
</h1>
<p>A propriedade display do CSS define como um elemento HTML será renderizado na página. Ela pode assumir diversos valores, que determinam o tipo de caixa de renderização utilizada para o elemento.</p>

Os `valores mais comuns` da propriedade display são:
<ul>
<li>block: o elemento é renderizado como um bloco, que ocupa toda a largura da linha e flui para a linha seguinte. Exemplos de elementos com display: div, p, ul, ol.</li>
<li>inline: o elemento é renderizado como um elemento inline, que é alinhado à esquerda ou à direita da linha. Exemplos de elementos com display: span, a, img.</li>
<li>none: o elemento é ocultaizado usando o layout flexbox.</li>
<li>grid: o elemento é renderizado usando o layout grid.</li>

</ul>
A propriedade display é uma ferramenta poderosa que pode ser usada para controlar a aparência e o comportamento dos elementos HTML.

## Exemplos de uso da propriedade display:

Para criar um menu de navegação, podemos usar a propriedade display: flex para alinhar os itens do menu horizontalmente.
Para criar uma galeria de imagens, podemos usar a propriedade display: grid para organizar as imagens em uma grade.
Para ocultar um elemento da página, podemos usar a propriedade display: none.
Para aprender mais sobre a propriedade display, consulte a documentação oficial do CSS.

TIPOS DE POSSIBILIDADES DE POSICIONAMENTO


O tipo de posicionamento position em CSS determina como um elemento será posicionado na página. O valor padrão é static, que significa que o elemento será posicionado no fluxo normal do documento. Os outros valores possíveis são:

relative: O elemento é posicionado em relação ao seu elemento pai.
absolute: O elemento é posicionado em relação ao seu elemento pai, mas fica fora do fluxo normal do documento.
fixed: O elemento é posicionado em relação à viewport (área visível da página).
sticky: O elemento é posicionado em relação ao seu elemento pai, mas fica fixo na viewport quando o usuário rola a página.
O posicionamento absoluto é um dos tipos de posicionamento mais utilizados em CSS. Ele é útil para criar efeitos visuais, como menus suspensos, barras de ferramentas e banners.



Flexbox

O Flexbox é um layout que organiza elementos em uma única dimensão, seja horizontal ou vertical. Ele é baseado em dois eixos: o eixo principal e o eixo cruzado.

Eixo principal: é o eixo ao longo do qual os elementos são dispostos. O eixo principal pode ser definido como horizontal ou vertical usando a propriedade flex-direction.

Eixo cruzado: é o eixo perpendicular ao eixo principal. O eixo cruzado é usado para definir o espaço entre os elementos.

Propriedades principais:

flex-direction: define o eixo principal.
justify-content: define o alinhamento dos elementos ao longo do eixo principal.
align-items: define o alinhamento dos elementos ao longo do eixo cruzado.
flex-wrap: define se os elementos devem ser wrapados ou não.
flex-grow: define como o elemento deve crescer quando o espaço disponível aumenta.
flex-shrink: define como o elemento deve encolher quando o espaço disponível diminui.
flex-basis: define o tamanho inicial do elemento.
Exemplos de uso:

Para criar um menu de navegação horizontal, podemos usar a propriedade flex-direction: row para definir o eixo principal como horizontal e a propriedade justify-content: space-between para alinhar os itens do menu uniformemente.
Para criar uma lista de itens alinhados à esquerda, podemos usar a propriedade align-items: flex-start para alinhar os itens do menu à esquerda.
Para criar uma galeria de imagens com dois itens por linha, podemos usar a propriedade flex-wrap: wrap para wrapar os itens e a propriedade flex-basis: 50% para definir o tamanho inicial dos itens como 50% da largura da linha.
Grid Layout

O Grid Layout é um layout que organiza elementos em uma grade bidimensional. Ele é baseado em linhas e colunas, que podem ser usadas para criar layouts complexos e adaptáveis.

Propriedades principais:

display: define o elemento como uma grade usando o valor grid.
grid-template-columns: define o número e o tamanho das colunas da grade.
grid-template-rows: define o número e o tamanho das linhas da grade.
grid-column-start: define a coluna inicial do elemento.
grid-column-end: define a coluna final do elemento.
grid-row-start: define a linha inicial do elemento.
grid-row-end: define a linha final do elemento.
grid-gap: define o espaço entre as colunas e as linhas da grade.
Exemplos de uso:

Para criar uma galeria de imagens com duas colunas e três linhas, podemos usar as propriedades grid-template-columns: 25% 75% e grid-template-rows: 25% 25% 25% para definir o número e o tamanho das colunas e das linhas da grade.
Para posicionar um elemento no centro da grade, podemos usar as propriedades grid-column-start: 50% e grid-row-start: 50% para definir a coluna e a linha inicial do elemento como 50%.
Para criar uma grade responsiva, podemos usar a propriedade grid-template-columns: repeat(auto-fill, minmax(25%, 1fr)) para definir o número de colunas como o mínimo necessário para caber todos os elementos, com um tamanho mínimo de 25% da largura da linha.
Conclusão

O Flexbox e o Grid Layout são ferramentas poderosas que podem ser usadas para criar layouts responsivos e adaptáveis. O Flexbox é mais adequado para layouts simples em uma dimensão, enquanto o Grid Layout é mais adequado para layouts complexos com várias dimensões.
