# Padrões estruturais e escrita front-end

Esta documentação foi criada para solucionar problemas nos projetos front-end, e teve como objetivo resolver problemas pontuais que nossa equipe vivia diariamente. Problemas como falta de padronização, estrutura do projeto que não tinha sentido, manter o projeto escalável e continuar tendo uma organização legível e diminuir a quantidade de repetição de código criando responsabilidades hierárquicas dentro do projeto sem torná-las uma dependente da outra.

Pode ser que você não siga ou não concorde com algumas dessas práticas ou utilizadas. Mas não existe uma padronização que agrade todos os gostos pessoais de cada um por isso precisamos escolher apenas um.

Ajude-nos a tornar o projeto cada vez melhor. Contribuições serão sempre bem vindas. Para contribuir basta fazer um fork do projeto, fazer suas sugestões e nos enviar um pull request.

## Índice

1. [Introdução](#introduction)
2. [Estrutura de pastas](#sctructure-folders)

<a name="introduction"></a>
## 1. Introdução

Para escrever arquivos CSS escolhomos utilizar as seguintes ferramentas:
- [SMACSS](https://smacss.com/book/categorizing) para organizar os diretórios
- [idiomatic.css](https://github.com/necolas/idiomatic-css) para organizar os comentários
- [BEM](http://getbem.com/introduction/) para organizar a hierarquia os seletores
- [CSScomb](http://csscomb.com/) para organizar as propriedades de cada seletor

Esta padronização foi necessária, pois, queriamos que o código fosse uniforme e qualquer pessoa conseguisse manter o código e pudesse garantir que o projeto seja flexível e escalável de forma consistente.


<a name="sctructure-folders"></a>
## 2. Estrutura de pastas

Procuramos padronizar a estrutura de diretórios e nomenclatura de arquivos JS e CSS para melhorar a interpretação. Assim, qualquer pessoa que precisar dar manutenção no projeto, será possível recuperar rapidamente os respectivos arquivos.

```js
├── App/
│   ├── Build
│   │   ├── Images
│   │   │   └── Sprite.png
│   │   │   └── Logo.svg
│   │   ├── Scripts
│   │   │   └── App.js
│   │   └── Styles
│   │       └── App.css
│   ├── Source
│   │   ├── Fonts
│   │   ├── Images
│   │   ├── Scripts
│   │   ├── Styles
│   │   │   ├── Base
│   │   │   │   ├── Breakpoint.scss
│   │   │   │   ├── Colors.scss
│   │   │   │   ├── Container.scss
│   │   │   │   ├── Fonts.scss
│   │   │   │   ├── Mixins.scss
│   │   │   │   └── Reset.scss
│   │   │   ├── Layout
│   │   │   ├── Modules
│   │   │   ├── Plugins
│   │   │   ├── Themes
│   │   │   │   ├── Templates
│   │   │   │   └── Views
│   │   │   ├── Utilities
│   │   │   ├── Common.scss
│   │   │   └── Sprite.scss
│   │   ├── Views
│   │   │   ├── Pages
│   │   │   └── Partials
```