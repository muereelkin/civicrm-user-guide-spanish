
Captación de Fondos
=====================

Su organización puede recaudar donaciones en eventos, pedir donaciones por correo postal y otros métodos offline. Todo lo recaudado a través de actividades offline debe registrarse manualmente en CiviCRM para garantizar que los informes finales sean precisos.

Hay tres pasos dentro de CiviCRM orientados a la recaudación de fondos offline: crear listas de contactos, crear envíos de correo masivo, y [registrar contribuciones manualmente](https://docs.civicrm.org/user/es/latest/contributions/manual-entry-of-contributions )

Crear listas de contactos[¶](https://docs.civicrm.org/user/es/latest/contributions/offline-fundraising/#creating-your-lists)
----------------------------------------------------------------------------------------------------------------------

Este proceso es bastante sencillo, si está familiarizado con los procesos de búsqueda en CiviCRM.

Vaya a **Buscar > Buscar contactos** para crear una lista de contactos que serán los destinatarios del envío de correo electrónico (podría ser toda su base de datos).

Si desea realizar un seguimiento del éxito de este envío por correo electrónico o quiere saber quién recibe ciertos envíos, guarde los resultados de la búsqueda como un grupo. Use la casilla de verificación para seleccionar todos los contactos y elija la opción adecuada del menú desplegable **Acción**, **Grupo - agregar contactos** o **Grupo - crear grupo inteligente**). Más tarde, puede marcar a todos los miembros de ese grupo como destinatarios de ese envío mediante la opción **Agregar actividad** en el menú desplegable **Acciones**.

Si desea crear cartas para correos postales, puede hacerlo utilizando la función interna **Imprimir Cartas PDF** de CiviCRM, o puede exportar la lista como un archivo CSV y usar la combinación de correspondencia en un procesador de textos.

Para exportar una lista:

1.  Seleccione todos los contactos o un subconjunto de contactos utilizando las casillas de verificación y desde el menú desplegable de **Acciones**, elija **Exportar Contactos**  

2.  Elija si quiere **Exportar los campos PRINCIPALES** o **Seleccionar los campos a exportar**. Si elige exportar los campos principales, el fichero CSV se generará inmediatamente cuando haga clic en **Continuar**.  Si elige seleccionar los campos a exportar, haga clic en **Continuar**, le aparecerá un listado de opciones desplegables entre las que podrá elegir los campos que quiere exportar.

3.  Seleccione los campos requeridos; si desea guardar la lista de campos exportados como un mapa de exportación para un uso futuro, marque la casilla **Guardar el mapeo de este campo**.

4.  Haga clic en **Exportar** para generar el fichero CSV.

5.  Haga clic en **Hecho** cuando haya terminado, esto le llevará a la lista de contactos.

Crear envíos postales[¶](https://docs.civicrm.org/user/es/latest/contributions/offline-fundraising/#creating-postal-mailings)
--------------------------------------------------------------------------------------------------------------------------------

Una vez haya creado o exportado una hoja de cálculo, puede realizar la unificación de envíos utilizando cualquier software de procesador de textos (como Openoffice, el software gratuito de procesador de textos) que introducirá cualquier campo que necesite en su carta.

CiviCRM también puede crear etiquetas de correo.  Realice la misma búsqueda que hizo en la sección anterior para crear una lista de destinatarios, luego:

1.  Del menú desplegable de **Acciones**,seleccione **Imprimir Etiquetas de Correo**.

2.  Seleccione el número de etiqueta de correo, determine si quiere excluir a contactos que tienen marcada la opción ¨no enviar correo¨ en sus preferencias de privacidad y si quiere unificar dos contactos que tengan la misma dirección de correo postal en una sola etiqueta.  Esta última opción es muy útil cuando realiza el envío a familias o organizaciones y no quiere que reciban cartas por duplicado.  Cuando los contactos estén unificados, cada nombre aparece en su propia línea en la etiqueta.

3.  Haga click en **Etiquetas de Correo** Click y se creará un documento PDF para imprimir.

Tenga en cuenta que CiviCRM imprime etiquetas en el orden mostrado en la página de resultado de la búsqueda con un patrón de columna por columna. 