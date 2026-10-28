# 10.9 Lista de verificación del módulo de Lightning

Antes de un taller de Lightning, verifique y explique:

* si la billetera es de custodia o de autocustodia
* cómo se le agregan fondos
* si agregar o retirar fondos requiere una transacción en cadena o un servicio
* la recuperación y la continuidad si el proveedor o el dispositivo falla
* si la solicitud es una factura, si admite una [dirección Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address), o si es de otro tipo
* monto, unidad, destinatario, vencimiento, comisión, límites y [liquidez](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) a considerar
* cómo se muestran los estados de éxito, pendiente, vencimiento o falla
* cómo ambas partes confirman el resultado de forma independiente; y
* la simulación sin conexión.


<!-- card: dark -->
> **Un pago exitoso por Lightning solo demuestra que esta ruta funcionó una vez**
>
> No demuestra que la billetera sea segura para mantener saldos mayores ni que la misma ruta funcione en todos los lugares.



<!-- micrographic: lightning-payment-sequence-01 -->
[Un pago Lightning en seis pasos: el destinatario crea una solicitud, el remitente la escanea, revisa el destinatario, el monto, la unidad, el vencimiento y la comisión, aprueba el pago, el pago se enruta y ambas billeteras muestran el resultado. Cada billetera puede ser de custodia o de autocustodia, y un pago fallido o vencido se inicia de nuevo con una nueva solicitud.](/micrographics/lightning-payment-sequence-01/es-419.md)
