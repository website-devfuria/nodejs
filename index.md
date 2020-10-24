---
layout:      secao
title:       Node.js
description: Descobrindo o Node.js
---


__Node.js__ é JavaScript do lado do servidor!

É um ambiente de execução para usar JavaScript fora do navegador!
Ele incorpora a "engine" de JavaScript Google V8, a mesma do Google Chrome (ECMAScript 5)

Imagine que seu código __JavaScript__ esteja em um arquivo denominado `program.js`.

Para executá-lo com o __Node.js__, digite no terminal `node program.js`.

O __Node.js__ também possui um terminal interativo, digite `node` no terminal e divirta-se!

    $ node
    >
    > 111 * 111
    12321

Do lado do servidor, temos a variável `process` que seria equivalente a conhecida
[variável global window](/javascript/objeto-global/) do lado do cliente.


## Instalando o Node.js

Leia este artigo para aprender [como instalar o Node.js no Linux](/linux/instalando-nodejs/).


## Express

O [Express.js](http://expressjs.com/) é um dos frameworks mais utilizados do __Node.js__.


{% include get-capitulo.html page_serie="node-express" %}
{% include menus.html %}


## Testes unitários (Unit Test) com Node.js

Em breve, uma série de arquivos falando sobre __testes unitários__ e JavaScript no lado do servidor.

{% include get-capitulo.html page_serie="node-unit-tests" %}
{% include menus.html %}


## Site Oficial

- [Node.js](http://nodejs.org/)