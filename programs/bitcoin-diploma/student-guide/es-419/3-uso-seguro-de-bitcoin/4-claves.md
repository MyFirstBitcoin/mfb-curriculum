# 3.4 Claves

La propiedad de Bitcoin se garantiza mediante claves criptográficas.


<!-- card: definition -->
> **Definition – Clave privada**
>
> Una [clave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) es información secreta que permite a una billetera crear [firmas digitales válidas](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). Una firma autoriza el gasto de los bitcoin controlados por la clave correspondiente. Cualquier persona que obtenga la [clave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) generalmente puede gastar esos fondos.


Una [**clave pública**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) se deriva matemáticamente de la [clave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Ayuda a verificar una firma sin revelar la [clave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Las direcciones se crean usando la [clave pública](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) como fuente de información.

La regla esencial es sencilla:

**La información pública para recibir fondos se puede compartir. La información privada para gastar fondos debe mantenerse en secreto.**

Una [firma digital](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) demuestra que la [clave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) requerida autorizó una [transacción](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). No incluye la [clave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) dentro de la [transacción](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Los nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifican la firma antes de aceptar el gasto.

La mayoría de las billeteras para principiantes utilizan [firma única](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): una sola clave privada autoriza una transacción. Las billeteras modernas gestionan muchas claves automáticamente. Los principiantes no deben copiar ni manipular [claves privadas](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) individuales en forma de cadenas de texto. Proteja la copia de seguridad aprobada por la billetera y siga su procedimiento de recuperación.

Ningún educador, empresa de billeteras, empleado de una plataforma de intercambio, trabajador de soporte técnico o desarrollador de Bitcoin legítimo necesita su [clave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ni su [frase semilla](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Cualquier persona que se la pida debe ser considerada una amenaza.


<!-- card: light -->
> **Inténtelo:** Clasifique los ejemplos preparados en tres grupos: información que se puede compartir de forma segura para recibir fondos, información secreta para gastar fondos e información que puede ser pública, pero que aun así debe mantenerse privada cuando esté vinculada a una persona.



<!-- micrographic: private-key-public-info-01 -->
[Una clave privada secreta, que nunca debe compartirse, da lugar a información pública que sí se puede compartir: una clave pública derivada de ella y una dirección de recepción creada a partir de esa clave pública. La misma clave privada crea firmas que los nodos verifican sin llegar a conocer la clave privada.](/micrographics/private-key-public-info-01/es-419.md)
