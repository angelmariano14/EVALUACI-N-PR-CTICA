<p align="center">
  <img src="https://user-images.githubusercontent.com/69064746/158085652-2c35bd59-80ac-4ac1-92d8-b8f53a4613f4.jpg"/>
</p>

## Ejercicio 1
### Instalación del ambiente
Visual Studio Code
<p align="center">
  <img src="https://user-images.githubusercontent.com/97711819/172035247-e95148ce-911c-46f8-a6d6-fcc74045c498.png" />
</p>

GitBash
<p align="center">
  <img src="https://user-images.githubusercontent.com/97711819/172035275-de059186-bf74-4ec8-9777-39657a229262.png"/>
</p>

---
## Ejercicio 2

**1. ¿Qué es un servidor HTTP?**
- Un servidor HTTP es un sotfware que se encuentra del lado del servidor, donde se realiza una conexión directa con el cleinte (usuario) a través de su navegador web de forma bidireccional o unidireccional, dando respuestas visibles al cliente.
**2. ¿Qué son los verbos HTTP? Menciona los más conocidos**
- Los métodos de petición o los *verbos HTTP* existen para hacer peticiones predeterminadas a un recurso determinado como por ejemplo:

| VERBO | DESCRIPCIÓN |
| ------ | ------ |
| GET | El método GET  solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos. |
| HEAD | El método HEAD pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta. |
| POST | El método POST se utiliza para enviar una entidad a un recurso en específico, causando a menudo un cambio en el estado o efectos secundarios en el servidor. |
| PUT | El modo PUT reemplaza todas las representaciones actuales del recurso de destino con la carga útil de la petición. 
| DELETE | El método DELETE borra un recurso en específico. |
| TRACE |El método TRACE  realiza una prueba de bucle de retorno de mensaje a lo largo de la ruta al recurso de destino. |

**3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?**
- Un *request* es el mensaje que se envía desde el cliente al servidor para solicitar un recurso, una *response* es el mensaje que envía el servidor al cliente tras haber recibido una petición o HTTP *request*. <br>
Los HTTP *headers* son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc. Aquí algunos ejemplos:

<p align = "center">
  <img src= https://user-images.githubusercontent.com/69064746/158096428-75a26ed6-87b0-49d1-9797-36033e25f8cc.png />
</p>

La primera línea es la línea del request, que contiene su información básica (método HTTP, URL y versión). Lo demás son headers HTTP.
<br>

**4. ¿Qué es un queryString? (En el contexto de una url)**
- Las Query String o cadenas de consultas es un término que se utiliza para hacer referencia a una interacción con una base de datos. Además, es la parte de una URL que contiene los datos que deben pasar a las aplicaciones web.

**5. ¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?**
- Los códigos de estado de respuesta HTTP indican si se ha completado satisfactoriamente una solicitud HTTP específica. Las respuestas se agrupan en cinco clases:

|CLASE|RANGO|
| ------ | ------ |
| Respuestas informativas|100-199|
| Respuestas satisfactorias|200-299|
| Redirecciones|300-399|
| Errores de los clientes|400-499|
| Errores de los servidores|500-599|

**6. ¿Cómo se envía la data en un Get y cómo en un POST?**

|MÉTODO|CONCEPTO|OBSERVACIONES
| ------ | ------ | ------ |
| GET | GET lleva los datos de forma "visible" al cliente (navegador web). El medio de envío es la URL. Los datos los puede ver cualquiera. | Los datos son visibles por la URL, por ejemplo:www.aprenderaprogramar.com/action.php?nombre=pedro&apellidos1= gomez
| POST | POST consiste en datos "ocultos" (porque el cliente no los ve) enviados por un formulario cuyo método de envío es post. Es adecuado para formularios. Los datos no son visibles. | La ventaja de usar POST es que estos datos no son visibles al usuario de la web. En el caso de usar get, el propio usuario podría modificar la URL escribiendo diferentes parámetros a los reales en su navegador, dando lugar a que la información tratada no sea la prevista.

<br>

**7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página?**
-  Se utiliza el verbo GET

