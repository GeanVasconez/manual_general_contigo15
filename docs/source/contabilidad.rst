Contabilidad
===============

.. image:: /_static/images/7/modulocontabilidad.png
    :align: center

Clientes
---------
Facturas/Clientes
^^^^^^^^^^^^^^^^^^^^^^
Seleccionar el módulo de **Contabilidad**, dirigirse al menú de **Clientes** y buscar
la opción **Facturas.**

Una factura es un documento de carácter mercantil que indica una
compraventa de un bien o servicio y que, entre otras cosas, debe incluir
toda la información de la operación. Al momento de seleccionar la
pestaña, el sistema permitirá crear facturas, eliminarlas, etc.

.. image:: /_static/images/7/crearfacturasclientes.png
    :align: center
    :class: bordered-img

Se procede a llenar los campos obligatorios (campos de color
azul), se selecciona al cliente, se llena la fecha de la factura; en el
caso de la fecha de vencimiento, se puede establecer utilizando una
fecha específica o un término; luego se selecciona el tipo de descuento
(Porcentaje o Cantidad), en el caso que se quiera realizar un descuento
a todos los productos de la factura, se procede a llenar el campo de
descuento global y se aplicará dicho descuento a los productos
ingresados.

.. image:: /_static/images/7/detallefactura.png
    :align: center

Las líneas de factura, sirven para agregar los
productos a la factura, para agregar un producto dar clic en **Agregar
línea**, automáticamente se puede seleccionar un producto que esté en el
sistema y al momento de añadirlo en la línea se cargarán por defecto los
datos del producto como la descripción, el tipo de cuenta (se puede
seleccionar otro tipo si se desea), el impuesto que por defecto es IVA
12% o código 401, el precio dependerá del producto (para más información
revisar **Productos**), en el caso que un producto tenga un descuento
específico, se lo puede añadir en la línea, indica la cantidad de dicho
producto y el subtotal dependerá del resultado de: cantidad \* precio
del producto - descuento + impuestos.

.. image:: /_static/images/7/calculosfacturas.png
    :alt: Calculos de Facturas
    :align: center

Al momento de completar las líneas de factura, el sistema le mostrará
los cálculos realizados para la obtención del total a cobrar.

Por defecto la forma de pago se genera automáticamente como “Sin
utilización del sistema financiero”, si desea especificar otra forma de
pago, deberá escoger manualmente.

.. image:: /_static/images/7/formadepago.png
    :align: center

Si se desea ingresar algún tipo de dato adicional, se lo podrá realizar
en la parte de “Información Adicional”, para agregar un dato adicional
dar clic en agregar línea y llenar el campo nombre y el campo
descripción.

.. image:: /_static/images/7/infoadicional.png
    :align: center

La factura se rige por los siguientes estados: **Borrador** y
**Publicado**

.. image:: /_static/images/7/estadosfacturas.png
    :align: center

Para cambiar el estado de la factura, se debe hacer lo siguiente: Se
debe dirigir a la esquina superior izquierda, donde se encontrará con
los siguientes botones.

.. image:: /_static/images/7/botonesfacturas.png
    :align: center

**Confirmar:** Permite cambiar el estado a Publicado, al momento de que la factura esté en este estado no
se podrá realizar ediciones en las líneas de factura y mostrará una
serie de opciones que serán detalladas a continuación:

.. image:: /_static/images/7/facturapublicada.png
    :align: center

**Generar Edoc:** Al momento de dar clic en esta opción se generará el
documento electrónico de la factura. (imagenporinsertar)

**Ride:** Al dar click aparecerá el documento factura completa.

.. image:: /_static/images/7/generaride.png
    :align: center

**Enviar e imprimir:** Esta opción visualizará el documento ya procesado
dentro del sistema para enviar e imprimir.

**Vista Previa:** Este botón muestra en pantalla cómo se verá la
factura, podremos descargar dicha previsualización en formato PDF o
enviarla a imprimir. Para poder previsualizar la factura se deberá tener
llenos los siguientes campos: Fecha de la factura, RUC del cliente,
secuencia interna de la factura, tipo de comprobante y la forma de pago.

.. image:: /_static/images/7/vistapreviafactura.png
    :align: center

**Añadir nota de crédito:** Esta opción le permite crear notas de crédito de
forma rápida y sencilla. Se recomienda utilizar este método al ingresar
facturas al sistema, ya que optimiza el tiempo dentro del proceso de
creación de notas de crédito. El proceso es fácil. Seleccione el método
de crédito y la fecha de cancelación.

.. image:: /_static/images/7/añadirnotadecredito.png
    :align: center

**Crear nota de débito:** Esta opción le permite crear debito de forma
rápida y sencilla. Se recomienda utilizar este método al ingresar en el
sistema, ya que optimiza el tiempo dentro del proceso de creación de
notas de débito. El proceso es fácil. Seleccione el método de débito y
la fecha de la nota de débito.

.. image:: /_static/images/7/crearnotadedebito.png
    :align: center


**Agregar Retención:** Para añadir una retención a la factura, se debe
dar clic en esta opción, se llenan los campos obligatorios como el
número de documento, la fecha, periodo fiscal, el número de
autorización, el diario, cliente y el detalle de la retención.

.. image:: /_static/images/7/agregarretencion.png
    :align: center

.. image:: /_static/images/7/borradorretenciones.png
    :align: center

Al momento de guardar la retención, se generará un pago
pendiente el cual mostrará en los valores totales de la factura un ítem
llamado “créditos pendientes”, dicho ítem nos mostrará todos los valores
de pago pendientes y se dará la opción de añadir dicho pago al monto
total de la factura; en el caso de que se le añada el pago, el monto
total de la factura se sumará con el valor pendiente dando como
resultado un monto total diferente.

.. image:: /_static/images/7/montototalfactura.png
    :align: center

**Anular Facturas:** Permite la anulación de la factura enviando la
misma a un estado adicional llamado Anulado, dicho estado sólo aparecerá
si se anuló la factura.

.. image:: /_static/images/7/anularfacturas.png
    :align: center

.. image:: /_static/images/7/vistaanulado.png
    :align: center

Cuando la factura está en este estado, solo mostrará los siguientes
botones: “Generar Edoc”, “Ride”, “ Vista Previa” y “Restablecer a
Borrador”.
Si se desea reactivar dicha factura se debe hacer clic en “Restablecer a
borrador”, en ese momento el sistema cambiará de estado anulado a
borrador, es el mismo estado que tienen las facturas al momento de
recién creadas; luego se procederá a modificar los datos existentes y
después se valida cuando esté completada.

.. image:: /_static/images/7/vistaanulado.png
    :align: center

Se añadirá a nuestras facturas creadas los términos y condiciones en la
sección final del documento, solo se podrá editar dicho término si la
factura se encuentra en estado de borrador.

.. image:: /_static/images/7/terminosycondiciones.png
    :align: center

**Compartir:** Esta acción se permitirá enviar el documento a uno o más
de los destinatarios designados, dichos destinatarios deben tener
definido el correo en su perfil de contacto.Compartir: Esta acción se
permitirá enviar el documento a uno o más de los destinatarios
designados, dichos destinatarios deben tener definido el correo en su
perfil de contacto.

.. image:: /_static/images/7/accionesfcts.png
    :align: center

.. image:: /_static/images/7/compartirdocumento.png
    :align: center

Notas de Credito
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de Contabilidad, seleccionar el menú Clientes y luego la
opción Notas de Crédito. Una nota de crédito es un documento legal que
se utiliza en transacciones de compraventa donde interviene un descuento
posterior a la emisión de la factura, una anulación total, un cobro de
un gasto incurrido de más o la devolución de bienes. Para la correcta
creación de una nota de crédito, es recomendable realizarla a través de
la factura (para más información revisar “Factura Clientes”). El sistema
permitirá la edición del documento, al momento de editarlo es necesario
llenar los campos obligatorios que existen en el mismo, la vista que
proyectará el sistema es casi idéntica a la factura con la diferencia
que se debe especificar el número de documento tributario para poder
generar la nota; también es idéntica a la de nota de débito. La nota de
crédito podremos validarla, previsualizarla, cancelarla, registrar
pagos, etc.

.. image:: /_static/images/7/vistanotasdecreditos.png
    :align: center

.. image:: /_static/images/7/notadecreditocreada.png
    :align: center

.. image:: /_static/images/7/detallenotadecredito.png
    :align: center

.. image:: /_static/images/7/formadepagonotacredito.png
    :align: center

Se sabe que es una nota de crédito porque en la pestaña “Otra
Información” existe el “Tipo de comprobante” que indica “Nota de
Crédito”.

.. image:: /_static/images/7/otrainfonotacredito.png
    :align: center

Entre otras se encontrara lo que es el botón de **“imprimir”:**

.. image:: /_static/images/7/btnimprimir.png
    :align: center

**Facturas:** La factura es un documento que indicará una compraventa de
un producto que se ha registrado en la compra.

.. image:: /_static/images/7/facturanotadecredito.png
    :align: center

Se presenta un boton de **acciones**:

.. image:: /_static/images/7/accionesnotadecredito.png
    :align: center

**Duplicar:** Duplica la información de la nota de crédito ya creada en
el sistema.

**Suprimir:** Se eliminará el documento dentro de la nota de crédito.

**Generar un enlace de pago:** Los enlaces de pago no son más que una
url que podemos enviar al cliente a través de cualquier medio y al
clicar en él, el consumidor accede directamente a la página final de
pago de nuestro producto o servicio.

.. image:: /_static/images/7/enlacedepago.png
    :align: center

**Compartir:** Consiste en un enlace o URL único o abierto, que se
genera para cada compra y que puedes compartir con tu cliente a través
de diferentes canales como correo electrónico, mensajes de texto, entre
otros.

.. image:: /_static/images/7/compartirnotadecredito.png
    :align: center

**Cambiar a reembolso/nota de crédito:**

.. image:: /_static/images/7/cambiar_a_reembolso.png
    :align: center

Facturas de Reembolso de Gastos
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar el menú **Clientes** y
luego la opción **Facturas de Reembolso de Gastos.**

Las facturas de reembolso de gastos son deducibles del Impuesto a la
Renta y, el IVA pagado, constituye crédito tributario.

Para solicitar el reembolso, el intermediario deberá emitir una factura
con el concepto de reembolso de gastos, en la cual se detallarán los
comprobantes de venta con el motivo del reembolso.

Además, quien solicita el reembolso debe adjuntar los originales de los
comprobantes por los que se pide el reembolso. Los comprobantes de venta
deben estar a nombre del intermediario. Esta factura por reembolso no
está sujeta a retenciones en la fuente de Impuesto a la Renta ni de IVA.

En el caso de que el intermediario del reembolso sea un empleado en
relación de dependencia con la empresa, éste podrá emitir una
liquidación de compra de bienes y prestación de servicios en sustitución
de la factura por el reembolso.

.. image:: /_static/images/7/facturarembolsos.png
    :align: center

.. image:: /_static/images/7/lineafacturareembolsos.png
    :align: center

.. image:: /_static/images/7/formadepagoreembolsos.png
    :align: center

Notas de Débito
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar en el menú **Clientes** la
opción **Notas de Débito.**

La nota de débito es un documento que se le enviará al comprador o
cliente para avisarle que ha aumentado la cantidad de su deuda por algún
motivo. Con este documento se le avisará que se le ha cargado, o que
debe una cantidad de dinero por el concepto que se especifica en la
nota. Al contrario que la nota de crédito es la notificación a un
comprador de que se le debe cobrar más dinero.

