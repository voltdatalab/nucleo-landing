---
layout: monitor
title: 'SciencePulse'
desc: 'Explore em um só lugar tendências e conversas sobre ciência nas redes sociais por +1.500 cientistas, especialistas e organizações de renome.'
tagline: APLICAÇÃO
background: 'pulse-destak.png'
contexto: 'Explore em um só lugar tendências e conversas sobre ciência nas redes sociais por +1.500 cientistas, especialistas e organizações de renome.'
iframe: '<iframe src="https://nucleojor.shinyapps.io/science/" width="100%" onload="loadIframe()" frameborder="no" scrolling="auto"></iframe>'
color: "#f33872"
incluir_apoio: sim
share_buttons: '
<ul class="share-buttons" style="text-align: center">
COMPARTILHE:
<li><a href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fnucleo.jor.br%2Fsciencepulse&quote=Explore%20tend%C3%AAncias%2C%20conversas%20e%20assuntos%20relevantes%20no%20debate%20cient%C3%ADfico%20que%20circulam%20nas%20redes%20sociais" target="_blank" title="Share on Facebook"><i class="fab fa-facebook-square fa-lg" aria-hidden="true"></i><span class="sr-only">Share on Facebook</span></a></li>
  <li><a href="https://twitter.com/intent/tweet?source=https%3A%2F%2Fnucleo.jor.br%2Fsciencepulse&text=Explore%20tend%C3%AAncias%2C%20conversas%20e%20assuntos%20relevantes%20no%20debate%20cient%C3%ADfico%20que%20circulam%20nas%20redes%20sociais:%20https%3A%2F%2Fnucleo.jor.br%2Fsciencepulse&via=thesciencepulse" target="_blank" title="Tweet"><i class="fab fa-twitter-square fa-lg" aria-hidden="true"></i><span class="sr-only">Tweet</span></a></li>
  <li><a href="http://www.reddit.com/submit?url=https%3A%2F%2Fnucleo.jor.br%2Fsciencepulse&title=Explore%20tend%C3%AAncias%2C%20conversas%20e%20assuntos%20relevantes%20no%20debate%20cient%C3%ADfico%20que%20circulam%20nas%20redes%20sociais" target="_blank" title="Submit to Reddit"><i class="fab fa-reddit-square fa-lg" aria-hidden="true"></i><span class="sr-only">Submit to Reddit</span></a></li>
  <li><a href="http://www.linkedin.com/shareArticle?mini=true&url=https%3A%2F%2Fnucleo.jor.br%2Fsciencepulse&title=Explore%20tend%C3%AAncias%2C%20conversas%20e%20assuntos%20relevantes%20no%20debate%20cient%C3%ADfico%20que%20circulam%20nas%20redes%20sociais&summary=&source=https%3A%2F%2Fnucleo.jor.br%2Fsciencepulse" target="_blank" title="Share on LinkedIn"><i class="fab fa-linkedin fa-lg" aria-hidden="true"></i><span class="sr-only">Share on LinkedIn</span></a></li>
  <li><a href="mailto:?subject=Explore%20tend%C3%AAncias%2C%20conversas%20e%20assuntos%20relevantes%20no%20debate%20cient%C3%ADfico%20que%20circulam%20nas%20redes%20sociais&body=:%20https%3A%2F%2Fnucleo.jor.br%2Fsciencepulse" target="_blank" title="Send email"><i class="fas fa-envelope-square fa-lg" aria-hidden="true"></i><span class="sr-only">Send email</span></a></li>
</ul>
'
---

<small>Sinta-se livre para utilizar nossos dados e gráficos. Pedimos apenas que citem a referência `Science Pulse`, se possível com link para `www.nucleo.jor.br/sciencepulse`.</small>

