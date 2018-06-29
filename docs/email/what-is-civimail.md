¿Qué es CiviMail?
=================

El módulo de CiviMail es una herramienta sofisticada para tratar campañas masivas de correo electrónico. Puede entregar un gran volumen de correo electrónico y proporcionar informes detallados sobre los resultados y la efectividad de esos correos electrónicos. CiviMail se usa a menudo para complementar otros módulos de CiviCRM, por ejemplo, para enviar correos electrónicos a personas que no son miembros,  para alentarlos a convertirse en miembros o enviar correos electrónicos a personas que aún no se han registrado para un evento.

CiviMail (como todas las funciones de correo de CiviCRM) interactúa con su servidor de correo. La configuración del servidor de correo y la configuración adecuada de CiviMail son tareas del administrador del sistema y es posible que requieran asistencia profesional. También deberá verificar con su proveedor de alojamiento web para asegurarse de que cumplan con los requisitos de configuración, y conocer los límites que pueden tener sobre cuántos correos electrónicos puede enviar por día o mes. Un servidor de correo mal configurado es una responsabilidad y si no sabe lo que está haciendo, podría terminar fácilmente en una lista negra de correo no deseado. Salir de una lista negra de spam es mucho más difícil que entrar en ella. Para obtener más información sobre cómo configurar su servidor de correo, consulte el capítulo "Configuración del sistema de correo electrónico" en la sección Configuración inicial.

Escenario: gestionar listas de correo electrónico
--------------------------------------------------

El Centro para la Paz y la Reconciliación de St Ethelburga usa CiviEvent para llevar a cabo un programa anual de eventos sobre diferentes temas. Han creado una página de listas de correo donde las personas pueden inscribirse para recibir información sobre los eventos que les interesan. Luego usan CiviMail para enviar correos electrónicos a esas personas en función de esos eventos. Cuando alguien cancela la suscripción a una lista de correo de un tipo de evento, CiviCRM mantiene un registro de la baja.

St Ethelburga también suscribe automáticamente a cualquier persona que haya asistido a un evento sobre un tema específico para recibir correos electrónicos sobre ese tema. No tienen que preocuparse de enviar correos no deseados a las personas que se han dado de baja de una lista de correo de eventos específico, ya que CiviCRM recordará que se han cancelado la suscripción y no se han vuelto a suscribir.

De vez en cuando, St. Ethelburga envía otros correos electrónicos a una lista de correo que incluye casi todos los contactos en su base de datos con mensajes personales del director del centro que resaltan problemas particulares. A menudo, se envían dos versiones similares del mismo correo electrónico a diferentes grupos en su base de datos para probar qué formatos de mensaje son más efectivos. Pueden hacerlo enviando el correo electrónico a la mitad de los contactos de un grupo en particular y luego enviando otro correo electrónico que excluya a los contactos que ya recibieron el primer correo electrónico.

Escenario: movilizando por correo electrónico
---------------------------------------------

La Organización para Inquilinos de Townsville (TOFT, por sus siglas en inglés) realizó una encuesta y una petición para reunir datos y apoyo para la campaña Solicita vivienda pública asequible. La encuesta fue realizada por voluntarios que visitaban a los electores seleccionados en sus hogares, y la petición fue ampliamente promocionada entre el público, que podía firmar y responder preguntas en línea.

En las primeras etapas de la campaña, el coordinador voluntario de TOFT buscó contactos en el grupo Voluntarios y usó la acción Enviar correo electrónico para enviar un correo electrónico general solicitando voluntarios para ayudar con la encuesta. De aquellos que respondieron que estaban disponibles, se capacitó a un pequeño grupo para llevar a cabo las visitas domiciliarias y registrar las respuestas de la encuesta.

Una vez que se creó la petición en línea usando las herramientas en CiviCampaign, el responsable de comunicaciones de TOFT creó un correo electrónico que incluía texto, imágenes y enlaces para promocionar la campaña y alentar a las personas a hacer clic en el sitio y completar la petición en línea. Este correo electrónico se envió a toda la base de datos usando CiviMail, incluido un enlace de reenvío para que los destinatarios pudieran distribuir fácilmente el correo electrónico a través de sus propias redes.

CiviMail habilitó TOFT para rastrear las respuestas a este correo masivo; se generaron informes que muestran que el 89% de los destinatarios hicieron clic para firmar la petición, y el 75% la reenviaron a otros. Luego, estos datos se compararon con esfuerzos previos de encuestas y solicitudes fuera de línea para demostrar el mayor alcance de la campaña mediante el uso de CiviCRM.