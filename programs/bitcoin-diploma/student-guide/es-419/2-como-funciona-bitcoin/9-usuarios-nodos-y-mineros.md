# 2.9 Usuarios, nodos y mineros

Bitcoin funciona porque distintos participantes desempeñan distintas funciones.

**Usuarios** reciben, guardan y envían bitcoin. Un usuario puede controlar sus propias claves almacenadas en una billetera o recurrir a un custodio. Los usuarios dan sentido económico a la red al elegir si aceptan bitcoin y en qué reglas o servicios confían.

**Nodos** ejecutan el software de Bitcoin y verifican de forma independiente el cumplimiento de las reglas. Un nodo completo comprueba que las transacciones tengan firmas válidas, que los bitcoin no se hayan gastado antes, que los bloques cumplan con la prueba de trabajo y que los nuevos bitcoin se emitan según el calendario de emisión. Los nodos comparten datos válidos con otros nodos y rechazan los datos inválidos.

**Mineros** reúnen transacciones pendientes, construyen bloques candidatos y compiten mediante la prueba de trabajo. El minero que lo logra difunde un bloque y puede recibir el subsidio de bloque permitido y las comisiones por transacción. Los mineros ayudan a ordenar las transacciones y hacen que reescribir el registro contable sea costoso.

**Desarrolladores** revisan, escriben y proponen cambios en el software. No son dueños de las reglas de Bitcoin. Un cambio en el software solo tiene efecto si los participantes deciden ejecutar software que siga esas reglas.

Estas funciones se limitan entre sí:

* un usuario no puede gastar bitcoin sin la firma válida requerida;
* un minero puede proponer un bloque, pero los nodos deciden si cumple con las reglas;
* un nodo verifica según sus propias reglas, pero el consenso requiere reglas compatibles en toda la red;
* los desarrolladores pueden proponer software, pero los participantes eligen si lo ejecutan.

Algunas personas desempeñan varias funciones. Un minero puede operar un nodo y también ser usuario. Un principiante no necesita desempeñar todas las funciones para explicar cómo se equilibran entre sí.

**Pregunta rápida:** ¿Por qué un nodo verifica las transacciones? Menciona al menos una regla que un nodo compruebe.
