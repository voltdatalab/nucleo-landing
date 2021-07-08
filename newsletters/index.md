---
layout: pages
title: 'Newsletters'
desc: 'Conheça as newsletters do Núcleo Jornalismo'
subtitle: ''
link: ''
icone: '<i class="far fa-envelope fa-lg"></i>'
---

<style>
#newsletter_page{
  margin: 0 auto;
}
#newsletter_page label{
  font-size: 1em;
}

img{
  max-width:100%;
}

h5{
  font-family: "Roboto Mono", monospace;
  color: #4b31dd;
  text-transform: uppercase;
  margin-bottom: 20px
}
</style>

O **Núcleo** quer chegar a seus leitores e leitoras onde quer que eles estejam, seja pelo nosso canal no [Telegram](https://t.me/nucleojor), seja pelas redes sociais ou por outras mídias.

Email é uma das formas mais simples e acessíveis, e queremos levar apenas o essencial (novidades que publicamos ou anúncios), sem _spam_, sem forçar a barra com um monte de emails.

<hr>

{% for newsletter in site.data.newsletters %}

[![{{ newsletter.nome }}]({{ site.baseurl }}/img/{{ newsletter.img-header }})]({{ site.baseurl }}/newsletters/{{ newsletter.link }})

##### **Tags**: {% if newsletter.tags %}{{ newsletter.tags }} {% endif %}

{{ newsletter.desc }}

<div id="newsletter_page">
<form action="https://sendy.voltdata.info/subscribe" method="POST" accept-charset="utf-8">
  <div class="revue-form-group">
  <input style="max-width:100%" class="revue-form-field" type="email" name="email" id="email" placeholder="EMAIL"/>
<br/>
<input style="max-width:100%" class="revue-form-field" type="text" name="name" id="name" placeholder="NOME" style="max-width:100%"/>
</div>
<div class="revue-form-actions">
  <input type="hidden" name="list" value="{{ newsletter.idn }}"/>
  <input type="hidden" name="subform" value="yes"/>
  <input style="max-width:100%" type="submit" name="submit" id="submit" value="RECEBER"/>
  </div>

</form>
</div>

<hr>

{% endfor %}

<small>O uso de seus dados é regido pelo nossa [política de privacidade]({{ site.baseurl }}/privacidade).</small>

<small>Veja abaixo os principais pontos cobertos por essa política:</small>

* <small>Caso você escolha receber nossa newsletter, seu email será usado somente para comunicação enviada pelo Science Pulse ou pelo Volt Data Lab;</small>

* <small>Nós não venderemos seu endereço de email para ninguém, mas reservamos o direito de compartilhá-lo com certos parceiros de nossa confiança;</small>

* <small>Não enviaremos, de forma nenhuma, spam ou conteúdo nocivo para você;</small>

* <small>Por questões estratégicas, podemos integrar seu email a outras newsletters do Volt Data Lab. Você será avisado disso;</small>

* <small>Fazemos um compromisso de tratar sua informação com zelo.</small>
