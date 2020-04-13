---
layout: posts
title: 'Todas as nossas matérias'
desc: 'Veja o índice de tudo o que já publicamos'
subtitle: ''
link: posts
atualizacao: 05/04/2020
---



<!-- índice simples de matérias  -->
<div class="container" style="padding: 0 5% 0px;max-width:850px">
          <div class="row">

{% for post in site.posts limit : 200 %}
        <div class="col-sm-6 col-lg-6">
                <a href="{{ post.url | prepend: site.baseurl | replace: '//', '/' }}">
                  <h3 class="page-tttt">{{ post.titulo_redes }}</h3></a>
                  <br />
                  <span class="arquivado" style="color:#000;font-weight:300">

                    <i class="far fa-calendar-alt"></i> {{ post.date | date: '%d/%m/%Y' }} &middot; Arquivado em <a href="{{ post.categories }}"><span style="color:#fff;background-color:#4b31dd">{% if post.cat %}{{ post.cat }} {% else %} {{ post.categories }}{% endif %}</span></a>

                  </span>
                  <br /><br />
          </div>

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