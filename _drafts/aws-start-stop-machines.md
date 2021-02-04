---
title: Reduzindo custos na AWS com Start e Stop de instâncias
author: Romaryo Ricardo
date: 2021-02-03 23:30:00 +0300
categories: [Blogging, "AWS"]
tags: ["AWS"]
toc: true
pin: false
---

<!-- .<br>
.<br>
.<br>
.<br>
.
.
.
Fala Pessoal, Tudo bem com vocês? 

Meu nome é [**Romaryo**](/tabs/about/), e sempre achei **compartilhar conhecimento** muito importante para a formação de um bom profissional, ao passar o conhecimento, você solidifica o seu, e esse blog foi criado com esse objetivo.

Aqui você vai encontrar assuntos relacionados a DevOps, Infra e Desenvolvimento.

**Conhecimento** nunca é demais 🙂 e Aprendizagem contínua é o nosso lema!!

Espero muito que o conteúdo te ajude a ir mais além na sua carreira e alcançar seus objetivos 🚀🚀
 -->

Fala Pessoal,

Nesse post vamos falar de uma forma de economizar 💰💰 na AWS. (Economizar é sempre bom 😁)

Sabe aquelas máquinas utlizada para desenvolvimento e homologação? Normalmente a noite e fins de semana elas não são utilizadas, e gera um custo que pode ser facilmente evitado.

Usar o seu ambiente em cloud te dá a flexibilidade de parar seus recursos e não ser cobrado por eles, e levando isso em consideração, vou te mostrar uma forma de automatizar o stop e start programado dessas instâncias, assim o estagiário não precisa fazer isso todos os dias hahaha
<br>
Então vamos lá ...
<br>




