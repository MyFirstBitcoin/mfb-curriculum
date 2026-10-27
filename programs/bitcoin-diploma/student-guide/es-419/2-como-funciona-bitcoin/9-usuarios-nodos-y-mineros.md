# 2.9 Usuarios, nodos y mineros

Bitcoin funciona porque distintos participantes desempeñan distintas funciones.

* **Los usuarios** reciben, mantienen y envían bitcoin. Un usuario puede controlar sus propias claves almacenadas en una billetera o recurrir a un [custodio](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Los usuarios dan sentido económico a la red al elegir si aceptan bitcoin y en qué reglas o servicios confían.
* [**Los nodos**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ejecutan el software de Bitcoin y verifican las reglas de forma independiente. Un [nodo completo](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) comprueba que las [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tengan firmas válidas, que los bitcoin no se hayan gastado ya, que los bloques cumplan con la [prueba de trabajo](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) y que los nuevos bitcoin sigan el [calendario de emisión](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Los nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) comparten datos válidos con sus pares y rechazan los datos inválidos.
* [**Los mineros**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) reúnen las [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) pendientes, construyen [bloques candidatos](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) y compiten mediante la [prueba de trabajo](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Un [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [difunde](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) un bloque cuando tiene éxito y puede recibir el [subsidio de bloque](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) permitido y las [comisiones de transacción](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Los mineros](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ayudan a ordenar las [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) y hacen que el [libro mayor](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) sea costoso de reescribir.
* **Los desarrolladores** revisan, escriben y proponen cambios en el software. No son dueños de las reglas de Bitcoin. Un cambio en el software solo tiene efecto si los participantes deciden ejecutar software que siga esas reglas.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Cuatro roles en Bitcoin: los usuarios reciben, guardan y envían bitcoin, los nodos verifican las reglas de forma independiente, los mineros construyen bloques candidatos mediante la prueba de trabajo y los desarrolladores proponen software. Ningún rol controla por sí solo la red.](/micrographics/bitcoin-participant-roles-01/es-419.md)


Estas funciones se limitan entre sí:

* un usuario no puede gastar bitcoin sin la firma válida requerida
* un [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) puede proponer un bloque, pero [los nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) deciden si cumple con las reglas
* un [nodo](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifica según sus propias reglas, pero el [consenso](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) requiere reglas compatibles en toda la red
* los desarrolladores pueden proponer software, pero los participantes eligen si lo ejecutan

Algunas personas desempeñan varios roles. Un [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) puede ejecutar un [nodo](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) y también ser usuario. Un principiante no necesita desempeñar todos los roles para explicar cómo se equilibran entre sí.

**Pregunta puntual:** ¿Por qué un [nodo](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifica [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Nombre al menos una regla que un [nodo](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) comprueba.

![El educador guía al estudiante técnico frente a una computadora que ejecuta un nodo, con el monitor orientado hacia ambos y su carcasa trasera visible para el espectador.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
