# 10.9 Lista de verificação do módulo Lightning

Antes de uma oficina sobre Lightning, verifique e explique:

* se a carteira é custodial ou de autocustódia
* como ela é abastecida
* se o abastecimento ou o saque usa uma transação on-chain ou um serviço
* a recuperação e a continuidade caso o provedor ou o dispositivo falhe
* se a solicitação é uma fatura (invoice), um [endereço Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) compatível ou outro tipo
* valor, unidade, destinatário, prazo de expiração, taxa, limites e aspectos de [liquidez](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) a considerar
* como se apresentam o sucesso, a pendência, a expiração ou a falha
* como ambas as partes confirmam o resultado de forma independente; e
* a simulação offline.


<!-- card: dark -->
> **Um pagamento Lightning bem-sucedido prova apenas que essa rota funcionou uma vez.**
>
> Isso não prova que a carteira é segura para saldos maiores nem que o mesmo caminho funcionará em qualquer lugar.



<!-- micrographic: lightning-payment-sequence-01 -->
[Um pagamento Lightning em seis etapas: o recebedor cria uma solicitação, o pagador a escaneia, confere destinatário, valor, unidade, validade e taxa, aprova, o pagamento é roteado e as duas carteiras mostram o resultado. Cada carteira pode ser custodial ou de autocustódia, e um pagamento que falhou ou expirou recomeça com uma nova solicitação.](/micrographics/lightning-payment-sequence-01/pt-BR.md)
