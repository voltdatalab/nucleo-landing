---
layout: monitor
title: 'Monitor Nuclear'
desc: 'Acompanhe e analise o debate político no Twitter'
tagline: APLICAÇÃO
background: 'monitornuclear.jpeg'
contexto: 'O <strong>Monitor Nuclear</strong> é uma aplicação que analisa tendências e engajamento de perfis dos políticos mais relevantes no Twitter'
iframe: '<iframe src="https://nucleojor.shinyapps.io/monitor_twitter/" width="100%" onload="loadIframe()" frameborder="no" scrolling="auto"></iframe>'
brand_top: '
<p><strong>APOIO:</strong> <a href="https://www.icfj.org/" style="border-bottom: 0px" target="_blank"><img src="https://sciencepulse.org/img/icfj.png" alt="logo ICFJ" width="200px" style="padding-right:8px"></a>
'
share_buttons: '
<ul class="share-buttons" style="text-align: center">
COMPARTILHE:
<li><a href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fnucleo.jor.br%2Fmonitor&quote=Monitor%20Nuclear%2C%20compare%20tend%C3%AAncias%20de%20engajamento%20dos%20principais%20pol%C3%ADticos" title="Share on Facebook" target="_blank"><i class="fab fa-facebook-square fa-lg" aria-hidden="true"></i><span class="sr-only"></span></a></li>
<li><a href="whatsapp://send?text=Núcleo, jornalismo, dados e transparência - https://nucleo.jor.br/monitor" target="_blank" title="Compartilhar no Facebook"><i class="fab fa-whatsapp-square fa-lg" aria-hidden="true"></i><span class="sr-only"></span></a></li>
<li><a href="https://twitter.com/intent/tweet?source=https%3A%2F%2Fnucleo.jor.br%2Fmonitor&text=Monitor%20Nuclear%2C%20compare%20tend%C3%AAncias%20de%20engajamento%20dos%20principais%20pol%C3%ADticos:%20https%3A%2F%2Fnucleo.jor.br%2Fmonitor&via=nucleojor" target="_blank" title="Tweet"><i class="fab fa-twitter-square fa-lg" aria-hidden="true"></i><span class="sr-only">Tweet</span></a></li>
<li><a href="http://www.reddit.com/submit?url=http%3A%2F%2Fnucleo.jor.br%2Fmonitor&title=Monitor%20do%20N%C3%BAcleo%20Jornalismo" target="_blank" title="Submit to Reddit"><i class="fab fa-reddit-square fa-lg" aria-hidden="true"></i><span class="sr-only"></span></a></li>
<li><a href="http://www.linkedin.com/shareArticle?mini=true&url=https%3A%2F%2Fnucleo.jor.br%2Fmonitor&title=Monitor%20Nuclear%2C%20compare%20tend%C3%AAncias%20de%20engajamento%20dos%20principais%20pol%C3%ADticos&summary=&source=https%3A%2F%2Fnucleo.jor.br%2Fmonitor" target="_blank" title="Share on LinkedIn"><i class="fab fa-linkedin fa-lg" aria-hidden="true"></i><span class="sr-only"></span></a></li>
</ul>
'
---

<small>Sinta-se livre para utilizar nossos dados e gráficos. Pedimos apenas que citem a referência `Monitor de Twitter, do Núcleo Jornalismo` ou `Monitor Nuclear`, se possível com link para `www.nucleo.jor.br/monitor`.</small>

### SOBRE O PROJETO

O Monitor Nuclear é uma aplicação do **Núcleo** que identifica tendências de engajamento no Twitter, considerando tweets publicados pelos principais políticos brasileiros e possíveis pré-candidatos à eleição presidencial de 2022.

Esses dados são relevantes porque podem indicar tanto o humor do momento quanto a mobilização de bases de apoio ou de oposição em relação a certo ator político ou assunto.