El sistema permitirá la edición del documento; al momento de editarlo es
necesario llenar los campos obligatorios que existen en el mismo, la
vista que proyectará el sistema es casi idéntica a la factura con la
diferencia que se debe especificar el número de documento tributario que
se generará en la nota; también es idéntica a la de nota de crédito. La
nota de débito se podrá validar, previsualizar, cancelarla, registrar
pagos, etc.

.. image:: /_static/images/7/borradornotadedebito.png
    :align: center

.. image:: /_static/images/7/formadepagonotadedebito.png
    :align: center

Sabemos que es una nota de crédito porque en la pestaña “Otra
Información” existe el “Tipo de comprobante” que indica “Nota de
Débito”.

.. image:: /_static/images/7/otrainfonotadedebito.png
    :align: center

Retenciones Ventas
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar el menú **Clientes** y la
opción **Retención Ventas.**

La retención es la cantidad que se retiene de un sueldo, salario u otra
percepción para el pago de un impuesto, de deudas en virtud de embargo,
es decir, te retienen ahora para asegurar el pago del impuesto. Para la
correcta creación de una retención ventas, es recomendable realizarla a
través de la factura (para más información revisar Factura Clientes).

Al momento de editar una retención de venta, se deben llenar los campos
obligatorios, el número de la retención, la empresa, el documento de
origen, el número de autorización, la fecha de vencimiento de dicha
autorización, el diario, el comprobante, la fecha de emisión y el
responsable de dicha retención.

**Detalle de retención:** Llenar el año fiscal y el impuesto ya sea IVA
o RENTA; la base del impuesto se llenará de manera automática, el valor
porcentual y el valor retenido.

**Información Extra:** Seleccionar el tipo de comprobante. En la esquina
superior izquierda, debajo de la opción Guardar nos aparecerá una barra
para poder Validar .

.. image:: /_static/images/7/retencionesventas.png
    :align: center

.. image:: /_static/images/7/detalleretencionventas.png
    :align: center

Detalle de Retención en Ventas
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar en el menú la opción
**Detalle de Retención Ventas.** Como su propio nombre lo indica,
muestra todas las retenciones en ventas de los clientes a una vista
sencilla.

.. image:: /_static/images/7/vistadetalleretencionventa.png
    :align: center

Pagos
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar el menú **Clientes** y
luego la opción **Pagos.**

Un pago es lo que una persona o entidad realiza para poder cancelar o
suprimir una obligación que se tenía contraída. El pago puede efectuarse
mediante la entrega de un bien, servicio o activo financiero a cambio de
otro bien, servicio o activo financiero.

Se recomienda realizar los pagos a través de las opciones que se dará
las facturas, notas de crédito y notas de débito dentro del sistema de
contigo.

**Seleccionar el tipo de pago:** “Enviar dinero”, “Recibir dinero” o
“Transferencia interna”; llenar la fecha de pago, la circular de este,
la fecha del depósito, el tipo de empresa (que por defecto está en
seleccionado cliente), la empresa y la cantidad. Por último, el sistema
permite ingresar las líneas de contrapartida.

También el sistema permitirá imprimir el recibo de pago, el comprobante
de pago y el cheque este último siempre y cuando el pago sea en cheques.

.. image:: /_static/images/7/editarpagos.png
    :align: center

.. image:: /_static/images/7/vistapagos.png
    :align: center

En el momento de seleccionar al cliente, si existen
pagos pendientes el sistema de manera automática nos mostrará el número
de pagos pendientes y la cantidad de estos.

.. image:: /_static/images/7/movpendientrescruce.png
    :align: center

En el caso de que se desee cancelar el asiento para volver a realizarlo,
es necesario configurar el diario para que permita la cancelación de
pagos (para más información dirigirse a Diarios).

.. image:: /_static/images/7/cancelarasientoerror.png
    :align: center

Al momento de realizar un pago en cheque es necesario primero configurar
la chequera en el sistema (para más información revisar **Chequeras** ),
la opción de cheques sólo aparecerá si el pago es **enviar dinero** o
una **transferencia interna** y se selecciona la opción de cheques.

Se procederá a llenar el punto de emisión correspondiente, la ciudad y
la fecha del depósito, si se deja la fecha de depósito en blanco el
sistema utilizará la fecha de pago como fecha de depósito.

.. image:: /_static/images/7/pagosborrador.png
    :align: center

Imprimir: El sistema nos permitirá realizar los siguientes reportes
,“recibo de pago”, “cheque”.

.. image:: /_static/images/7/btnimprimirnd.png
    :align: center

.. image:: /_static/images/7/opcimprimirpagos.png
    :align: center

.. image:: /_static/images/7/recibopagopdf.png
    :align: center

**Acciones:** La opción de pagos cuenta con las opciones duplicar,
suprimir y enviar recibo por correo electrónico.

.. image:: /_static/images/7/accionespago.png
    :align: center

En la parte superior encontraremos dos botones:

.. image:: /_static/images/7/botonespagos.png
    :align: center

**Factura:**

.. image:: /_static/images/7/facturaenpagos.png
    :align: center

.. image:: /_static/images/7/detallefacturaenpagos.png
    :align: center

**Asiento contables:**

.. image:: /_static/images/7/asientoscontablespagos.png
    :align: center

.. note::

    En el caso de que se necesite crear un pago con múltiples
    facturas, primero se debe visualizar que las facturas estén en estado
    Abierto.

Se seleccionan las facturas del mismo cliente, por consiguiente, se debe
dirigir en la opción Acción y seleccionar Registrar Pago.

.. image:: /_static/images/7/accionregistropago.png
    :align: center

Después de dar clic en la opción Registrar Pago, se debe llenar el
formulario seleccionando la cantidad, el diario de pago, la fecha del
pago y seleccionar en la opción grupo de facturas; al finalizar dar clic
en el botón Validar.

.. image:: /_static/images/7/registrarpago.png
    :align: center

Para terminar de registrar el pago, se debe editar el nuevo formulario
que el sistema mostrar, que es el mismo formulario de pagos, pero con la
diferencia que es un pago de múltiples facturas.

.. image:: /_static/images/7/llenarfacturaenpagos.png
    :align: center

.. image:: /_static/images/7/facturaapartirdepagos.png
    :align: center

Vehìculo
^^^^^^^^^^^^^^^^^^^^^^

Estos campos son útiles para llevar un registro organizado de los
vehículos y sus propietarios, así como para proporcionar una forma de
identificar y comunicarse con las personas asociadas con los vehículos
en caso de necesidad.

.. image:: /_static/images/7/vehiculos.png
    :align: center

Guías de Remisión
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de Contabilidad, seleccionar en el menú Clientes la opción
Guías de Remisión.

Este documento sirve para sustentar el traslado de mercaderías dentro de
la nación. De esta forma habrá constancia de que es un traslado legal.
La función de este documento es identificar actividades que se puedan
estar realizando fuera del marco legal y además tener un control
tributario, que garantice que no se evadan los tributos.

Al momento de generar una nueva guía se debe:

- Configurar primero el punto de emisión (ver Punto de Emisión), seleccionar el transportista (ver Contactos), el destinatario (ver Contactos) y la factura (ver Factura en el menú de Clientes).
- Se llenarán todos los campos obligatorios y los que se considere necesario llenar.
- Al momento de seleccionar el destinatario automáticamente se cargarán los datos de este en las siguientes columnas: Identificación, teléfono, cédula y correo.
- Al momento de seleccionar la factura, automáticamente se cargarán en ítems de guía, los datos de la factura de igual manera en Detalle electrónico.

.. image:: /_static/images/7/borradorguiaderemision.png
    :align: center

.. image:: /_static/images/7/infodestinatarioguiaremision.png
    :align: center

.. image:: /_static/images/7/detalleelectronicoguiaremision.png
    :align: center

Productos
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar en el menú **Clientes** la
opción **Productos.**

Un producto es una opción elegible, viable y repetible que la oferta
pone a disposición de la demanda, para satisfacer una necesidad o
atender un deseo a través de su uso o consumo. La diferencia entre un
producto cliente y un proveedor es que el producto cliente puede ser
vendido.

| Se podrá añadir una imagen o foto que identifica el producto, el
  nombre del producto y si el producto puede ser vendido o puede ser
  comprado.
|

.. image:: /_static/images/7/ejemploproducto.png
    :align: center

En la esquina superior derecha podremos observar tres recuadros: Precio
extra, Entrada y Salida, y Unidades vendidos la primera nos permite ver
todos los movimientos que ha tenido dicho producto en la empresa,
mientras que la segunda nos permite archivar y desarchivar el producto;
en el caso de que se archive este producto no aparecerá en las compras o
ventas hasta que se desarchive.

.. image:: /_static/images/7/botonesproductos.png
    :align: center

**Información General:** Se permitirá ingresar detalles específicos del
producto y también dejará notas para una mejor referencia como el tipo
de producto, referencia interna, código de barras, categoría del
producto (si se desea añadir una nueva categoría, el sistema le
permitirá crearla desde el ítem de selección), el precio de venta,
precio al por mayor, el impuesto a cliente y el costo; también se podrá
añadir una nota interna.

.. image:: /_static/images/7/infogeneralproductos.png
    :align: center


**Compra:** Esta opción sólo aparecerá si está marcado ‘Puede ser
Comprado’ y especificará el número de impuesto del proveedor para
futuras facturas.

.. image:: /_static/images/7/compraproductos.png
    :align: center

**Inventario:** Permitirá ingresar cómo será
la operación y logística de dicho producto, agregar descripción para
pedidos de entrega y recepciones.

.. image:: /_static/images/7/inventarioproductos.png
    :align: center

**Contabilidad:** Permite
seleccionar la cuenta de ingreso (A cobrar) y la cuenta de gastos (A
pagar) de dicho producto.

.. image:: /_static/images/7/contabilidadproductos.png
    :align: center

También el sistema permitirá imprimir en este caso la etiqueta del
producto y el código de barra del producto.

.. image:: /_static/images/7/imprimiretiquetas.png
    :align: center

Clientes
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar en el menú de **Clientes**
la opción **Clientes.**

Automáticamente se abrirá la vista de Clientes que es igual a la vista
de Contactos (para más información dirigirse a Contactos), por defecto
se añadirá un filtro con el nombre de ‘Clientes’. Dicho contacto
aparecerá en la opción de cliente si y sólo si está marcada la opción en
Ventas y Compras el ítem de ‘Es Cliente’.

.. image:: /_static/images/7/contabilidadclientes.png
    :align: center

Proveedores
---------------

.. image:: /_static/images/7/moduloproveedores.png
    :align: center

Facturas/Proveedores
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar en el menú de
**Proveedores** la opción **Facturas.**

Una factura es un documento de carácter mercantil que indicará una
compraventa de un bien o servicio y que, entre otras cosas, debe incluir
toda la información de la operación. Al momento de seleccionar la
pestaña, se permitirá crear facturas, eliminarlas, etc.

.. image:: /_static/images/7/facturaproveedor.png
    :align: center

Se procedera a llenar los campos obligatorios (campos de color azul), es
importante añadir el número de la factura, el número de la autorización,
la fecha de vencimiento de la autorización, el tipo de comprobante que
por defecto es “Factura”, seleccionar el diario correspondiente, el
proveedor, la fecha de la factura; en el caso de la fecha de vencimiento
esta se colocará automáticamente dependiendo del plazo de pago (en este
caso el plazo es de 2 meses, por lo tanto, del 1 de julio se le suman
esos 2 meses dando como resultado final 30 de agosto); el punto de
emisión que se encuentra en la vista corresponde solamente a las
retenciones que se realizarán en las facturas agregadas y el digito
cambiará según la secuencia establecida.

.. image:: /_static/images/7/detallefactproveedor.png
    :align: center

