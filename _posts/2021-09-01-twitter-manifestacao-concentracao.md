---
published: TRUE
visible: 1
layout: conteudo
tipo: reportagem
title: 'No Twitter, apenas 12% dos perfis tentam bombar manifestações do 7 de setembro'
titulo_redes: "No Twitter, apenas 12% dos perfis tentam bombar manifestações do 7/9"
subtitle: 'Campanha coordenada sobre o protesto está concentrada em poucos usuários, que impulsionaram mais de dois terços dos tweets sobre o ato'
subtitle_redes: 'Campanha coordenada sobre o protesto está concentrada em poucos usuários'
excerpt: 'No Twitter, apenas 12% dos perfis tentam bombar manifestações do 7/9'
date: "02/09/2021 06:02"
analise:
  - "Lucas Lago"
  - "Lucas Gelape"
dados: "Pedro Barciela"
edicao:
  - "Sérgio Spagnuolo"
  - "Alexandre Orrico"
credito_img: "Rodolfo Almeida"
creditos:
  - "Lucas Lago"
  - "Lucas Gelape"
  - "Sérgio Spagnuolo"
  - "Alexandre Orrico"
image: 'img/twitter-files/7setembro_Teaser.png'
categories:
  - "reportagem"
atualizacao: "Texto atualizado às 12h08 de 2.set.2021 para esclarecer no segundo parágrafo que os 12% dizem respeito aos perfis que tuitaram sobre o assunto."
tags:
  - "Twitter, "
  - "Manifestação, "
  - "Bolsonarismo, "
  - "Política"
---

A manifestação de 7 de setembro organizada por bolsonaristas (e endossada por Jair Bolsonaro) cresceu em número de menções no Twitter, mas não conseguiu se expandir para além do núcleo duro do presidente nessa rede.

Análise do **Núcleo** com monitoramento de termos e hashtags associadas à manifestação mostra que apenas `12%` dos perfis **que tuitaram sobre o assunto** impulsionaram mais de dois terços dos tweets a respeito da manifestação.  

---

###### É importante porque…

- *Embora mostre aumento no número de menções e no peso das manifestações, também mostra que há um limite na adesão de apoiadores no Twitter, uma rede que, embora tenha menos usuários do que Facebook, Instagram e YouTube, por exemplo, consegue pautar o noticiário e serve como termômetro para o debate político.*

---

![grafico - post]({{ site.baseurl }}/img/twitter-files/7setembro_concentracao.png)

A conclusão é de que a concentração no compartilhamento e o convite às manifestações são realizadas por um grupo específico no Twitter, que consegue alavancar o número de menções mas não fazer com que muitos outros usuários tenham o mesmo entusiasmo com a campanha.

O **Núcleo** detectou cerca de 590 mil tweets de 84 mil usuários sobre o 7 de setembro desde o dia 24 de agosto, com as ocorrências crescendo significativamente nos últimos quatro dias.

O **Núcleo** se baseou em duas linhas de análise para chegar a esse resultado:

- Número de menções capturadas em buscas e o número de usuários únicos
- Cálculo do Coeficiente de Gini para verificar a concentração de tweets nos mesmos usuários

A análise não indica que as manifestações serão grandes ou pequenas em número de presentes, mas sim que a conversa nessa rede social está concentrada em poucos atores muito articulados. Chamamos isso de "ação coordenada".

Uma ação coordenada acontece quando membros de uma campanha estimulam suas bases para que elas sejam mais ativas. Isso garante que essas bases façam mais publicações utilizando, por exemplo, uma hashtag – o que resulta em concentração em poucos usuários (daí a desigualdade).

Em geral, métricas de engajamento medem mais apoio ou popularidade de posts e assuntos, mas no caso de manifestações o número de menções é particularmente relevante porque são atos que exigem presença das pessoas como forma de sucesso, e não apenas endosso à pauta.

{% include monitor_sugestao.html %}

