=============
Iniciar
=============
Para empezar a procesar pagos a través de 4Geeks Payments debes 
`crear una cuenta <http://dashboard.payments.4geeks.io/accounts/register>`_, lo que entregará
las credenciales de acceso API KEYS en ambiente de pruebas, para que simules transacciones y todas las funciones del API
como si fuese real. 

Al crear la cuenta, también tendrás acceso al Panel de Administración; ésto te permitirá ver todos los datos 
de tus transacciones de forma interactiva, con gráficos y otros recursos.

Negocios permitidos
----------------------------

Estamos dispuestos a apoyar a la mayor cantidad de negocios posibles, sin embargo se debe de cumplir con ciertos requisitos que el departamento legal revisará minuciosamente. 

Cualquier negocio puede crear una cuenta, y automáticamente obtendrá crendenciales de prueba. Sin embargo, debe presentar documentación que garantice su legalidad y correcto funcionamiento bajo las leyes del país.

.. note::
  Un negocio puede ser representado por persona física o persona jurídica.
  
La documentación que te solicitaremos puede variar, sin embargo en este `video <https://youtu.be/NAZUyIrFdoc>`_ encontrarás los requisitos básicos siendo una persona jurídica o personas fisica.

Algunos negocios que no podemos soportar:

* Donaciones.
* Loteria y juegos online.
* Venta de fármacos, medicinas.
* Venta de alimentos.
* Envío de dinero

Cabe que posibilidad que no podemos soportar tu negocio, inclusive si no está listado arriba.
  

Disponibilidad del servicio
---------------------------
4Geeks Payments está disponible únicamente para negocios basados en Costa Rica. Estamos trabajando para permitir nuevas regiones pronto. Síguenos en Facebook para conocer detalles de próximas regiones.

Monedas y marcas de tarjeta
---------------------------
Puedes procesar Visa, MasterCard y AMEX, emitidas en cualquier país. 
Las monedas en las que puedes procesr montos es colones costarricenses y dólares estadounidense. Sin embargo, con AMEX sólo es permitido procesar en dólares estadounidenses.

Credenciales de acceso
-----------------------
Por defecto, a cada nueva cuenta se le entregarán credenciales de acceso (`client_secret` y `client_id`) al modo de prueba, con el fin de que cada desarrollador pueda asegurarse que el flujo de negocio corre según lo espera. En este modo puedes usar las `tarjetas de prueba <http://docs.payments.4geeks.io/#testing-cards>`_, que proveemos.

Para procesar tarjetas reales de clientes reales, debes enviar una `solicitud <https://dashboard.payments.4geeks.io/request-live/>`_. Te solicitaremos algunos documentos requeridos que prueben la validez de tu empresa.

Precio
-------
El modelo en que 4Geeks Payments cobra es mediante una comisión pequeña por transacción de 5.5% + $0.30 USD por cada transacción satisfactoria. No hay mensualidades, ni cobros por configurar una cuenta, ni cargos ocultos.

.. note::
  Si procesas una alta cantidad de transacciones mensuales, talvez te gustaría saber acerca de los descuentos por volumen.
  Escríbenos a payments@4geeks.io y te damos más detalles.

Payouts
-------
Los payouts o pagos corresponde al monto cargado a tus clientes, lo recibirás cada viernes recibirás, automátiacmente en tu cuenta bancaria en cualquier banco de Costa Rica. El corte del pago corresponderá a la semana anterior.

Podrás llevar un control detallado de cada payout desde Saldo, en el Panel de Administrador. Tal como las transacciones que ya fueron pagadas y las que no. En cuanto a las transacciones pagadas, podrás obtener el número de referencia bancaria.

Según tu banco, es posible que incurras en atrasos. Cuando detectes un atraso en un pago, por favor comunícate directamente con tu banco.

No incurrirás en comisiones extra por concepto de envío de dinero a tu cuenta bancaria. En Costa Rica pagamos en dólares estadounidenses y colones costarricenses.

Integración
-----------
4Geeks Payments viene con las herramientas necesarias para integrarlo a cualquier sistema informático, ya se web o móvil. Estas herramientas son creadas en su mayoria por la comunidad abierta de desarrolladores, pero estrictamente valoradas por los ingenieros de 4Geeks.

Mira la sección `Librerías cliente <http://gpayments-support.readthedocs.io/en/latest/libreria.html>`_ para conocer más.
