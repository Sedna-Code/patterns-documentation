# Pradrões estruturais e escrita front-end
----

## Introdução
//Aqui escrever o problema e a solução encontrada

## Índice
//Colocar índice

## 1. Princípios da documentação
Quando decidimos a criar um padrão de escrita, fomos atrás de padrões e nomeclaturas para termos referências do que era tendência do mercado. Encontramos os seguintes padrões: SMACSS, Idiomatic e BEM que foram a base para chegarmos neste resultado final.

Esta padronização foi necessária, pois, queriamos que o código fosse uniforme e qualquer pessoa conseguisse manter o código e pudesse garantir que o projeto seja flexível e escalável de forma consistente.

Estes padrões foram definidos para a equipe de front-end da Advise Brasil. Aceitamos qualquer colaboração positiva deste projeto.

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