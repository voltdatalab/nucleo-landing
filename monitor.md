---
layout: monitor
title: 'Monitor Nuclear'
desc: 'Análises e tendências de engajamento político no Twitter'
tagline: APLICAÇÃO
background: 'monitor_destaque1.jpeg'
subtitle: ''
---
<br>

<ul class="share-buttons" style="text-align: center">
COMPARTILHE:
<li><a href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fnucleo.jor.br%2Fmonitor&quote=Monitor%20Nuclear%2C%20compare%20tend%C3%AAncias%20de%20engajamento%20dos%20principais%20pol%C3%ADticos" title="Share on Facebook" target="_blank"><i class="fab fa-facebook-square fa-lg" aria-hidden="true"></i><span class="sr-only"></span></a></li>
<li><a href="whatsapp://send?text=Núcleo, jornalismo, dados e transparência - https://nucleo.jor.br/monitor" target="_blank" title="Compartilhar no Facebook"><i class="fab fa-whatsapp-square fa-lg" aria-hidden="true"></i><span class="sr-only"></span></a></li>
<li><a href="https://twitter.com/intent/tweet?source=https%3A%2F%2Fnucleo.jor.br%2Fmonitor&text=Monitor%20Nuclear%2C%20compare%20tend%C3%AAncias%20de%20engajamento%20dos%20principais%20pol%C3%ADticos:%20https%3A%2F%2Fnucleo.jor.br%2Fmonitor&via=nucleojor" target="_blank" title="Tweet"><i class="fab fa-twitter-square fa-lg" aria-hidden="true"></i><span class="sr-only">Tweet</span></a></li>
<li><a href="http://www.reddit.com/submit?url=http%3A%2F%2Fnucleo.jor.br%2Fmonitor&title=Monitor%20do%20N%C3%BAcleo%20Jornalismo" target="_blank" title="Submit to Reddit"><i class="fab fa-reddit-square fa-lg" aria-hidden="true"></i><span class="sr-only"></span></a></li>
<li><a href="http://www.linkedin.com/shareArticle?mini=true&url=https%3A%2F%2Fnucleo.jor.br%2Fmonitor&title=Monitor%20Nuclear%2C%20compare%20tend%C3%AAncias%20de%20engajamento%20dos%20principais%20pol%C3%ADticos&summary=&source=https%3A%2F%2Fnucleo.jor.br%2Fmonitor" target="_blank" title="Share on LinkedIn"><i class="fab fa-linkedin fa-lg" aria-hidden="true"></i><span class="sr-only"></span></a></li>
</ul>

<small>Sinta-se livre para utilizar nossos dados e gráficos. Pedimos apenas que citem a referência `Monitor de Twitter, do Núcleo Jornalismo` ou `Monitor Nuclear`, se possível com link para `www.nucleo.jor.br/monitor`.</small>

### SOBRE O PROJETO

O **Monitor Nuclear** é uma aplicação do **Núcleo Jornalismo** que identifica tendências de engajamento político no Twitter nos tweets publicados por possíveis pré-candidatos à eleição presidencial de 2022.

Esses dados são relevantes porque podem indicar tanto o humor do momento quanto a mobilização de bases de apoio ou de oposição em relação a certo ator político ou assunto.

Com apenas 14,35 milhões de usuários [^1], o Twitter está longe de representar o eleitorado brasileiro [^2], mas, nos últimos anos, a rede social passou a funcionar como um termômetro do debate político no Brasil [^3].

A rede social é recorrentemente um meio utilizado por autoridades para se comunicar diretamente com suas bases, o que a tornou uma ferramenta de tomada de decisões, além de pautar a imprensa e boa parte do debate do momento.


### METODOLOGIA

A fim de garantir total transparência para nossos métodos e abordagens, descrevemos abaixo passo a passo de como chegamos aos resultados do gráfico.

