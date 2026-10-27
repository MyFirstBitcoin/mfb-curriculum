# 2.10 Prova de trabalho

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Prova de Trabalho (PoW)**
>
> [A Prova de Trabalho (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) é o processo que os [mineradores](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) usam para competir pelo direito de propor o próximo bloco.


Uma [função hash](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) transforma dados em um resultado de tamanho fixo. Uma pequena alteração na entrada produz um novo resultado imprevisível. Um [minerador](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) altera uma pequena parte dos dados de um bloco proposto e calcula o hash dele repetidamente. Um resultado só é válido quando seu número está abaixo do [alvo](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) da rede, um limite definido pelas regras; um [alvo](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) menor significa menos [resultados válidos](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) e mais tentativas. Não existe atalho, então os [mineradores](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) podem precisar fazer muitas tentativas.

Quando um [minerador](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) encontra um [resultado válido](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), ele [transmite](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) o bloco. Os [nós](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) conseguem verificar a prova rapidamente, mesmo que encontrá-la tenha exigido muito processamento e energia. Se o bloco incluir uma [transação](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), essa [transação](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) recebe sua [primeira confirmação](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): seu registro foi incluído em um bloco válido. Cada bloco válido adicionado depois dele acrescenta mais uma [confirmação](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), tornando a posição da [transação](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) na [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) mais custosa de reescrever. Essa diferença é importante: o trabalho é custoso de produzir e fácil de verificar.


<!-- micrographic: proof-of-work-process-01 -->
[Um minerador calcula o hash de um bloco proposto repetidamente até que um resultado fique abaixo do alvo da rede e, então, transmite o bloco. Os nós verificam rapidamente a prova e cada regra antes de o bloco entrar na blockchain: o trabalho é caro de produzir e fácil de verificar.](/micrographics/proof-of-work-process-01/pt-BR.md)


[A Prova de Trabalho (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) cumpre várias funções:

* ela oferece aos [mineradores](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) independentes uma forma de competir sem um coordenador central
* ela torna a ordenação das [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) custosa de reescrever
* ela vincula a segurança da rede a equipamentos e energia do mundo real
* ela sustenta um método público para escolher entre históricos válidos concorrentes: a cadeia com mais [trabalho acumulado](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[A mineração](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) não resolve equações úteis para um propósito externo. Seu propósito é garantir a ordenação das [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) do Bitcoin. A rede ajusta periodicamente o alvo: quando os blocos chegam rápido demais, ela reduz o alvo, e quando chegam devagar demais, ela o aumenta, buscando em média cerca de um bloco a cada dez minutos à medida que o poder computacional muda.

[A Prova de Trabalho (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) envolve um custo real de energia. Os defensores argumentam que esse custo é o que ancora a segurança do Bitcoin e pode criar demanda por energia flexível ou que, de outra forma, não seria utilizada. Os críticos questionam a quantidade e a origem da energia utilizada. Uma avaliação responsável pergunta qual energia é usada, de onde ela vem, que segurança ela proporciona e quais alternativas estão sendo comparadas.

![O educador, o aluno iniciante e o aluno técnico conversam sobre uma unidade de mineração de mesa com um ventilador e uma fonte de alimentação separada.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
