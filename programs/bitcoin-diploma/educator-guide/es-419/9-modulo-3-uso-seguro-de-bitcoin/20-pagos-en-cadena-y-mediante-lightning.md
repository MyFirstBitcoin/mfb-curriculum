# 9.20 Pagos en cadena y mediante Lightning

Use una comparación que distinga la vía de pago de la [custodia](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody).


| Pregunta | En cadena | Lightning |
| --- | --- | --- |
| ¿Dónde se registra la liquidación? | Directamente en la cadena de bloques de Bitcoin | Las actualizaciones de los pagos ocurren a través de una red construida sobre Bitcoin; los canales dependen, en última instancia, de Bitcoin |
| Información habitual para recibir pagos que usan los principiantes | Dirección en cadena | Factura, dirección Lightning compatible u otro tipo de solicitud aprobado |
| Uso típico | Liquidación en la capa base, a menudo para transferencias de mayor monto o menos frecuentes | A menudo para pagos pequeños o frecuentes, donde las herramientas locales y la liquidez los permiten |
| Tiempo | La primera confirmación depende de la inclusión en un bloque | A menudo es rápido, pero los pagos pueden fallar |
| Comisiones y capacidad | Dependen de los datos de la transacción y de la demanda de espacio en los bloques | Dependen de la billetera, la ruta, la liquidez, el servicio y las condiciones del pago |
| Custodia | Puede ser con custodia o con autocustodia | Puede ser con custodia o con autocustodia |
| Verificación principal para principiantes | Dirección, red, monto, comisión y confirmación correctos | Factura o destino, monto, vencimiento, comisión y resultado del pago correctos |


Lightning no es una moneda distinta. Un pago exitoso por Lightning no demuestra que la billetera sea segura para mantener un saldo mayor. La operación de los canales, la infraestructura de enrutamiento, así como la [liquidez](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) y su gestión son temas de [Aprendizaje avanzado](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/) que quedan fuera del Diplomado en Bitcoin.


<!-- micrographic: on-chain-and-lightning-01 -->
