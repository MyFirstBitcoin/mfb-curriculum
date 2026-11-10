# 3.4 Chaves

A propriedade de bitcoin é garantida por meio de chaves criptográficas.


> **Definition – Chave Privada**
>
> Uma [chave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) é uma informação secreta que permite a uma carteira criar [assinaturas digitais](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) válidas. Uma assinatura autoriza o gasto de bitcoin controlado pela chave correspondente. Qualquer pessoa que obtenha a [chave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) geralmente consegue gastar esses fundos.


Uma [**chave pública**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) é derivada matematicamente da [chave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Ela ajuda a verificar uma assinatura sem revelar a [chave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Os endereços são criados a partir de informações da [chave pública](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key).

A regra essencial é simples:

**As informações públicas de recebimento podem ser compartilhadas. As informações privadas de gasto devem permanecer em segredo.**

Uma [assinatura digital](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) comprova que a [chave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) necessária autorizou uma [transação](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Ela não coloca a [chave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) dentro da [transação](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Os [nós](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verificam a assinatura antes de aceitar o gasto.

A maioria das carteiras para iniciantes usa [assinatura única](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): uma chave privada autoriza uma transação. As carteiras modernas gerenciam muitas chaves automaticamente. Iniciantes não devem copiar nem manusear sequências individuais de [chave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Proteja o backup aprovado da carteira e siga o procedimento de recuperação dela.

Nenhum educador legítimo, empresa de carteiras, funcionário de corretora, profissional de suporte técnico ou desenvolvedor de Bitcoin precisa da sua [chave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ou da sua [frase-semente](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Qualquer pessoa que pedir essas informações deve ser tratada como uma ameaça.


> **Light**
>
> **Experimente:** Classifique exemplos preparados em três grupos: seguro para compartilhar para recebimento, informação secreta de gasto e informação que pode ser pública, mas que ainda assim deve ser mantida privada quando vinculada a uma pessoa.



<!-- micrographic: private-key-public-info-01 -->
