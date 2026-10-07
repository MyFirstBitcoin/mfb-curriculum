# 4.5 Pagos con Lightning donde sea adecuado según el contexto local

Lightning puede hacer que los pagos rápidos y pequeños en bitcoin sean prácticos. Puede ser adecuado para pagos en el mostrador de un comercio, pagos locales recurrentes, servicios en línea o transferencias en las que una comisión por transacción en la cadena sería demasiado alta en relación con el pago.

Una demostración local de Lightning debe identificar:

* si la billetera es de custodia o de autocustodia;
* cómo se agregan fondos a la billetera;
* si agregar fondos requiere una transacción en la cadena o un servicio;
* qué mecanismo de respaldo o recuperación protege el saldo;
* qué tipo de solicitud de pago se está usando;
* qué comisiones o límites se aplican;
* qué sucede cuando un pago falla;
* cómo confirma el pago el destinatario.

Una **factura Lightning** es una solicitud de pago creada para un pago específico. Puede incluir un monto, información de destino y un plazo de vencimiento. Lee la pantalla de confirmación de la billetera antes de pagar.

Una **dirección Lightning** es un identificador legible para las personas que algunos servicios admiten. Puede parecer una dirección de correo electrónico, pero es una herramienta que facilita el enrutamiento de pagos, no una cuenta de correo electrónico. Depende del proveedor o dominio que la respalda.

Para un pago guiado:

1. El destinatario crea la solicitud correcta.
1. El remitente la escanea o la copia.
1. El remitente verifica el destinatario, el monto, la unidad y la comisión.
1. El remitente aprueba el pago solo después de verificar que los datos sean correctos.
1. Ambas partes confirman el resultado en sus propias billeteras.
1. El grupo explica los riesgos de custodia y de fallas.

No supongas que un pago exitoso por Lightning demuestra que la billetera es segura para mantener saldos mayores. La facilidad de pago y la seguridad de la custodia son cuestiones distintas.
