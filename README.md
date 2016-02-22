# Padrões estruturais e escrita front-end

Esta documentação foi criada para solucionar problemas nos projetos front-end, e teve como objetivo resolver problemas pontuais que nossa equipe vivia diariamente. Problemas como falta de padronização, estrutura do projeto que não tinha sentido, manter o projeto escalável e continuar tendo uma organização legível e diminuir a quantidade de repetição de código criando responsabilidades hierárquicas dentro do projeto sem torná-las uma dependente da outra.

Pode ser que você não siga ou não concorde com algumas dessas práticas ou utilizadas. Mas não existe uma padronização que agrade todos os gostos pessoais de cada um por isso precisamos escolher apenas um.

Ajude-nos a tornar o projeto cada vez melhor. Contribuições serão sempre bem vindas. Para contribuir basta fazer um fork do projeto, fazer suas sugestões e nos enviar um pull request.

## Índice

1. [Introdução](#introduction)
2. [Estrutura de pastas](#sctructure-folders)
3. [Escrita de arquivos](#writing-files)
 3.1 [CSS](#css)
 3.2 [JavaScript](#js)

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
│   ├── Build // Diretório de arquivos compilados
│   │   ├── Images
│   │   │   └── Sprite.png
│   │   │   └── Logo.svg
│   │   ├── Scripts
│   │   │   └── App.js
│   │   └── Styles
│   │       └── App.css
│   ├── Source // Diretório de arquivos para desenvolvimento
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
│   │   │   ├── Pages // Páginas com informações específicas
│   │   │   └── Partials // Template com conteúdo reaproveitado em páginas
```

<a name="css"></a>
# 3. Escrita de arquivos

Para escrita de aquivos adotamos os seguintes padrões:
- [DRY](Don't Repeat Yourself) Visa reduzir a repetição de informações de todos os tipos.
- [KISS](Keep it simple, Stupid) Tem como objetivo evitar a complexidade desnecessária no projeto.
- [SOLID](Single responsibility, Open-closed, Liskov substitution, Interface segregation and Dependency inversion) Criar um sistema que seja fácil de manter e estender ao longo do tempo.

Ao utilizar estes padrões evitamos que problemas sutis possam causar grandes problemas futuros e melhora a legibilidade do código e estrutura. Além disso, os padrões permitem que os desenvolvedores desenvolvam um tipo de código só e em um único tipo de arquitetura, seguindo o primordial dos conceitos de que "".

<a name="files"></a>
## 3.1 Arquivos



<a name="css"></a>
## 3.2 CSS

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Itaque quam modi laboriosam necessitatibus harum! Ducimus optio laboriosam nam totam. Ipsum cum dolor minus aspernatur cupiditate sapiente repudiandae soluta laborum dolores?

<a name="js"></a>
## 3.3 JavaScript

Escrever aquivos em JS deve-se utilizar o padrão UpperCamelCase:
– Atributos
– Métodos
- Classes

```js
var CodeFlavor
```

Criamos um arquivo de configuração do [JSHint](http://jshint.com/docs/options/) com opções específicas para nossa. As configurações estão no arquivo .jshintrc do nosso [Web Generator] (https://github.com/Sedna-Code/structure-web-generator/blob/master/.jshintrc)