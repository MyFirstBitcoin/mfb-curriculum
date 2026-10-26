# 3.14 Pagos en cadena y mediante Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Pagos en cadena y por Lightning**
>
> [Los pagos en cadena](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) se registran en Bitcoin, en su [cadena de bloques](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) y reciben [confirmaciones](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning es una red de pagos construida sobre Bitcoin que permite realizar pagos rápidos y frecuentes. Un pago por Lightning puede completarse rápidamente o fallar, y la billetera utilizada puede ser de custodia o de autocustodia.



> **Dark – La vía de pago no determina la custodia**
>
> Los pagos en cadena y por Lightning implican distintos [compromisos entre ventajas y desventajas](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Una billetera Lightning puede ser de custodia o de autocustodia, y un pago rápido y exitoso no demuestra que un servicio sea adecuado para saldos mayores o para cualquier situación.



<!-- micrographic: onchain-lightning-table-01 -->


¿Qué vía de pago espera el destinatario? Confirme si le ha proporcionado una dirección en cadena o una [factura Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) o solicitud antes de pagar. Una billetera en cadena no puede pagar directamente cualquier [factura Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), y una billetera Lightning puede no admitir todas las operaciones en cadena. Algunas aplicaciones admiten ambas vías, pero pueden añadir comisiones o dependencias de otros servicios. La configuración detallada de Lightning, los canales, el enrutamiento y la [liquidez](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) son temas de [Aprendizaje avanzado](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); la práctica presencial en el entorno local corresponde al **Módulo 4** cuando sea seguro y apropiado.

Imagine que un escenario preparado ofrece ambas vías de pago. ¿Qué solicitud puede utilizar la billetera prevista y qué verificaría usted antes de aprobarla? La respuesta depende de la solicitud de cobro, de la billetera y de la situación, y no de una vía universalmente «mejor».

![El educador señala dos vías de pago geométricas diferentes en una pizarra mientras los estudiantes principiantes y los de perfil técnico las analizan.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
