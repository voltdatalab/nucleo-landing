---
published: TRUE
visible: 1
layout: ideias
tipo: ideias
title: "Falta de transparência dos governos não é um problema de tecnologia"
titulo_redes: "Falta de transparência dos governos não é um problema técnico"
subtitle: 'Por que APIs podem não ser a melhor forma de divulgar dados públicos?'
subtitle_redes: 'Por que APIs podem não ser a melhor forma de divulgar dados públicos?'
excerpt: 'Por que APIs podem não ser a melhor forma de divulgar dados públicos?'
date: "25/02/2021 12:30"
por:  Jessica Voigt
arte: Rodolfo Almeida
edicao: Sérgio Spagnuolo
bio: "é cientista de dados, fellow da Fundação Alexander von Humboldt, e pesquisa o uso de dados abertos para combate à corrupção na WWU-Münster. Entre 2016 e 2020 trabalhou como líder de dados na ONG Transparência Brasil. Mais sobre o seu trabalho Twitter do projeto Open Data Against Corruption <a href='https://twitter.com/dataagainstcorr' target='_blank'>(@dataagainstcorr)</a>"
contato: '@voigtjessica'
contato_link: https://www.linkedin.com/in/voigtjessica/
credito_img: "Rodolfo Almeida"
image: 'img/ideias/lock-privacidade.png'
atualizacao: ""
nota_abertura: ""
categories:
  - "ideias"
tags:
  - "Transparência, "
  - "Dados abertos, "
  - "Tecnologia"

---

Quanto mais um dado puder ser cruzado com outras informações, mais ele vale. Para isso, o seu formato e informações adjacentes são fundamentais. Dados precisam estar atualizados, disponíveis em formatos legíveis por máquina e acompanhados de outras informações que permitam compreendê-lo corretamente.

