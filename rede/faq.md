---
layout: single
title: Rede Comboios
subtitle: Perguntas Frequentes
---

### Como é que a informação das Estações de Comboio é obtida?
A informação tem duas fontes. A primeira é um ficheiro de excel que a Infraestruturas de Portugal disponibiliza [aqui](https://dados.gov.pt/pt/datasets/estacoes-e-apeadeiros/). Estes dados são depois tratado com [esta ferramenta](https://github.com/joaoc-pires/macos-app-ptstations) de forma a obter mais alguns detalhes. Posteriormente a informação é publicada [aqui](https://dados.gov.pt/pt/datasets/estacoes-e-apeadeiros-dos-caminhos-de-ferro-portugueses/).
Além deste processo, a API da Infraestruturas de Portugal, que esta aberta, mas não documentada, é utilizada para a pesquisa.

### Como é que a informação do horário dos Comboios é obtida?
Da mesma forma como a informação das estações está disponível no site da Infraestruturas de Portugal, também a dos horários dos comboios tem uma API aberta.

### Que informação minha é partilhada com a App?
Essencialmente nenhuma. Quando são feitos pedidos na internet o IP é sempre partilhado, mas os pedidos são feitos aos servidores da Infraestruturas de Portugal e do GitHub, pelo que a app não guarda, nem sequer regista o IP.

### O que acontece se a Infraestruturas de Portugal remover acesso à API?
Não sei. A informação está disponível na internet de forma aberta há anos, pelo que não antevejo isso a acontecer. Se acontecer, na altura verei o que pode ser feito.

### Quem é o responsável pela App?
[Eu](https://joaopires.com). Também estou disponível [aqui](mailto:developer@joaopires.com).