_Você pode acessar nosso código aberto desta aplicação [neste link](https://github.com/voltdatalab/science-pulse-public)._

_For the translated version of the methodology [click here](https://sciencepulse.org/eng/methodology)._

## SOBRE OS DADOS

### COLETA DE PERFIS E PÁGINAS

Todos os perfis e páginas de cientistas, especialistas, médicos, universidades, organizações e iniciativas científicas foram compilados pela equipe de desenvolvimento do Science Pulse por uma variedade de métodos. Encontramos esses perfis e páginas, principalmente, de três formas:

1. Um crowdsourcing, pelo qual convidamos as pessoas a sugerir perfis;

2. Ao identificar usuários com perfis verificados pelo Twitter ou Facebook e, a partir deles, encontrar novos perfis/páginas a partir de quem seguem;

3. Consultando listas de Twitter e Facebook feitas por universidades, jornalistas ou outras iniciativas.

Qualquer pessoa pode sugerir um novo perfil para ser incluído em nossa plataforma através [deste formulário](https://forms.gle/KHufKHzJxJVdsD7s8).

Caso seja um cientista ou especialista com o perfil mapeado por esta ferramenta, você pode solicitar sua exclusão do banco de dados do Science Pulse. Envie um email para [sciencemonitor@icfj.org](mailto:sciencemonitor@icfj.org).


### COLETA DE DADOS

Atualmente, coletamos dados de tweets e posts no Facebook.

No Twitter, nosso banco de dados é atualizado regularmente com novos tweets e contagens, respeitando os limites da API gratuita. Nossa coleta é atualizada a cada 20 minutos, mas disponibilizamos somente postagens dos últimos 30 dias.

No Facebook, restringimos a coleta de dados aos posts com performance superior ao esperado (*overperforming*) realizados pelas páginas monitoradas nas últimas 24 horas. Além disso, seguindo as regras de uso da API do Crowd Tangle, não disponibilizamos a íntegra dos bancos de dados de posts coletados.

## SOBRE O ALGORITMO

## DADOS DE TWITTER

### TENDÊNCIAS

Todas as nossas tendências consideram apenas tweets publicados ou recompartilhados nas últimas 12 horas pelos perfis que seguimos.

Nossa aba principal de tendências é separada em três grupos para cada idioma:

1. **Popular no Pulse**: lista tweets de autoria de perfis monitorados pelo Science Pulse que tenham o maior número de retweets de toda a população de usuários (contagem de RTs), no momento da última coleta de dados. Usuários podem escolher duas opções para visualização: *Descoberta* mostra tweets de usuários que estejam abaixo da mediana do número de seguidores dentre os perfis listados no Science Pulse, e *Popularidade* mostra tweets de todos os perfis da base de dados.

2. **Popularidade em alta**: ranqueia os cinco tweets com maior proporção de RTs por seguidores (RT:followers) publicados por membros da lista do Science Pulse (apenas se tiverem mais de 10 retweets). Essa lista mostra posts que tiveram engajamento significativo (com base em RTs), levando em conta o alcance (número de seguidores) do perfil que a escreveu. Se um tweet tiver 200 RTs e seu autor tiver 400 seguidores, o tweet possui uma razão de 0,5 RT:seguidores.

3. **Descubra mais**: mostra uma lista de 5 tweets aleatórios que tiveram mais que um RT (por usuários de toda a rede social) e são de autoria de perfis listados no Science Pulse. Ao clicar no ícone "Mostrar novos tweets" o usuário sorteia uma nova lista com 5 tweets aleatórios.

### DESCUBRA MAIS

Essa aba serve para maior exploração do banco de dados de tweets do Science Pulse. Ela contém quatro conjuntos de informações sobre tweets publicados nas últimas 12 horas, também filtrados por idioma:

1. **Usuários ativos**: os usuários que mais tuitaram no período;

2. **Hashtags**: as hashtags mais compartilhadas no mesmo período;

3. **Também populares no pulse**: utilizamos um algoritmo de agrupamento (*k-means clustering*) para classificar esses tweets em quatro grupos, de acordo com sua contagem de retweets com base na última coleta de dados (de 1 a 4, sendo 4 o grupo com mais retweets). Então, consideramos apenas tweets do "grupo 2", eliminando aquelas que provavelmente são mensagens pessoais e, assim, possuem menos retweets (grupo 1) e aquelas que atingiram o topo dos nossos *trending topics* (da aba Trends) ou com grande volume orgânico (grupos 3 ou 4). Dentro do grupo 2 é utilizada a mesma métrica da coluna "Popular no Pulse" da aba Tendências.  

4. **Radar Pulse**: este conjunto de dados representa uma amostra aleatória de cinco tweets do grupo 2 (descrito acima). Os tweets apresentados nesta coluna podem coincidir com aqueles do conjunto anterior, mas ela proporciona ao usuário maiores chances de encontrar conteúdo científico interessante e que não alcançou os trends.

5. **Popular entre cientistas**: mostra as publicações mais retuitadas pelos perfis monitorados pelo Science Pulse. Toda vez que um perfil que monitoramos compartilha um tweet, ele conta como um (n = 1). As publicações melhor ranqueadas possuem o maior número de retweets dentro dessa amostragem, assim identificando os tweets que conseguiram mais atenção entre os perfis monitorados pelo Science Pulse. Por exemplo: se 15 perfis em nosso banco de dados compartilharam este  [tweet da OMS](https://twitter.com/WHO/status/1275349898209173505), ele possui um taxa de compartilhamento de 15.


### ESPECIAL COVID-19

O **ESPECIAL COVID-19** apresenta tweets em destaque nas últimas 12 horas em posts filtrados por palavras-chave relacionadas à pandemia. As métricas utilizadas são as mesmas para usuários ativos e hashtags da aba Descubra Mais - com a exclusão de hashtags mais recorrentes, como [#COVID-19](https://twitter.com/hashtag/covid19) - e das colunas da aba Tendências.  

Essas são as palavras-chave aplicadas como filtro: "Covid", "covid", "Coronavirus", "coronavirus",
                    "Corona", "corona", "SARS-CoV-2", "Sars-CoV-2",
                    "SRAG", "sindrome", "syndrome", "pandemic",
                    "pandemia", "WHO", "OMS", "quarantine", "social distancing",
                    "quarentena", "isolamento social", "distanciamento social",
                    "mascara", "mask", "distanciamiento social", "spread", "asymptomatic",
                    "epidemic", "outbreak", "epidemia", "vacina", "vaccine", "wuhan", "Wuhan",
                    "herd immunity", "imunidade de rebanho", "imunidade coletiva".

### PERFIS ACOMPANHADOS

Na aba Perfis Acompanhados, listamos todos os perfis que compõe a curadoria do Science Pulse, entre cientistas, instituições, pesquisadores e especialistas. Para ajudar usuários a descobrir novas fontes de informação científica, a tabela *Encontre novos especialistas* retorna uma amostra aleatória de cinco perfis que possuam o número de seguidores menor do que a mediana dessa medida dentre todos os perfis em nosso banco de dados.

### ABA BUSCA POR TWEETS

Na aba Busca por Tweets, usuários podem pesquisar tweets dos últimos 90 dias de acordo com diferentes filtros, como algumas palavras-chave, intervalo de datas, perfis verificados, retweets ou replies.

## DADOS DE FACEBOOK

### POSTS POPULARES

Essa seção é composta por posts de Facebook com performance superior ao esperado (*overperforming*) feitas nas últimas 24 horas. Ela apresenta duas colunas com posts em destaque nas páginas seguidas pelo Science Pulse, a partir de dados do [Crowd Tangle](https://www.crowdtangle.com/), além de uma coluna com a possibilidade do usuário explorar outros posts nas páginas monitoradas pela nossa ferramenta.

Os três grupos de postagem são:

1. **Desempenho em alta**: posts com os maiores escores na medida de desempenho em alta (*overperforming*), desenvolvida pelo Crowd Tangle. Essa métrica mostra publicações que estão se saindo melhor em engajamento em relação ao que seria esperado pelas características da página em que ela foi publicada.  

2. **Populares**: postagens com o maior número de compartilhamentos na lista de páginas selecionadas pelo Science Pulse. Essa métrica serve para identificar o que tem sido compartilhado em massa.

3. **Descubra mais**: amostra aleatória de 5 posts das páginas monitoradas pelo Science Pulse. Ao clicar no ícone "Mostrar novos posts" o usuário sorteia uma nova lista com 5 posts.

### ABA PÁGINAS ACOMPANHADAS

Nesta aba, listamos todas as páginas públicas do Facebook que no momento são monitoradas pelo Science Pulse. Esta lista é formada por páginas de universidades, organizações científicas e iniciativas de divulgação de pesquisas brasileiras e internacionais. A coluna *Encontre novas páginas* mostra uma amostra aleatória de cinco páginas que possuam um número de seguidores menor do que a mediana de todas as páginas em nosso banco de dados.
