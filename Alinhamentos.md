# GRID: Alinhamento

Existem 6 propriedades de alinhamento:
1. `justify-content`
2. `align-content`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

Vamos separar em 2 grupos
1. `justify` e `align`
2. `content`, `items` e `self`


## Justily e Align

Sabendo que o grid é bidimensional, nós  temos o eixo x e y;

O **eixo x** é o posicionamento horizontal, da esquerda para a direita 

O **eixo y** é o posicionamento vertical, da cima para baixo

## Content, items e self

Juntado o `justify`, ou `align`, com esses elementos: `content`, `items` e `self`; nós observamos nossas propriedades


### Content

`justify-content` e `align-content` nos permite alinha o proprio grid, relativo a espaço fora do grid

O uso dessas propriedades são raras, pois só é aplicado caso o grid seja  menor que a area defenida.
(Por exemplo, quando usamos em px o tamanha do grid, podemos terminar com um grid pequeno, para o 
tamanha da area do grid)


Podemos usar **7 valores**

1. start
2. end
3. center
4. stretch
5. space-between
6. space-around
7. space-evenly


### Items

`justify-items` e `align-items` vai permitir alinhar os items do nosso grid, em qualquer espaço
disponivel, na célula que ele habitar.

Podemos usar **4 valores**

1. start
2. end
3. center
4. stretch

### Self

`justify-self` e `align-self` vai permitir alinhar os items em si.

Faz a mesma coisa que o `justify-items` e `align-items`, porém, aplicado diretamente no item  de um grid


