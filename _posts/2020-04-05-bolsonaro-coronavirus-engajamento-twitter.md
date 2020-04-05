---
published: FALSE
layout: conteudo
tipo: análise
title: 'Antes seu domínio, Bolsonaro tem perdido a briga no Twitter'
titulo_redes: "Bolsonaro tem perdido a briga no Twitter"
subtitle: ""
subtitle_redes: ""
excerpt: ""
date: 02/04/2020
analise: Sérgio Spagnuolo
graficos: Sérgio Spagnuolo
dados_abertos: ""
dados_abertos_link: ''
dados_abertos2: ""
dados_abertos_link2: ""
background: '../img/corona-twitter/bolsonaro_twitter_destaque.jpg'
nota_abertura: ""
atualizacao: ""
categories:
  - "redes"
tags:
  - "Jair Bolsonaro, "
  - "Polarização política, "
  - "Twitter, "
  - "Coronavírus"
---




---

###### É importante porque...

- *Mostra a dificuldade prática na política de isolamento social nas periferias, para combate ao coronavírus*

- *Em domicílios com muitos moradores por quarto, pode ser praticamente impossível adotar medidas de isolamento caso algum morador apresente sintomas do coronavírus*

---

| data          | status id           | perfil     | curtidas | RTs | interações totais |
|---------------------|---------------------|-----------------|----------------|---------------|------------|
| 2020-03-25 00:32:29 | 1242610268301074434 | felipeneto      | 227045         | 47492         | 274537     |
| 2020-03-27 03:39:48 | 1243382186264244224 | felipeneto      | 184785         | 33587         | 218372     |
| 2020-03-18 18:31:16 | 1240345038065893376 | FeCastanhari    | 167463         | 26255         | 193718     |
| 2020-03-17 21:14:05 | 1240023624272183303 | mamede_filho    | 145378         | 42806         | 188184     |
| 2020-03-24 23:48:40 | 1242599244634238977 | cellbit         | 135172         | 41970         | 177142     |
| 2020-03-19 02:42:11 | 1240468581516787714 | felipeneto      | 154998         | 20975         | 175973     |
| 2020-03-18 02:08:36 | 1240097745123368960 | ricardolisias   | 153759         | 19842         | 173601     |
| 2020-03-19 22:19:44 | 1240764924185513987 | irisfigueiredo  | 138558         | 29089         | 167647     |
| 2020-03-25 00:25:41 | 1242608558232961024 | Haddad_Fernando | 137395         | 28626         | 166021     |
| 2020-04-01 03:03:38 | 1245185021855612929 | IandeAlbuquerq  | 112174         | 46131         | 158305     |
| 2020-03-27 20:16:29 | 1243633007812128771 | felipeneto      | 124971         | 24094         | 149065     |
| 2020-03-31 01:59:11 | 1244806416151478274 | luanaserrax     | 112720         | 34049         | 146769     |
| 2020-03-23 11:37:04 | 1242052740873957378 | Marcelo_Mendonc | 109581         | 34434         | 144015     |
| 2020-03-18 12:21:26 | 1240251968834191360 | kabarizon       | 107043         | 26899         | 133942     |
| 2020-03-24 20:37:56 | 1242551242007744512 | YuriMarcal      | 89797          | 36488         | 126285     |
| 2020-03-23 15:17:46 | 1242108284456390657 | Efipedotrembala | 86882          | 38612         | 125494     |
| 2020-03-30 16:17:19 | 1244659983087697923 | felipeneto      | 104231         | 20950         | 125181     |
| 2020-03-31 23:39:10 | 1245133566767489025 | Haddad_Fernando | 106876         | 15507         | 122383     |
| 2020-03-18 19:16:54 | 1240356524750524416 | isabellaboghi   | 90295          | 30418         | 120713     |
| 2020-03-31 16:46:36 | 1245029739347283969 | felipeneto      | 105575         | 12106         | 117681     |

### METODOLOGIA

Utilizamos os dados do Censo 2010 nesta análise, tanto do questionário geral quanto do questionário da amostra. O questionário da amostra é um questionário expandido e é aplicado só em uma amostra dos domicílios. Nos microdados desse questionário há tanto o número de habitantes quanto de dormitórios por domicílio. O número de habitantes por quarto é uma divisão dessas duas variáveis.

Como esse questionário é feito por amostragem, ele tem uma área geográfica maior do que os setores censitários (a unidade de recenseamento do IBGE). Essas áreas são chamadas de “áreas de ponderação”. Uma tabela disponibilizada pelo IBGE permite cruzar as as áreas de ponderação com os setores censitários.

Para calcular o percentual de moradores na Região Metropolitana de SP que vivem em domicílios com mais de duas pessoas por quarto, multiplicamos o número de moradores dentro de cada área de ponderação (extraído a partir da junção com os setores censitários) pela porcentagem de pessoas vivendo nessas condições.

Vale ressaltar que esse número é provavelmente subestimado, uma vez que os domicílios mais densos devem concentrar uma parcela ainda maior da população das suas áreas de ponderação, justamente por serem mais densos. Em breve publicaremos o código completo da análise aqui.

<style>
.expandimg{
  width: 900px !important;
}

@media(max-width:767px) {
    .expandimg {
      display: none;
    }
  }

.botao {
  border-radius: 5px;
  background-color: #eeeeee;
  padding: 5px 7px;
  font-size: 0.8em;
  line-height: 1.5em;
  border: 1px solid #4b31dd
}

.botao:hover {
  background-color: #4b31dd;
  color: #fff;
}

.cf:before, .cf:after {
	 content: "";
	 display: table;
}
 .cf:after {
	 clear: both;
}
 .cf {
	 zoom: 1;
}
 #content {
	 max-width: 650px;
	 margin: 3rem auto;
	 text-align: center;
}
 #featured_img img, #thumb_img img {
	 max-width: 100%;
}
 #thumb_img {
	 margin-top: 2%;
}
 #thumb_img img {
	 float: left;
	 max-width: 32%;
	 width: 32%;
	 cursor: pointer;
	 margin-right: 2%;
	 border: 2px solid #eee;
	 box-sizing: border-box;
}
 #thumb_img img.active {
	 border: 2px solid #cac6b8;
}
 #thumb_img img:last-child {
	 margin-right: 0;
}

</style>

<script>
function changeimg(url,e) {
  document.getElementById("img").src = url;
  let nodes = document.getElementById("thumb_img");
  let img_child = nodes.children;
  for (i = 0; i < img_child.length; i++) {
    img_child[i].classList.remove('active')
  }
  e.classList.add('active');

}
</script>
