# Etapas do Projeto!

Esse READ ME tem como finalidade fixar os conteúdos abordados sobre a tecnologia Sass e os principais pontos da sua sintaxe.

## Etapa 01:

- Carregamos o projeto base que vamos estilizar neste treinamento com Sass;
- Organizamos os arquivos de estilos criando partials, que contêm pequenos 
  trechos de CSS que podem ser incluídos em outros arquivos Sass;
- Modularizamos o CSS tornando as folhas de estilos mais fáceis de manter;
- Estilizamos o navbar e incluímos o efeito hover através do operador &.

### Palavras Reservadas

|Palavra Reservada  |	O que ela faz                         |
|-------------------|-----------------------------|
|`@use`|  Carrega mixins, functions e variáveis de outras folhas de estilos Sass e combina o CSS de diversas folhas de estilo juntos.      |
|`@forward`|Carrega uma folha de estilo Sass e torna os mixins, functions e variáveis disponíveis quando a folha de estilo é carregada pela regra do @use.|
|`@import`|Estende as regras de CSS para carregar styles, mixins, functions e variáveis de outras folhas de estilo.|
|`@mixings` and `@include`|Facilitam a reutilização de trechos de código.|
|`@function`|Define funções customizadas que podem ser utilizadas em expressões.|
| `@extend` |Permite que os seletores herdem estilos uns dos outros.|
| `@at-root` |Coloca estilos dentro dele na raiz do documento CSS.|
| `@error` |Faz com que a compilação falhe com uma mensagem de erro.|
| `@warn` | Imprime um aviso sem parar totalmente a compilação.|
| `@debug` | Imprime uma mensagem para fins de debugging. |
