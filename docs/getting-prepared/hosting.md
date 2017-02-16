Alojamiento
========

Antes de instalar CiviCRM, se debe prestar cuidadosa atención a donde se alojará. Las principales opciones son:

Alojamiento interno
------------------

Si usted tiene un departamento de TI interno o miembros del personal con una formación técnica, puede alojar CiviCRM internamente. Para hacer esto, usted necesitará:

- Servidores o PCs dedicados disponibles para configurarse como servidor web en modo 24x7  
- Un espacio adecuado en sus instalaciones ubicar los servidores, posiblemente con aire acondicionado.
- Un sistema de alimentación ininterrumpido (SAI) para que el servidor esté disponible durante cortes de electricidad.- Una conexión estable a internet con una dirección IP estática con alta disponibilidad. Es importante destacar que si la conectividad a Internet de su oficina se cae sólo los usuarios de la red interna podrán acceder al sistema. Los visitantes externos no podrán acceder a su página web y realizar acciones como ingresar a CiviCRM o realizar contribución online. El ancho de banda es también un factor importante, ya que debe ser lo suficientemente alto para responder a las peticiones que su sitio web recibe.

También hay otros aspectos importantes a comentar. Si tiene una red interna, el servidor web debe estar separado de los otros equipos y servidores para mejorar la seguridad (por ejemplo en una VPN o una DMZ).
Un servidor web podría potencialmente introducir vulnerabilidades que un usuario externo, un script o un bot podrían utilizar como puerta entrada a sus sistemas privados. También es una buena idea investigar los costos de mantenimiento y gestión diario de tener un servidor interno y compararlos con los de utilizar un servidor externo.

Alojamiento externo
========

Con la experiencia adecuada podría gestionar la instalación y la configuración en un servidor interno, pero considere alojar CiviCRM con un proveedor externo. En este caso, se recomienda que contratar un VPS (Servidor Privado Virtual) para asegurarse de que tiene un control completo de su instalación (p. ej. PHP, MySQL, etc) y por lo tanto es capaz es capaz de configurarlos a sus necesidades específicas.

Muchos alojamientos compartidos restringen el nivel de acceso que tienen y pueden no permitirle instalar CiviCRM si no puede cumplir los requisitos necesarios. Los alojamientos compartidos pueden ser propensos a problemas de rendimiento, debido a que el hardware es compartido entre un grupo de clientes con diferentes niveles de uso. Si el sitio web de un cliente recibe un número grande de tráfico de manera repentina, el resto de sitios alojados pueden experimentar velocidades lentas o interrupciones.

Inconvenientes aparte, alquilar un servidor compartido es normalmente más barato que un VPS, ambos son servicios de suscripción mensuales o anuales (algunos descuentos pueden estar disponibles para alquileres a más largo plazo).

**Le aconsejamos probar cualquier servicio antes de comprometerse por períodos largos**

Alojamiento existente
------------------

Si ya utiliza un alojamiento Web, póngase en contacto con su proveedor para determinar si es compatible con los paquetes y librerías de CiviCRM. Si no es así, hay dos opciones:

### ** Migrar a otro alojamiento **.

En función del CMS que utiliza, el proceso de pasar de un host a otro puede ser bastante sencillo. Estás en una buena posición para transferir a otro host si puede:  

1. Solicitar que sus usuarios **dejen de crear y actualizar contenidos** durante la migración,2. **exportar e importar** todo el contenido desde/hacia el CMS elegido,3. **editar sus registros DNS** para cambiar los enlaces que apuntaban al sitio anterior por el nuevo sitio web

### **Ejecutar el sitio web y CiviCRM en distintos servidores**.

Si no puede mover su sitio we a un host diferente, podría contratar un segundo alojamiento para CiviCRM y ejecutar los dos sistemas en paralelo.

En este caso, puede utilizar un DNS CNAME para que apunte al servidor con CiviCRM con un subdominio (por ejemplo, civicrm.yourwebsite.com; el CNAME añade un prefijo a la dirección de su sitio web) y pueda enlazar a él desde su sitio web, tal vez con un botón de iniciar sesión.

Aparte de pagar un segundo servicio, una de las limitaciones de este enfoque es la necesidad de clonar el estilo de su sitio web en el segundo servidor para dar al usuario la sensación de que están en el mismo sitio. Si se cambian los cambios en el estilo web, también se debe cambiar en el segundo sitio.

Contratar a un implementador de CiviCRM
-------------------------------------------

Existen implementadores y expertos en la comunidad CiviCRM capaces de gestionar y alojar su sistema. Si se lo solicita, también pueden administrar una implementación local y una configuración en sus instalaciones.

Para una lista de expertos recomendada dentro de la comunidad, visite: [https://civicrm.org/providers] (https://civicrm.org/providers)


