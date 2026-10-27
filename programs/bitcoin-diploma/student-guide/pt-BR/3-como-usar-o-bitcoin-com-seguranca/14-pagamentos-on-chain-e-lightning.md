# 3.14 Pagamentos on-chain e Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->
[Os pagamentos on-chain são registrados diretamente na blockchain do Bitcoin, enquanto a Lightning é uma rede de pagamentos construída sobre o Bitcoin para pagamentos rápidos e frequentes, que também podem falhar. Qualquer um dos caminhos pode ser custodial ou de autocustódia.](/micrographics/on-chain-and-lightning-01/pt-BR.md)



<!-- card: definition -->
> **Definition – Pagamentos on-chain e Lightning**
>
> [Pagamentos on-chain](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) são registrados na [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) do Bitcoin e recebem [confirmações](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). A Lightning é uma rede de pagamentos construída sobre o Bitcoin que pode suportar pagamentos rápidos e frequentes. Um pagamento Lightning pode ser concluído rapidamente ou falhar, e sua carteira pode ser custodial ou autocustodial.



<!-- card: dark -->
> **O caminho do pagamento não determina a custódia**
>
> Pagamentos on-chain e Lightning envolvem diferentes [compensações](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Uma carteira Lightning pode ser custodial ou autocustodial, e um pagamento rápido e bem-sucedido não prova que um serviço seja adequado para saldos maiores ou para qualquer situação.



<!-- micrographic: onchain-lightning-table-01 -->
[Uma tabela que compara o Bitcoin on-chain e a Lightning: informações para recebimento, resultado do pagamento, uso comum e verificações para iniciantes. Qualquer um dos caminhos pode ser custodial ou de autocustódia.](/micrographics/onchain-lightning-table-01/pt-BR.md)


Qual caminho o destinatário espera? Antes de pagar, confirme se ele forneceu um endereço on-chain ou uma [fatura Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) ou solicitação. Uma carteira on-chain não consegue pagar diretamente toda [fatura Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), e uma carteira Lightning pode não suportar todas as ações on-chain. Alguns aplicativos suportam os dois caminhos, mas podem acrescentar taxas ou dependências de serviço. A configuração detalhada da Lightning, os canais, o roteamento e a [liquidez](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) fazem parte do [Aprendizado Avançado](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); a prática local ao vivo pertence ao **Módulo 4**, quando for segura e apropriada.

Imagine que um cenário preparado ofereça os dois caminhos de pagamento. Qual solicitação a carteira pretendida pode usar, e o que você verificaria antes de aprová-la? A resposta depende da solicitação de recebimento, da carteira e da situação — não de um caminho “melhor” universal.

![O educador aponta para dois caminhos de pagamento geométricos diferentes em um quadro, enquanto os alunos iniciante e técnico os analisam.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
