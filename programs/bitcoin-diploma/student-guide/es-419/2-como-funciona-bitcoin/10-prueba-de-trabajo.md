# 2.10 Prueba de trabajo

**La prueba de trabajo** es el proceso que usan los mineros para competir por el derecho a proponer el siguiente bloque.

Un minero modifica repetidamente los datos de un bloque candidato y los procesa mediante una función hash matemática. El resultado es impredecible. El minero busca un resultado inferior a un valor objetivo establecido por la regla de dificultad de la red. No hay atajos; los mineros deben realizar muchos intentos.

Cuando un minero encuentra un resultado válido, difunde el bloque. Los nodos pueden verificar la prueba rápidamente, aunque encontrarla haya requerido una cantidad considerable de cómputo y energía. Si el bloque incluye una transacción, esa transacción recibe su primera **confirmación**. Cada bloque válido que se agrega después añade otra confirmación, lo que hace más costoso alterar la posición de la transacción en la cadena de bloques. Esta diferencia es importante: realizar el trabajo es costoso y verificarlo es fácil.

La prueba de trabajo cumple varios propósitos:

* les permite a los mineros independientes competir sin un coordinador central;
* hace que alterar el orden de las transacciones sea costoso;
* vincula la seguridad de la red con equipos físicos y energía;
* sustenta un método público para elegir entre historiales válidos que compiten entre sí: la cadena con más trabajo acumulado.

La minería no resuelve ecuaciones útiles para un propósito externo. Su propósito es proteger el orden de las transacciones de Bitcoin. La red ajusta la dificultad de minería para que los bloques sigan generándose aproximadamente cada diez minutos en promedio, a medida que cambia la potencia de cómputo.

La prueba de trabajo implica un costo energético real. Sus defensores sostienen que este costo es lo que sustenta la seguridad de Bitcoin y que puede generar demanda de energía de suministro flexible o que, de otro modo, no se aprovecharía. Sus críticos cuestionan la cantidad y el origen de la energía utilizada. Una evaluación responsable examina qué energía se utiliza, de dónde proviene, qué seguridad brinda y qué alternativas se están comparando.
