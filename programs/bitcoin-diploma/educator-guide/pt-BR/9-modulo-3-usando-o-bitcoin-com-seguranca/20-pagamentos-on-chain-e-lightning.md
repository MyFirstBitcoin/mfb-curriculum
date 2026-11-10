# 9.20 Pagamentos on-chain e Lightning

Use uma comparação que separe o caminho do pagamento da [custódia](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody).


| Pergunta | On-chain | Lightning |
| --- | --- | --- |
| Onde a liquidação é registrada? | Diretamente na blockchain do Bitcoin | As atualizações de pagamento ocorrem por meio de uma rede construída sobre o Bitcoin; os canais, em última instância, dependem do Bitcoin |
| Informação de recebimento comum para iniciantes | Endereço on-chain | Fatura (invoice), endereço Lightning compatível ou outro tipo de solicitação aprovado |
| Uso típico | Liquidação na camada base, geralmente transferências maiores ou menos frequentes | Geralmente pagamentos pequenos ou frequentes, onde as ferramentas locais e a liquidez permitem |
| Tempo | A primeira confirmação depende da inclusão em um bloco | Geralmente rápido, mas os pagamentos podem falhar |
| Taxas e capacidade | Dependem dos dados da transação e da demanda por espaço nos blocos | Dependem da carteira, da rota, da liquidez, do serviço e das condições de pagamento |
| Custódia | Pode ser custodial ou de autocustódia | Pode ser custodial ou de autocustódia |
| Principal verificação para iniciantes | Endereço, rede, valor, taxa e confirmação corretos | Fatura ou destino, valor, prazo de expiração, taxa e resultado do pagamento corretos |


A Lightning não é uma moeda separada. Um pagamento Lightning bem-sucedido não prova que a carteira é segura para um saldo maior. A operação de canais, a infraestrutura de roteamento e a gestão de [liquidez](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) são [Aprendizado Avançado](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/), fora do escopo do Bitcoin Diploma.


<!-- micrographic: on-chain-and-lightning-01 -->