Ainda estamos trabalhando em melhorias e novos recursos, e por isso o código ainda não está disponível, mas esperamos abri-lo no futuro.  

#### Escolha dos nomes

Os nomes foram escolhidos tanto pela sua relevância no noticiário político nacional recente quanto pela percepção de que são possíveis pré-candidatos às eleições presidenciais de 2022. A lista pode ser aumentada, e, inclusive, reduzida, a depender de fatores políticos e eleitorais.

Uma medida utilizada para a lista final veio a partir da análise 50 perfis de políticos. Essa análise mostrou que a taxa de engajamento mediana era de 1.133 interações por tweet em 2020. Todos os perfis que não checaram a esse patamar foram excluídos da lista.

No entanto, a ideia é identificar e analisar os políticos mais relevantes. Qualquer pessoa pode sugerir um nome para integrar o **Monitor Nuclear**, através [deste formulário](https://docs.google.com/forms/d/e/1FAIpQLSc_Spz0v-_kUqfm1GG_XSY4OCRxGw0IP233UeFdXaOgZK3hvg/viewform), explicando por que.

Muitos das arrobas selecionadas foram obtidas pela lista [^5] compilada pelo projeto [7c0]().


#### Dados

Os dados são baseados em tweets originais (retweets são desconsiderados) publicados pelos próprios atores em seus perfis oficiais e verificados pelo Twitter.

Os tweets analisados são obtidos diretamente do Twitter[^4], utilizando a API do Workbench, atualizada a cada seis horas. Os dados são abertos e podem ser consultados e baixados [neste link](https://app.workbenchdata.com/workflows/70006/).

O **Monitor** é construido com a linguagem R.

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

2. `Tendência de engajamento`: é a média móvel exponencial de X dias da taxa de engajamento. Consideramos 4 dias como o _default_, indicando um ciclo noticioso rápido, mas constante.  

Em todos os casos, a linha de tendência utiliza [regressão local (LOESS)](http://www.leg.ufpr.br/lib/exe/fetch.php/projetos:saudavel:loess.pdf), um método estatístico que estima curvas e superfícies através de suavização, melhor para identificar tendências de curso prazo.

#### Créditos

O **Monitor Nuclear** foi desenvolvido por [Sérgio Spagnuolo](https://twitter.com/sergiospagnuolo).

A estratégia digital é de [Alexandre Orrico](https://twitter.com/alexorrico).

A arte de destaque e o conceito visual dos gráficos são de [Rodolfo Almeida](https://twitter.com/rodolfoalmd).

As opiniões de [Lucas Gelape](https://twitter.com/lgelape), [Renata Hirota](https://twitter.com/renata_mh), [Luiza Bodenmuller](https://twitter.com/lubodenmuller) e [Vitor Conceição](https://twitter.com/vitor) foram importantes para a melhoria do projeto.

#### Referências

[^1]: [Statista](https://www.statista.com/statistics/242606/number-of-active-twitter-users-in-selected-countries/), ref. abril de 2020

[^2]: [TSE](http://www.tse.jus.br/eleicoes/estatisticas/estatisticas-eleitorais) - Estatísticas de Eleitorado

[^3]: Uma definição interessante vem do jornalista José Roberto de Toledo, no podcast Foro de Teresina: _"O Twitter não é um espelho da sociedade, ele é um espelho do debate político e ali o que a gente está medindo é o engajamento, a força dos atores, de quanto eles conseguem mobilizar suas bases."_ - [Episódio #95, Foro de Teresina aos 28m28s](https://piaui.folha.uol.com.br/foro-de-teresina-95-os-mitos-da-pandemia-queda-de-braco-com-mandetta-e-o-bate-cabeca-na-economia/)

[^4]: [API DO TWITTER](https://developer.twitter.com/en/docs)

[^5]: [Arquivo .csv](https://github.com/projeto7c0/redes-sociais-politicos/blob/master/redes-sociais-politicos-full.csv) com redes sociais de políticos
