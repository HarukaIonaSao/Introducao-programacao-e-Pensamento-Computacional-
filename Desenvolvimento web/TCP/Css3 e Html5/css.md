#CSS


. (classe)

- (id só pode ser usado uma vez)

#Flexbox

Flex container
- Tag que envolve os itens, aplica propriedade "display:flex". Pode ser aplicada em qualquer tipo de tag

Propriedades relacionadas

- display(inicializador)
- flex-direction(direcionador)
 -flex-warp(quebra de linha)
 -flex-flow
 -justify-content
 -aling-items
 - align-content(alinhar as linhas do container)

Flex Item
- Elementos filhos diretos do Flex Container.E podem se tornar Flex Container

Propriedades relacionadas:
-Flex-grow 
-flex-basis
-Flex-shirink
-Flex(abreviação do grow,basis e shirink)
-order
-align-self 

##flex-direction
Estabelece o eixo do container
linha e coluna

-row(padrão):à direção do texto, esq p direita
-row-reverse:sentido oposto

-column: ordenação de cimapara baixo
-column-reverse: de cima p baixo

#Flex wrap

Define se os itens devem ou nãoquebrar linha

-nowrap : não que bra linha
-wrap:permite quebra de linha
-wrap-reverse

#flex flow
 atalho p "direction" e "wrap".

 -não é muito usado,pois mantém o padrão do wrap

#Justify Content

Alinha os itens dentro do container de acordo com a direção pretendida e tratar da disribuição de espaçamento entre eles.Se os  itens ocuparem 100% do conatainer, ela não se aplica

-variações

-flex-start:início do container
-flex-end:final do container
-center:ao cenro do container
-space-between: cria e espaçamento entre os elementos
-space-around:os espaçamentos do meio são duas vezes maiores que o inicial e o final

#align-itens

Alinha de acordo com o eixo do container
permite alinhamento central no eixo vertical
Diferente qundo os itens estão em colunas ou linhas

Tipos:
-center
-stretch
-flex-start
-flex-end
-baseline

#flex-items
flex-grow

define a prporcionalidade dos itens e o tamanho de seus conteúdos internos
Não funciona caso tenha adicionado justify 

-content ao flex-container

#Flex-basis
Estabelece o tamanho inicial do item antes da distrbuição de espaço restante dento dele,usando como base o conteúdo intern disposto
-auto
-px,%,em...
-0(zero):terá relação com a definiçao do flex grow

