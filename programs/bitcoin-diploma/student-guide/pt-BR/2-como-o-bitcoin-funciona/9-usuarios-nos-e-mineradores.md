# 2.9 Usuários, nós e mineradores

O Bitcoin funciona porque diferentes participantes desempenham diferentes papéis.

* **Os usuários** recebem, guardam e enviam bitcoin. Um usuário pode controlar as próprias chaves mantidas em uma carteira ou usar um [custodiante](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Os usuários dão significado econômico à rede ao escolher se aceitam bitcoin e em quais regras ou serviços confiam.
* [**Os nós**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) executam o software do Bitcoin e verificam as regras de forma independente. Um [nó completo](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) verifica se as [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) têm assinaturas válidas, se os bitcoins ainda não foram gastos, se os blocos atendem à [Prova de Trabalho (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) e se os novos bitcoins seguem o [cronograma de emissão](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Os nós](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) compartilham dados válidos com seus pares e rejeitam dados inválidos.
* [**Os mineradores**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) reúnem as [transações pendentes](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), montam [blocos candidatos](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) e competem por meio da [Prova de Trabalho (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Um [minerador bem-sucedido](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [transmite](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) um bloco e pode receber o [subsídio de bloco permitido](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) e as [taxas de transação](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Os mineradores](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ajudam a ordenar as [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) e tornam o [livro-razão](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) caro de reescrever.
* **Os desenvolvedores** revisam, escrevem e propõem mudanças no software. Eles não são donos das regras do Bitcoin. Uma mudança no software só importa se os participantes escolherem executar um software que siga essas regras.


<!-- micrographic: bitcoin-participant-roles-01 -->


Esses papéis limitam uns aos outros:

* um usuário não pode gastar bitcoin sem a assinatura válida exigida
* um [minerador](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pode propor um bloco, mas os [nós](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) decidem se ele segue as regras
* um [nó](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifica usando suas próprias regras, mas o [consenso](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) exige regras compatíveis em toda a rede
* desenvolvedores podem propor software, mas os participantes escolhem se vão executá-lo

Algumas pessoas desempenham vários papéis. Um [minerador](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pode executar um [nó](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) e também ser um usuário. Um iniciante não precisa desempenhar todos os papéis para explicar como esses papéis se equilibram entre si.

**Pergunta rápida:** Por que um [nó](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifica [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Cite pelo menos uma regra que um [nó](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifica.

![O educador orienta o aluno técnico diante de um computador que funciona como nó, com o monitor voltado para eles e a parte traseira do gabinete visível para o observador.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
