# 2.10 Prueba de trabajo

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – Prueba de trabajo**
>
> [La prueba de trabajo](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) es el proceso que los [mineros](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) utilizan para competir por el derecho a proponer el siguiente bloque.


Una [función hash](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) transforma datos en un resultado de longitud fija. Un pequeño cambio en los datos de entrada produce un nuevo resultado impredecible. Un [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) cambia una pequeña parte de los datos de un bloque propuesto y le aplica la función hash repetidamente. Un resultado es válido solo cuando su número está por debajo del [objetivo](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) de la red, un umbral establecido por las reglas; un menor [objetivo](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) significa menos [resultados válidos](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) y más intentos. No hay atajos, por lo que los [mineros](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pueden necesitar muchos intentos.

Cuando un [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) encuentra un [resultado válido](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), [difunde](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) el bloque. [Los nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) pueden verificar la prueba rápidamente, aunque encontrarla haya requerido una cantidad considerable de cómputo y energía. Si el bloque incluye una [transacción](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), esa [transacción](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) recibe su [primera confirmación](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): su registro se ha incluido en un bloque válido. Cada bloque válido que se agrega después añade otra [confirmación](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), lo que hace que reescribir la posición de la [transacción](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) en la [cadena de bloques](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) sea más costoso. Esta diferencia es importante: el trabajo es costoso de producir y fácil de verificar.


<!-- micrographic: proof-of-work-process-01 -->


[La prueba de trabajo](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) cumple varias funciones:

* les da a los [mineros](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) independientes una forma de competir sin un coordinador central
* hace que el orden de las [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sea costoso de reescribir
* vincula la seguridad de la red con equipos y energía del mundo real
* ofrece un método público para elegir entre historiales válidos en competencia: la cadena con más [trabajo acumulado](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[La minería](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) no resuelve ecuaciones útiles para un fin externo. Su propósito es garantizar en Bitcoin el orden de las [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). La red ajusta periódicamente el valor objetivo: cuando los bloques llegan demasiado rápido, lo reduce, y cuando llegan demasiado lento, lo aumenta, buscando mantener un promedio aproximado de un bloque cada diez minutos a medida que cambia la potencia de cómputo.

[La prueba de trabajo](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) implica un costo energético real. Sus defensores argumentan que este costo es lo que sustenta la seguridad de Bitcoin y puede generar demanda de energía de uso flexible o que de otro modo no se aprovecharía. Sus críticos cuestionan la cantidad y la procedencia de la energía utilizada. Una evaluación responsable examina qué energía se utiliza, de dónde proviene, qué seguridad proporciona y qué alternativas se están comparando.

![El educador, el estudiante principiante y el estudiante con conocimientos técnicos conversan sobre una unidad de minería de sobremesa con un ventilador y una fuente de alimentación independiente.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
