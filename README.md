# Etapas do Projeto!

Esse READ ME tem como finalidade fixar os conteúdos abordados sobre a tecnologia Sass e os principais pontos da sua sintaxe.

## Etapa 01:

- Carregamos o projeto base que vamossta estilizar neste treinamento com Sass;
- Organizamos os arquivos de estilos criando partials, que contêm pequenos 
  trechos de CSS que podem ser incluídos em outros arquivos Sass;
- Modularizamos o CSS tornando as folhas de estilos mais fáceis de manter;
- Estilizamos o navbar e incluímos o efeito hover através do operador &.

## Etapa 02

- Criamos a partial para manter os estilos do banner e posicionamos a imagem e os textos;
- Realizamos operações matemáticas para ajustar os tamanho dos textos das tags h1 e do h2;
- Vimos de forma prática que as variáveis declaradas no nível superior de uma folha de estilo são globais, porém aqueles  declarados em blocos geralmente são locais e só podem ser acessados dentro do bloco em que foram declarados.

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

## Etapa 03

- Modularizamos os códigos de estilo criando a partial de serviço e cupom;
- Aplicamos os estilos nas imagens e nos textos melhorando a visibilidade do SPA.
