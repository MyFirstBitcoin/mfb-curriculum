# 4.5 Pagamentos Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


A Lightning pode tornar viáveis pagamentos em Bitcoin rápidos e de pequeno valor. Ela pode ser adequada para o balcão de um comerciante, pagamentos locais recorrentes, serviços on-line ou transferências em que uma taxa on-chain seria alta demais em relação ao valor do pagamento.

Uma demonstração local da Lightning deve identificar:

* se a carteira é custodial ou de autocustódia
* como a carteira é abastecida
* se o abastecimento exige uma [transação](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) on-chain ou um serviço
* qual backup ou método de recuperação protege o saldo
* que tipo de solicitação de pagamento está sendo usado
* quais taxas ou limites se aplicam
* o que acontece quando um pagamento falha
* como o destinatário confirma o pagamento

Uma [**fatura Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) é uma solicitação de pagamento criada para um pagamento específico. Ela pode incluir um valor, informações sobre o destino e um prazo de validade. Leia a tela de [confirmação](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) da carteira antes de pagar.

Um [**endereço Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) é um identificador legível por pessoas, aceito por alguns serviços. Ele pode se parecer com um endereço de e-mail, mas é uma facilidade para o roteamento de pagamentos, e não uma conta de e-mail. Ele depende do provedor ou do domínio que o suporta.

Para um pagamento guiado:

1. O recebedor cria a solicitação correta.
1. O pagador a escaneia ou copia.
1. O pagador verifica o destinatário, o valor, a unidade e a taxa.
1. O pagador só aprova depois que os dados estiverem corretos.
1. Ambos os lados confirmam o resultado em suas próprias carteiras.
1. O grupo explica os riscos de [custódia](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) e de falha.

Não presuma que um pagamento Lightning bem-sucedido prova que a carteira é segura para saldos maiores. A praticidade dos pagamentos e a segurança da [custódia](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) são questões distintas.
