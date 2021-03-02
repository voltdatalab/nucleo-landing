---
published: TRUE
layout: conteudo
tipo: investigação
title: "Genealogia de uma hashtag: como ações coordenadas da direita nascem no Twitter"
titulo_redes: "Como ações coordenadas da direita nascem no Twitter"
subtitle: "O <strong>Núcleo</strong> analisou 3,6 milhões publicações no Twitter, a partir de buscas por 18 hashtags e três termos diferentes, e identificou indícios de coordenação em campanhas da direita política na rede social."
subtitle_redes: "Análise de 3,6 milhões de publicações identificou indícios de coordenação em campanhas na rede social."
excerpt: "Em novembro de 2019, um curioso e raro evento nas redes sociais envolveu o ministro do STF Gilmar Mendes: ele foi alvo de uma campanha no Twitter tão coordenada que conseguiu ficar no topo dos trending topics uma semana inteira. O esforço online pedia pelo impeachment do magistrado e foi amplamente difundido entre aqueles que declaradamente se identificam com a direita política. "
date: 08/01/2020
analise: Lucas Lago
edicao: Sérgio Spagnuolo
graficos: Rodolfo Almeida
credito_img: Rodolfo Almeida
dados_abertos: Acesse o código e os dados
dados_abertos_link: https://www.kaggle.com/lucaslago/hashed-tweets/
background: 'twitter-files/twitter_destaque.jpeg'
destaque: 'twitter-files/twitter_destaque.jpeg'
atualizacao: "Texto atualizado em 9.jan.2020 às 19h41 para incluir link para explicação sobre trending topics"
categories:
  - "redes"
tags:
- "Twitter, "
- "redes sociais, "
- "Gilmar Mendes"
---

