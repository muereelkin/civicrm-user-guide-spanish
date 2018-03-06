Menu, Panel de control y Dashlets
============================

Este capítulo da una visión de conjunto del **Panel de Control** de CiviCRM que es su página de inicio y del menú de navegación disponible para personas que trabajan con CiviCRM.


El menú de navegación
-----------------------------------------------------------------------------------------------------------------------------------

El menú de navegación es una pequeña barra en la parte de arriba de cada página de CiviCRM.

![image](../img/4.5%20Menubar.png)

Proporciona acceso a casi todas las funciones de CiviCRM y está ampliamente organizado en cabeceras a través de componentes Civi individuales (como Contribuciones, Eventos y Envio de correos), con algunas excepciones para Buscar y Administrar, ambas de las cuales cubren todos los componentes de Civi habilitados.

![NavMenu_SearchPulldown](../img/CiviCRM_update-CiviCore-NavMenu_SearchPulldown-en.jpg "NavMenu_SearchPulldown")

Puede modificar el menú de navegación a través de la opción: **Administrar > Pantallas y Campos personalizados > Menú de Navegación** y así añadir o reorganizar los elementos del menú en la pantalla.

Recuerde que los cambios que haga en el menú de navegación serán vistos por todas las personas que tengan los permisos determinados para ver el menú, para bien o para mal, por lo que tenga cuidado cuando modifique el menú de navegación.

A la izquierda del menú de navegación hay un campo de búsqueda rápida. Consulte el capítulo sobre *Búsquedas* para más detalles.


El Panel de Control y los dashlets de la página principal
-----------------------------------------------------------------------------------------------------------------------------------------------------

Cuando se registra en CiviCRM por primera vez, la primera página que verá es el panel de control (página de inicio de CiviCRM). El panel de control le permite ver información importante sobre su página y CiviCRM a través de una serie de dashlets. Un dashlet es un informe que puede mostrar en el panel de control de su página principal. Muchos dashlets vienen por defecto con CiviCRM, y usted o su administrador pueden crear dashlets adicionales que sean específicos para las necesidades de su organización. Algunos ejemplos de dashlets que vienen por defecto con CiviCRM incluyen:

-   Informes de Donantes: un gráfico de barras de la cantidad del total de contribuciones por mes de los últimos cinco meses.

-   Actividades: una lista de actividades recientes que se han registrado en CiviCRM (como emails enviados a integrantes, donaciones realizadas, o reuniones programadas en CiviCRM).

-   Informe de Membresías: un cuadro de resumen de información sobre Miembros monitoreados por CiviCRM y desglosado por meses. Esto incluye el número de Miembros por tipo, el total de pagos realizados y el número de contribuciones hechas, entre otras cosas.

![Dashboard_homescreen](../img/CiviCRM_update-CiviCore-Dashboard_homescreen-en.jpg "Dashboard_homescreen")

Puede añadir estos dashlets a su panel de control de CiviCRM haciendo clic en la opción **Configurar Panel de Control** . Podrá ver una lista de dashlets que se pueden arrastrar hacia las columnas derecha o izquierda de su panel de control.

![Dasboard_editscreen](../img/CiviCRM_update-CiviCore-Dasboard_editscreen-en.jpg "Dasboard_editscreen")

Haga clic en **Finalizado** para salvar los dashlets en su panel de control. A partir de ahora, podrá ver las actualizaciones del estado de sus dashlets cada vez que se registre (si quiere comprobar y ver cualquier cambio que se haya producido recientemente, siempre puede hacer clic en **Recargar Datos del Panel de Control**, esto hará que se vuelva a cargar cada dashlet con la información nueva que se haya añadido). Por motivos de rendimiento, los dashlets están escondidos. Usted puede elegir cada cuanto tiempo se actualizan los dashlets a través de la opción **Administrar > Opciones del Sistema > Varios** *tiempo de espera del caché del Panel de Control*. 

Casi todos los informes de CiviCRM pueden aparecer disponibles como un dashlet.

Para crear un dashlet, siga los siguientes pasos:

-   Haga clic en **Informes > Crear Informes desde Plantillas**.

-   Seleccione la plantilla para el informe que desee usar.

-   Elija las opciones que quiere mostrar en su dashlet. Por ejemplo, quizás quiera que la versión del informe, para su panel de control, muestre siempre información de ¨Este trimestre¨ o ¨Este Año¨. También puede elegir mostrar el informe como una tabla, o como un gráfico de barras o sectores.

-   Haga clic en **Previsualizar Informe**

-   Haga clic en **Crear Informe**.

-   En la parte de abajo de la sección *Crear Informe*, seleccione la casilla **Disponible para el Panel de Control** . Los usuarios con permiso para ver la información podrán añadir el dashlet. (Consulte sección sobre permisos para más informacion).

-   Haga clic en **Crear Informe**

Ahora añada el dashlet a su panel de control

-   Haga clic en Página Principal para ver su panel de control.

-   Haga clic en **Configurar Panel de Control**. Arrastre el dashlet desde la tabla ¨Dashlets disponibles¨hasta la columna en la que quiera que aparezca.

-   Haga clic en **Finalizado**.

(Consulte la sección de Informes para más detalles sobre cómo utilizar los informes).