Las líneas de factura, sirven para agregar los productos a la factura, para agregar un
producto dar clic en “Agregar línea”, automáticamente puedes seleccionar
un producto que esté en el sistema y al momento de añadirlo en la línea
se cargarán por defecto los datos del producto como la descripción del
mismo, el tipo de cuenta (se puede seleccionar otro tipo si se desea),
el impuesto (que por defecto es IVA 12% o código 500 si el producto
cuenta con retención); es necesario añadir la línea según el número de
retención aplicado en dicho producto, en este caso el código de la
retención es 303, el precio dependerá del producto (para más información
revisar **Productos**), si en el caso de que un producto tenga un
descuento específico se lo puede añadir en la línea, indicas la cantidad
de dicho producto y el subtotal dependerá de la suma de : cantidad +
precio del producto + descuento + impuestos.

.. image:: /_static/images/7/montototalproveedor.png
    :align: center

En el caso de que la factura exceda los mil dólares, el sistema le
notificará que se debe crear una forma de pago para dicha factura, esta
se encuentra la parte inferior, para ingresar una forma de pago se debe
hacer clic en agregar línea, se selecciona la forma de dicho pago para
esa factura, el total, los plazos y la unidad de tiempo.

.. image:: /_static/images/7/formadepagoproveedor.png
    :align: center

La factura se rige por los siguientes estados: “Borrador”, “Publicado”.

.. image:: /_static/images/7/estadofactproveedor.png
    :align: center

Para cambiar el estado de la factura, se deberá hacer lo siguiente: se
dirige a la esquina superior izquierda, donde nos encontraremos con los
siguientes botones.

.. image:: /_static/images/7/botonestadosproveedor.png
    :align: center

**Confirmar:** Antes de validar la factura del proveedor es necesario
hacer clic en esta opción, ya que nos ayuda a guardar el cálculo de los
impuestos y añade las líneas correspondientes en retenciones.

**Cancelar:** Permitirá suspender el proceso de guardar el registro del
documento.

.. image:: /_static/images/7/cancelarfactproveedor.png
    :align: center

**Imprimir:** Esta opción nos permite realizar el reporte de
la factura realizada.

.. image:: /_static/images/7/imprimirfactproveedor.png
    :align: center

.. image:: /_static/images/7/factproveedorpdf.png
    :align: center


**Registrar pago:** Esta opción permitirá realizar el pago de dicha
factura, al momento de hacer clic en el botón “Registrar pago” se abrirá
una ventana emergente, para completar el pago se deberá llenar los
siguientes campos: la cantidad a pagar que debe ser igual al monto total
de la factura, la fecha de pago, la fecha del depósito, el circular, el
diario de pago que se derivará a tres opciones (Banco, Efectivo y
Retenciones Clientes) y la cuenta contable, aunque este campo sólo
aparecerá si el diario de pago es banco o efectivo. Pero en el caso de
que el diario de pago sea bancos o retenciones clientes, aparecerá en la
vista el tipo de método de pago del cual se podrá seleccionar de manera
manual o cheque.

.. image:: /_static/images/7/registrarpagoproveedor.png
    :align: center

Al momento de registrar el pago tenemos lo que es el campo de cuenta
contable de pago que se dará ayuda indicando a qué cuenta contable se
está dirigiendo la factura, pero en el caso de que el pago de la factura
se derive a diferentes cuentas contables, se tendrá en la parte de abajo
el ítem de líneas de contrapartida, que permitirá agregar dichas cuentas
contables al pago de la factura.

En el caso de que el pago en las líneas de contrapartida no sea igual al
valor total del pago facturado, la diferencia del mismo pago será tomada
por la cuenta contable de pago que se encuentra en la parte superior.

Al momento de guardar la retención, se generará un pago pendiente el
cual mostrará en los valores totales de la factura un ítem llamado
créditos pendientes, dicho ítem que se mostrará todos los valores de
pago pendientes y nos dará la opción de añadir dicho pago al monto total
de la factura, en el caso de que se le añada el pago, el monto total de
la factura se sumará con el valor pendiente dando como resultado un
monto total diferente.

.. image:: /_static/images/7/montototalapagarproveedor.png
    :align: center

**Agregar nota de crédito:** Esta opción permite la creación de notas de
crédito de manera rápida y sencilla, si la factura está ingresada al
sistema es recomendable utilizar este método, ya que permite la
optimización del tiempo dentro del proceso de creación de notas de
crédito. El proceso es simple: se selecciona el método de crédito (en
este caso es el número de la factura) y la fecha de la nota de crédito.

.. image:: /_static/images/7/agregarnotadecreditoproveedor.png
    :align: center

.. image:: /_static/images/7/crearnotadedebitoproveedor.png
    :align: center

**Cancelar:** Permite la cancelación de la factura enviando la misma en
un estado adicional llamado cancelado, dicho estado sólo aparecerá si se
canceló la factura.

.. image:: /_static/images/7/estadocancelarproveedor.png
    :align: center

| Cuando la factura está en este estado, solo mostrará los siguientes
  botones: “Documento Electrónico”, “ Previsualizar” y “Cambiar a
  Borrador”.
| Si se desea reactivar dicha factura se debe hacer clic en “Cambiar a
  borrador”, en ese momento el sistema cambiará de estado cancelado a
  borrador, es el mismo estado que tienen las facturas al momento de
  recién creadas; luego se procede a modificar los datos existentes y
  después de válida cuando esté completada.

.. image:: /_static/images/7/grabardescartarproveedor.png
    :align: center

.. note::

    Cuando la factura se encuentra en los estados “Validado” o
    “Cancelado”, nos mostrará dentro de la vista de la factura los
    siguientes botones.

.. image:: /_static/images/7/botonesfactproveedores.png
    :align: center

La primera opción mostrará las retenciones creadas que correspondan a
dicha factura.

La segunda opción va a aparecer para los clientes que estén usando el
módulo de inventario, sirve para crear un movimiento de inventario para
reducir o aumentar el stock.

**Compartir:** Esta acción nos permite enviar el documento a uno o más
de los destinatarios designados, dichos destinatarios deben tener
registrado su correo electrónico en su perfil de contacto.

.. image:: /_static/images/7/accionesproveedor.png
    :align: center

.. image:: /_static/images/7/compartirdocproveedor.png
    :align: center

**Procesar XML:** Esta opción permitirá procesar datos de un documento
con extensión XML al sistema; primero se debe subir el archivo y después
de que el archivo esté cargado, de manera automática el sistema llenará
los campos con los datos del XML. Si el proveedor no existe, creará de
manera automática los datos de este y los utilizará a la vez en el
documento.

.. image:: /_static/images/7/subirxmlproveedor.png
    :align: center

Notas de Crédito
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar en el menú **Proveedores**
la opción **Notas de Crédito.**

Una nota de crédito es un documento legal que se utiliza en
transacciones de compraventa donde interviene un descuento posterior a
la emisión de la factura, una anulación total, un cobro de un gasto
incurrido de más o la devolución de bienes.

Para la correcta creación de una nota de crédito, es recomendable
realizarla a través de la factura (para más información revisar Factura
Proveedores). El sistema permitirá la edición del documento, al momento
de editarlo es necesario llenar los campos obligatorios que existen en
el mismo, la vista que proyectará el sistema es casi idéntica a la
factura con la diferencia que se debe especificar el número de documento
tributario para poder generar la nota; también es idéntica a la de nota
de débito. La nota de crédito podremos validarla, previsualizarla,
cancelarla, registrar pagos, etc.

.. image:: /_static/images/7/notacreditoproveedor.png
    :align: center

.. image:: /_static/images/7/detallefacturasproveedor.png
    :align: center

.. image:: /_static/images/7/formapagoproveedor.png
    :align: center

Retenciones Compras
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar en el menú **Proveedores**
la opción **Retenciones Compras.**

La retención es la cantidad que se retiene de un sueldo, salario u otra
percepción para el pago de un impuesto, de deudas en virtud de embargo,
es decir, te retienen ahora para asegurar el pago del impuesto. Para la
correcta creación de una retención ventas, es recomendable realizarla a
través de la factura (para más información revisar Factura Proveedores).

Al momento de editar una retención de compra, se deben llenar los campos
obligatorios, como colocar el número de la retención, la empresa, el
documento de origen, el número de autorización, la fecha de vencimiento
de dicha autorización, el diario, el comprobante la fecha de emisión y
el responsable de dicha retención.

**Detalle de retención:** Llenar con el año fiscal, el impuesto ya sea
IVA o RENTA, la base del impuesto se llenará de manera automática, el
valor porcentual y el valor retenido.

**Información Extra:** Seleccionar el tipo de comprobante.

En la esquina superior izquierda, debajo de la opción Guardar nos
aparecerá una barra para poder validar , y generar el documento
electrónico.

.. image:: /_static/images/7/barraretencioncompras.png
    :align: center

.. image:: /_static/images/7/ejemploretencionesencompras.png
    :align: center

.. image:: /_static/images/7/detalleelectronicoretencion.png
    :align: center

Detalle de Retenciones en Compras
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar en el menú **Proveedores**
la opción **Detalle de Retenciones Compras.**

Como su propio nombre lo indica, muestra todas las retenciones en
compras de los proveedores a una vista sencilla.

.. image:: /_static/images/7/detalleretencionencompras.png
    :align: center

Liquidaciones de Compras
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar el menú **Proveedores** y
luego la opción **Liquidaciones de Compras.**

La Liquidación de compra es un comprobante de pago emitido por las
personas naturales o jurídicas, sociedades conyugales, sucesiones
indivisas, sociedades de hecho u otros entes colectivos por las
adquisiciones que efectúen a personas naturales productoras y/o
acopiadoras de productos primarios derivados de la actividad
agropecuaria, pesca artesanal y extracción de madera, de productos
silvestres, minería aurífera artesanal, artesanía, desperdicios y
desechos metálicos, desechos de papel y desperdicios de caucho, siempre
que estas personas no otorguen comprobantes de pago por carecer de
número de RUC.

El sistema permitirá la creación y edición del documento, al momento de
generar una nueva liquidación es necesario llenar los campos
obligatorios que existen en el mismo, la vista que proyectará el sistema
es casi idéntica a la factura con la diferencia que se debe especificar
el tipo de documento, que en este caso será una liquidación de compra,
si se selecciona otro tipo aparecerán unos datos que se deberán llenar;
estos son el número de documento tributario, el número de la
autorización y la fecha del mismo para poder generar el documento. Podrá
validar la liquidación de compra, previsualizar, cancelar, registrar
pagos, generar notas de créditos, etc.

.. image:: /_static/images/7/liquidacioncompras.png
    :align: center

Pagos
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar en el menú **Proveedores**
la opción **Pagos.**

Un pago es lo que una persona o entidad realiza para poder cancelar o
suprimir una obligación que se tenía contraída. El pago puede efectuarse
mediante la entrega de un bien, servicio o activo financiero a cambio de
otro bien, servicio o activo financiero.

Es recomendable realizar los pagos a través de las opciones que dan las
facturas, notas de crédito y notas de débito dentro del sistema de
contigo.

Seleccionar el tipo de pago ya sea enviar dinero, recibir dinero o
transferencia interna; llenar la fecha de pago, la circular de este, la
fecha de depósito, el tipo de empresa que, por defecto está tiene
seleccionado “Cliente”, la empresa y la cantidad.

Por último, el sistema permite ingresar las líneas de contrapartida.

También el sistema permitirá imprimir el recibo de pago, el comprobante
de pago y el cheque, este último siempre y cuando el pago sea en
cheques.

.. image:: /_static/images/7/pagosvistaproveedor.png
    :align: center

.. image:: /_static/images/7/listviewproveedores.png
    :align: center

