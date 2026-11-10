# 4.5 Pagos Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


Lightning puede hacer prácticos los pagos rápidos de pequeñas cantidades en Bitcoin. Puede ser adecuado para el punto de cobro de un comercio, pagos locales recurrentes, servicios en línea o transferencias en las que una comisión en cadena sería demasiado alta en relación con el pago.

Una demostración local de Lightning debe identificar:

* si la billetera es de custodia o de autocustodia
* cómo se agregan fondos a la billetera
* si agregar fondos requiere realizar en cadena una [transacción](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) o usar un servicio
* qué respaldo o método de recuperación protege el saldo
* qué tipo de solicitud de pago se está utilizando
* qué comisiones o límites se aplican
* qué sucede cuando falla un pago
* cómo confirma el pago el destinatario

Una [**factura Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) es una solicitud de pago creada para un pago específico. Puede incluir un monto, información de destino y un plazo de vencimiento. Lea en la billetera la [confirmación](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) que aparece en pantalla antes de pagar.

Una [**dirección Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) es un identificador legible para las personas que algunos servicios admiten. Puede parecer una dirección de correo electrónico, pero es una herramienta que facilita el enrutamiento de pagos, no una cuenta de correo electrónico. Depende del proveedor o del dominio que la admite.

Para un pago guiado:

1. El receptor crea la solicitud correcta.
1. El remitente la escanea o la copia.
1. El remitente verifica el destinatario, el monto, la unidad y la comisión.
1. El remitente aprueba el pago solo después de verificar que los detalles sean correctos.
1. Ambas partes confirman el resultado en sus propias billeteras.
1. El grupo explica los riesgos de [custodia](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) y de fallas.

No suponga que un pago exitoso por Lightning demuestra que la billetera es segura para mantener saldos mayores. La comodidad de los pagos y la [custodia](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) segura son cuestiones distintas.
