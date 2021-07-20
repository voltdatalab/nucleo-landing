---
layout: pages
title: 'Cobertura de tecnologia'
desc: 'Sites que acompanham o assunto de tecnologia, no Brasil e no Exterior'
tagline: PAUTAS E CVS
subtitle: 'Sites que acompanham o assunto de tecnologia'
atualizacao: 26/05/2021
---


O **Núcleo Jornalismo** se propõe a fazer uma cobertura mais aprofundada sobre o impacto da tecnologia na vida das pessoas, especialmente no que diz respeito às redes sociais, políticas públicas e privadas e algoritmos.

Mas há diversos outros veículos que cobrem tecnologia. Eis uma lista de quem acompanhamos no dia a dia para saber o que está acontecendo por aí.

{% for site in site.data.sites %}

| {{ site.nome }}      | [{{ site.link }}]({{ site.link }})          | {{ site.local }} |


{% endfor %}
