# Relógio Digital em JavaScript e CSS
Projeto de um relógio virtual que atualiza as horas, minutos e segundos em tempo real estilizado em CSS

Este projeto consiste em um relógio digital desenvolvido utilizando JavaScript e CSS. O relógio exibe as horas, minutos e segundos em tempo real em uma página da web.

## JavaScript

### Variáveis

- `horas`, `minutos` e `segundos`: Armazenam as referências aos elementos HTML responsáveis por exibir as horas, minutos e segundos na página.

### Função setInterval

- `setInterval`: Cria um intervalo de tempo repetitivo que executa a função `time` a cada intervalo definido.

### Função `time()`

- `dateToday`: Cria um objeto `Date` que representa a data e hora atuais.
- `hr`, `min` e `sec`: Armazenam as horas, minutos e segundos extraídos da data atual.
- Verificações condicionais: Garantem que os valores de horas, minutos e segundos sempre tenham dois dígitos, adicionando um zero à frente se forem menores que 10.
- Atualização do conteúdo HTML: Atualiza os elementos HTML correspondentes com os valores das variáveis `hr`, `min` e `sec`, garantindo que os valores sejam exibidos na página.

## CSS

### Seletor `*`

- Define estilos para todos os elementos na página.
- Define um padding e margem de 0 para todos os elementos.
- Especifica a fonte utilizada como Arial, Helvetica ou uma fonte genérica sans-serif.

### Seletor `body`

- Define estilos específicos para o elemento `<body>` da página.
- Define a altura como 100% da altura da viewport (toda a altura visível da janela do navegador).
- Define um fundo com um gradiente linear de duas cores.
- Utiliza `display: flex` para criar um container flexível.
- Utiliza `align-items: center` e `justify-content: center` para centralizar verticalmente e horizontalmente o conteúdo dentro do `<body>`.

### Seletor `.relogio`

- Define estilos para uma classe chamada "relogio".
- Utiliza `display: flex` para criar um container flexível para os elementos internos.
- Utiliza `align-items: center` e `justify-content: space-around` para centralizar verticalmente o conteúdo e distribuir o espaço igualmente entre os elementos internos.
- Define altura, largura, fundo, bordas arredondadas e sombra para o relógio.

### Seletor `.relogio div`

- Define estilos para os elementos `<div>` dentro do elemento com a classe "relogio".
- Define altura, largura, fundo, bordas arredondadas, sombra e espaçamento entre letras.
- Utiliza `display: flex` para criar um container flexível para o conteúdo interno.
- Utiliza `flex-direction: column` para empilhar o conteúdo verticalmente.
- Utiliza `align-items: center` e `justify-content: center` para centralizar verticalmente e horizontalmente o conteúdo.

### Seletor `.relogio span`

- Define estilos para os elementos `<span>` dentro do elemento com a classe "relogio".
- Define a espessura da fonte como "bolder" (mais negrito) e o tamanho da fonte.
- Utiliza a classe `.tempo` para definir um tamanho de fonte menor.

Utilize este projeto como base para criar e estilizar um relógio digital personalizado em sua página web.