En el momento de seleccionar al cliente, si existen pagos
pendientes el sistema de manera automática nos mostrará el número de
pagos pendientes y la cantidad de estos.

**Desglose de pago:** Consiste en detallar el gasto total, lo cual
permitirá realizar un seguimiento de los gastos se deberá cancelar la
proporción del impuesto que tuvo vigente de aquel año.

.. image:: /_static/images/7/pagoavanzadoproveedores.png
    :align: center

Para realizar un pago en cheque es necesario primero configurar la
cuenta bancaria y chequera en el sistema (para más información revisar
**Cuentas Bancarias** y **Chequeras** ), la opción de cheques sólo
aparecerá si el pago es **enviar dinero** o una **transferencia
interna** y se selecciona la opción de cheques.

Se procede a llenar el punto de emisión correspondiente, la ciudad y la
fecha del depósito, si se deja la fecha de depósito en blanco el sistema
utilizará la fecha de pago como fecha de depósito.

**Imprimir:** El sistema permitirá realizar los siguientes reportes.

.. image:: /_static/images/7/btnimprimirnd.png
    :align: center

.. image:: /_static/images/7/opcionesimprimirproveedores.png
    :align: center

**Recibo de pago:** El recibo de pago es la transacción realizada donde
se especificará la cantidad que el cliente ha comprado.

.. image:: /_static/images/7/recibodepagoproveedor.png
    :align: center

**Cheque:** Específica en diseño de cuanto es el monto.

.. image:: /_static/images/7/chequeproveedor.png
    :align: center

**Acciones:** La opción de pagos cuenta con las opciones de duplicar,
suprimir y enviar recibo por correo.

.. image:: /_static/images/7/accionespago.png
    :align: center

Productos
^^^^^^^^^^^^^^^^^^^^^^

En el módulo de **Contabilidad**, seleccionar en el menú **Clientes** la
opción **Productos.**

Un producto es una opción elegible, viable y repetible que la oferta
pone a disposición de la demanda, para satisfacer una necesidad o
atender un deseo a través de su uso o consumo. La diferencia entre un
producto cliente y un producto proveedor es que el producto cliente
puede ser vendido.

Se puede añadir una imagen o foto que identifica el producto, el nombre
del producto y si el producto puede ser vendido o puede ser comprado.

.. image:: /_static/images/7/ejemploproductoproveedor.png
    :align: center

En la esquina superior derecha podremos observar 6 recuadros: precios
extra, a mano , previsto, entrada y salida, regla de reabastecer.

.. image:: /_static/images/7/botonesproveedorvista.png
    :align: center

**Información General:** Permitir ingresar detalles específicos del
producto y también dejar notas para una mejor referencia como el tipo de
producto, referencia interna, código de barras, categoría del producto
(si se desea añadir una nueva categoría, el sistema le permitirá crearla
desde el ítem de selección), el precio de venta, precio al por mayor, el
impuesto al cliente y el costo; también se podrá añadir una nota
interna.

.. image:: /_static/images/7/infogeneralproductos.png
    :align: center

**Compra:** Esta opción sólo aparecerá si está marcado ‘Puede ser
Comprado’ y especifica el número de impuesto del proveedor para futuras
facturas.

.. image:: /_static/images/7/apartadocompraproveedor.png
    :align: center

**Inventario:** Nos permite ingresar cómo será la operación y logística
de dicho producto, agregar descripción para pedidos de entrega y
recepciones.

.. image:: /_static/images/7/apartadoinventarioproveedor.png
    :align: center

**Contabilidad:** Permite seleccionar la cuenta de ingreso (A cobrar) y
la cuenta de gastos (A pagar) de dicho producto.

.. image:: /_static/images/7/apartadocontabilidadproveedor.png
    :align: center

También el sistema en la parte superior en las izquierda nos permite
imprimir en este caso la etiqueta del producto , actualización de
cantidad y reabastecer .

.. image:: /_static/images/7/imprimiretiquetasproveedor.png
    :align: center

Proveedores
^^^^^^^^^^^^^^^^^^^^^^

Seleccionar el módulo de **Contabilidad**, dirigirse al menú de
**Proveedores** y buscar la opción **Proveedores.**

Automáticamente se abrirá la vista de Proveedores que es igual a la
vista de Contactos (para más información dirigirse a Contactos), por
defecto se añadirá un filtro con el nombre de ‘Proveedor’. Dicho
contacto aparecerá en la opción de cliente si y sólo si está marcada la
opción en Ventas y Compras el ítem de ‘Es Proveedor’.

.. image:: /_static/images/7/moduloproveedores.png
    :align: center

En la parte superior encontrarás en boton “Accion”:

.. image:: /_static/images/7/btnaccionproveedor.png
    :align: center

**Archivar:** En esta opción al momento de dar click te aparecera si
desea guardar (aceptar o cancelar)

.. image:: /_static/images/7/opcarchivarproveedor.png
    :align: center

**Mandar mensaje de texto SMS:** Permite enviar mensajes de texto tanto
al destinatario .

.. image:: /_static/images/7/opcmandasmsproveedor.png
    :align: center

**Libro mayor:** Permite registrar los datos o movimientos de cuentas
que se han realizado con el cliente.

.. image:: /_static/images/7/opclibromayorproveedor.png
    :align: center

En la parte inferior podrás encontrar los siguientes botones Ver
,Exportar a PDF ,Exportar a XLSX y Cancelar.

**Extracto-Cliente:** Permite realizar registro de forma detallada de
las cuentas con mayor facilidad para el usuario.

.. image:: /_static/images/7/opcextractoclienteproveedor.png
    :align: center

En la parte inferior podrás encontrar los siguientes botones Ver
,Exportar a PDF ,Exportar a XLSX y Cancelar.

**Otorgar acceso al portal:** Permite seleccionar los contactos dentro
del sistema ya registrada el contacto, correo electrónico,etc. Y luego
de terminar de llenar correctamente se podrá dar acceso al portal.

.. image:: /_static/images/7/accesoalportalproveedor.png
    :align: center


Contabilidad
------------

Documentos Electrónicos / Carga de Documentos Electrónicos
^^^^^^^^^^^^^^^^^^^^^^

Nos dirigimos al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Documentos Electrónicos** la opción
**Carga de Documentos Electrónicos.**

Esta opción permite generar los diferentes documentos electrónicos que
hayan emitido.

.. image:: /_static/images/7/cargadocelectronico.png
    :align: center

1) Dirigirse al SRI y descargar el archivo de documento a cargarse.

.. image:: /_static/images/7/documentosriacargar.png
    :align: center

2) Cargar dicho archivo (Subir Archivo) y dar clic en Cargar.

.. image:: /_static/images/7/cargareldocelectronico.png
    :align: center

3) Los documentos cargados, se generarán en estado borrador para su
   respectiva revisión, para visualizar los documentos generados se debe
   hacer clic en “Ver Documentos”; de manera automática se abrirá una
   vista en “Análisis de Facturas”.

.. image:: /_static/images/7/documentosgeneradossri.png
    :align: center

Cada documento generado por este medio se registrará según su tipo, por
ejemplo: Si los documentos generados son Facturas, estas se podrán
visualizar en Facturas Proveedor; de igual manera con los diferentes
tipos de documentos.

Conciliaciones / Conciliación Bancarias
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Bancos** la opción **Conciliación
Bancaria.**

La conciliación bancaria es una comparación que se hace entre los
apuntes contables que lleva una empresa de su cuenta corriente (o cuenta
de bancos) y los ajustes que el propio banco realiza sobre la misma
cuenta. Se trata de un proceso que permite comparar los valores que la
empresa tiene registrados de una cuenta de ahorros o cuenta corriente
con los valores que el banco le suministra por medio del estado de
cuenta, que suele recibirse cada mes.

Se puede seleccionar el tipo del diario al que pertenece la
conciliación, la fecha inicial, la fecha final, el tipo, también podemos
ingresar el saldo anterior, los ingresos, egresos e inmediatamente
calcula el saldo actual.

.. image:: /_static/images/7/crearconciliacionbancaria.png
    :align: center

.. note::

    En la parte superior
    tenemos la opción de “Confirmar todos”, “Borrar no conciliados”,
    “Calcular”, y “Cancelar todos”,”Confirmar”.

**Confirmar:** Confirma el asiento y el estado cambia de borrador a
cerrado.

.. image:: /_static/images/7/borradorcerrarconciliaciones.png
    :align: center

**Confirmar todos:** Confirma todos los asientos que se encuentran
dentro de la conciliación.

**Borrar no conciliados:** Elimina los asientos que no se encuentran
confirmados.

**Calcular:** Calcula los valores de los libros, bancos y diferencias
(calcula sólo los asientos que están confirmados).

**Conciliar líneas:** Abre una vista en donde muestra todos los asientos
para su respectiva revisión (práctico cuando hay múltiples registros).

En la parte superior izquierda, tendremos una barra con la opción de
confirmar dicha conciliación, sólo aparecerá dicha conciliación si y
sólo si está confirmada.

.. image:: /_static/images/7/conciliacionesasientos.png
    :align: center

**Importante:** Para realizar una correcta conciliación, es necesario:

::

   • Añadir las líneas de asientos a conciliar.
   • Confirmar dichos asientos (en el caso de que todas las líneas estén correctas, es recomendable dar clic en “Confirmar todos”).
   • Borrar las líneas no conciliadas (dar clic en “Borrar no conciliados”).
   • Calcular dicha conciliación (dar clic en “Calcular”).
   • Si todo está correcto, se procede a confirmar la conciliación (dar clic en “Confirmar”).

En la parte inferior tenemos varias opciones:

.. image:: /_static/images/7/barraopcionesconciliar.png
    :align: center

**Cuentas:** Permite agregar líneas en el diario de asientos
contables.

**D/C no incluidos-Banco:** Detalla los depósitos y créditos no
incluidos por el Banco.

.. image:: /_static/images/7/noincluidosBanco.png
    :align: center


**Cheques G/NC:** Detalla los cheques girados y no cobrados.

**Débitos no registrados-Banco:** Detalla los débitos no registrados por
el Banco

.. image:: /_static/images/7/debitosnoregistradosBanco.png
    :align: center

**D/OC no incluidos-Libros:** Detalla los depósitos y otros créditos no
incluidos en Libros.

**Débitos no registrados-Libros:** Detalla los débitos no registrados en
los Libros.

Asientos Contables / Asientos contables
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Varios** la opción **Asientos
Contables.**

Un asiento contable es la anotación en el libro de contabilidad que
refleja los movimientos económicos de una persona o empresa, además, se
realiza cada vez que una empresa contabiliza una entrada o salida
relacionada con su actividad.

El sistema Contigo genera de manera automática los asientos contables
correspondientes a los diferentes documentos emitidos por la entidad. Si
un documento se encuentra en un estado borrador, el asiento se generará
como no asentado.

.. image:: /_static/images/7/asientocontablepublicado.png
    :align: center

.. image:: /_static/images/7/otrainfoasientoscontables.png
    :align: center

**Publicar automáticamente reversión de:** Al marcar la casilla lo que
hará es que el asiento contable se valide automáticamente en la fecha.

**Para revisar:** Al marcar esta casilla este asiento queda para
revisión.

**Tipos de contribuyentes:** Son posiciones fiscales. Su valor viene por
defecto.

**Asiento de reversión:** Permite revertir el asiento seleccionado.

.. image:: /_static/images/7/asientodereversion.png
    :align: center

El sistema nos permite realizar las siguientes acciones:

.. image:: /_static/images/7/accionesasientoscontables.png
    :align: center

**Duplicar:** Duplica el asiento seleccionado.

**Suprimir:** Elimina el asiento seleccionado.

**Generar enlace de pago:** Genera un enlace para una forma de pago.

