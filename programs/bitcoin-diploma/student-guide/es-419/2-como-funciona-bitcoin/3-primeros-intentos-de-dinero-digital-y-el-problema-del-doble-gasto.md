# 2.3 Primeros intentos de dinero digital y el problema del doble gasto

Bitcoin no fue el primer intento de crear dinero digital. Se construyó sobre cuatro décadas de experimentación, tomando ideas de muchos proyectos anteriores que ayudaron a dar forma a su exitoso diseño.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) utilizó [criptografía](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) para permitir pagos digitales privados. Dependía de una empresa central y de relaciones con bancos. Cuando la empresa fracasó, el sistema no pudo continuar como una red monetaria independiente.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) utilizó [prueba de trabajo](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) para hacer costoso el envío de correos electrónicos no deseados. La computadora del remitente tenía que realizar trabajo antes de enviar un mensaje. La idea mostró cómo el costo computacional podía desalentar el abuso.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) describió una propuesta de sistema en el que el trabajo computacional podía crear registros digitales escasos. No se lanzó como un sistema completo de dinero descentralizado, pero desarrolló ideas importantes sobre la [escasez digital](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) y la prueba.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) y la [**prueba de trabajo reutilizable (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) exploraron formas en que los participantes podían crear o transferir [valor](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) digital escaso sin depender únicamente de una base de datos central. Eran proyectos incompletos, pero ayudaron a aclarar qué necesitaría un sistema funcional.
* Aunque [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) no era dinero, mostró que una [red entre pares](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) podía permitir que muchas computadoras independientes compartieran información sin que un servidor central controlara todo el sistema.

En conjunto, estos experimentos mostraron piezas útiles del rompecabezas. También aclararon el problema que aún quedaba por resolver.


<!-- card: definition -->
> **Definition – Doble gasto**
>
> [El doble gasto](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) es un intento de enviar la misma unidad digital a dos destinatarios. Los datos digitales se pueden copiar perfectamente, por lo que un sistema de dinero digital necesita una forma de establecer qué [transacción](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) es válida.


[Los sistemas centralizados](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) evitan esto al permitir que una base de datos de confianza decida qué pago se realizó primero. El 31 de octubre de 2008, [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto), en su libro blanco, [_Bitcoin: un sistema de efectivo electrónico entre pares_](https://bitcoin.org/bitcoin.pdf), explicó un enfoque diferente: un sistema público que pudiera establecer un historial de pagos compartido sin un banco, una empresa u otra autoridad central.

El libro blanco reunió las características necesarias para ese enfoque:

1. **Una [red entre pares](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [las transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) se anuncian directamente a una red de participantes.
1. **[Firmas digitales](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** una [clave privada](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) es información secreta que crea una firma para autorizar un gasto; solo su titular puede hacerlo.
1. **Bloques y [minería](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [los mineros](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) agrupan [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) en bloques y utilizan la [prueba de trabajo](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) para competir por agregar el siguiente bloque.
1. **Independencia en la [verificación](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [los nodos](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifican [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) y bloques según las reglas de Bitcoin.
1. **Un historial compartido con acumulación de [prueba de trabajo](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** los participantes reconocen la [cadena válida](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) de [transacciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) con la mayor cantidad de [trabajo acumulado](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) como el registro compartido.


<!-- micrographic: five-part-response-01 -->
[Cinco elementos se combinan para resolver el problema del doble gasto: una red entre pares, firmas digitales, bloques y minería, verificación independiente y un historial compartido con la mayor prueba de trabajo acumulada. Juntos permiten que la red rechace un segundo gasto sin una autoridad central.](/micrographics/five-part-response-01/es-419.md)


Este módulo explica estos conceptos con más detalle. En conjunto, dieron una respuesta práctica al [problema del doble gasto](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): la red puede rechazar un segundo intento de gastar el mismo bitcoin sin depender de una autoridad central. Bitcoin ofreció la combinación que faltaba y que se había buscado durante décadas de experimentos con dinero digital.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
