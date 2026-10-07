# 3.14 Pagos en cadena y en Lightning

Bitcoin tiene más de una vía de pago. **Los pagos en cadena** se registran en la cadena de bloques de Bitcoin y acumulan confirmaciones. **Lightning** es una red de pagos construida sobre Bitcoin que permite realizar pagos rápidos y frecuentes. Un pago por Lightning puede completarse rápidamente o fallar, y la billetera utilizada puede ser de custodia o de autocustodia.


| Pregunta | Bitcoin en cadena | Lightning |
| --- | --- | --- |
| Información para recibir pagos | Dirección de Bitcoin o solicitud de pago en cadena | Factura, oferta o dirección de Lightning compatible |
| Resultado del pago | Primero se transmite a la red y luego recibe confirmaciones | Por lo general, se completa o falla rápidamente |
| Uso común | Liquidación en la capa base o transferencia menos frecuente | Pago rápido, de menor monto o frecuente |
| Verificaciones para principiantes | Dirección correcta, red, monto, comisión y estado de confirmación | Factura o solicitud correcta, monto, vencimiento, tipo de custodia y resultado del pago |


¿Qué vía de pago espera usar el destinatario? Antes de pagar, confirma si te proporcionó una dirección en cadena o una factura o solicitud de Lightning. Una billetera en cadena no puede pagar directamente cualquier factura de Lightning, y una billetera Lightning puede no admitir todas las operaciones en cadena. Algunas aplicaciones admiten ambas vías, pero pueden agregar comisiones o depender de servicios adicionales. La configuración detallada de Lightning, los canales, el enrutamiento y la liquidez son temas de nivel avanzado; la práctica local en vivo corresponde al Módulo 4, cuando sea segura y apropiada.

Imagina que un escenario preparado ofrece ambas vías de pago. ¿Qué solicitud puede usar la billetera prevista y qué revisarías antes de aprobar el pago? La respuesta depende de la solicitud de pago del destinatario, de la billetera y de la situación, no de una vía que sea la “mejor” en todos los casos.