**Compartir:** Permite compartir un enlace que dirige a la página del
asiento contable.

**Cambiar a reembolso:** Esta opción permite

**Generar Documentos Electrónicos:** Esta opción permite

**Cambiar a borrador:** Permite cambiar el estado del documento
(publicado-borrador).

**Anular facturas:** Permite anular facturas referentes/enlazadas a ese
asiento.


Asientos Contables / Apuntes contables
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Varios** la opción **Apuntes Contables.**

Un apunte contable es aquella anotación que detalla cualquier movimiento
comercial o económico que modifique el patrimonio de una persona o
empresa.

En contabilidad, se utilizan los apuntes contables para registrar cada
una de las operaciones que realiza una empresa. Cada apunte contable
supone un registro contable en el libro diario, y después un registro en
el libro mayor.

El sistema Contigo genera los apuntes contables según el asiento
contable.

.. image:: /_static/images/7/editarapuntecontable.png
    :align: center

El sistema permite realizar las siguientes acciones:

.. image:: /_static/images/7/accionesapuntescontables.png
    :align: center

**Suprimir:** Elimina el apunte contable.

.. image:: /_static/images/7/suprimirapuntecontable.png
    :align: center

**Entradas automáticas:** Permite registrar/crear asientos contables de
forma automática para la respectiva utilización de estos en los diarios
contables.

.. image:: /_static/images/7/entradasautomaticasapuntescontables.png
    :align: center

.. note::

    La creación de asientos contables automáticos sólo se puede
    realizar en asientos contables no conciliados.

Acciones / Conciliación
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Acciones** la opción **Conciliación.**

.. image:: /_static/images/7/accion_conciliacion.png
    :align: center

**Conciliar:** Esta opción permite realizar el respectivo
cruce de las diferentes cuentas; tanto las cuentas por cobrar como las
cuentas por pagar hasta lograr saldarlas.

Para saldar dichos valores pendientes es necesario primero elegir a
nuestro cliente o proveedor, al momento de seleccionarlo aparecerá en la
parte de abajo el nombre del cliente o proveedor con los respectivos
montos para su cruce.

.. image:: /_static/images/7/nombreusuarioconciliar.png
    :align: center

.. image:: /_static/images/7/cporcclientes.png
    :align: center

En el caso de que estén múltiples movimientos pendientes, el sistema
proporciona un filtro para cada cliente o proveedor.

.. image:: /_static/images/7/filtrobusquedaapuntecontables.png
    :align: center

Si se desea saber cuántos cruces hay pendientes en el sistema, solo nos
fijamos en la parte derecha superior del sistema; habrá una barra que
indicará el número de cruces pendientes a realizar, en este ejemplo
podremos observar que tenemos 1 conciliación a realizar.

.. image:: /_static/images/7/pendientesaconciliar.png
    :align: center

Para realizar el cruce es necesario crear un saldo, dependiendo del
monto de este, nos permitirá conciliar o no.

.. image:: /_static/images/7/saldoparaconciliar.png
    :align: center

Si se desea omitir dicho cruce, solo se debe dar clic en la opción
Saltar, de esta manera no aparecerán dichos movimientos pendientes a
conciliar.

.. image:: /_static/images/7/omitirconciliacion.png
    :align: center
**Importante:** Antes de realizar cualquier documento dentro del
sistema, se debe configurar los respectivos diarios (para más
información revisar **Diarios**).

Acciones / Fecha de bloqueo
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Acciones** la opción **Actualizar fecha
de bloqueo.**

La fecha de bloqueo sirve para evitar posibles errores contables y
fiscales por la creación o modificación de facturas, gastos/compras o
apuntes manuales.

Para evitar estos errores se bloquea la posibilidad de crear o modificar
todo lo anterior a la fecha que se escoja.

.. image:: /_static/images/7/actualizarfechabloqueo.png
    :align: center

Gestión de Chequeras / Chequeras
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Gestión de Chequeras** la opción
**Chequeras.**

Se trata de un documento firmado por el propietario de una cuenta en un
banco que habilita al que lo recibe a disponer de una cantidad
determinada de dinero (adeudo a cuenta) sobre una cuenta bancaria.

Su principal finalidad es emitir un pago sin la necesidad de transportar
efectivo, y dando al beneficiario más libertad para elegir el momento y
el lugar del cobro.

Al momento de generar una chequera, es necesario colocar el número de la
chequera, la cuenta bancaria (solo se puede tener una chequera por
cuenta bancaria), número inicial, número final, el relleno (número de
datos que irán en los cheques).

.. image:: /_static/images/7/borradorchequeras.png
    :align: center

Para generar los cheques de dicha chequera es necesario dar clic en la
opción Revisar, de manera automática el sistema generará los cheques con
los parámetros especificados anteriormente; cuando se hayan generado los
cheques, ya no será posible editar los datos anteriores para su
creación.

.. image:: /_static/images/7/btnrevisarchequera.png
    :align: center

.. image:: /_static/images/7/chequesgeneradoschequera.png
    :align: center
**Información:** Permite agregar una nota.

.. image:: /_static/images/7/apartadoinformacionchequeras.png
    :align: center

Para poder utilizar los cheques generados, es necesario dar clic en la
opción Activar.

.. image:: /_static/images/7/btnactivarchequeras.png
    :align: center

.. image:: /_static/images/7/chequeraactiva.png
    :align: center

**Nota:** Si se desea cancelar la chequera, es necesario indicar el
motivo de su cancelación y después de eso dar clic en la opción cancelar
que se encuentra ubicada en la parte superior izquierda; en el caso de
querer volver a utilizar la chequera, se deberá dar clic en la opción
volver a borrador.

.. image:: /_static/images/7/razondecancelacionchequeras.png
    :align: center

Si se desea inactivar la chequera, más no cancelarla, es necesario dar
clic en la opción hibernar la chequera, de manera automática los cheques
que no se han utilizado quedarán inactivos.

.. image:: /_static/images/7/btnreactivarchequera.png
    :align: center

.. image:: /_static/images/7/estadoinactivochequera.png
    :align: center

Gestión de Chequeras / Cheques de Proveedores
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Gestión de Chequeras** la opción
**Cheques de Proveedores.**

Si el pago que realizó un proveedor fue por medio de un cheque; dicho
pago aparecerá en esta vista.

.. image:: /_static/images/7/gestiodechequeras.png
    :align: center

.. image:: /_static/images/7/vistaeditarchequera.png
    :align: center

Diarios Contables /Ventas
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Diarios Contables** la opción **Ventas.**

.. image:: /_static/images/7/diarioscontablesventasview.png
    :align: center

Al seleccionar registros nos aparecen acciones que podemos realizar
según nuestra necesidad:

.. image:: /_static/images/7/accionesdiarioscontables.png
    :align: center

**Exportar:** Permite descargar los datos en un archivo excel o en un
archivo csv.

**Suprimir:** Elimina el o los registros seleccionados.

**Romper conciliación:** Elimina las conciliaciones enlazadas entre
cuentas.

**Conciliar:** Permite enlazar las cuentas seleccionadas.

**Entradas automáticas:** Nos permite crear asientos contables
automáticamente.

Existe la opción de exportar todos los registros dentro de este apartado
en un archivo excel:

.. image:: /_static/images/7/localizacionpaisesdescarga.png
    :align: center

.. image:: /_static/images/7/exceldiariocontable.png
    :align: center

.. image:: /_static/images/7/vistaexceldiariocontable.png
    :align: center

Dentro de Ventas se pueden visualizar diferentes vistas como poder ver
los registros e interactuar con ellos:

1) **Vista Lista:** Muestra los datos en forma de listado

   .. image:: /_static/images/7/viewlistdiariocontable.png
    :align: center

2) **Tabla Dinámica:** Muestra los datos en forma de tabla que permite
   interactuar con los ejes y cambiar los datos (medidas), también nos
   permite descargar un XML

   .. image:: /_static/images/7/tabladinamicadiariocontableventas.png
    :align: center

   .. image:: /_static/images/7/excelvistadinamica.png
    :align: center

3) **Vista Gráfica:** Permite visualizar los datos en diferentes
   diagramas gráficos de manera ascendente y descendente.

   .. image:: /_static/images/7/vistagrafica.png
    :align: center

   .. image:: /_static/images/7/tipodevistagrafica.png
    :align: center

4) **Vista Kanban:** vista basada en tarjeta en la que se muestran los
   datos de manera organizada para una mejor comprensión.

   .. image:: /_static/images/7/vistakanbandiarioscontablesventas.png
    :align: center

Diarios Contables /Compras
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Diarios Contables** la opción
**Compras.**

Al igual que el apartado anterior muestra opciones/filtros de búsqueda,
diferentes maneras de visualizar los registros.

.. image:: /_static/images/7/diariocontablescompras.png
    :align: center

Al seleccionar registros aparecen acciones que podemos realizar según
nuestra necesidad:

.. image:: /_static/images/7/accionesdiarioscompras.png
    :align: center

**Exportar:** Permite descargar los datos en un archivo excel o en un
archivo csv.

**Suprimir:** Elimina el o los registros seleccionados.

**Romper conciliación:** Elimina las conciliaciones enlazadas entre
cuentas.

**Conciliar:** Permite enlazar las cuentas seleccionadas.

**Entradas automáticas:** Permite crear asientos contables
automáticamente.

Existe la opción de exportar todos los registros dentro de este apartado
en un archivo excel:

.. image:: /_static/images/7/localizacionparroquiasdescarga.png
    :align: center

.. image:: /_static/images/7/exceldiariocontable.png
    :align: center

.. image:: /_static/images/7/exceldescargadiariocontcompras.png
    :align: center

Se visualiza una barra de búsqueda en la que se puede filtrar los datos
para obtener lo que se conoce como una búsqueda personalizada:

.. image:: /_static/images/7/barrabusquedacompras.png
    :align: center

Dentro de Compras obtenemos diferentes vistas de como poder visualizar
los registros e interactuar con ellos:

1) **Vista Lista:** Muestra los datos en forma de listado

   .. image:: /_static/images/7/viewlistcompras.png
    :align: center

2) **Tabla Dinámica:** Muestra los datos en forma de tabla que permite
   interactuar con los ejes y cambiar los datos (medidas), también nos
   permite descargar un XML

   .. image:: /_static/images/7/tabladinamicacompras.png
    :align: center

   .. image:: /_static/images/7/excelvistadinamicacompras.png
    :align: center

3) **Vista Gráfica:** Permite visualizar los datos en diferentes
   diagramas gráficos de manera ascendente y descendente.

   .. image:: /_static/images/7/vistagraficacompras.png
    :align: center

   .. image:: /_static/images/7/tipodevistagraficacompras.png
    :align: center

4) **Vista Kanban:** vista basada en tarjeta en la que se muestran los
   datos de manera organizada para una mejor comprensión.

   .. image:: /_static/images/7/vistakanbancompras.png
    :align: center

Diarios Contables /Banco y Efectivo
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Diarios Contables** la opción **Banco y
Efectivo.**

Un diario contable es un registro detallado de todas las transacciones
financieras de una empresa o entidad en un orden cronológico.

.. image:: /_static/images/7/bancoyefectivo.png
    :align: center

**Diario de Banco:** Este diario registra todas las transacciones
relacionadas con las cuentas bancarias de la empresa. Incluye depósitos,
retiros, transferencias, pagos de cheques, cobros y cualquier otro
movimiento financiero que involucre las cuentas bancarias.

**Diario de Efectivo:** El diario de efectivo registra todas las
transacciones de efectivo realizadas por la empresa. Esto puede incluir
ventas en efectivo, pagos de gastos en efectivo, retiros de caja chica y
otros movimientos que involucren dinero en efectivo.

