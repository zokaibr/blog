---
layout: post
title: 'Testing codeberg - Orientação a Objetos com Ruby (Parte 01) - Introdução e História'
image: /assets/images/posts/ruby-parte-01.webp
tags:
  - ruby
  - poo
  - oop
lang: ruby
playlist: orientacao_a_objetos_ruby
---

Fala comigo!

Recentemente eu me peguei explicando Orientação a Objetos com Ruby e embora eu tenha conseguido expressar o que queria, me frustrou não conseguir de uma forma melhor.

Estou revisitando algumas bibliografias e aproveitando pra escrever essa série e solidificar o conteúdo novamente.

Antes de começar qualquer coisa, embora eu vá deixar todas as referências que estou utilizando no final dessa série, eu PRECISO dar um destaque nesse primeiro post a uma playlist do Guanabara do Curso em Vídeo sobre Programação Orientada à Objetos que é uma coisa linda de assistir:

<a href="https://www.youtube.com/playlist?list=PLHz_AreHm4dmGuLII3tsvryMMD7VgcT7x" target="_blank">https://www.youtube.com/playlist?list=PLHz_AreHm4dmGuLII3tsvryMMD7VgcT7x</a>

Espero conseguir abordar alguns conceitos importantes da base da Orientação a Objetos. Então vamos começar pelo começo: de onde que surgiu isso? Pra que serve?

<hr />

## Uma Breve História da Orientação a Objetos

Os primeiros conceitos da orientação a objetos surgiram na Noruega na década de 70, quando Ole Johan Dahl e Kristen Nygaard criaram o Simula I em 1962, uma extensão da linguagem de programação Algol, e posteriormente o Simula 67 (em 1967), para simular comportamento de partículas de gases.

Posteriormente, aproveitando desses conceitos, o matemático estaduniense Alan Kay, uma figura importantíssima na área de Tecnologia da Informação, criou a linguagem Smalltalk dentro de uma área de pesquisa da Xerox PARC, onde os conceitos de Orientação a Objetos foram solidificados. Alan Kay também escreveu sua tese de PHD abordando a Orientação a Objetos.

Quando estava na Xerox, Alan Kay criou a linguagem Smalltalk devido a um projeto chamado Dynabook, que tinha o intuito de montar um ambiente de computação para pessoas de qualquer idade.

> Aqui eu deixo uma recomendação: Alan Kay foi uma figura ímpar na área de TI e criar a Smalltalk e cunhar o termo Orientação a Objetos foi uma de suas várias realizações. Fica a dica pra pesquisar mais sobre ele.

## O Paradigma Orientado a Objetos

Se você der uma googlada pela definição de "Paradigma", provavelmente você encontrará algo parecido que eu encontrei no Dicio (dicio.com.br): "Exemplo ou padrão a ser seguido".

Pensando na Orientação a Objetos como um modelo de programação, é importante dizer que ele não é o único e nem foi o primeiro a existir. Outros existem, como a programação estruturada, a imperativa e a funcional.

> Acho importante fazer um adendo que eu já vi alguns lugares colocando a programação orientada a objetos como uma "evolução da programação estruturada", onde existe um bloco único de código que executa sequencialmente. Eu particularmente não gosto dessas definições, já que o paradigma estruturado existe até hoje e ainda é utilizado na resolução de problemas. Então, é bom ficar atento com lugares que colocam a Orientação a Objetos como uma bala de prata, porque ela não é.

O modelo (ou paradigma) da Orientação a Objetos, evoluído pelo querido Alan Kay, tinha como base o que foi chamado de Análise Biológica: "Como seria se um software funcionasse como um ser vivo?". Através disso, a ideia era que cada parte do código fossem como células que interagem entre si enviando mensagens para alcançar um objetivo comum.

Com isso, podemos ver que a Orientação a Objetos nada mais é que um paradigma que tem por objetivo trazer pra dentro do software uma representação do mundo real, e a essa representação nós chamamos de "Objetos".

## E o que faz um Objeto?

Por ser uma representação de algo do mundo real, um Objeto sempre terá propriedades e comportamentos e com isso a gente pode literalmente pegar qualquer coisa tangível e intangível que está no nosso mundo, como: Pessoa, Animal, Livro, Temperatura, etc.

E esses objetos podem interagir uns com os outros para termos uma determinada ação dentro do sistema. Por exemplo, se um Veterinário atende um Animal, nós literalmente podemos ter dentro de um sistema
um objeto do tipo Veterinário que interagiria com um outro objeto do tipo Animal. Mas isso são cenas dos próximos capítulos =)

## Tá, mas e o Ruby com isso tudo?

O Ruby é uma linguagem japonesa criada por Yukihiro Matsumoto (mais conhecido como "Matz") em 1995. Ela tem como seu paradigma principal a Orientação a Objetos. Inclusive, umas das inspirações do Ruby foi o próprio Smalltalk.

Nesta série eu não vou abordar mais da história do Ruby, o intuito daqui pra frente é falar dos conceitos da Orientação a Objetos em si e como o Ruby lida com isso.