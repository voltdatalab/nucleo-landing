---
layout: posts
title: 'Conteúdo especial'
desc: 'Reportagens, análises e investigações e fôlego publicadas no Núcleo Jornalismo'
tagline: 'ESPECIAIS'
icone: '<i class="fas fa-star"></i>'
link: posts
atualizacao: 05/04/2020
---

<div class="container" style="padding: 0 5% 0px;max-width:850px">
          <div class="row">
{% for post in site.posts offset:0 limit:20 %}
{% if post.tipo contains 'especial' %}
{% unless post.categories contains 'draft' %}
{% unless post.categories contains 'institucional' %}
          <div class="indexpost" style="border-bottom:1px solid #fff;margin:0 auto;background: url('../img/{{ site.baseurl }}{{ post.background }}') rgba(0, 0, 0, 0.4);">
                <a href="{{ post.url | prepend: site.baseurl | replace: '//', '/' }}">
                  <h3 class="page-ttt">{{ post.titulo_redes }}</h3></a>
                  <br />
                  <span class="arquivado" style="color:#fff">

                    <i class="far fa-calendar-alt"></i> {{ post.date | date: '%d/%m/%Y' }} &middot; Arquivado em <a href="{{ post.categories }}"><span class="spancateg">{% if post.cat %}{{ post.cat }} {% else %} {{ post.categories }}{% endif %}</span></a>

                  </span><br /><br />

                </div>
                {% endunless %}
                {% endunless %}
                {% endif %}
                {% endfor %}
              </div>
      </div>


<br /><br /><br />

<style>
  .row [class*='col-'] {
  background-clip: content-box;
  min-height: 120px;
  margin-bottom: 10px;
}

.tall {
  height: 160px;
}
.taller {
  height: 200px;
}

</style>

<script type="text/javascript">
  $('.row').masonry({
  itemSelector : '.col-xs-6'
});
</script>
