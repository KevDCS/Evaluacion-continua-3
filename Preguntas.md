## Preguntas

- 1 ¿Cuál de las siguientes es una característica general de las arquitecturas de servicios distribuidos? (1 punto)

  - A. Permiten la interoperabilidad entre diferentes sistemas
  - B. Aumentan la dependencia de sistemas monolíticos
  - C. Restringen el uso de protocolos estándares
  - D. Limitan la escalabilidad de las aplicaciones

- ### Respuesta: <strong>A</strong>

- 2 ¿Cuál es una característica de los certificados digitales? (1 punto)

  - A. Son válidos indefinidamente sin necesidad de renovación
  - B. Se utilizan únicamente para firmar correos electrónicos
  - C. Permiten la autenticación y el cifrado en comunicaciones electrónicas
  - D. No requieren una entidad certificadora para ser válidos

- ### Respuesta: <strong>C</strong>

- 3: ¿Qué estándar de seguridad se utiliza en servicios web para garantizar la autenticación y la integridad de los mensajes? (1 punto)

  - A. WS-Security
  - B. SSL
  - C. TLS
  - D. HTTP

- ### Respuesta: <strong>A</strong>

- 4: ¿Qué protocolo es comúnmente utilizado para la implementación de servicios web basados en mensajes? (1 punto)

  - A. SMTP
  - B. SOAP
  - C. FTP
  - D. REST

- ### Respuesta: <strong>A</strong>

- 5: ¿Cuál de las siguientes afirmaciones describe mejor el modelo RBAC (control de acceso basado en roles)? (1 punto)

  - A. RBAC permite a los usuarios definir sus propios roles y permisos.
  - B. RBAC asigna permisos a roles, y los usuarios se asignan a esos roles.
  - C. RBAC es un sistema de control de acceso basado en listas.
  - D. RBAC solo se utiliza en sistemas operativos, no en aplicaciones web.

- ### Respuesta: <strong>B</strong>

- 6: ¿Qué herramienta se puede utilizar para la definición y prueba de servicios web? (1 punto)

  - A. MySQL
  - B. Adobe
  - C. NetBeans
  - D. Postman

- ### Respuesta: <strong>D</strong>

- 7: ¿Qué tipo de criptografía utiliza una clave pública y una clave privada para cifrar y descifrar datos? (1 punto)

  - A. Criptografía simétrica
  - B. Criptografía asimétrica
  - C. Criptografía de flujo
  - D. Criptografía de bloque

- ### Respuesta: <strong>B</strong>

- 8: ¿Cuál es una ventaja clave de utilizar UDDI en servicios web? (1 punto)

  - A. Facilita el descubrimiento y la publicación de servicios web.
  - B. Mejora la compatibilidad entre diferentes lenguajes de programación.
  - C. Garantiza la encriptación de los datos transmitidos.
  - D. Permite la ejecución de código en múltiples plataformas.

- ### Respuesta: <strong>A</strong>

- 9: ¿Cuál es la diferencia principal entre servicios web basados en mensajes y servicios web basados en recursos? (1 punto)

  - A. Los servicios basados en mensajes permiten una comunicación segura, mientras que los basados en recursos no.
  - B. Los servicios basados en mensajes son más adecuados para aplicaciones móviles, mientras que los basados en recursos son más adecuados para aplicaciones web.
  - C. Los servicios basados en mensajes siempre utilizan el protocolo SOAP, mientras que los basados en recursos siempre utilizan REST.
  - D. Los servicios basados en mensajes se enfocan en la comunicación de datos, mientras que los basados en recursos se enfocan en el estado de los recursos.

- ### Respuesta: <strong>D</strong>

- 10: ¿Qué característica distingue a los servicios web SOAP de los servicios web REST? (1 punto)

  - A. Los servicios SOAP permiten la comunicación asíncrona, mientras que los servicios REST no.
  - B. Los servicios SOAP utilizan operaciones HTTP, mientras que los servicios REST utilizan protocolos personalizados.
  - C. Los servicios SOAP requieren un contrato definido en WSDL, mientras que los servicios REST se basan en URIs y utilizan operaciones estándar HTTP.
  - D. Los servicios SOAP son siempre más eficientes en términos de rendimiento que los servicios REST.

- ### Respuesta: <strong>C</strong>

- 11: ¿Cuál es la función principal de un proveedor de servicios en una arquitectura orientada a servicios (SOA)? (1 punto)

  - A. Crear y consumir servicios web
  - B. Proporcionar y publicar servicios web
  - C. Monitorizar el tráfico de la red
  - D. Gestionar bases de datos

- ### Respuesta: <strong>B</strong>

