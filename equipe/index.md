---
layout: pages
title: 'Equipe do Núcleo Jornalismo'
desc: 'Quem somos'
tagline: EQUIPE
subtitle: 'Conheça nossos profissionais'
atualizacao: 24/02/2021
---

O **Núcleo** é composto por pessoas comprometidas com o jornalismo e que possuem experiência em reportagem, análise de dados, investigações de documentos, estratégia digital e produtos editoriais.

---

<div class="container" style="padding: 0 5% 0px;max-width:550px">

<div style="padding: 0 5% 0px;max-width:550px">

<div class="row">

{% for d in site.data.equipe %}


<div class="col-sm-6 col-lg-6" style="margin-bottom:20px;">

<h4 style="margin-bottom:0;"><a href="{{ site.baseurl }}/equipe/{{ d.twitter }}">{{ d.nome }}</a></h4>

<small>{{ d.posicao }} - <a href="{{ site.baseurl }}/equipe/{{ d.twitter }}">bio <i class="fas fa-link fa-sm"></i></a></small>

</div>

{% endfor %}

</div>
</div>
</div>
