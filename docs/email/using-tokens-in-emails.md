Usar tokens en correos electrónicos
===================================

Puede usar tokens para incluir texto personalizado (como el nombre de una persona), agregar enlaces de acción (como una opción de cancelación de suscripción) o mostrar información de organización estándar (como la dirección de dominio) en un correo masivo enviado con CiviCRM. Los tokens se reemplazan por el valor apropiado en el momento en que se envía el correo electrónico.

Para ver la lista de tokens de contacto disponibles, haga clic en **Insertar tokens**. Para obtener más información acerca de los tokens en general, consulte * Funciones de combinación de correo (a.k. a. usando Tokens) *en la sección* Trabajar con sus datos * de este manual.

Tokens de información de contacto
---------------------------------

Si desea que cada correo electrónico se dirija a la persona por su nombre de pila, después del saludo "Estimado", debe escribir un espacio y luego hacer clic en ** Insertar tokens ** en la parte superior derecha del campo Formato HTML. La ventana emergente que aparece le permite encontrar el token apropiado cuando teclee  "Nombre" en el cuadro y elegir así el token que corresponda. Haga clic en Cerrar y verá que su mensaje ahora dice "Estimado {primer nombre}". Cuando se envía el correo electrónico, se insertará el nombre apropiado en cada mensaje. Examine la ventana emergente Tokens de inserción para obtener una lista completa de los tokens de datos de contacto, incluido cualquiera de los campos personalizados que se han creado para su sitio. También puede consultar: <http://wiki.civicrm.org/confluence/display/CRMDOC/Tokens> para más detalles.

**Tokens de Acción y Organización**
------------------------------------

También puede introducir tokens de acción, como por ejemplo tokens de exclusión, anulación de suscripción y reenvío. Estos tokens introducen enlaces que darán lugar a una acción específica; para mostrar correctamente los enlaces en los mensajes HTML, deberá agregar las etiquetas de enlace adecuadas utilizando el icono Fuente en el editor.

También puede introducir información estándar de la organización, como "Dominio (de la organización)", que muestra la dirección de su organización tal como se define en **Administrar > Comunicaciones > Dirección de la organización e información de contacto**. Para obtener una lista completa de los tokens de acción y organización, consulte: [http://wiki.civicrm.org/confluence/display/CRMDOC/Tokens](http://wiki.civicrm.org/confluence/display/CRMDOC/CiviMail+Action+and+Organizational+Tokens).

Nota: es obligatorio incluir un token para anular o dar de baja la suscripción, así como el token de dirección de la organización (dominio) en cada correo de CiviMail. Estos tokens pueden colocarse directamente en el cuerpo de su correo electrónico, o puede colocarlos en el encabezado o pie de página del mismo. Si su organización ha creado un pie de página de correo estándar, simplemente incluya estos tokens en el pie de página para que la gente no tenga que pensar en ellos cada vez que crean un nuevo envío de correos.

En general, incluir enlaces de cancelación de suscripción y de desactivación por clic es un poco más amigable para los destinatarios (a diferencia del método de respuesta por correo electrónico). También puede proporcionar ambas opciones. Más detalles en: <http://wiki.civicrm.org/confluence/display/CRMDOC/Tokens>

Tokens personalizados y Suma de comprobación
---------------------------------------------

Solo los campos de contacto, los enlaces de acción y la información de la organización se pueden insertar en su correo electrónico como tokens. Los registros relacionados, como el nombre del evento para el cual los contactos tienen inscripciones pendientes, no se pueden incluir. Sin embargo, puede proporcionar un enlace al panel de contacto de la persona para que puedan revisar sus datos de registro por sí mismos (una vez que haya iniciado sesión).

Puede crear y usar un token para campos de datos personalizados que haya creado para almacenar datos sobre sus contactos. También puede crear un token de suma de comprobación que genere una URL única para cada contacto para que pueda modificar su información sin tener que iniciar sesión. Consulte más información sobre tokens personalizados y de suma de comprobación, incluida la forma de construir las URL que necesita, en (http://wiki.civicrm.org/confluence/display/CRMDOC/Tokens).

** Nota: ** En el área de edición de formato HTML, los tokens que generan URLs (enlaces) deben incluirse en el campo URL de la pantalla de creación de enlaces. De lo contrario, se mostrarán como texto y no como un enlace clicable en el correo electrónico del destinatario.