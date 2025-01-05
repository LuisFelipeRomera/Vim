# Moving through the lines in Vim text editor

## Movimentos Básicos no Modo Normal:

1. **Caracteres:**

- `h`: Move o cursor para a esquerda.
- `l`: Move o cursor para a direita.   

2. **Linhas:**

- `j`: Move o cursor para a linha abaixo.
- `k`: Move o cursor para a linha acima.

## Movimentos por Palavra:

1. **Avançar para a próxima palavra:**

- `w`: Vai para o início da próxima palavra.
- `e`: Vai para o final da palavra atual ou da próxima.

2. **Retroceder para a palavra anterior:**

- `b`: Vai para o início da palavra anterior.
- `ge`: Vai para o final da palavra anterior.

## Movimentos por Linha:

1. **Início ou Fim:**
   
- `0`: Vai para o início absoluto da linha.
- `^`: Vai para o primeiro caractere não vazio.
- `$`: Vai para o final da linha.

## Movimentos por Tela:

1. **Para cima e para baixo:**

- `Ctrl-d`: Move metade da tela para baixo.
- `Ctrl-u`: Move metade da tela para cima.
- `Ctrl-f`: Move uma tela inteira para baixo (scroll).
- `Ctrl-b`: Move uma tela inteira para cima (scroll).

2. **Mover para o topo, meio ou final da tela:**

- `H`: Vai para o topo da tela (high).
- `M`: Vai para o meio da tela (middle).
- `L`: Vai para o final da tela (low).

## Movimentos por Texto:

1. **Parágrafos:**

- `{`: Vai para o início do parágrafo anterior.
- `}`: Vai para o início do próximo parágrafo.

2. **Sentenças:**

- `(`: Vai para o início da sentença anterior.
- `)`: Vai para o início da próxima sentença.

## Movimentos para Navegar no Documento:

1. **Linhas específicas:**

- `gg`: Vai para o início do documento.
- `G`: Vai para o final do documento.
- `NúmeroG`: Vai para uma linha específica (ex.: 10G vai para a linha 10).

2. **Buscas:**

- `/texto`: Busca por "texto" no documento (para frente).
- `?texto`: Busca por "texto" no documento (para trás).
- `n`: Repete a última busca para frente.
- `N`: Repete a última busca para trás.

## Movimentos Visuais:

1. **Movimentos por blocos de código:**

- `%`: Salta entre parênteses, colchetes ou chaves correspondentes.

2. **Marcadores:**

- `m{letra}`: Marca a posição atual com uma letra (ex.: ma).
- `'a`: Move para a linha marcada com a.
- `` `a ``: Move para o caractere exato marcado com a.

*Este texto foi produzido em maioria pelo chat-GPT, com algumas modificações para ficar a meu gosto*
