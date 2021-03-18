---
layout: pages
title: 'Jornalismo do Núcleo em outros veículos'
desc: 'O Núcleo permite, caso a caso, que outras publicações republiquem nosso conteúdo, a fim de aumentar a abrangência do nosso jornalismo.'
tagline: Republicação
subtitle: ''
atualizacao: 04/03/2021
---

O **Núcleo** permite que outras publicações republiquem nosso conteúdo, a fim de aumentar a abrangência do nosso jornalismo e de nossos projetos. Saiba mais sobre nosso impacto [nesta página]({{ site.baseurl }}/impacto).

## COMO FUNCIONA?

- **AUTORIZAÇÃO**: Permissões para republicações de nossas matérias são discutidas caso a caso com editores de outros veículos. Nosso conteúdo **não** é _Creative Commons_ nem possui nenhum outro tipo de licença aberta, é necessário nossa autorização para republicar.  

- **VALORES**: Fazer jornalismo de qualidade custa caro. A cobrança por licenciamento varia de acordo com as conversas, e uma reportagem pode até mesmo ser cedida gratuitamente caso isso faça parte da estratégia de impacto digital do **Núcleo**.

- **ALTERAÇÕES**: Caso uma matéria seja cedida ao seu veículo, quaisquer alterações de conteúdo precisam ser combinadas de antemão com os editores do **Núcleo**, inclusive título.

- **REFERÊNCIAS E LINKS**: O nosso jornalismo é baseado em transparência e crédito a terceiros. Caso uma matéria seja cedida ao seu veículo, todos as referências e links da matéria original deverão permanecer, mesmo que citem veículos concorrentes.

- **ASSINATURA DA MATÉRIA**: Nosso jornalismo é coletivo, e em geral nossas matérias são assinadas por mais de uma pessoa, seja a reportagem, a análise, a arte ou edição, entre outras colaborações. Esses créditos deverão ser atribuídos na republicação. Nesse caso, reportagem e análise podem ficar no _byline_ e o restante dos créditos no pé da matéria.

- **COMO CREDITAR O NÚCLEO**: Crédito de republicações deverá ser dado a `Núcleo Jornalismo`, obrigatoriamente com o link para a análise de referência ou para o site `www.nucleo.jor.br`.

Caso sua iniciativa jornalística tenha interesse em republicar nosso conteúdo, entre em contato.

##### Estamos nesses canais:

<i class="fab fa-whatsapp"></i> [Whatsapp](https://wa.me/5511934441844)

<i class="fab fa-telegram"></i> [Telegram](https://t.me/nucleojor )

<i class="far fa-envelope"></i> [nucleo@voltdata.info](mailto:nucleo@voltdata.info)

<i class="fab fa-twitter"></i> [@nucleojor](https://twitter.com/nucleojor)


## &#8594; Matérias republicadas em parceria

{% for rep in site.data.republicacao %}

&#8594; __{{ rep.veiculo }}__: [{{ rep.titulo }}]({{ rep.link }})

{% endfor %}

## &#8594; Matérias de repercussão

{% for rep in site.data.repercussao %}

&#8594; __{{ rep.veiculo }}__: [{{ rep.titulo }}]({{ rep.link }})

{% endfor %}