Al seleccionar registros nos aparecen acciones que podemos realizar
según nuestra necesidad:

.. image:: /_static/images/7/accionbancoefectivo.png
    :align: center

**Exportar:** Permite descargar los datos en un archivo excel o en un
archivo csv.

**Suprimir:** Elimina el o los registros seleccionados.

**Romper conciliación:** Elimina las conciliaciones enlazadas entre
cuentas.

**Conciliar:** Permite enlazar las cuentas seleccionadas.

**Entradas automáticas:** Permite crear asientos contables
automáticamente.

Al igual que el apartado anterior se muestra opciones/filtros de
búsqueda, diferentes maneras de visualizar los registros.

.. image:: /_static/images/7/filtrobusquedabancoefectivo.png
    :align: center

Existe la opción de exportar todos los registros dentro de este apartado
en un archivo excel:

.. image:: /_static/images/7/localizacionpaisesdescarga.png
    :align: center

.. image:: /_static/images/7/exceldiariocontable.png
    :align: center

.. image:: /_static/images/7/excelbancoefectivo.png
    :align: center

Dentro de Compras obtenemos diferentes vistas como poder visualizar los
registros e interactuar con ellos:

1) **Vista Lista:** Muestra los datos en forma de listado

   .. image:: /_static/images/7/vistalistabancoefectivo.png
    :align: center

2) **Tabla Dinámica:** Muestra los datos en forma de tabla que permite
   interactuar con los ejes y cambiar los datos (medidas), también nos
   permite descargar un XML

   .. image:: /_static/images/7/tabladinamicabancoefectivo.png
    :align: center

   .. image:: /_static/images/7/tabladinamicabancoefectivoexcel.png
    :align: center

3) **Vista Gráfica:** Permite visualizar los datos en diferentes
   diagramas gráficos de manera ascendente y descendente.

   .. image:: /_static/images/7/vistagraficabancoefectivo.png
    :align: center

   .. image:: /_static/images/7/tipovistagraficabancoefectivo.png
    :align: center

4) **Vista Kanban:** vista basada en tarjeta en la que se muestran los
   datos de manera organizada para una mejor comprensión.

   .. image:: /_static/images/7/vistakanbanbancoefectivo.png
    :align: center



Diarios Contables /Varios
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Contabilidad** y buscar en **Diarios Contables** la opción **Varios.**

Informes
--------

Administración / Análisis de Facturas
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Administración** la opción **Facturas**.

Esta opción nos permite ver cuánto se ha facturado en lo que va de los
meses trabajados, se podrá ver tanto el valor facturado de los
proveedores como el de los clientes.

.. image:: /_static/images/7/administracionanalisisdefacturas.png
    :align: center

Administración / Cuentas por Pagar
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Administración** la opción **Cuentas por
Pagar.**

El sistema mostrará los apuntes contables realizados, la fecha de
creación, los montos vencidos dentro de 30, 60, 90 o más días y el total
pendiente; de esta manera nos permite visualizar los pagos realizados
hacia nuestros clientes/proveedores y observar los pagos pendientes de
realizar.

.. image:: /_static/images/7/cuentasporpagar.png
    :align: center

Administración / Cuentas por Cobrar
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Administración** la opción Cuentas por
**Cobrar**.

El sistema mostrará los apuntes contables realizados, la fecha de
creación, los montos vencidos dentro de 30, 60, 90 o más días y el total
pendiente; de esta manera nos permite visualizar los pagos realizados
hacia nuestros clientes/proveedores y observar los cobros pendientes de
realizar.

.. image:: /_static/images/7/Administracioncuentasporcobrar.png
    :align: center

Administración / Información de Ventas
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Administración** la opción **Información de
Ventas**.

Genera un reporte con la información de venta en un rango de fechas
especificado; podremos seleccionar Diario (Facturas de cliente, Guías de
Remisión, Retenciones Cliente), la fecha inicial, la fecha final y
cuales son las tablas que va a elegir, el borrador, publicado o anulado,
“Borrador” si va a mostrar los valores hechos en borrador, “Publicado”
si quiere mostrar los valores ya publicados, “Anulados” si quiere
mostrar los valores anulados o puede elegir los tres, después de
presionar en “Generar Reporte” se descargará un archivo.

.. image:: /_static/images/7/administracioninformedeventas.png
    :align: center

Administración / Información de Compras
^^^^^^^^^^^^^^^^^^^^^^
Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Administración** la opción **Información de
Compras**.

Genera un reporte con la información de compra en un rango de fechas
especificado; podremos seleccionar Diario (Facturas de proveedor,
Retenciones Proveedor), la fecha inicial, la fecha final y cuales son
las tablas que va a elegir, el borrador, publicado o anulado, “Borrador”
si va a mostrar los valores hechos en borrador, “Publicado” si quiere
mostrar los valores ya publicados, “Anulados” si quiere mostrar los
valores anulados o puede elegir los tres, después de presionar en
“Generar Reporte” se descargará un archivo.

.. image:: /_static/images/7/admiformaciondecompras.png
    :align: center

.. image:: /_static/images/7/informaciondeCompras.png
    :align: center

Informes de Contabilidad /Libro mayor
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Informes de Contabilidad**  la opción
**Libro mayor**.

Genera una tabla con todo el balance con la información de un periodo
desde una fecha inicial hasta una fecha final, los movimientos de
destino en el cual se puede elegir entre dos opciones: Todos los
asientos publicados o solo todos los asientos que son los asientos que
han sido creados pero no han sido publicados, además de haber un grupo
llamado “agrupado por:” (Empresas, Impuestos o Ninguna), sigue por
elegir entre varias opciones entre las cuales se encuentra: Activar
centralización que mostrará los valores con las fechas, Ocultar saldos
finales con valor 0, Mostrar Moneda Extranjera, Mostrar etiquetas
analíticas y Mostrar Cuenta Analítica, también tendremos filtros,
filtros de cuenta en el cual si desea que les muestre solo las cuentas a
pagar, las cuentas a cobrar o ambas, también puede poner desde que
código hasta que código pero también hay una barra para poner los código
que quiere ver, en filtrar empresa se encuentra una barra para poner
cuantas empresas desea mostrar, filtrar por etiquetas analíticas permite
ver cuales datos desea ver que contienen la etiquetas que deseamos y
filtrado adicional que nos permite combinar todos los registros según el
dominio que hayamos editado, sino elige ningun cambio por los filtros el
resultado sería que esté mostrará todas las tablas de datos que hayamos
insertados, al final puedes mostrar la tabla o importarla a XLS o a Pdf,
se mostrará una tabla conformada por fecha, asiento, diario, cuenta,
impuestos, empresas, referencias, cuentas analiticas, el debe, el haber
y el saldo acumulado

.. image:: /_static/images/7/informaciondeCompras.png
    :align: center

Informes de Contabilidad /Libro diario
^^^^^^^^^^^^^^^^^^^^^^

.. image:: /_static/images/7/informesdecontabilidadOCAlibrodiario.png
    :align: center

Ingresar al módulo de **Contabilidad**, posteriormente
seleccionar **Informe** y buscar en **Informes** de Contabilidad  la
opción **Libro diario**.

Genera una tabla con el balance en base a los diarios, con la
información de periodo, una fecha de inicio, una fecha final, también
hay opciones, acerca de cuál va a ser el asiento objetivo (Todos
refiriéndose a todos los asientos, posteado solamente a los que sí están
publicados, sin postear refiriéndose a los que no están publicados),
también está ordenar asientos por número de asientos o por las fechas de
los asientos dichos, está también agrupar por diario o sin agrupar,
habrán unas opciones múltiples, monedas extranjera que muestra la
monedas que está usando, cuenta con nombre que muestra los nombres de la
cuenta, mostrar auto secuencia, que como el nombre indica va a mostrar
los asientos de forma secuencial, al final se encuentra una opción que
se llama diario, en este puede poner que diarios quiere que le muestre,
al final puedes mostrar la tabla o importarla a XLS o a Pdf, va a salir
una tabla conformada por secuencia, asiento, fecha, cuenta, empresa,
Ref. Etiqueta, los impuestos, el debe, el haber, actual, importe monedas


.. image:: /_static/images/7/librodiario.png
    :align: center

.. image:: /_static/images/7/diariodecontabilidad.png
    :align: center

Informes de Contabilidad /Balance de Sumas y Saldos
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Informes** de Contabilidad  la opción
**Balance de Sumas y Saldos**.

Genera una tabla con el balance en base de sumas y saldos, con la
información de periodo, una fecha de inicio, una fecha final, en el lado
derecho hay varias opciones la primera de ellas “Movimientos destino”
(Todos los asientos publicados, todos los asientos) es de una sola
opción, las demás son de opción múltiple, ocultar cuentas a 0 que no va
a mostrar un saldo inicial igual a 0, le sigue una opción Mostrar
detalles de la empresa, Mostrar jerarquía, mostrar moneda extranjera
para saber que moneda se está usando, en el lado izquierdo hay una
opción que se llama diario, en este puede pedirle que diarios quiere que
les muestre. En el filtro cuentas, habrán algunas opciones de opción
múltiple, estas son Sólo cuentas a cobrar y Sólo cuentas a pagar,
después se encuentra Desde código … A … que permite mostrar desde qué
código ya hasta que código, al final puedes mostrar la tabla con la
opción de vista o exportar a XLS o a Pdf, en cualquiera que vaya a ser
seleccionada el resultado será que va a salir una tabla conformado por
el filtro periodo, el filtro movimiento destino, el filtrar por cuenta 0
y limitar niveles de jerarquía.

.. image:: /_static/images/7/balancedesumasysaldo.png
    :align: center

.. image:: /_static/images/7/balancedesumaysaldo.png
    :align: center

Informes de Contabilidad /Pérdidas y Ganancias
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Informes** de Contabilidad  la opción
**Pérdidas y Ganancias**.

Genera una tabla con las pérdidas y ganancias, con la información de
periodo, una fecha de inicio, una fecha final, en el lado derecho hay
varias opciones la primera de ellas es el rango de fechas, fecha de que
tendrá que poner en que desde que fecha quiere mostrar y fecha hasta en
el que tendrá que poner hasta que fecha es el límite en el que quieren
que le muestre los valores, en el lado derecho se encuentran otras
opciones como Movimientos de destinos, en el cual se encuentran dos
opciones del cual tendrá que elegir solo, las dos son entradas
publicadas para solo mostrar las entradas que han sido publicadas o
puede elegir todas las entradas, para mostrar tanto las publicadas como
las no publicadas, las que le siguen son opcionales, ocultar cuentas en
0, cuando esa opcion está seleccionado no se mostrarán saldos iniciales
que tengan 0, el siguiente es “Mostrar jerarquía” si selecciona esta
opción los diarios se mostrarán de forma jerarquica, además aparecerán
otras opciones, como “Limitar niveles de jerarquía” que nos permite
mostrar la jerarquía pero hasta cierto nivel, el cual será modificado
con “Niveles de jerarquía para mostrar” pero también si no quiere
mostrar los niveles principales elija la opción “No mostrar los niveles
principales”, por ultimo tenemos la opción “Mostrar moneda extranjera”
esta opción sirve para mostrar la moneda extranjera usada, en el lado
izquierdo se encuentra “Diario” para elegir que diarios ya registrados
va a usar, al terminar todo esto elija como Mostrar la tabla “Vista” si
quiere que se muestre en el propio sistema, o lo quiere exportar a PDF o
XLS, se mostrará una tabla con las fechas, el codigo,la cuenta, el
balance, balance inicial y balance final

.. image:: /_static/images/7/perdidasyganancias.png
    :align: center

.. image:: /_static/images/7/perdidasygananciass.png
    :align: center