Em novembro de 2019, um curioso e raro evento nas redes sociais envolveu o ministro do STF [Gilmar Mendes](http://bit.ly/2SYZg18): ele foi alvo de uma campanha no Twitter tão coordenada que conseguiu ficar no topo dos trending topics uma semana inteira. O esforço online pedia pelo impeachment do magistrado e foi amplamente difundido entre aqueles que declaradamente se identificam com a direita política. 

A grande sacada desse movimento teve duas facetas: a primeira foi a alternância de hashtags à medida que as anteriores perdiam força, fazendo o assunto permanecer sempre “popular”. A segunda foi contar com uma rede muito ativa de usuários nas redes sociais, que concentrava bastante o uso das hashtags por relativamente poucos perfis, amplificando significativamente seu alcance.

O **Núcleo** analisou 3,6 milhões de tweets e retweets no Twitter, a partir de buscas por 18 hashtags e três termos diferentes, e calculou o quão concentrada foi a distribuição dos resultados encontrados -- ou seja, quando poucos perfis foram responsáveis por muitos tweets e compartilhamentos.

Essa concentração pode ser vista principalmente em campanhas promovidas pela direita. Na esquerda foi apurada uma maior distribuição entre perfis participantes, o que em parte explica o menor engajamento e, consequentemente, as limitadas repercussões de campanhas desse campo político no Twitter.

**Em poucas palavras**: a direita faz mais barulho concentrando a repercussão em poucos perfis engajados. A esquerda é mais espontânea, mas não gera tanta repercussão.

---

###### É importante porque...

- *O Twitter tornou-se um espaço importante de debate político e de reivindicações*

- *A concentração de tweets em poucos perfis pode não ser representativa do sentimento geral dos usuários da rede social*

- *Espontaneidade geralmente é preferida, embora popularidade gere mais repercussão em outros círculos*

---

Note que por essa análise não é possível determinar a operação de robôs, apenas a concentração de muitas publicações por poucos usuários da rede social. *Bots* são recursos que, por exemplo, republicam ou comentam alguma publicação mediante o uso de uma palavra-chave, automaticamente.

Uma ação coordenada acontece quando membros de uma campanha estimulam suas bases para que elas sejam mais ativas, não contando com a espontaneidade muitas vezes esperada de um engajamento político. Isso garante que essas bases façam mais publicações utilizando, por exemplo, uma hashtag -- o que resulta em concentração em poucos usuários (daí a desigualdade).

##### É muito importante ressaltar que **ações coordenadas não necessariamente representam utilização de robôs**.

Uma amostra dessa concentração de tweets foi primeiramente [publicada](https://vortex.media/dados/19632/campanha-no-twitter-por-impeachment-de-gilmar-mendes-tem-marcas-de-acao-coordenada/) no site *Vortex Media*. (*Disclaimer: os autores dessa análise trabalharam na equipe do Vortex*). 

Na reportagem do *Vortex*, com mais de 1 milhão de tweets, foi apurado que somente 1.770 perfis no Twitter tuitaram ou retuitaram mais de 100 vezes, em menos de três dias, as hashtags #ImpeachmentGilmarMendes ou #GilmarMendesImpeachment.

Esses perfis correspondem a apenas 2% dos usuários -- dentre os cerca de 90 mil -- que utilizaram as hashtags em um período de três dias. Apesar disso, foram diretamente responsáveis por 35% de todos os resultados de buscas dessa campanha no Twitter.

Para calcular a concentração de tweets e retweets, o **Núcleo** valeu-se do Coeficiente de Gini, uma fórmula para medir a desigualdade em uma amostra qualquer, utilizada principalmente para avaliar a desigualdade da distribuição de renda entre países. A ideia desse cruzamento foi sugerida à equipe pelo cientista de dados [João Carabetta](https://twitter.com/joaocarabetta), que trabalha no [Banco Inter-Americano de Desenvolvimento](https://www.iadb.org/pt). 

#### [-- Leia o posicionamento do Twitter](#pos-twitter)

As hashtags em questão giravam em torno de duas figuras, o próprio Gilmar e o presidente do Senado, [David Alcolumbre](https://www25.senado.leg.br/web/senadores/senador/-/perfil/3830) (DEM-AP). O primeiro por ser o alvo das críticas dos que se manifestavam, o segundo por ser a pessoa com poder para iniciar um dos processos de impeachment que existem contra o ministro do Supremo.

As hashtags analisadas relacionadas à movimentação contra Gilmar Mendes foram as seguintes:

![gráfico 1 - Gilmar Mendes](https://github.com/voltdatalab/nucleo-landing/blob/gh-pages/img/twitter-files/gini-tweets_data.png?raw=true)

##### O motivo pelo qual essa campanha foi escolhida como ponto de partida é claro: ela permaneceu uma semana inteira no topo dos *trending topics*, um evento incomum para hashtags políticas.

#### [-- Saiba mais como funcionam os trending topics](https://help.twitter.com/pt/using-twitter/twitter-trending-faqs)

Analisando a atividade dessas hashtags, percebemos que existem diversas contas que compartilham a hashtag dezenas de vezes, enquanto outras contas compartilham uma única vez, indicando uma ação intensa de um pequeno grupo e não um movimento amplo e orgânico.

Alguma forma de coordenação pode ser vista [neste tweet](https://twitter.com/dimacgarcia/status/1194288289869651968) de um influenciador de direita, na qual ele sugere hashtags que possam ser utilizadas a fim de manter o tema nos trending topics. 

### Os dados de desigualdade

O Coeficiente de Gini é uma das ferramentas mais comuns para avaliar a desigualdade da [distribuição de renda entre países](http://www.ipea.gov.br/desafios/index.php?Itemid=23&id=2048%3Acatid%3D28&option=com_content). O site **Nexo** tem uma [boa explicação](https://www.nexojornal.com.br/grafico/2017/07/31/A-evolu%C3%A7%C3%A3o-da-desigualdade-de-renda-no-Brasil-e-no-mundo) sobre o tema.

No entanto, o Coeficiente de Gini é simplesmente uma medida de desigualdade em uma distribuição qualquer.

Adaptando o cálculo desse coeficiente, substituindo o que normalmente é a renda de cada pessoa para a quantidade de tweets que ela publicou, podemos calcular o resultado para cada um dos movimentos analisados do Twitter, e observarmos qual a distribuição do empenho de cada conta na popularização das hashtags.

![gráfico 2 - hashtags de direita](https://github.com/voltdatalab/nucleo-landing/blob/gh-pages/img/twitter-files/gini-tweets_direita.png?raw=true)

Para todas as hashtags acima analisadas, o Coeficiente de Gini é superior a 0.5. As tags com Coeficiente de Gini acima de 0,65, são mais desiguais que a renda na África do Sul em 2014 — maior índice já registrado pelo Banco Mundial.

Quase todas essas hashtags são mais desiguais, por exemplo, do que o [Brasil em 2017](https://data.worldbank.org/indicator/SI.POV.GINI?locations=BR) (53,3) segundo essa medida — que é apenas dentre várias para medir desigualdade. Para acessar dados sobre índice de Gini de países, acesso esse [site de dados](https://data.worldbank.org/indicator/SI.POV.GINI) Banco Mundial.

Um outro exemplo pode vir da CPMI das Fake News, com a deputada federal [Joice Hasselman](https://www.camara.leg.br/deputados/204546) (PSL-SP), que foi atacada no Twitter com a hashtag #JoiceTraidora. A hashtag também ficou nos _trending topics_ da plataforma depois de ser compartilhada mais de 250 mil vezes.

Aplicando a mesma análise, encontramos indicativos de que o comportamento organizado é comum em mais de uma pauta da direita, não somente contra Gilmar Mendes.

![gráfico 3 - hashtag Joice](https://github.com/voltdatalab/nucleo-landing/blob/gh-pages/img/twitter-files/gini-tweets_joice.png?raw=true)

### Comparando com outras hashtags

O Núcleo analisou outras hashtags que tiveram movimentações similares aos movimentos comentados acima, além de outras palavras que entraram no _trending topics_ do Twitter na segunda quinzena de novembro de 2019.

As hashtags que foram capitaneadas pela esquerda possuem coeficiente de Gini menores ou iguais a 0,51, o que indica que há menor coordenação da esquerda no Twitter, e maior espontaneidade. No entanto, o "barulho" é bem menor.

##### Por que não puxar o assunto pela esquerda? Consideramos que a organização e a força da direita no Twitter é mais importante do que a espontaneidade e o menor engajamento da esquerda.    

![gráfico 4 - hashtags de esquerda](https://github.com/voltdatalab/nucleo-landing/blob/gh-pages/img/twitter-files/gini-tweets_esquerda.png?raw=true)

Já olhando outras hashtags populares, relacionadas a outros assuntos além de política, como esporte e K-pop, que movimentaram o Twitter entre novembro e dezembro de 2019, os Coeficientes de Gini variam entre 0,39 até 0,69.

![gráfico 5 - hashtags diversas](https://github.com/voltdatalab/nucleo-landing/blob/gh-pages/img/twitter-files/gini-tweets_naopoliticas.png?raw=true)

---

### Como fizemos isso

O **Núcleo** monitorou algumas das principais hashtags por duas semanas, entre meados de novembro e o começo de dezembro de 2019. [Veja aqui](https://gist.github.com/voltdatalab/4b2351f5752e5f2b64c6978f53965a74) um exemplo de código para utilização da API do Twitter.

A partir dessa coleta de dados, utilizamos o Coeficiente de Gini para medir a concentração de tweets, conforme fórmula abaixo. O código para esse cálculo e dados anonimizados podem ser encontrados [neste link](https://www.kaggle.com/lucaslago/calculadora-indice-de-gini-hashed-data).

![gráfico 5 - hashtags diversas](https://github.com/voltdatalab/nucleo-landing/blob/gh-pages/img/twitter-files/gini-tweets_curvagini.png?raw=true)



<div id="pos-twitter"> </div>


### Posicionamento do Twitter

Em nota enviada ao **Núcleo** por email em 18.dez.2019, o Twitter informou:

> O Twitter investe contínua e fortemente em iniciativas para combater tentativas de interferência no debate público na plataforma, incluindo spam, engajamento não autêntico e atividades coordenadas com o objetivo de influenciar artificialmente as conversas. Especificamente no caso dos Assuntos do Momento, tomamos medidas preventivas como excluir Tweets e usuários automatizados de nossos cálculos de Tendências. Como os spammers mudam suas táticas, nós modificamos ativamente nossas ferramentas tecnológicas para abordar tais situações.
