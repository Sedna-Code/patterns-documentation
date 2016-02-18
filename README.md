# Pradrões estruturais e escrita front-end

Esta documentação foi criada para solucionar problemas nos projetos frontend, e teve como objetivo resolver problemas pontuais que nossa equipe vivia diariamente. Problemas como falta de padronização, estrutura do projeto que não tinha sentido, manter o projeto escalável e continuar tendo uma organização legível e diminuir a quantidade de repetição de código criando responsabilidades hierárquicas dentro do projeto sem torná-las uma dependente da outra.

Pode ser que você não siga ou não concorde com algumas dessas práticas ou utilizadas. Mas não existe uma padronização que agrade todos os gostos pessoais de cada um por isso precisamos escolher apenas um.

Todas as sugestões para colaborar com essas boas práticas iram ser analisadas para sempre melhorarmos cada vez mais a mesma.

## Índice

1. [Introdução](#introduction)
2. [Estrutura de pastas](#sctructure-folders)

<a name="introduction"></a>
## 1. Introdução

Quando decidimos a criar um padrão de escrita, fomos atrás de padrões e nomeclaturas para termos referências do que era tendência do mercado. Encontramos os seguintes padrões: SMACSS, Idiomatic e BEM que foram a base para chegarmos neste resultado final.

Esta padronização foi necessária, pois, queriamos que o código fosse uniforme e qualquer pessoa conseguisse manter o código e pudesse garantir que o projeto seja flexível e escalável de forma consistente.

<a name="sctructure-folders"></a>
## 2. Estrutura de pastas

App/
----- Images/
---------- Sprite/
---------- Temp/

----- Scripts/
---------- Source/
-------------- Base/
-------------- Layout/
-------------- Library/
-------------- Modules/
-------------- Plugins/
------------------ handlebars.runtime.min.js
------------------ jquery.min.js
-------------- Themes/
------------------ Templates/
------------------ Views/
-------------- Utilities/

-------------- Common.js
-------------- Config.js

---------- Styles/
-------------- Base/
------------------ Breakpoint.scss
------------------ Colors.scss
------------------ Container.scss
------------------ Fonts.scss
------------------ Mixins.scss
------------------ Reset.scss
-------------- Layout/
-------------- Modules/
-------------- Plugins/
-------------- Themes/
------------------ Templates/
------------------ Views/
-------------- Utilities/