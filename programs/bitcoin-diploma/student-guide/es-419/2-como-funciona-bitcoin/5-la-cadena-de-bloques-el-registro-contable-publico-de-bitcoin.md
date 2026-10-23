# 2.5 La cadena de bloques: el registro contable público de Bitcoin

> **Definition – Cadena de bloques**
>
> En Bitcoin, la [cadena de bloques](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) es un registro público de [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) replicado en muchas computadoras independientes. Un bloque agrupa un conjunto de [transacciones válidas](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) en la siguiente parte propuesta de ese registro. Cada bloque válido se enlaza con el anterior, lo que le da a la red un historial compartido y ordenado que puede verificar.



> **Definition – Nodo**
>
> [Los nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifican de forma independiente las mismas reglas y convergen en el historial válido con la mayor [prueba de trabajo acumulada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Modificar un registro anterior cambia su bloque y rompe los enlaces con los bloques posteriores, por lo que un historial alternativo debe rehacer ese trabajo y ponerse al día antes de que los [nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) lo acepten. Este costoso proceso de ordenamiento ayuda a la red a alcanzar un [consenso](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) sin un encargado central del registro. Las copias no cambian simultáneamente; los [nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) reciben y validan los datos de forma independiente. Bitcoin tiene como objetivo generar un bloque nuevo aproximadamente cada diez minutos, en promedio. Reescribir el historial es difícil y costoso, pero no es literalmente imposible modificarlo: pueden surgir historiales alternativos temporales y ocurrir reorganizaciones.