- 12: ¿A qué hace referencia el “ProductoPromocionPedidoId” en el siguiente fragmento de código? (1 punto)

  - A. Es una entidad que representa la tabla ProductoPromocionPedido en la base de datos.
  - B. Es un servicio que gestiona las operaciones de negocio relacionadas con ProductoPromocionPedido.
  - C. Es una clase que define la clave primaria compuesta de la entidad ProductoPromocionPedido.
  - D. Es una clase que contiene la lógica de implementación para la entidad ProductoPromocionPedido.

  - ### Respuesta: <strong>C</strong>


---------------------------------------------------------------------------------------------
## Problema práctico (12 puntos -un punto por cada apartado-)

<strong>Este ejercicio no requiere de código de programación</strong>

Eres el desarrollador principal de una aplicación web para una librería en línea. La aplicación necesita gestionar un catálogo de libros, las órdenes de los clientes y los detalles de cada usuario. Debes diseñar y seleccionar los servicios web adecuados para integrar estos componentes de manera eficiente y segura. Considera las siguientes tareas específicas:

### 1. Gestionar el Catálogo de Libros:

  - Obtener la lista completa de libros disponibles. (1 punto)
  - Añadir un nuevo libro al catálogo.  (1 punto)
  - Actualizar la información de un libro existente.  (1 punto)
  - Eliminar un libro del catálogo.  (1 punto)

### 2. Gestionar las Órdenes de Clientes:

  - Crear una nueva orden de compra.  (1 punto)
  - Obtener los detalles de una orden específica.  (1 punto)
  - Actualizar el estado de una orden.  (1 punto)
  - Eliminar una orden si es necesario.  (1 punto)

### 3. Gestionar los Detalles del Usuario:

  - Crear un nuevo perfil de usuario.  (1 punto)
  - Obtener la información de un usuario específico.  (1 punto)
  - Actualizar la información del usuario.  (1 punto)
  - Eliminar un perfil de usuario.  (1 punto)


## Tarea

Para cada una de las tareas mencionadas arriba, especifica qué tipo de método HTTP (GET, POST, PUT, DELETE) utilizarías y justifica tu elección. Considera los siguientes aspectos en tu reflexión:

- La naturaleza de la operación (lectura, creación, actualización, eliminación).
- La necesidad de seguridad en la transmisión de datos.
- La estructura y claridad del diseño del servicio web.
- Las especificaciones y estándares de los protocolos web.



## Respuestas:

### 1. Gestionar el Catálogo de Libros:
- Obtener la lista completa de libros disponibles. (1 punto) - 
  - Metodo: **GET** 
  - Justificacion: **GET** se utiliza para obtener la lista completa de libros disponibles, para que asi los usuarios puedan consultarlos.
- Añadir un nuevo libro al catálogo.  (1 punto)
  - Metodo: **POST**
  - Justificacion: **POST** se utiliza para añadir un nuevo libro al catálogo para que los usuarios puedan consultarlo.
- Actualizar la información de un libro existente.  (1 punto)
  - Metodo: **PUT**
  - Justficacion: **PUT** se utiliza para actualizar la información de un libro existente para que los usuarios puedan consultarlo.
- Eliminar un libro del catálogo.  (1 punto)
  - Metodo: **DELETE**
  - Justificacion: **DELETE** se utiliza para eliminar un libro del catálogo para que los usuarios puedan consultarlo.

### 2. Gestionar las Órdenes de Clientes:
- Crear una nueva orden de compra.  (1 punto)
  - Metodo: **POST**
  Justificacion: **POST** se utiliza para crear una nueva orden de compra para que los usuarios puedan consultarla.
- Obtener los detalles de una orden específica.  (1 punto)
  - Metodo: **GET**
  - Justificacion: **GET** se utiliza para obtener los detalles de una orden específica para que los usuarios puedan consultarla.
- Actualizar el estado de una orden.  (1 punto)
  - Metodo: **PUT**
  - Justificacion: **PUT** se utiliza para actualizar el estado de una orden para que los usuarios puedan consultarla.
- Eliminar una orden si es necesario.  (1 punto)
  - Metodo: **DELETE**
  - Justificacion: **DELETE** se utiliza para eliminar una orden si es necesario para que los usuarios puedan consultarla.

### 3. Gestionar los Detalles del Usuario:
- Crear un nuevo perfil de usuario.  (1 punto)
  - Metodo: **POST**
  - Justificacion: **POST** se utiliza para crear un nuevo perfil de usuario para que los usuarios puedan consultarlo.
- Obtener la información de un usuario específico.  (1 punto)
  - Metodo: **GET**
  - Justificacion: **GET** se utiliza para obtener la información de un usuario específico para que los usuarios puedan consultarlo.
- Actualizar la información del usuario.  (1 punto)
  - Metodo: **PUT**
  - Justificacion: **PUT** se utiliza para actualizar la información del usuario para que los usuarios puedan consultarlo.
- Eliminar un perfil de usuario.  (1 punto)
  - Metodo: **DELETE**
  - Justificacion: **DELETE** se utiliza para eliminar un perfil de usuario para que los usuarios puedan consultarlo.