Com pouco mais de 16 milhões de usuários [^1], o Twitter não representa o eleitorado brasileiro [^2], mas, nos últimos anos, a rede social passou a funcionar como um termômetro do debate político no Brasil [^3] e em muitos outros países.

A rede social é recorrentemente um meio utilizado por autoridades para se comunicar diretamente com suas bases, o que a tornou uma ferramenta de tomada de decisões, além de pautar a imprensa e boa parte do debate.

Para entender mais a importância do Twitter na política e na diplomacia, acesse o estudo Twiplomacy[^4]. Segundo a pesquisa, governos e líderes de 189 países possuíam uma presença oficial na rede social -- quase todos os membros das Nações Unidas.


### METODOLOGIA

A fim de garantir total transparência para nossos métodos e abordagens, descrevemos abaixo passo a passo de como chegamos aos resultados do gráfico.

A base do código é [aberta](https://github.com/voltdatalab/science-pulse-public) e tem como referência a ferramenta [Science Pulse](https://sciencepulse.org/), projeto de monitoramento de ciência do [Volt Data Lab](www.voltdata.info), a empresa por trás do **Núcleo**.

#### Escolha dos nomes

Os perfis dos políticos foram baseados em diversas fontes:

- [Lista de senadores](https://twitter.com/i/lists/1049263545530142720), via conta oficial do Senado Federal

- [Lista de deputados](https://twitter.com/i/lists/1126190774805258241), via conta oficial da Câmara dos Deputados

- [Lista de governadores](https://twitter.com/i/lists/1376874024949649411), via Sérgio Spagnuolo (editor do *Núcleo*)

- [Lista de ministros](https://twitter.com/i/lists/1376880814860931082), via Sérgio Spagnuolo (editor do *Núcleo*)

- [Lista com presidente e vice-presidente](https://twitter.com/i/lists/1376883897607335936) via Sérgio Spagnuolo (editor do *Núcleo*)

- [Lista de atores políticos](https://twitter.com/i/lists/1376884601122082821), que contém personagens relevantes na cena política, políticos eleitos que não constam nas outras listas e políticos ou autoridades sem cargos eletivos, com curadoria de Sérgio Spagnuolo (editor do *Núcleo*)

A lista pode ser aumentada, e, inclusive, reduzida, a depender de fatores políticos e eleitorais.

Qualquer pessoa pode sugerir um nome para integrar a lista de _atores políticos_, através [deste formulário](https://docs.google.com/forms/d/e/1FAIpQLSc_Spz0v-_kUqfm1GG_XSY4OCRxGw0IP233UeFdXaOgZK3hvg/viewform), explicando por que.

#### Dados

Os dados são baseados em tweets originais (retweets são desconsiderados) publicados pelos próprios atores em seus perfis oficiais e verificados pelo Twitter.

Os dados analisados são obtidos diretamente da API do Twitter[^5], e atualizados a cada 20 minutos. O código para extração pode ser encontrado [neste gist](https://gist.github.com/sergiospagnuolo/16f59265c79f26a95959cd3c9b279f99). A política de API do Twitter não permite a reprodução integral dos dados.

A API gratuita do Twitter só permite retornar os últimos 3.200 tweets de cada perfil.

#### Base da análise

A análise é baseada em três variáveis: data de publicação, total de curtidas por tweet e total de retweets por tweet.

Os dados não consideram comentários, por dois motivos:

**1.** curtidas e retweets estão limitados a apenas um por perfil, funcionando quase como uma métrica de endosso ao conteúdo. Isso torna mais difícil para _bots_ e perfis falsos inflarem artificialmente tweets originais, ao contrário do que acontece com uma hashtag, por exemplo, à medida que um perfil pode curtir múltiplos tweets com um termo.

**2.** comentários são ilimitados, o que pode inflar indevidamente o número de interações. Além disso, eles frequentemente não refletem uma interação provável de endosso, podendo ser críticos, ofensivos, spam, piadas, memes ou _tags_ para pessoas acompanharem o assunto.

Vale notar que a metodologia do **Monitor** é válida para se visualizar engajamento em perfis específicos, mas não acerca de dados conversacionais. Com uma hashtag ou campanha online, por exemplo, o caso é diferente, à medida que há vários tweets com hashtags ou termos que um bot ou um humano possam interagir em massa.

#### Fórmulas

O **Monitor** agrega, por dia, o número de tweets disparados entre 00h e 23h59 e soma o total de curtidas e retweets. Essa soma é considerada como o `total de interações`.  

Isso nos permite calcular duas métricas fundamentais para nossa análise: a `taxa de engajamento` e `tendência de engajamento`.  

1. `Taxa de engajamento`: é a média simples do total de interações pelo número de tweets disparados em um único dia. Assim, se um perfil tuitou 10 vezes e teve 100 interações, a taxa de engajamento é de 10 interações por tweet. Se outro perfil tuitou uma vez e teve 100 interações, essa taxa é de 100 por tweet.

2. `Tendência de engajamento`: é a média móvel exponencial de X dias da taxa de engajamento. Consideramos 15 dias como o _default_, indicando um ciclo noticioso rápido, mas constante.  

3. `Tweets em alta`: lista tweets de autoria de perfis monitorados pelo Science Pulse que tenham o maior número de retweets de toda a população de usuários (contagem de RTs), no momento da última coleta de dados. Usuários podem escolher duas opções para visualização: Descoberta mostra tweets de usuários que estejam abaixo da mediana do número de seguidores dentre os perfis listados no Science Pulse, e Popularidade mostra tweets de todos os perfis da base de dados.

Em todos os casos, a linha de tendência utiliza [regressão local (LOESS)](http://www.leg.ufpr.br/lib/exe/fetch.php/projetos:saudavel:loess.pdf), um método estatístico que estima curvas e superfícies através de suavização, melhor para identificar tendências de curto prazo.

#### Fundamentos técnicos

O **Monitor** é construído com a linguagem de programação R, utilizando o pacote `Shiny`. O ETL (processo de captura e organização de dados) é feito a partir de uma instância no Rstudio, e o banco de dados que armazena as informações é `PostgresSQL`.

#### Créditos

- [Sérgio Spagnuolo]({{ site.baseurl }}/equipe/sergiospagnuolo) - idealizador e desenvolvedor

- [Lucas Gelape]({{ site.baseurl }}/equipe/lgelape) - desenvolvedor de aplicação

- [Felippe Mercurio]({{ site.baseurl }}/equipe/ztock) - desenvolvedor de banco de dados

- [Renata Hirota]({{ site.baseurl }}/equipe/renata_mh) - consultoria

- [Alexandre Orrico]({{ site.baseurl }}/equipe/alexorrico) e [Jade Drummond]({{ site.baseurl }}/equipe/jade_dru) - estratégia digital e comunidades

- [Rodolfo Almeida]({{ site.baseurl }}/equipe/rodolfoalmd) - Arte

#### Referências

[^1]: [Statista](https://www.statista.com/statistics/242606/number-of-active-twitter-users-in-selected-countries/), ref. fevereiro de 2021

[^2]: [TSE](http://www.tse.jus.br/eleicoes/estatisticas/estatisticas-eleitorais) - Estatísticas de Eleitorado

[^3]: Uma definição interessante vem do jornalista José Roberto de Toledo, no podcast Foro de Teresina: _"O Twitter não é um espelho da sociedade, ele é um espelho do debate político e ali o que a gente está medindo é o engajamento, a força dos atores, de quanto eles conseguem mobilizar suas bases."_ - [Episódio #95, Foro de Teresina aos 28m28s](https://piaui.folha.uol.com.br/foro-de-teresina-95-os-mitos-da-pandemia-queda-de-braco-com-mandetta-e-o-bate-cabeca-na-economia/)

[^4]: [Twiplomacy Study 2020](https://twiplomacy.com/blog/twiplomacy-study-2020/)

[^5]: [API DO TWITTER](https://developer.twitter.com/en/docs)