**8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.**
- *JSON_ son cadenas - útiles cuando se quiere transmitir datos a través de una red. Debe ser convertido a un objeto nativo de JavaScript cuando se requiera acceder a sus datos. Ésto no es un problema, dado que JavaScript posee un objeto global _ son cadenas - útiles cuando se quiere transmitir datos a través de una red. Debe ser convertido a un objeto nativo de JavaScript cuando se requiera acceder a sus datos. Ésto no es un problema, dado que JavaScript posee un objeto global _*JSON_ que tiene los métodos disponibles para convertir entre ellos. Como se describió previamente, un _JSON_ es una cadena cuyo formato recuerda al de los objetos literales JavaScript. Es posible incluir los mismos tipos de datos básicos dentro de un _JSON*_ que en un objeto estándar de JavaScript - cadenas, números, arreglos, booleanos, y otros literales de objeto. Esto permite construir una jerarquía de datos, como ésta:


![carbon (2)](https://user-images.githubusercontent.com/69064746/158222562-44a46f06-532e-4d4f-8973-a559ebdf9482.png)

- *XML_ es un lenguaje de marcado similar a HTML. Significa Extensible Markup Language (Lenguaje de Marcado Extensible) y es una especificación de W3C como lenguaje de marcado de propósito general. Esto significa que, a diferencia de otros lenguajes de marcado, _ es un lenguaje de marcado similar a HTML. Significa Extensible Markup Language (Lenguaje de Marcado Extensible) y es una especificación de W3C como lenguaje de marcado de propósito general. Esto significa que, a diferencia de otros lenguajes de marcado, _*XML*_ no está predefinido, por lo que debes definir tus propias etiquetas. El propósito principal del lenguaje es compartir datos a través de diferentes sistemas, como Internet. Aquí un rápido ejemplo:


![carbon (3)](https://user-images.githubusercontent.com/69064746/158232852-f49d86be-61df-44ca-b7ee-3cd4011d4108.png)

**9. Explicar brevemente el estándar SOAP**
- La comunicación dentro de internet esta establecida principalmente bajo protocolos como ya vimos antes, como por ejemplo: HTTPS, FTP o TCP. Sin embargo, *SOAP* es fundamental para los servicios web, interfaces a través de las cuales un dispositivo puede hacer uso de los servicios de un servidor, como por ejemplo las tiendas en línea como Amazon.

<br/>

- SOAP  juega un papel importante cuando un sistema quiere acceder a otro de manera ordenada y limitada. En lugar de darle al cliente solicitante acceso total al servidor, con un protocolo como SOAP puede limitarse el acceso a las funciones que necesita. La arquitectura del protocolo, al facilitar un marco al que la aplicación puede incorporarse, ofrece así la ventaja de que sistemas muy diferentes pueden cooperar entre sí. Ejemplo de una solicitud HTTP con SOAP :


![carbon (4)](https://user-images.githubusercontent.com/69064746/158235664-842d562d-09e1-491d-90e9-7e256ff3b0b9.png)

**10. Explicar brevemente el estándar RESTFUL**
- REST es una lógica de restricciones y recomendaciones bajo la cual se construyen API´s, resultando en RESTFUL API´s y no está atado a ningún lenguaje de programación, es por esto que se ha convertido en el estándar a la hora de hacer aplicaciones con una relación cliente servidor.

**11. Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?**
- Los headers en un request contienen toda la información básica (método HTTP, URL y versión) de la petición, a la espera de una *RESPONSE*

<br/>
- <code> Content-Type</code> es la propiedad de cabecera (header) usada para indicar el  media type (en-US) del recurso. En solicitudes (tales como <code>POST</code> o <code> PUT</code>), el cliente indica al servidor que tipo de dato es enviado actualmente.

### Sintaxis
<code>Content-Type: text/html; charset=utf-8
  <br/>
Content-Type: multipart/form-data; boundary=something</code>

- Por ejemplo: En una solicitud <code>POST</code>  , que resulta del envio de un formulario html, el <code> Content-Type</code> de la solicitud es especificado como un atributo enctype del elemento <code> form </code> .

![carbon (5)](https://user-images.githubusercontent.com/69064746/158243517-b52962c0-e7d7-450e-bd43-54effb4b7bcc.png)

---

## Ejercicio 3

**1. Realizar un request GET a la URL**: [https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json](https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json)

<img src="https://user-images.githubusercontent.com/97711819/172035467-dfb475bb-2631-4347-9e27-63bb51eb59a3.png"/>


**2. Realizar un request POST a la URL anterior, y con body:**

<code>
{
  "name":"Tu nombre"
  "email": tunombre.tuapellido@procontacto.com.mx
}
</code>

<img src="https://user-images.githubusercontent.com/97711819/172035505-dead334b-8f09-41e1-bb23-66f812ef1c41.png"/>

3. *Realizar nuevamente un request GET a la URL*  [https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json](https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json)
**¿Qué diferencias se observan entre las llamadas del punto 1 y el 3?**
- Mi request post fue satisfactorio, ahora mi nombre y correo fueron registrados en la URL y aparecen al momento de hacer un request GET:

<img src="https://user-images.githubusercontent.com/97711819/172035535-f1cc220b-160a-4d10-a0ff-0c1840558cf2.png"/>

---

## Ejercicio 4

**MÓDULOS DE TRAILHEAD

-LINK DEL PERFIL PUBLICO: https://trailblazer.me/id/avzquezdelmercadosnchez

<BR>
  
<img src="https://user-images.githubusercontent.com/97711819/172456945-f450e02b-900b-4fd0-bff8-e27b80ec546d.png"/>


## EJERCICIO 5

  <BR>
    
Explicar que son conceptualmente, qué datos almacenan en forma estándar y cómo se relacionan el resto (algunos no se relacionan entre sí) cada uno de los siguientes objetos de Salesforce:
    
  <BR>
    
    DIAGRAMA:
    
  <BR>
    
<img src="https://user-images.githubusercontent.com/97711819/172461605-050b4574-4aa7-4d95-83fa-100ec432260f.png"/>
    
    Conceptos:
    
**1.	Lead:**
    
El lead es un potencial cliente que demostró interés en un producto o servicio ofrecido por la marca a través de la interacción con contenidos y otros materiales.
    
**2.	Account:**
    
Se utilizan para almacenar información acerca de clientes o personas individuales con las que hace negocios. Existen dos tipos de cuentas. Las cuentas de negocio almacenan información acerca de compañías. Las cuentas personales almacenan información acerca de personas individuales.
    
**3.	Contact:**
    
Se utilizan los contactos para almacenar información acerca de personas con las que hace negocios. Los contactos se asocian habitualmente con una cuenta, pero también se pueden asociar con otros registros como oportunidades.
    
**4.	Opportunity:**
    
Las oportunidades son acuerdos en curso. Los registros de oportunidad realizan un seguimiento de detalles acerca de acuerdos, incluyendo para qué cuentas son, quiénes son las personas implicadas y las cantidades de las ventas potenciales.
    
**5.	Product:**
    
Productos son los elementos y servicios que distribuye a clientes. Cada producto puede existir en múltiples listas de precios con precios diferentes
    
**6.	PriceBook:**
    
Un PriceBook es una lista de productos y sus precios asociados. Cada producto y su precio se denomina entrada del libro de precios.Salesforce proporciona dos tipos de libros de precios: estándar y personalizados.
    
**7.	Quote:**
    
Las cotizaciones en Salesforce representan los precios propuestos de los productos y servicios de su empresa.
    
**8.	Asset:**
    
Los activos representan los productos específicos que sus clientes han comprado.
    
**9.	Case:**
    
Un caso es una pregunta, un comentario o un problema de un cliente. Los agentes del servicio de atención al cliente pueden revisar casos para ver cómo pueden ofrecer un mejor servicio. Los representantes de ventas utilizan casos para ver cómo afectan al proceso de ventas.
    
**10.	Article:**
    
Los artículos de conocimientos son documentos de información. Los artículos pueden incluir información sobre procesos, como cómo restablecer su producto a sus valores predeterminados o preguntas más frecuentes.
    
##    EJERCICIO 6
     <br><br>

**Responder las siguientes preguntas brevemente sobre:**

***Soluciones de Salesforce***  
     <br><br>
    
**A.	¿Qué es Salesforce?**

   Es la primera compañía que llevó el CRM a la nube
    
**B.	¿Qué es Sales Cloud?**

   Forma parte del sistema CRM que ofrece Salesforce, utilizando la nube para poder administrar el negocio donde sea que uno de encuentre.
    
**C.	¿Qué es Service Cloud?**

   Es una plataforma de servicio al cliente que permite ofrecer un servicio al cliente de clase mundial desde cualquier lugar gracias a sus herramientas innovadoras, datos integrados e informes en tiempo real.
    
**D.	¿Qué es Health Cloud?**

   Health Cloud es una plataforma especialmente diseñada para la gestión clínica de pacientes por medio de tecnologías on-cloud.
    
**E.	¿Qué es Marketing Cloud?**

   Marketing Cloud es una plataforma de marketing digital de Salesforce que incluye herramientas para el marketing por correo electrónico, el marketing a través de redes sociales, el marketing para dispositivos móviles, la publicidad online y la automatización del marketing.
    
 <br><br>
***Funcionalidades de Salesforce***
 <br><br>   
**A.	¿Qué es un RecordType?**
    
Los Record Types en Salesforce nos permiten definir diferentes Business Process, Pages Layouts y Picklist Values en un determinado objeto. Así mismo, los Record Types nos ayudan a mostrar distintos tipos de información según el perfil del usuario.
    
**B.	¿Qué es un ReportType?**
    
Indica el tipo de informe al que pertenece la plantilla seleccionada previamente por el creador de la misma.
    
**C.	¿Qué es un Page Layout?**
    
Nos permite personalizar el diseño y organización de detalle y editar páginas de registros en Salesforce. Los diseños de página se pueden utilizar para controlar la apariencia de los campos, las listas relacionadas y los enlaces personalizados en la página de edición y detalle de objetos estándar y personalizados.
    
**D.	¿Qué es un Compact Layout?**
    
Los formatos compactos controlan qué campos aparecen en el encabezado. Para cada objeto, puede asignar hasta 10 campos, incluyendo el campo Nombre, para mostrar en esa área.
    
**E.	¿Qué es un Perfil?**
    
Los perfiles definen cómo acceden los usuarios a objetos y datos y qué pueden hacer en la aplicación.
    
**F.	¿Qué es un Rol?**
    
Es aquella función que determina los niveles de acceso que tienen los usuarios.
    
**G.	¿Qué es un Validation Rule?**
    
Las reglas de validación verifican que los datos ingresados por usuarios en registros cumplen los estándares que especifica antes de poder guardarlos. Una regla de validación puede contener una fórmula o expresión que evalúa los datos en uno o más campos y ofrece un valor “Verdadero” o “Falso”.
    
**H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?**
    
En Lookup, no es obligatorio especificar cuál es el registro principal del objeto “hijo”, mientras que en Master Detail, tenemos que especificar el registro principal para el registro secundario.
    
**I.	¿Qué es un Sandbox?**
    
Un Sandbox es una copia de su organización en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación. Los sandbox están completamente aislados de su organización de producción de Salesforce.
    
**J.	¿Qué es un ChangeSet?**
    
Un conjunto de cambios entrantes es un conjunto de cambios que se ha enviado desde otra organización de Salesforce a la organización en la que ha iniciado sesión. Un conjunto de cambios se debe implementar para que los cambios surtan efecto.
    
**K.	¿Para qué sirve el import Wizard de Salesforce?**
    
Se puede utilizar para importar un máximo de 50,000 registros.
    
**L.	¿Para qué sirve la funcionalidad Web to Lead?**
    
Sirve para definir una campaña o fuente de clientes potenciales colocando valores dentro de los campos ocultos.
    
**M.	¿Para qué sirve la funcionalidad Web to Case?**
    
Para ver cómo afectan al proceso de ventas., responder a casos satisface a sus clientes y mejora su marca.
    
**N.	¿Para qué sirve la funcionalidad Omnichannel?**
    
Omni- canal es una función personalizable y flexible que se puede configurar de forma declarativa en Salesforce, es decir, sin necesidad de escribir código. OmniCanal ayuda al enrutamiento automático de diferentes tipos de elementos de trabajo (como casos y clientes potenciales) a los agentes.
    
**O.	¿Para qué sirve la funcionalidad Chatter?**
    
Chatter facilita la conexión con las personas y la información que les es más relevante.
    
   ***Conceptos generales***
    
    
**A.	¿Qué significa SaaS?**
    
Software como servicio, o Software as a Service.
    
**B.	¿Salesforce es Saas?**
    
Salesforce es PaaS, que significa plataforma como servicio, y es una derivada de SaaS.
    
**C.	¿Qué significa que una solución sea Cloud?**
    
De una manera simple, la computación en la nube es una tecnología que permite acceso remoto a softwares, almacenamiento de archivos y procesamiento de datos por medio de Internet, siendo así, una alternativa a la ejecución en una computadora personal o servidor local.
    
**D.	¿Qué significa que una solución sea On-Premise?**
    
El software on-premise está instalado en los servidores y dispositivos locales de la empresa. Esto permite tener acceso físico a la información y control directo de la configuración, manejo y seguridad de esos datos.
    
**E.	¿Qué es un pipeline de ventas?**
    
El pipeline de ventas es, precisamente, el proceso de actividades y estrategias que necesita un vendedor para acelerar el ciclo de ventas, transformando clientes potenciales (aquellos que acaban de conocer tu marca o servicio) en clientes.
    
**F.	¿Qué es un funnel de ventas?**
    
Es la forma en que una empresa planea y establece procesos para ponerse en contacto con los diferentes usuarios y así llegar a cumplir un objetivo final, que bien puede ser la conversión de clientes, lograr un registro, cerrar una venta, entre otras.
    
**G.	¿Qué significa Customer Experience?**
    
Es la experiencia del cliente al usar nuestros servicios.
    
**H.	¿Qué significa omnicanalidad?**
    
Es una estrategia de comunicación utilizada para estar en contacto con los prospectos o clientes a través de diferentes canales (email, redes sociales, sitio web, etc.).
    
**I.	¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?¿Qué es un KPI?**
    
El término B2B nace de la expresión en inglés “business to business” (empresa a empresa). Es decir, son las ventas de una empresa a otra.
    
B2C es el acrónimo en inglés de “business to consumer” (empresa a consumidor). Es decir, es un modelo de negocio en el que una empresa le vende de forma directa al consumidor final.
    
Un KPI, conocido también como indicador clave o medidor de desempeño o indicador clave de rendimiento, es una medida del nivel del rendimiento de un proceso. El valor del indicador está directamente relacionado con un objetivo fijado previa y normalmente se expresa en valores porcentuales.
    
**J.	¿Qué es una API y en qué se diferencia de una Rest API?**
    
Por lo general, la API sigue el formato de aplicación a aplicación, mientras que REST sigue una estructura diferente: Cliente-Servidor. El cliente y el servidor están evolucionando de forma independiente, proporcionando más flexibilidad en el trabajo.
    
**K.	¿Qué es un Proceso Batch?**
    
Es un sistema que induce a la producción de cantidades finitas de material, sometiendo las cantidades de material de entrada a un conjunto ordenado de actividades de procesamiento sobre un periodo finito de tiempo, usando uno o más recursos.
    
**L.	¿Qué es Kanban?**
    
Kanban hace referencia a las tarjetas visuales. Esta metodología es muy sencilla, se puede actualizar y los equipos de trabajo la pueden asumir sin problema.
    
**M.	¿Qué es un ERP?** 
    
Es un tipo de software que las organizaciones utilizan para gestionar las actividades empresariales diarias, como la contabilidad, el aprovisionamiento, la gestión de proyectos, la gestión de riesgos, el cumplimiento y las operaciones de la cadena de suministro.
    
**N.	¿Salesforce es un ERP?**
    
Si, ya que complementa las plataformas de planificación de recursos de negocio (ERP) mediante la conversión de los datos de la gestión de procesos desde el prospecto hasta el pedido de Salesforce CPQ en datos de transacciones.

