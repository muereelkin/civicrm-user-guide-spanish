Trabajos programados
===================

CiviCRM se basa en una serie de trabajos programados que se ejecutan para mantener los datos actualizados y realizar ciertas tareas. Estos trabajos deben ser activados por un proceso denominado [cron](https://es.wikipedia.org/wiki/Cron_(Unix)) que se ejecuta regularmente en su servidor de alojamiento web.

Ejemplos de trabajos programados:

-	El procesamiento de miembros, que actualiza los estados de membresía.
-	La lista de espera de eventos, que invita a las personas que están en la lista de espera a registrarse para eventos cuando estén disponibles.
-	CiviMail envía y procesa el envío masivo de correos y el proceso de email.
-	CiviReport puede enviar por correo electrónico los informes regularmente

Algunos trabajos deben ejecutarse con mucha frecuencia, por ejemplo, la tarea de envío de correos electrónicos suele a ejecutarse cada 5 o 10 minutos. 

Otros necesitan ser ejecutados con menos frecuencia, por ejemplo, el script de actualización de miembros que puede ejecutarse una vez al día.

Existen dos formas de configurar los trabajos planificados:

-	A través de la interfaz de usuario, que puede configurar en **Administrar > Ajuste de Sistemas > Tareas Programadas**.
-	Mediante la configuración de múltiples "crons" para tareas específicas.

Estos métodos se detallan a continuación.

## ¿Qué es un cron?

Cron es un planificador automático basado en el tiempo que activa ciertos programas para ejecutar en su servidor web. Por lo general, cron (también conocido como "un cronjob") se puede configurar en su panel de control de alojamiento web o puede ser configurado por el administrador del servidor a cargo de su alojamiento web. Recomendamos elegir un alojamiento web que ofrece cron como un servicio gratuito.

Antes que los trabajos programados y configurados a través de la interfaz de usuario funcionen, necesitará configurar un trabajo CRON en el servidor web. 

Hay ejemplos de configuración de crons en la [guía de administración de CiviCRM (en inglés)](https://docs.civicrm.org/sysadmin/en/latest/)

## Configuración de tareas programadas a través de la interfaz de usuario

La interfaz de usuario para tareas programadas está diseñada para facilitar a las personas la configuración de trabajos programados y evitar tener que crear o editar un trabajo cron cada vez que desee realizar un cambio en un trabajo programado. Para la mayoría de las instalaciones pequeñas debería ser suficiente con la configuración por defecto. Los sitios más grandes deben considerar crear trabajos cron de manera normal para cada tarea. Eso requiere tener experiencia en administración de servidores.

La página de Trabajos programados **Administrar > Opciones del sistema > Tareas Programadas** está diseñada para facilitar la configuración de los trabajos programados y acceder al historial de la última ejecución. Muestra una lista de todos los trabajos programados disponibles. Puede editar cada uno de ellos y establecer su frecuencia (horaria, diaria, semanal, mensual, trimestral, anual o cada vez que se ejecuta el cron del servidor, que suele ser cada 5-10 minutos).

Puede encontrar una lista actualizada de los trabajos programados y los parámetros que se pueden enviar a ellos en la página de [Gestión de tareas programadas (inglés) de la guía de administración de sistemas](https://docs.civicrm.org/sysadmin/en/latest/setup/jobs/).
Algunos trabajos realizan tareas especiales de actualización de datos y no están diseñados para ejecutarse de forma automática o repetida. Estos son: "Actualizar saludos y destinatarios" y "Establecer fechas de recordatorio de renovación". Los detalles sobre cuándo ejecutarlos se proporcionan en la página de Gestión de tareas programadas de la guía de administración de sistema.

## Ejecución manual de trabajos programados

La página de trabajos programados también se puede utilizar para ejecutar trabajos programados de forma puntual. Esto es útil para algunos de los trabajos programados diseñados para ejecutarse de forma menos regular, incluido el trabajo de geocodificación y el trabajo de saludos y destinatarios. Ejecute un trabajo manualmente haciendo clic en el enlace *Más > Ejecutar ahora* para el trabajo seleccionado en *Administrar > Opciones del sistema> Tareas Programadas*.

## Programación de trabajos específicos mediante tareas cron individuales

Los administradores de sistemas suelen hablar de trabajos programados como "trabajos cron". Si ejecuta una gran cantidad de trabajos programados en conjuntos de datos grandes, puede que desee considerar la posibilidad de contratar a un administrador de sistemas con experiencia para trabajos cron. Esto permitirá un control más granular sobre cuándo y cómo se ejecutan estos trabajos, lo que puede ser útil si estos procesos generan una carga de procesamiento alta en sus servidor.