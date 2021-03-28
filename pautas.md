---
layout: pages
title: 'Colabore com o Núcleo'
desc: 'Buscamos colaboradores interessados em produzir jornalismo e compartilhar ideias sobre tecnologia'
tagline: PAUTAS E CVS
subtitle: 'Buscamos colaboradores interessados em produzir jornalismo e compartilhar ideias sobre tecnologia'
link: impacto
icone: '<i class="fas fa-laptop-house fa-lg"></i>'
atualizacao: 24/02/2021
---

O **Núcleo** está em busca de colaboradores freelancers para trazerem pautas sobre o impacto da tecnologia na vida das pessoas, assim como debates e discussões de redes sociais.

Veja abaixo a tabela de valores que costumamos pagar para frilas e os elementos que as compõem. Vale notar que nenhum valor é fechado, e que negociação pode ser feita dependendo da pauta e dos recursos apresentados.

Os textos da seção [IDEIAS]({{ site.baseurl }}/ideias) possuem valor fixo, considerando que são mais simples de escrever e se baseiam em visões e experiências pessoais.


| Valor              | Elementos de peso na avaliação                                                                                                                                                                                                                                      |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Mínimo R$800                 | Podem interessar, mas: não tenham tanto apelo imediato no ciclo noticioso; não tragam conhecimento novo ou muito relevante; venham ainda no início da apuração (o que nos dá mais trabalho interno); não tenham dados ou ideias de recursos além do texto. |
| Média R$1.500                | Em geral, essas pautas:  têm dados ou ideias de recursos além do texto; vêm quase prontas, pendentes apenas de edição e alguns detalhes; trazem assuntos relevantes e atuais no ciclo noticioso.                                                              |
| Acima de R$2000 (negociação) | Essas pautas:  apresentam novos conhecimentos ou informações muito quentes e relevantes (furos, investigações, análises aprofundadas); vêm preferencialmente avançadas na apuração e no desenvolvimento; trazem ideas e dados para recursos além do texto     |
| Texto Ideias R$300           | Valor fixo, o texto precisa:  trazer um ponto interessante sobre tecnologia; colaborar com o debate do assunto; ser bem escrito e apurado; não se basear somente em opinião, mas também em observação (exceto quanto solicitado)                            |


---

<div id="formulario_frilas"></div>
### FORMULÁRIO

Preencha o formulário abaixo que mais se encaixa no seu interesse em colaborar com o **Núcleo**. Note que _há dois formulários_, basta selecionar na aba seu interesse. Pautas enviadas por email serão desconsideradas.

**IMPORTANTE**: Devido ao grande número de envios no formulário de _freelancers_, não será possível responder a todas as sugestões de pautas que recebermos.

<div class="tabset">
  <!-- Tab 1 -->
  <input type="radio" name="tabset" id="tab1" aria-controls="pt" checked>
  <label for="tab1"><h2>Pautas como freelancer</h2></label>
  <!-- Tab 2 -->
  <input type="radio" name="tabset" id="tab2" aria-controls="en">
  <label for="tab2"><h2>Cadastro de CVs</h2></label>

  <div class="tab-panels">
    <section id="marzen" class="tab-panel">

        <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdFqy_EUQ48MQ2O_6-UMCqAZk9MDzDUHMTutRrrr1B8bUWk-g/viewform?embedded=true" width="100%" height="2300" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

  </section>


    <section id="rauchbier" class="tab-panel">

        <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdbBb_pS9WGf9j8VyR1xwuFGrYjAGyuEHkKmX1VZcswVcWzxQ/viewform?embedded=true" width="100%" height="3000" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

    </section>
  </div>

</div>


<style>
  form{
    max-width: 400px;
    margin: 0 auto;
  }
  h2{
    text-transform: uppercase
  }

  h2,h4{
    text-align: center
  }

.tabset > input[type="radio"] {
  position: absolute;
  left: -200vw;
}

.tabset .tab-panel {
  display: none;
}

.tabset > input:first-child:checked ~ .tab-panels > .tab-panel:first-child,
.tabset > input:nth-child(3):checked ~ .tab-panels > .tab-panel:nth-child(2),
.tabset > input:nth-child(5):checked ~ .tab-panels > .tab-panel:nth-child(3),
.tabset > input:nth-child(7):checked ~ .tab-panels > .tab-panel:nth-child(4),
.tabset > input:nth-child(9):checked ~ .tab-panels > .tab-panel:nth-child(5),
.tabset > input:nth-child(11):checked ~ .tab-panels > .tab-panel:nth-child(6) {
  display: block;
}

.tabset > label {
  position: relative;
  display: inline-block;
  padding: 5px 15px 20px;
  border: 0px solid transparent;
  border-bottom: 0;
  cursor: pointer;
  border-radius: 3px;
  font-weight: 600;
}

.tabset > label::after {
  content: "";
  position: absolute;
  left: 15px;
  bottom: 10px;
  width: 22px;
  height: 4px;
  background: #f4f4f4;
}

.tabset > label:hover,
.tabset > input:focus + label {
  color: #1cd999;
}

.tabset > label:hover::after,
.tabset > input:focus + label::after,
.tabset > input:checked + label::after {
  background: #1cd999;
}

.tabset > input:checked + label {
  border-color: #000;
  border-bottom: 1px solid #fff;
  margin-bottom: -1px;
}

.tab-panel {
  padding: 30px 0;
  border-top: 1px solid #d91c5c;
}
</style>
