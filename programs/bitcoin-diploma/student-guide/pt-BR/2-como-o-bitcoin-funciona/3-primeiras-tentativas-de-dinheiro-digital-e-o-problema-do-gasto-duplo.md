# 2.3 Primeiras tentativas de dinheiro digital e o problema do gasto duplo

O Bitcoin não foi a primeira tentativa de criar dinheiro digital. Ele foi construído sobre quatro décadas de experimentação, aproveitando ideias de muitos projetos anteriores que ajudaram a moldar seu design bem-sucedido.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) usava [criptografia](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) para viabilizar pagamentos digitais privados. Dependia de uma empresa central e de relações bancárias. Quando a empresa faliu, o sistema não pôde continuar como uma rede monetária independente.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) usava [prova de trabalho (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) para tornar caro o envio de e-mails indesejados. O computador do remetente precisava realizar um trabalho antes de enviar uma mensagem. A ideia mostrou como o custo computacional poderia desestimular abusos.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) descrevia um sistema proposto no qual o trabalho computacional poderia criar registros digitais escassos. Não foi lançado como um sistema monetário descentralizado completo, mas desenvolveu ideias importantes sobre [escassez](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) digital e prova.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) e [**prova de trabalho reutilizável (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) exploraram formas de os participantes criarem ou transferirem [valor](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) digital escasso sem depender apenas de um único banco de dados central. Eram incompletos, mas ajudaram a esclarecer o que um sistema funcional exigiria.
* Embora o [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) não fosse dinheiro, ele mostrou que uma [rede peer-to-peer (P2P)](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) poderia permitir que muitos computadores independentes compartilhassem informações sem que um servidor central controlasse todo o sistema.

Juntos, esses experimentos revelaram peças úteis do quebra-cabeça. Eles também esclareceram o problema que restava.


> **Definition – Gasto duplo**
>
> [O gasto duplo](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) é uma tentativa de enviar a mesma unidade digital para dois destinatários. Dados digitais podem ser copiados perfeitamente, então um sistema de dinheiro digital precisa de uma forma de determinar qual [transação](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) é válida.


[Os sistemas centralizados](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) impedem isso permitindo que um único banco de dados confiável decida qual pagamento veio primeiro. Em 31 de outubro de 2008, o whitepaper de [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto), [_Bitcoin: Um Sistema de Dinheiro Eletrônico Peer-to-Peer_](https://bitcoin.org/bitcoin.pdf), explicou uma abordagem diferente: um sistema público capaz de estabelecer um histórico de pagamentos compartilhado sem um banco, uma empresa ou outra autoridade central.

O whitepaper reuniu os recursos necessários para essa abordagem:

1. **Uma [rede peer-to-peer (P2P)](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** as [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) são anunciadas diretamente a uma rede de participantes.
1. **[Assinaturas digitais](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** uma [chave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) é uma informação secreta que cria uma assinatura para autorizar um gasto; somente quem a possui pode fazer isso.
1. **Blocos e [mineração](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [os mineradores](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) reúnem [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) em blocos e usam a [Prova de Trabalho (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) para competir pela adição do próximo bloco.
1. **Verificação [independente](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [os nós](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) conferem as [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) e os blocos com base nas regras do Bitcoin.
1. **Um histórico compartilhado com acúmulo de [Prova de Trabalho (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** os participantes reconhecem a [cadeia válida](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) de [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) com mais [trabalho acumulado](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) como o registro compartilhado.


<!-- micrographic: five-part-response-01 -->


Este módulo explica esses conceitos com mais detalhes. Juntos, eles deram uma resposta prática ao [problema do Gasto Duplo](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): a rede pode rejeitar uma segunda tentativa de gastar o mesmo bitcoin sem depender de uma autoridade central. O Bitcoin ofereceu a combinação que faltava e que décadas de experimentos com dinheiro digital vinham buscando.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
