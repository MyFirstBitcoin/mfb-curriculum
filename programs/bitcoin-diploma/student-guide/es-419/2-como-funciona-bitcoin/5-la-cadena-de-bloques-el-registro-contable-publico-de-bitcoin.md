# 2.5 La cadena de bloques: el registro contable público de Bitcoin

<!-- card: definition -->
> **Definition – Cadena de bloques**
>
> En Bitcoin, la [cadena de bloques](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) es un registro público de [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) replicado en muchas computadoras independientes. Un bloque agrupa un conjunto de [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) válidas en la siguiente parte propuesta de ese registro. Cada bloque válido se enlaza con el anterior, lo que proporciona a la red un historial compartido y ordenado que puede verificar.



<!-- card: light -->
> **Cómo alcanzan el consenso los nodos**
>
> [Los nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifican de forma independiente las mismas reglas y convergen en el historial válido con la mayor cantidad acumulada de [prueba de trabajo](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Modificar un registro anterior cambia su bloque y rompe los enlaces con los bloques posteriores, por lo que un historial alternativo debe rehacer ese trabajo y ponerse al día antes de que [los nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) lo acepten. Este costoso proceso de ordenamiento ayuda a la red a alcanzar el [consenso](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) sin un encargado central del registro. Las copias no cambian simultáneamente; [los nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) reciben y validan los datos de forma independiente. Bitcoin tiene como objetivo generar un bloque nuevo aproximadamente cada diez minutos en promedio. El historial es difícil y costoso de reescribir, pero no es literalmente imposible modificarlo: pueden surgir temporalmente historiales alternativos y producirse reorganizaciones.