[Matéria](https://nucleo.jor.br/redes/2020-01-08-twitter-hashtags-gilmar-analise) do **Núcleo** em janeiro de 2020 mostrou como a direita faz mais ações coordenadas e menos espontâneas do que a esquerda, mas consegue mais engajamento e menções.

Note que por essa análise não é possível determinar a operação de robôs, apenas a concentração de muitas publicações por poucos usuários da rede social. Bots são recursos que, por exemplo, republicam ou comentam alguma publicação mediante o uso de uma palavra-chave, automaticamente.

| grupo         | usuarios | tweets | % do total de tweets    |
|---------------|----------|--------|--------|
| 1 tweet        | 46.646    | 46.646  | 8.49%  |
| 2 a 5 tweets   | 25.902    | 75.143  | 13.67% |
| 6 a 10 tweets   | 75.32     | 57.325  | 10.43% |
| 11 a 50 tweets  | 9.479     | 205.229 | 37.33% |
| 51 a 200 tweets | 1.674     | 139.244 | 25.33% |
| +200  tweets    | 79        | 26.109  | 4.75%  |


### ECONOMIA

O bolsonarismo tem dificuldades em extrapolar seu núcleo duro no Twitter. Dentre os motivos, está a série de problemas enfrentados pelo governo na área econômica, como a crise energética, a inflação e o desaquecimento da economia. Não por acaso, a hashtag #EnergiaParaTodos, utilizada por atores da oposição no dia 31/08 se sobrepôs até mesmo a hashtag #Dia07VaiSerGigante nas menções junto ao nome de Jair Bolsonaro.

Segundo dados do Monitor Nuclear, o mês de agosto foi aquele em que os políticos brasileiros mais falaram em inflação. Foram 405 tuítes contendo esta palavra ao longo do mês, sendo que o segundo com maior número de menções foi março (126). Essa tendência também foi observada nas citações a combustíveis e ao ministro Paulo Guedes.

É nítida a dificuldade do bolsonarismo para contornar o tema "custo de vida" em suas tentativas de convocações. Ainda que sem impacto direto nelas, o tema exige que este campo promova a defesa do governo. Uma das linhas adotadas aqui são os ataques contra governadores, a quem responsabilizam pelo preço do gás de cozinha.

{% include assine_newsletter.html %}


### COMO FIZEMOS ISSO

O **Núcleo** detectou cerca de 590 mil tweets de 84 mil usuários sobre o 7 de setembro desde o dia 24 de agosto, com as ocorrências crescendo significativamente nos últimos quatro dias. Veja aqui um exemplo de código para utilização da API do Twitter.

A partir dessa coleta de dados, utilizamos o Coeficiente de Gini para medir a concentração de tweets, conforme fórmula abaixo. O código para esse cálculo e dados anonimizados podem ser encontrados neste link.

O Gini calculado pelo **Núcleo** sobre as manifestações foi de 0.71. Quanto mais perto de 1, mais concentradas nos mesmos usuários são.

O Coeficiente de Gini é uma das ferramentas mais comuns para avaliar a [desigualdade da distribuição de renda](http://www.ipea.gov.br/desafios/index.php?Itemid=23&id=2048%3Acatid%3D28&option=com_content) entre países. O site Nexo tem uma [boa explicação](https://www.nexojornal.com.br/grafico/2017/07/31/A-evolu%C3%A7%C3%A3o-da-desigualdade-de-renda-no-Brasil-e-no-mundo) sobre o tema.

No entanto, o Coeficiente de Gini é simplesmente uma medida de desigualdade em uma distribuição qualquer.

Adaptando o cálculo desse coeficiente, substituindo o que normalmente é a renda de cada pessoa para a quantidade de tweets que ela publicou, podemos calcular o resultado para cada um dos movimentos analisados do Twitter, e observarmos qual a distribuição do empenho de cada conta na popularização das hashtags.

Apenas como comparação, são mais desiguais que a renda na África do Sul em 2014 — maior índice já registrado pelo Banco Mundial (0.64).

Quase todas essas hashtags são mais desiguais, por exemplo, do que o Brasil em 2019 (53,4) segundo essa medida — que é apenas dentre várias para medir desigualdade. Para acessar dados sobre índice de Gini de países, acesse [esse site de dados](https://data.worldbank.org/indicator/SI.POV.GINI) do Banco Mundial.

![grafico - post]({{ site.baseurl }}/img/twitter-files/gini-tweets_curvagini.png)
