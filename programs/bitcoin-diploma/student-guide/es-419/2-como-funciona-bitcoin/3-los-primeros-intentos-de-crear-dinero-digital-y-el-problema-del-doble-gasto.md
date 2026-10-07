# 2.3 Los primeros intentos de crear dinero digital y el problema del doble gasto

Bitcoin no fue el primer intento de crear dinero digital. Se construyó sobre cuatro décadas de experimentación, retomando ideas de muchos proyectos anteriores que ayudaron a dar forma a su exitoso diseño.

**DigiCash** utilizaba criptografía para permitir pagos digitales privados. Dependía de una empresa central y de relaciones con bancos. Cuando la empresa quebró, el sistema no pudo continuar como una red monetaria independiente.

**Hashcash** utilizaba la prueba de trabajo para hacer costoso el envío de correos electrónicos no deseados. La computadora del remitente tenía que realizar trabajo antes de enviar un mensaje. La idea demostró cómo el costo computacional podía desalentar el abuso.

**Bit Gold** describía un sistema propuesto en el que el trabajo computacional podía crear registros digitales escasos. No se lanzó como un sistema completo de dinero descentralizado, pero desarrolló ideas importantes sobre la escasez digital y la prueba de trabajo.

**B-money** y **la prueba de trabajo reutilizable** exploraron formas en que los participantes pudieran crear o transferir valor digital escaso sin depender únicamente de una base de datos central. Eran propuestas incompletas, pero ayudaron a aclarar qué necesitaría un sistema funcional.

**BitTorrent** no era dinero. Demostró que una red entre pares podía permitir que muchas computadoras independientes compartieran información sin que un servidor central controlara todo el sistema.

En conjunto, estos experimentos aportaron piezas útiles del rompecabezas. También ayudaron a aclarar el problema que aún quedaba por resolver.

El problema central era **el doble gasto**. Un billete no se puede entregar a dos personas al mismo tiempo. Sin embargo, los datos digitales se pueden copiar de manera idéntica. Un usuario deshonesto podría intentar enviar la misma unidad digital a dos destinatarios.

Los sistemas centralizados evitan esto al dejar que una única base de datos confiable decida qué pago se realizó primero. El 31 de octubre de 2008, el documento técnico de Satoshi Nakamoto, _Bitcoin: un sistema de efectivo electrónico entre pares_, explicó un enfoque diferente: un sistema público que pudiera establecer un historial compartido de pagos sin un banco, una empresa u otra autoridad central.

El documento técnico reunió las características necesarias para ese enfoque:

1. **Una red entre pares:** las transacciones se anuncian directamente a una red de participantes.
1. **Firmas digitales:** solo quien posee la clave privada correspondiente puede autorizar un gasto.
1. **Bloques y minería:** los mineros agrupan las transacciones en bloques y utilizan la prueba de trabajo para competir por agregar el siguiente bloque.
1. **Verificación independiente:** los nodos verifican que las transacciones y los bloques cumplan con las reglas de Bitcoin.
1. **Un historial compartido con prueba de trabajo acumulada:** los participantes reconocen como registro compartido la cadena válida de transacciones con la mayor cantidad de trabajo acumulado.

Este módulo explica estos conceptos con más detalle. En conjunto, dieron una respuesta práctica al problema del doble gasto: la red puede rechazar un segundo intento de gastar el mismo bitcoin sin depender de una autoridad central. Bitcoin ofreció la combinación que faltaba y que se había buscado durante décadas de experimentación con dinero digital.
