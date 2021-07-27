---
layout: pages
title: 'Equipe do Núcleo Jornalismo'
desc: 'Conheça nossos profissionais'
tagline: EQUIPE
subtitle: 'Conheça nossos profissionais'
atualizacao: 22/03/2021
---

O **Núcleo** é composto por pessoas comprometidas com o jornalismo e que possuem experiência em reportagem, análise de dados, investigações de documentos, estratégia digital e produtos editoriais.

{% assign staff = site.data.equipe | size %}

Temos atualmente {{ staff }} colaboradores trabalhando conosco.

---

<!-- MAIN CONTAINER -->
<div class="container" style="padding: 0 5% 0px;max-width:100%;margin: 0 auto">

<!-- TOP CONTAINER -->
<div style="padding: 0 5% 0px;max-width:650px">

<!-- 1o ROW CONTAINER -->
<div class="row">

<h4 style="text-align:center">Quem faz <br>
<small style="text-align:center;">O pessoal que faz a mágica do Núcleo</small></h4>

{% for d in site.data.equipe %}


<div class="col-sm-4 col-lg-4" style="margin:15px 0;text-align:center;min-height:170px">

<a href="{{ site.baseurl }}/equipe/{{ d.nome | downcase | replace: " ", "-" | replace: "é", "e" | replace: "í", "i" | replace: "á", "a" | replace: "ó", "o" | replace: "ú", "u" }}"><img style="max-width: 50%;min-height:50px" src="{{ site.baseurl }}/img/artes-equipe/cortes-justos/{{ d.nome | downcase | replace: " ", "-" | replace: "é", "e" | replace: "í", "i" | replace: "á", "a" | replace: "ó", "o" | replace: "ú", "u" }}.png"></a>
<h4 style="margin-bottom:0;">{{ d.nome }}</h4>

<small>{{ d.posicao }} - <a href="{{ site.baseurl }}/equipe/{{ d.nome | downcase | replace: " ", "-" | replace: "é", "e" | replace: "í", "i" | replace: "á", "a" | replace: "ó", "o" | replace: "ú", "u" }}">bio <i class="fas fa-link fa-sm"></i></a></small>

</div>

{% endfor %}

<!-- FECHA 1o ROW -->
</div>

<!-- 2o ROW CONTAINER -->
<div class="row" style="margin-top:30px">
<h4 style="text-align:center">Colaboradores externos <br>
<small style="text-align:center">Vêm de fora, mas são de casa</small></h4>

{% for d in site.data.colaboradores %}

<div class="col-sm-4 col-lg-4" style="margin:15px 0;text-align:center;min-height:170px">

<a href="{{ site.baseurl }}/equipe/{{ d.nome | downcase | replace: " ", "-" | replace: "é", "e" | replace: "í", "i" | replace: "á", "a" | replace: "ó", "o" | replace: "ú", "u" }}"><img style="max-width: 50%;" src="{{ site.baseurl }}/img/artes-equipe/cortes-justos/{{ d.nome | downcase | replace: " ", "-" | replace: "é", "e" | replace: "í", "i" | replace: "á", "a" | replace: "ó", "o" | replace: "ú", "u" }}.png"></a>
<h4 style="margin-bottom:0;">{{ d.nome }}</h4>

<small>{{ d.posicao }} - <a href="{{ site.baseurl }}/equipe/{{ d.nome | downcase | replace: " ", "-" | replace: "é", "e" | replace: "í", "i" | replace: "á", "a" | replace: "ó", "o" | replace: "ú", "u" }}">bio <i class="fas fa-link fa-sm"></i></a></small>

</div>

{% endfor %}

<!-- FECHA 2o ROW -->
</div>

<!-- 3o ROW CONTAINER
<div class="row" style="margin-top:30px">
<h4 style="text-align:center">Quem fez <br>
<small style="text-align:center">Passaram por aqui e vão deixar saudades</small></h4>

{% for d in site.data.equipe-old %}

<div class="col-sm-6 col-lg-6" style="margin-bottom:5px;">

<h4 style="margin-bottom:0;"><a href="{{ site.baseurl }}/equipe/{{ d.twitter }}">{{ d.nome }}</a></h4>

<small>{{ d.posicao }} - <a href="{{ site.baseurl }}/equipe/{{ d.twitter }}">bio <i class="fas fa-link fa-sm"></i></a></small>

</div>

{% endfor %}
 -->
<!-- FECHA 3o ROW
</div>
-->


<!-- CLOSE TOP CONTAINER -->
</div>

<!-- CLOSE MAIN CONTAINER -->
</div>