.. image:: /_static/images/7/perdidayganancia.png
    :align: center

Informes de Contabilidad /Balance General
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Informes** de Contabilidad  la opción
**Balance General**.

Genera una tabla con el balance general, con la información de periodo,
una fecha de inicio, una fecha final, en el lado derecho hay varias
opciones la primera de ellas “Movimientos destino” (Todos los asientos
publicados, todos los asientos) es de una sola opción, las demás son de
opción múltiple, ocultar cuentas a 0 que no va a mostrar saldo inicial
que sea cero, le sigue una opción Mostrar detalles de la empresa,
Mostrar jerarquía, mostrar moneda extranjera para saber que moneda se
está usando, en el lado izquierdo hay una opción que se llama diario,
este podemos pedirle que diarios quiere que le muestre. En filtrar
cuentas, habrán algunas opciones de opción múltiple, estas son Sólo
cuentas a cobrar y Sólo cuentas a pagar, después se encuentra Desde
código … A … que mostrara desde que código hasta que código, al final
puedes mostrar la tabla o exportar a XLS o a Pdf,

.. image:: /_static/images/7/balancegeneral.png
    :align: center

.. image:: /_static/images/7/balancesgeneral.png
    :align: center

Informes de Contabilidad /Partidas abiertas
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Informes** de Contabilidad  la opción
**Partidas abiertas**.

Genera una tabla en base a las partidas abiertas que están disponibles
hecha con la información de fecha actual con una fecha anterior, en el
lado derecho hay varias opciones la primera de ellas “Movimientos
destino” (Todos los asientos publicados, todos los asientos) es de una
sola opción, las demás son de opción múltiple, Mostrar detalles de la
empresa, ocultar cuentas a 0 que no nos va a mostrar que tengan saldo
inicial a 0, Mostrar Moneda extranjera, que nos muestra la moneda que se
usó en caso de que sea extranjera, en el lado izquierdo hay una opción
que se llama Filtrar empresa, en este puede pedirle que empresas quiere
que le muestre, Solo cuentas a cobrar y Solo cuentas a pagar son
opciones de las cuales opcionalmente puede elegir las dos, después se
encuentra Desde código … A … que permite mostrar desde qué código ya
hasta que código, al final puedes mostrar la tabla o importarla a XLS o
a Pdf

.. image:: /_static/images/7/partidasabierta.png
    :align: center

.. image:: /_static/images/7/partidasabiertas.png
    :align: center

Informes de Contabilidad /Calidad de la deuda
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Informes** de Contabilidad  la opción
**Calidad de la deuda**.

Genera una tabla en base a la calidad de la deuda que están disponibles
hecha con la información de fecha actual con una fecha de inicio, en el
lado derecho hay varias opciones la primera de ellas “Movimientos
destino” (Todos los asientos publicados, todos los asientos incluso si
no han sido publicados) es de una sola opción, la segunda es opcional
Mostrar detalles Apuntes, en el lado izquierdo hay una opción que se
llama “Filtrar empresa”, en este puede pedirle que empresas quiere que
les muestre, Solo cuentas a cobrar y Solo cuentas a pagar son opciones
de las cuales opcionalmente podemos elegir las dos, después se encuentra
Desde código … A … que permite mostrar desde qué código ya hasta que
código, al final puedes mostrar la tabla o importarla a XLS o a Pdf.

.. image:: /_static/images/7/calidaddeladeuda.png
    :align: center

.. image:: /_static/images/7/calidaddeladeudas.png
    :align: center

Informes de Contabilidad /Informe de Impuestos
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Informes** de Contabilidad  la opción
**Informe de impuestos**.

Genera una tabla en base a la información de los impuestos, esta tabla
está hecha con la información de fecha de comienzo y una fecha final,
después de eso hay varias opciones la primera de ellas “Movimientos
destino” (Todos los asientos publicados, todos los asientos incluso si
no han sido publicados) es de una sola opción obligatoria, la segunda
opción es Basados en (Etiquetas de impuestos que usan las propias
etiquetas de los impuestos y Grupos de impuestos en el que son agrupados
en tax groups) y es obligatoria, la última opción es Detalle de
impuestos y esta es opcional, al final puedes mostrar la tabla o
importarla a XLS o a Pdf, esto mostrará una tabla conformada por los
códigos, el nombre, el valor neto y el impuesto

.. image:: /_static/images/7/informesdeimpuesto.png
    :align: center

.. image:: /_static/images/7/informesdeimpuestos.png
    :align: center

**NOTA**: Los campos en color celeste son campos obligatorios.

**Movimientos destino**:Se debe seleccionar si se requiere visualizar
elementos específicos.

**Basados en**: Se debe seleccionar si se necesita organizar,
categorizar y mostrar los elementos de impuestos.

**Detalle de impuestos**: Muestra información desglosada de ese
impuesto.

Una vez seleccionadas las opciones deseadas por el usuario, nos muestra
tres alternativas:

.. image:: /_static/images/7/infodeimpuestos.png
    :align: center

**Ver**: Se redirige al usuario dentro del
sistema a una página para que pueda visualizar el balance.

.. image:: /_static/images/7/infodeimpuestosrio.png
    :align: center

**Exportar PDF**: Se descarga la información en un archivo pdf para su
visualización.

.. image:: /_static/images/7/informedeimpuestosexportarpdf.png
    :align: center

**Exportar XLSX** : Se descarga la información
en un archivo de excel.

.. image:: /_static/images/7/informedeimpuestoexportarxlsx.png
    :align: center

Reportes Financieros/Plan Contable
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **Reportes** Financieros la opción **Plan
Contable**.

Genera un reporte con la información del plan contable de la empresa,
por defecto seleccionará la compañía y los niveles que se desean
visualizar en el reporte.

Importante: El plan contable cuenta con niveles (del 1 al 6), al momento
de seleccionar el nivel en el plan contable por ejemplo 5, el reporte
mostrará desde el nivel 1 hasta el nivel 5.

.. image:: /_static/images/7/reporfinancierosplancontable.png
    :align: center

.. image:: /_static/images/7/plancontable.png
    :align: center

SRI/Generar y Exportar A.T.S.
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Informe** y buscar en **SRI** la opción **Generar y Exportar A.T.S**.

Genera un reporte con la información del Anexo Transaccional
Simplificado, se debe especificar el año fiscal, el periodo y si se
desea mostrar los documentos electrónicos. Al momento de exportar se
abrirá una nueva ventana en donde tendremos que descargar el XML
generado.

.. image:: /_static/images/7/exportarats.png
    :align: center

.. image:: /_static/images/7/exportar.png
    :align: center



Configuracion
---------------

Contabilidad / Plan de Cuentas
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Contabilidad** la opción **Plan de
Cuentas**.

El Plan de Cuentas es un conjunto de normas que establecen los
procedimientos y métodos necesarios para el registro de la actividad
económica de una empresa.

**Importante:** Es necesario revisar el plan de cuentas para verificar
si están todas las cuentas que son necesarias para la empresa, si no se
encuentran todas las cuentas requeridas para tu negocio; el sistema
contigo te permite crearlas para utilizarlas posteriormente.

.. image:: /_static/images/7/contabilidadplandecuentas.png
    :align: center

Al momento de generar una nueva cuenta, es necesario añadir el código de
esta, si depende de una cuenta padre, el nombre de la cuenta, el tipo de
cuenta, si contiene impuesto por defecto, si tiene etiqueta, grupo, si
permite conciliación, si esta descatalogado, nivel (dependiendo de la
cuenta padre, indicará el nivel de manera automática), búsqueda rápida y
habilitarla para que pueda ser utilizada dentro del sistema.

.. image:: /_static/images/7/contaplandecuentas.png
    :align: center

.. image:: /_static/images/7/configuracionplandecuentas.png
    :align: center

El sistema nos permite realizar las siguientes acciones:

.. image:: /_static/images/7/contplandecuentasaccion.png
    :align: center

**Duplicar**: Nos permite duplicar dicho registro.

**Suprimir**: Nos permite borrar.

Contabilidad / Impuestos
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Contabilidad** la opción **Impuestos**.

Un impuesto es un tributo que se paga al estado para soportar los gastos
públicos. Estos pagos obligatorios son exigidos tanto a personas
físicas, como a personas jurídicas. Al momento de generar un nuevo
impuesto es necesario añadir el nombre de este y el ámbito del impuesto
(compra, venta, ninguno y ajustes).

.. image:: /_static/images/7/contabilidadimpuestos.png
    :align: center

**Definición:** De igual manera se debe añadir el cálculo del impuesto,
el importe, la cuenta de impuestos y la cuenta de impuestos en notas de
crédito.

.. image:: /_static/images/7/contabilidadimpuestosdefinicion.png
    :align: center

**Opciones avanzadas:** Se añade la etiqueta que tendrá en facturas, el
grupo de impuestos, etiquetas, si incluye en el precio, si contiene base
imponible de impuestos subsiguientes.

.. image:: /_static/images/7/contabilidadimpuestoavanzado.png
    :align: center

Contabilidad / Posiciones Fiscales
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Contabilidad** la opción **Posiciones
Fiscales**.

Una posición fiscal define, para cada cliente, un conjunto de impuestos,
de modo que, si un cliente dispone de una posición fiscal específica,
los impuestos pueden variar. Al momento de generar una nueva posición
fiscal es necesario indicar el nombre de esta, en el caso de que se
desee que se detecte de manera automática hay que dar clic en la casilla
del lado derecho, esto indica si se debe aplicar automáticamente esta
posición fiscal.

.. image:: /_static/images/7/posicionesfiscales.png
    :align: center

**Mapeo de impuestos:** Se agregan los impuestos que incluirá la
posición fiscal, se añade el impuesto sobre el producto y el impuesto
para aplicar.

.. image:: /_static/images/7/mapeodeimpuesto.png
    :align: center

**Mapeo de cuentas:** Se agregan las cuentas que incluirá la
posición fiscal, se añade la cuenta del producto y la cuenta
alternativa.

.. image:: /_static/images/7/mapeodecuentas.png
    :align: center

Si se desea añadir alguna advertencia, se procede a llenar la
casilla de Advertencia legal.

.. image:: /_static/images/7/advertencialegal.png
    :align: center

Contabilidad / Grupos de Diarios
^^^^^^^^^^^^^^^^^^^^^^

Se refiere a una forma de organizar y categorizar los registros
contables según diferentes criterios. Estos grupos ayudan a clasificar y
gestionar las transacciones financieras de una empresa de manera más
eficiente.

.. image:: /_static/images/7/contabilidadgrupodiarios.png
    :align: center

Contabilidad / Diarios Contables
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Contabilidad** la opción **Diarios
Contables**.

El libro diario es el registro contable principal de cualquier sistema
contable, en el cual se anotan todas las operaciones. Es un documento
que registra de forma cronológica las transacciones económicas que una
empresa realiza. Estas transacciones están relacionadas con la actividad
principal de la firma.

Para generar un diario, es necesario agregar el nombre de este, el tipo
(venta, compra, efectivo, banco y miscelánea), el código corto, el
próximo número, cuenta deudora por defecto, cuenta acreedora por
defecto, si se desea transferir dicho diario a compañías, propina
producto, si es caja chica, si es liquidación de gastos, si es tarjeta
de crédito, si contiene un producto en descuento y el tipo de cuenta
bancaria.

.. image:: /_static/images/7/contabilodaddiarioscontables.png
    :align: center

**Configuración avanzada:** Se indica el método de pago para los pagos
recibidos de dicho diario (manual o electrónico), para pagos salientes
(manual o cheques), cuentas de beneficios, cuentas de pérdidas, si se
desea mostrar la cuenta, si permite la cancelación de asientos y si se
valida en la conciliación bancaria.

