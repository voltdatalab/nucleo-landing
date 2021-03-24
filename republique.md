---
layout: pages
title: 'Jornalismo do Núcleo em outros veículos'
desc: 'O Núcleo permite, caso a caso, que outras publicações republiquem nosso conteúdo, a fim de aumentar a abrangência do nosso jornalismo.'
tagline: Republicação
subtitle: ''
atualizacao: 24/03/2021
---

O **Núcleo** permite que outros sites de jornalismo republiquem nosso conteúdo, a fim de aumentar a abrangência do nosso jornalismo e de nossos projetos. Saiba mais sobre nosso impacto [nesta página]({{ site.baseurl }}/impacto).

Caso sua iniciativa jornalística tenha interesse em republicar nosso conteúdo, entre em contato: [nucleo@votdata.info](mailto:nucleo@voltdata.info)

## COMO FUNCIONA?

- **AUTORIZAÇÃO**: Permissões para republicações de nossas matérias são discutidas caso a caso com editores de outros veículos. Nosso conteúdo **não** é _Creative Commons_ nem possui nenhum outro tipo de licença aberta, é necessário nossa autorização para republicar.  

- **VALORES**: Fazer jornalismo de qualidade custa caro. A cobrança por licenciamento varia de acordo com as conversas, e uma reportagem pode até mesmo ser cedida gratuitamente caso isso faça parte da estratégia de impacto digital do **Núcleo**.

- **TIMING**: Reportagens cedidas gratuitamente não podem ser reproduzidas antes de 24h da publicação original no site do **Núcleo**.

- **ALTERAÇÕES**: Caso uma matéria seja cedida ao seu veículo, quaisquer alterações de conteúdo precisam ser combinadas de antemão com os editores do **Núcleo**, inclusive título.

- **REFERÊNCIAS E LINKS**: O nosso jornalismo é baseado em transparência e crédito a terceiros. Caso uma matéria seja cedida ao seu veículo, todos as referências e links da matéria original deverão permanecer, mesmo que citem veículos concorrentes.

- **ASSINATURA DA MATÉRIA**: Nosso jornalismo é coletivo, e em geral nossas matérias são assinadas por mais de uma pessoa, seja a reportagem, a análise, a arte ou edição, entre outras colaborações. Esses créditos deverão ser atribuídos na republicação. Nesse caso, reportagem e análise podem ficar no _byline_ e o restante dos créditos no pé da matéria.

- **COMO CREDITAR O NÚCLEO**: Crédito de republicações deverá ser dado a `Núcleo Jornalismo`, obrigatoriamente com o link para a análise de referência ou para o site `www.nucleo.jor.br`.


## Matérias republicadas em parceria

{% for rep in site.data.republicacao %}

&#8594; __{{ rep.veiculo }}__: [{{ rep.titulo }}]({{ rep.link }})

{% endfor %}

## &#8594; Matérias de repercussão

{% for rep in site.data.repercussao %}

&#8594; __{{ rep.veiculo }}__: [{{ rep.titulo }}]({{ rep.link }})

{% endfor %}
