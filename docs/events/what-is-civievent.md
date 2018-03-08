¿Qué es CiviEvent?
==================

CiviEvent proporciona un conjunto de herramientas para organizar eventos. Estas
herramientas le harán más eficiente como organizador de eventos y reducirán el
número de procesos administrativos necesarios.

CiviCRM le ayuda a gestionar tanto los procesos de registro simples como los
complicados. Algunas características principales incluyen:

-   auto-inscripción de participantes, incluyendo los pagos online.

-   seguimiento de registros, cancelaciones, y asistencias

-   promoción de sus eventos en su página web

-   simplificación en la organización para eventos similares y recurrentes con
    plantillas y funcionalidades de copia.

-   registro de los participantes en el lugar del evento desde cualquier
    ordenador con conexión a internet

Escenario: Taller de liderazgo juvenil
--------------------------------------

Un grupo de arte de la comunidad, *Arts in Action,* lleva a cabo talleres para
personas menores de 25 años durante el año.

El personal de comunicación de *Arte en Acción* utiliza CiviEvent para gestionar
eficientemente cada taller desde el principio de su planificación hasta el final
de su evaluación. Primero, un empleado crea una página para el evento que
incluye un formulario de registro online. Debido a que este es un evento
regular, un empleado ha creado previamente una plantilla del evento, que cubre
la mayor parte de información que se necesitará en el proceso de la organización
del evento. Hay un precio fijo por inscripción, con cuotas adicionales para
talleres opcionales; los asistentes pueden elegir en lo que se inscriben y
pueden pagar online. El formulario de inscripción también recoge información
sobre la comida de los participantes y sus preferencias de alojamiento usando la
opción de CiviCRM llamada perfil.

Se crea una lista de jóvenes y grupos específica de entre los contactos
existentes y los empleados envían invitaciones personalizadas utilizando
CiviMail (también basadas en plantillas, para así reutilizar la información de
un evento a otro). La invitación incluye un enlace directo a la página del
evento para que los participantes puedan acceder a la inscripción online con un
solo clic. El evento también se anuncia públicamente en la página web de Arte en
Acción y se habilita la función de ¨Díselo-a-un-amigo¨ para que la información
pueda difundirse a través de las redes de la gente.

Se designa a un empleado para gestionar el proceso por el que los participantes
se registran ellos mismos. Debe supervisar el proceso periódicamente, para
asegurarse que los pagos se hacen, gestionando la lista de espera cuando las
inscripciones de participantes exceden el número máximo y contestando preguntas.

En el día del evento, los organizadores pueden controlar in situ a cada
asistente para llevar un seguimiento a tiempo real de quién asiste al evento y
de si hay alguna ausencia. Se podrá solicitar a los participantes con tasas
pendientes que paguen en ese momento. La base de datos se actualiza
inmediatamente, dejando libres espacios para aquellos que estaban en la lista de
espera y grabando los pagos realizados.

Después de cada taller, los empleados de Arte en Acción evaluan el éxito del
evento y usan CiviEvent para generar informes rápidamente como el número de
asistentes, el total de tasas pagadas y el la cantidad de tasas todavía
pendientes de pago. El evento y las plantillas de envío de correo pueden
actualizarse si fuera necesario y guardadas para el próximo evento.

Algunos conceptos clave
-----------------------

El capítulo en esta sección le llevará a través de todo lo que necesita saber
con el objetivo de sacarle el mayor partido a CiviEvent. Más abajo encontrará
varios conceptos que podrá encontrar útiles antes de organizar su evento. Pondrá
en práctica estos conceptos en el capítulo siguiente de esta sección.

### Eventos, participantes y contactos

Primero explicaremos algunos conceptos básicos. CiviCRM le permite crear uno o
más **eventos** en los que sus **contactos** pueden participar. Cuando un
contacto participa en un evento pasa a llamarse **participante**.

### Tipos de Evento

CiviCRM le permite definir diferentes tipos de eventos, como conferencias,
reuniones y eventos de captación de fondos. El tipo de evento que cree depende
de usted según sean las necesidades de su organización.

Los tipos de evento resultan útiles si tiene diferentes necesidades por tipo de
evento. Por ejemplo, puede crear campos personalizados para almacenar y mostrar
información adicional sobre un evento según su tipo de evento. Consulte el
capítulo *Información personalizada o Eventos* en esta sección para más
información sobre este punto. También son útiles para categorizar y segmentar
eventos y asistentes, por ejemplo, podría encontrar fácilmente todos los
contactos que hayan participado en alguna de sus formaciones o haya asistido a
alguno de sus eventos de captación de fondos.

### Papeles de los participantes

A todo contacto que participa en un evento se le asigna un papel de
participante. El más frecuente es probablemente asistente. Otros incluyen
voluntario o ponente. Los papeles de los participantes son totalmente
personalizables para que coincidan con el tipo de eventos que realiza su
organización. Esto le permite segmentar participantes por categorías relevantes
según su implicación en el evento, por ejemplo, para enviar un correo
electrónico solo a voluntarios o crear una lista de anteriores *capitanes de
mesa* para fundraisers.  También puede crear campos personalizados que se
aplican solo a papeles específicos, por ejemplo, recoger información sobre la
disponibilidad de solo voluntarios.

### Estado de los participantes

Los estados de los participantes (por ejemplo, registrados, en lista de espera,
asistió o cancelado) se usan para realizar el seguimiento de la etapa en la que
se encuentra el contacto dentro su ¨viaje/evento¨.  Los estados de los
participantes son totalmente personalizables para que coincida con la forma en
la que su organización realiza el registro del evento.  Esto le permite
segmentar a los participantes en categorías representativas basadas en su
comportamiento con respecto al evento, con la intención de crear procesos como
la generación de hojas de firmas, realizar el seguimiento de cuántas personas
tienen la intención de asistir al evento y adaptar las comunicaciones por correo
electrónico a los inscritos.

Otras partes de CiviCRM que funcionan con CiviEvent
---------------------------------------------------

CiviEvent está diseñado para funcionar junto a otras partes de CiviCRM.  Por
ejemplo, puede promocionar el evento a una lista específica y comunicarse con
los participantes del evento a través del correo electrónico antes y después del
evento usando CiviMail (para más información diríjase a la sección  *Correo
Electrónico, *en especial a los capítulos de *Instalación *y * Recordatorios de
horarios*).  CiviEvent funciona con CiviContribute para permitirle aceptar pagos
del evento en línea.  Para hacer esto, debe habilitar CiviContribute e instalar
un procesador de pagos;  para más información diríjase a la sección *Contribuciones*.