Transparência e abertura são conceitos complementares, e considerações sobre  formato e granularidade do dado em sua divulgação são inclusive discutidos na [Lei de Acesso à Informação](http://www.planalto.gov.br/ccivil_03/_ato2011-2014/2011/lei/l12527.htm). No entanto, a divulgação de dados públicos no Brasil costuma [não seguir essas orientações](https://www.ok.org.br/projetos/open-data-index/), e o valor do dado tanto para o controle social quanto para melhoria de políticas acaba sendo limitado.

Como solução, tem sido tendência propor a disponibilização de dados no formato de uma API. Mas apesar das vantagens, as APIs não são necessariamente o método mais democrático ou efetivo de se abrir dados públicos. Além disso, essa proposta pressupõe que o problema dos dados públicos é resultado de uma carência de tecnologia.

##### Mas assim como não se trata de falta de regulação, o problema também não diz respeito à carência tecnológica.

O ponto central é que enquanto a discussão sobre divulgação de dados públicos trata de interconectividade, muitos órgãos públicos ainda estão na internet dos hiperlinks. Isso quer dizer que para estes órgãos a informação é vista como um serviço que o setor público é obrigado, por lei, a prestar e, por sua vez, a transação é pensada de forma individual e limitada.

A consequência disso é que os órgãos podem até cumprir a lei, mas em muitos casos de maneira insatisfatória, por exemplo disponibilizando uma imagem escaneada, uma visualização qualquer em dashboards confusos ou até mesmo um mecanismo de consulta limitado. A transparência é pensada para que um cidadão acesse uma informação de seu interesse, e não para que os cidadãos monitorem o poder público.

E quando as APIs são, de fato, interessantes? Se pensadas estrategicamente, elas têm um potencial gigantesco de interconectividade e podem mudar a forma como os cidadãos monitoram o poder público.

##### As APIs são úteis e potencialmente invertem a lógica da transparência "individual", mas precisam ser analisadas do ponto de vista de demanda, acesso e custo.

### Mas afinal, o que são APIs?

API é uma interface de transmissão de informações pensada em viabilizar o uso de informações em aplicações externas. Normalmente a API do Google Maps é citada como (excelente) exemplo: o Waze, Uber, 99 e outros serviços de transporte utilizam essa API para calcular as rotas e estabelecer tarifas. O aplicativo [Tá de Pé](https://www.transparencia.org.br/projetos/tadepe), da Transparência Brasil, utiliza a API do Google Maps para cruzar o endereço oficial da obra de escola pública com um pin no mapa. É bastante útil!

Na ciência de dados, as APIs permitem que diversas pessoas realizem consultas simultâneas, e são úteis especialmente em bancos de dados muito grandes e frequentemente atualizados. Com uma API, o cidadão não precisa mais baixar arquivos enormes para ter acesso aos dados atualizados. Eu costumo brincar que se banco de dados é o futuro da planilha, a API é o futuro do banco de dados.

### Primeiro problema: demanda

Mas aí vem a primeira pergunta: será que todos os dados públicos são grandes e frequentemente atualizados? E será que todos os dados públicos têm uma demanda de consulta tão intensa que justifique a criação de uma API?

##### Será que todos os dados públicos seriam interessantes o suficiente para serem usados em aplicações de terceiros?

Acredito que temos que argumentar em favor de APIs no setor público para dados de grande interesse público, que possuem grande volume e que sejam atualizados com frequência, preferencialmente por diferentes servidores ou entes federativos, de modo que um acompanhamento dinâmico seja realmente útil.

### Segundo problema: acesso

De acordo com a [Open Government Partnership](https://www.opengovpartnership.org/stories/que-tal-definirmos-principios-de-governo-aberto/), um dos princípios do governo aberto é a participação cidadã. Se estamos pensando em políticas de dados abertos visando maior participação, não deveríamos limitar esse acesso a programadores e cientistas de dados.

Organizações como o [Observatório Social do Brasil](https://osbrasil.org.br/) possuem voluntários para avaliar as compras públicas e realizam um grande trabalho de fiscalização. Eles conhecem bem as regras de compras públicas, mas não necessariamente são experts em dados. Apesar de ser desejável que os conhecimentos em ciência de dados sejam de domínio público, essa ainda não é a realidade no Brasil.

Portanto, não há como exigir que cada uma dessas organizações conte com especialistas capazes de fazer requisições a APIs para acompanhar as compras locais. Isso seria inviabilizar a fiscalização do terceiro setor e remar na contramão de um Estado mais transparente e que presta contas devidamente.

### Terceiro problema: custo

Quanto custa criar e manter uma API? Tenho alguma experiência com isso e posso dizer que não é barato e nem rápido. Para além de criar e documentar a API, é preciso testá-la diversas vezes em diferentes ambientes para garantir que não há erros. Mesmo assim, já fui pega de surpresa em hackathons que usavam a API que eu tinha encomendado com alguma consulta ou alguma documentação que precisava ser melhorada.

Desenvolver algo assim necessita de uma cultura gerencial preparada para receber muitos feedbacks, e apesar de conhecer excelentes exemplos no setor público de times com cultura orientada a dados, eu sei que essa não é a realidade em todos os órgãos públicos, assim como não é realidade em todas as empresas.

Se pensarmos nesses órgãos que provavelmente não tem à disposição profissionais capacitados para criar uma arquitetura de API e somarmos isso à lógica de contratação do Estado, podemos imaginar quanto tempo e recurso humano vai ser empregado para desenvolver essa API. Às vezes, mesmo quando a API é desejável, ela pode não ser a melhor solução.

### O Veredito

A adoção de APIs como mecanismo de transmissão de dados públicos deve ser pensada do ponto de vista estratégico, considerando demanda para consulta constante daqueles dados, o custo de construção e manutenção desta API e as limitações de acesso que a transmissão desses dados via API podem vir a impor.

As APIs modificam sim a lógica individual do fornecimento de informações e são sim um grande recurso para interconectividade. Mas mesmo quando as condições mencionadas são satisfeitas, a API ainda precisa ser estruturada de maneira a fornecer dados relevantes e dentro de um contexto que permita a interpretação dos dados. E, se a demanda e os custos não compensam a criação de uma API, arquivos bem elaborados, documentados e atualizados (ex. csv, tsv, json) podem dar conta de garantir abertura e acesso ao Estado.

*Artigo adaptado pela autora para o Núcleo Jornalismo, originalmente publicado [neste blog pessoal](https://jessicavoigt.medium.com/por-que-apis-podem-n%C3%A3o-ser-a-melhor-forma-de-divulgar-dados-p%C3%BAblicos-b559ac9def72) na plataforma Medium*