.. image:: /_static/images/7/contabilidadconfiguracionavanzada.png
    :align: center

Contabilidad /Monedas
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Contabilidad** la opción **Monedas**.

Las monedas se especifican de cada país al momento de enviar una
transacción de dinero de un lugar a otro dentro de la estructura podemos
ver sus ingresos y actualizaciones.

.. image:: /_static/images/7/contabilidadmonedas.png
    :align: center

Al momento de crear nos envía un formulario donde se llenará
los campos solicitados para registrar dando grabar sin embargo también
tenemos descartar para interrumpir el proceso que no queramos guardar
aun.

.. image:: /_static/images/7/contabilidadmoneda.png
    :align: center

La tasa podemos ver la fecha donde podemos agregar línea donde
se refleja unidad por USD y USD por unidad.

Facturación / Incoterms
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Facturación** la opción **Incoterms**.

Los incoterms (palabra derivada del sigloide en lengua inglesa
international commercial terms, que se traduce al español como «términos
de comercio internacional) son términos, de tres letras cada uno, que
reflejan las normas de aceptación voluntaria por las partes en un
contrato de compraventa internacional de mercaderías acerca de las
condiciones de entrega de las mercancías. Se usan para aclarar los
costes de las transacciones comerciales internacionales, delimitando las
responsabilidades entre el comprador y el vendedor, y reflejan la
práctica actual en el transporte internacional de mercancías.

Al momento de generar un nuevo Incoterms es necesario ingresar el nombre
y el código de este.

.. image:: /_static/images/7/facturación_incoterms.png
    :align: center

Contabilidad / Tipos de Cuentas
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Contabilidad** la opción **Tipos de
Cuentas**.

Al momento de generar una nueva cuenta bancaria, es necesario indicar el
nombre de esta, el tipo, el tipo de informe y si se desea adelantar en
el balance de cuentas; también se puede añadir una breve descripción de
esta.

.. image:: /_static/images/7/contabilidadtiposdecuenta.png
    :align: center

Contabilidad / Etiquetas de cuenta
^^^^^^^^^^^^^^^^^^^^^^

Se refiere a una etiqueta o descripción adicional que se adjunta a una
cuenta contable específica en un sistema contable para proporcionar
información complementaria o para identificar la cuenta de manera más
detallada.

.. image:: /_static/images/7/contabilidadetiqutasdecuenta.png
    :align: center

Contabilidad / Grupos de cuentas
^^^^^^^^^^^^^^^^^^^^^^

Los grupos de cuentas son categorías organizativas utilizadas en
contabilidad para agrupar cuentas similares con el propósito de
facilitar la contabilización, la generación de informes financieros y el
análisis.

.. image:: /_static/images/7/gruposdecuentas.png
    :align: center

.. image:: /_static/images/7/grupodecuentas.png
    :align: center

Contabilidad / Grupos de impuestos
^^^^^^^^^^^^^^^^^^^^^^

Los grupos de impuestos son categorías organizativas utilizadas en
contabilidad y finanzas para agrupar diferentes tipos de impuestos y
obligaciones tributarias con el fin de simplificar su cálculo, registro
y presentación.

.. image:: /_static/images/7/gruposdeimpuestos.png
    :align: center


Bancos / Agregar una cuenta bancaria
^^^^^^^^^^^^^^^^^^^^^^

Se refiere a registrar y configurar esa cuenta bancaria en el sistema
contable de una empresa para llevar un registro preciso de todas las
transacciones financieras relacionadas con esa cuenta.

.. image:: /_static/images/7/banco_agregarunacuentabancaria.png
    :align: center

Bancos / Modelos de Conciliación
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Bancos** la opción **Modelos de
Conciliación.**

El modelo de conciliación bancaria proporciona orientación detallada
sobre cómo llevar a cabo cada aspecto del proceso de conciliación, desde
la configuración hasta la creación de registros de ajuste. Cada elemento
mencionado anteriormente estaría explicado en profundidad para guiar a
los usuarios a través del proceso de manera efectiva.

.. image:: /_static/images/7/banco_modelosdeconciliacion.png
    :align: center

.. image:: /_static/images/7/banco_modeloconciliacion.png
    :align: center

.. image:: /_static/images/7/bancos_modelosconciliacion.png
    :align: center

Contabilidad / Sustento de Comprobantes
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Contabilidad** la opción **Sustento de
Comprobantes.**

Nos permite generar los diferentes tipos de documentos, ingresar el
código, el tipo de sustento, fecha de inicio, fecha de fin y agregar los
sustentos de comprobantes relacionados al tipo de documento (para más
información revisar Comprobantes Autorizados).

.. image:: /_static/images/7/contabilidad_sustentodecomprobantes.png
    :align: center

.. image:: /_static/images/7/contabilidad_sustentosdecomprobantes.png
    :align: center

Contabilidad / Tipos de Documentos
^^^^^^^^^^^^^^^^^^^^^^

Se refiere a las distintas formas o registros utilizados para respaldar
y registrar las transacciones financieras de una empresa. Estos
documentos son esenciales para mantener un registro adecuado de las
operaciones financieras y para cumplir con los requisitos legales y
contables.

.. image:: /_static/images/7/contabilidad_tiposdedocumentos.png
    :align: center

Facturación / Puntos de Emisión
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Facturación** la opción **Puntos de
Emisión.**

El punto de emisión corresponde al primer grupo del número de serie de
una factura o comprobante autorizado, tiene 3 dígitos, este número
identifica al establecimiento o negocio en particular.

En este apartado podremos controlar los diferentes puntos de emisión de
cada documento realizado por la empresa. Al momento de generar un nuevo
punto es necesario ingresar el nombre, el código, la agencia y el
ambiente. Por lo general cuando se genera un nuevo punto de emisión, los
secuenciales para facturas, notas de crédito, notas de débito, guía de
remisión, retenciones y las liquidaciones de compra por defecto serán 1.

La precisión decimal consiste en el número de decimales que aparecerán
en los reportes realizados, donde tendremos la precisión de precio
unitario y la precisión de cantidades.


.. note::

    El secuencial se asigna de manera automática en el sistema,
    por ejemplo, se ha realizado una nueva factura el secuencial de factura
    se aumentará al siguiente; en este caso de 1 cambiará a 2 y así
    sucesivamente. En el caso de que se desee cambiar el secuencial de algún
    documento se lo podrá realizar, pero no es un proceso recomendable.

.. image:: /_static/images/7/facturacion_puntosdeemision.png
    :align: center

Facturación/ Periodos
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Facturación** la opción **Periodos.**

Un período contable, en contabilidad, es el período en el que se hace
referencia a los libros contables de cualquier entidad.

Es el período durante el cual los libros están equilibrados y los
estados financieros están preparados. En general, el período contable
consta de 12 meses. Sin embargo, el comienzo del período contable
difiere según la jurisdicción. Por ejemplo, una entidad puede seguir el
año calendario regular, es decir, enero a diciembre como el año
contable, mientras que otra entidad puede seguir de abril a marzo como
el período contable.

Se ingresa el nuevo año fiscal, el nombre, el código, la fecha de inicio
y la fecha de fin.

.. image:: /_static/images/7/facturacion_periodos.png
    :align: center

.. image:: /_static/images/7/facturacion_periodo.png
    :align: center

Facturación / Año Fiscal
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Facturación** la opción **Año Fiscal.**

Se trata del periodo de doce meses de duración con el cual una empresa
organiza y planifica su calendario fiscal. De este modo es posible
llevar a cabo sus respectivas obligaciones tributarias con normalidad y
planificar el siguiente ejercicio fiscal.

Al momento de generar un nuevo año fiscal, es necesario ingresar el
nombre de este, la fecha de inicio y la fecha de finalización. Para
generar los periodos de manera rápida tendremos en la parte superior
izquierda una opción llamada ‘Crear Periodos’, esta opción tomará la
fecha de inicio y la fecha fin para generar los periodos según el rango
asignado.

.. image:: /_static/images/7/facturacion_añosfiscales.png
    :align: center

.. image:: /_static/images/7/facturacion_añosfiscale.png
    :align: center

Facturación/ Payment Methods SRI (Métodos de Pago SRI)
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Facturación** la opción **Payment
Methods (Métodos de Pago SRI).**

.. image:: /_static/images/7/Facturacion_PaymentMethodsSRI(MetodosdePagoSRI).png
    :align: center

En este apartado podemos crear diferentes métodos de pago , estos
métodos se verán reflejados en secciones como Facturas entre otros.

Al momento de generar un nuevo es necesario llenar los campos , el
nombre y el código. Damos en en la parte superior izquierda damos en
Grabar y listo !.

.. image:: /_static/images/7/Facturacion_PaymentMethodsSRI.png
    :align: center

Facturación / Plazos de Pago
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Facturación** la opción **Plazos de
Pago.**

Se denomina compraventa a plazos a una modalidad de compraventa
utilizada, normalmente, para bienes duraderos, a través del cual el pago
del precio no se hace en el momento de la adquisición del bien, sino que
se difiere en el tiempo a través de una serie de pagos denominados
“plazos”, “cuotas” o “abonos” (en ocasiones, también reciben
coloquialmente el nombre de “letras”).

Para generar un plazo de pago se debe ingresar el nombre de este, una
breve descripción para indicar el motivo del plazo, al momento de añadir
un término de pago es necesario crearlo en el caso de que no exista
ninguno; se indica el tipo de término, el cálculo de fechas de
vencimiento y el número del mes.

.. image:: /_static/images/7/facturacion_plazodepagos.png
    :align: center

.. image:: /_static/images/7/facturacion_tipodeplazo.png
    :align: center

Administración / Categoría de Productos
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Administración** la opción **Categoría
de Productos.**

Las categorías te permiten clasificar tus productos de forma que se
puedan agrupar productos similares en los listados. Al momento de
ingresar una nueva categoría es necesario ingresar el nombre de esta, si
esta depende de otra categoría (categoría padre) se la puede agregar,
forzar las estrategias de retiradas por medio de los métodos FIFO y
LIFO, indicar el método de coste, la valoración del inventario, la
cuenta de ingreso del producto, la cuenta de gasto de este, la cuenta de
entrada de stock, la cuenta de salida de stock, la cuenta de valoración
de stock y el diario del stock.

.. image:: /_static/images/7/administracion_categoriadeproductos.png
    :align: center

.. image:: /_static/images/7/gruposdeimpuestos.png
    :align: center

.. image:: /_static/images/7/administracion_categoria.png
    :align: center

Si se desea observar todos los productos que contengan dicha categoría,
podremos observarlos en esta opción.

.. image:: /_static/images/7/administracion_producto.png
    :align: center

Administración / Modos de pago
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Administración** la opción **Modos de
pago.**

La información en estos campos se utilizaría para llevar un registro de
las transacciones financieras y para garantizar que los pagos se
realicen de manera adecuada y segura.

.. image:: /_static/images/7/administracion_modosdepago.png
    :align: center

.. image:: /_static/images/7/administracion_mododepago.png
    :align: center

Administración / Métodos de pago
^^^^^^^^^^^^^^^^^^^^^^

Ingresar al módulo de **Contabilidad**, posteriormente seleccionar
**Configuración** y buscar en **Administración** la opción **Métodos de
pago.**

Estos campos se utilizan para describir, categorizar y gestionar las
diferentes opciones disponibles para realizar transacciones financieras.
Cada campo proporciona información clave sobre cómo se realiza el pago,
qué requisitos pueden estar involucrados y cómo se clasifica el método
de pago en relación con otros.

.. image:: /_static/images/7/administracion_metododepago.png
    :align: center

.. image:: /_static/images/7/administracion_metodosdepago.png
    :align: center

