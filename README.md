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
    

** Responder las siguientes preguntas brevemente sobre:**

**Soluciones de Salesforce**
    
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

