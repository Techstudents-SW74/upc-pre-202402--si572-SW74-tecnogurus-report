

# Capitulo VI: Product Implamentation, Validation & Deployment

## 6.1 Software Configuration Management 
### 6.1.1 Software Development Environment Configuration
En esta sección se presentan los softwares correspondientes utilizados por los miembros del equipo y los enlaces utilizados para que cada uno tenga asignado el rol de administrador y pueda ejecutar sus cambios al proyecto:  
- **Miro:** Event Storming, Candidate Context Discovery, Domain Message Flows Modeling, Bounded Context Canvases
*Imagen*

Enlace del miro: https://miro.com/app/board/uXjVKkI6spU=/ 

- *Lucidchart:* Context Mapping, DDD Bounded Context Class Diagram
  
*Imagen*

- *Structurizr:* C4 Model System, Container, Component Diagram
  
*Imagen*

- *Vertabelo:* DDD Database Diagram
  
*Imagen*

- *Visual Paradigm:* Bounded Context Component Diagram
  
*Imagen*

- *Visual Studio Code:* Software Development
  
*Imagen*

  
- *Figma:* Web/Mobile Prototype & User Flow
  
*Imagen*

Enlace del figma: https://www.figma.com/design/nyBckh8w59BwWU4cN4DRW9/IoT?node-id=27-667&node-type=canvas&t=yWeXn4Jr6F7oE6yY-0 

### 6.1.2 Source Code Management
El manejo y la gestión de las diferentes modificaciones que se llevaron a cabo, fueron mediante una organización de GitHub para nuestro Startup. 

Organización: https://github.com/Techstudents-SW74 

Repositorio de Landing Page: https://github.com/Techstudents-SW74/LandingPage 

Deployment del Landing Page: https://techstudents-sw74.github.io/ 

Asimismo, se establecieron dos ramas correspondientes para el desarrollo:  

- Main: esta rama cuenta con la versión estable de nuestra landing page luego de que cada componente haya sido aprobado mediante una pull request. 

- develop: esta rama cuenta con versiones donde se pusieron a prueba los componentes que cada integrante implemento a la landing page

### 6.1.3 Source Code Style Guide & Conventions

###HTML:
Se aplicarán las directrices de “HTML Style Guide and Coding” de W3Schools, destacando convenciones clave como declarar siempre el tipo de documento (<!DOCTYPE>), utilizar etiquetas y atributos en minúsculas para mantener un código limpio y organizado, y cerrar todas las etiquetas para prevenir errores. Se colocarán comillas en los valores de los atributos y se especificarán siempre los atributos alt, width y height en las imágenes para mejorar la accesibilidad y el SEO. Además, no se omitirán las etiquetas <head> y los metadatos esenciales para la optimización en motores de búsqueda.

### CSS:
Basado en la “Google HTML/CSS Style Guide”, se seguirán prácticas recomendadas como usar nombres de clase generales, cortos y descriptivos, empleando guiones para separar palabras. Se evitarán los selectores de ID, priorizando selectores de clase, y se utilizarán propiedades abreviadas como margin, padding, y border para mejorar la legibilidad y reducir el número de líneas de código. Estas convenciones aseguran un estilo CSS más limpio y escalable.

### JavaScript:
Se implementarán las “JavaScript Best Practices” recomendadas por el W3C, priorizando nombres cortos y fáciles de entender para variables y funciones. Se evitará el uso de variables globales (var), prefiriendo let o const para evitar colisiones de nombres y errores a largo plazo. Se documentarán y comentarán solo las partes necesarias del código, explicando las secciones complejas, y se adoptarán notaciones y operadores sencillos para manipular estructuras de datos.

### Gherkin:
Para las pruebas, se seguirá la guía “Gherkin Conventions for Readable Specifications”, organizando claramente los bloques Given-When-Then mediante la indentación adecuada y el uso de la palabra clave "And" para pasos adicionales. Se utilizarán tablas cuando los pasos requieran mayor información y se emplearán comillas simples para los parámetros en los escenarios, mejorando la legibilidad. Los escenarios múltiples se separarán con comentarios para facilitar la organización visual.

### Frontend y Backend:
La landing page y las aplicaciones web seguirán las pautas de diseño de Material Design, utilizando Angular Material como biblioteca de componentes de UI. El frontend será desarrollado en Angular Framework, combinando HTML5, CSS3 y JavaScript/TypeScript para los aspectos estáticos y lógicos de las aplicaciones. En el backend, se implementarán servicios web bajo el estilo arquitectónico RESTful API usando Spring Boot y Java como lenguaje principal.

### Control de versiones:
El control de versiones será gestionado con GIT desde GitHub, siguiendo las prácticas de GitFlow Workflow junto con Conventional Commits y Semantic Versioning. Esto permitirá una integración continua, con despliegues automáticos y manejo eficiente de hotfixes.


### 6.1.4 Software Deployment Configuration
La siguiente tabla presenta los commits del repositorio del landing page en GitHub:
| Id del commit          | Commit           |
|------------------------|------------------|
|babf1bf8b1439d841dc4fde5b33f2aac61105ce0 |Initial commit |
|6aff73d0b39a7c9a4d5ae1c99d9338f9c6bd662d |Part 1 |
|b001457e48e36f514a12f978dbb9475c25c50e06 |Part 2 |
|                                         |Merge branch 'main' of https://github.com/Techstudents-SW74/LandingPage |
|70f08b4f25df21ae3535a38c6a58269014181cfd |Part 3 |
|bd7bee8feec07792a080e8d29913ebeb7db84b6e |Part 4 |
|d38272d239da0f26d26452496e6d3e89f8a871fe |(feat) "add header & footer" |

## 6.2 Landing Page, Services & Application Implementation 
En esta sección, se explicará y evidenciará el proceso de despliegue para la Landing page de nuestro startup, utilizando la herramienta de despliegue. Para lograr este objetivo se utilizó el CLI de esta herramienta y el GitHub donde se creó el repositorio. 

### 6.2.1 Sprint 1
#### 6.2.1.1 Sprint Planning 1 
A continuación, se presenta el Sprint Planning 1, donde se muestran las evidencias de planificación e implementación del Landing Page. Las evidencias se encuentran disponibles dentro del repositorio de GitHub.
| Sprint                        | Sprint 1            |
|-------------------------------|---------------------|
|Sprint Planning Background  |Initial commit |
|Date  |26 de septiembre del 2024 |
|Time  |13:00 horas (GMT-5) |
|Location  |Modalidad remota por Discord  |
|Prepared by  |Fabrizzio Antonio Castro Manrique  |
|Attendees (to planning meeting)  |Todos los integrantes del equipo |
|Sprint 1 – Review Summary  |En el primer sprint se estableció la agrupación de componentes y el despliegue del Landing Page. |
|Sprint 1 – Retrospective Summary |Para el primer sprint se estableció desarrollar el Landing Page y dividirlo por secciones. Establecimos un acuerdo de la utilización HTML, CSS y JS para seguir una arquitectura lineal y se pueda tener una mejor limpieza de código para eliminar o agregar secciones dentro de este. Se utilizaron diseños sobrios para poder utilizar conceptos de CSS de una forma más eficiente, asimismo como herramientas que permitieron su despliegue rápido dentro de Github |
|Sprint Goal & User Stories |                     |
|Sprint 1 Velocity | 33 |
|Sum of Story Points| 33 |

#### 6.2.1.2 Sprint Backlog
<table>
  <tr>
    <th colspan="2">Sprint #</th>
    <th colspan="6">Sprint 1</th>
  </tr>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item / Task</th>
  </tr>
  <tr>
    <th>Id</th>
    <th>Title</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned to</th>
    <th>Status</th>
  </tr>
  <tr>
    <th>US001</th>
    <th>Seccion de Header </th>
    <th>2</th>
    <th>Seccion de Header</th>
    <th>COMO usuario QUIERO visualizar un encabezado de página que contenga opciones PARA una mejor navegación por la página. </th>
    <th>2</th>
    <th>Fabrizzio Castro</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US002</th>
    <th>Seccion de Footer</th>
    <th>3</th>
    <th>Seccion de Footer</th>
    <th>COMO usuario QUIERO visualizar pie de página que contenga información PARA un mejor entendimiento de la página. </th>
    <th>1</th>
    <th>Nicolas Zagal</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US005</th>
    <th>Boton para ver mas informacion</th>
    <th>4</th>
    <th>Boton para ver mas informacion</th>
    <th>COMO usuario QUIERO ver más información sobre la página PARA comprender más sobre la start-up.  </th>
    <th>1</th>
    <th>Esteban Calderon</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US006</th>
    <th>Sección de contacto </th>
    <th>5</th>
    <th>Sección de contacto </th>
    <th>COMO usuario QUIERO observar una seccion que contenga información de la página PARA poder conocer sobre qué se trata. </th>
    <th>2</th>
    <th>Sandro Alarcon</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US003</th>
    <th>Barra de Navegación </th>
    <th>13</th>
    <th>Barra de Navegación </th>
    <th>COMO usuario QUIERO presionar botones en el encabezado del landing page para desplazarme por la página.  </th>
    <th>3</th>
    <th>Nicolas Zagal</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US004</th>
    <th>Descripción de la Start-Up </th>
    <th>14</th>
    <th>Descripción de la Start-Up </th>
    <th>COMO usuario QUIERO observar una seccion “Contacto” PARA poder comunicarme directamente con el equipo de desarrollo.</th>
    <th>2</th>
    <th>Esteban Calderon</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US007</th>
    <th>Sección de información del equipo </th>
    <th>15</th>
    <th>Sección de información del equipo </th>
    <th>COMO usuario QUIERO observar en el encabezado una seccion de información del equipo PARA conocer más a fondo su desarrollo. </th>
    <th>3</th>
    <th>Fabrizzio Castro</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US009</th>
    <th>Logout </th>
    <th>1</th>
    <th>Logout </th>
    <th>COMO cliente QUIERO salir de la aplicación PARA evitar el uso de mi cuenta por otras personas.  </th>
    <th>1</th>
    <th>Sandro Alarcon</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US014</th>
    <th>Sección de inicio de sesión  </th>
    <th>9</th>
    <th>Sección de inicio de sesión  </th>
    <th>COMO usuario QUIERO iniciar sesión en mi cuenta PARA acceder a la información de la plataforma.  </th>
    <th>2</th>
    <th>Fabrizzio Castro</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US015</th>
    <th>Sección de registro  </th>
    <th>10</th>
    <th>Sección de registro  </th>
    <th>COMO usuario QUIERO observar una seccion de “Regístrate” PARA crear una cuenta nueva.  </th>
    <th>2</th>
    <th>Nicolas Zagal</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US016</th>
    <th>Dirigir a perfil de usuario  </th>
    <th>18</th>
    <th>Dirigir a perfil de usuario  </th>
    <th>COMO cliente QUIERO acceder a mi perfil PARA cambiar cualquier dato que necesite actualización. </th>
    <th>3</th>
    <th>Sandro Alarcon</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US018</th>
    <th>Ver y editar datos de usuario  </th>
    <th>19</th>
    <th>Ver y editar datos de usuario  </th>
    <th>COMO usuario QUIERO ver y editar mi información PARA mantenerla actualizada.  </th>
    <th>3</th>
    <th>Esteban Calderon</th>
    <th>In Progress </th>
  </tr>
  <tr>
    <th>US025</th>
    <th>Enviar pedido guardado a cocina y caja  </th>
    <th>28</th>
    <th>Enviar pedido guardado a cocina y caja  </th>
    <th>COMO mesero QUIERO enviar pedidos a cocina o caja PARA continuar con el flujo de trabajo sin necesidad de dictar la orden manualmente. </th>
    <th>4</th>
    <th>Fabrizzio Castro</th>
    <th>In Progress </th>
  </tr>
  <tr>
    <th>US013</th>
    <th>Ver resumen de ventas</th>
    <th>30</th>
    <th>Ver resumen de ventas</th>
    <th>COMO administrador QUIERO ver el resumen de ventas por días PARA saber cuánto se vendió en cada jornada.  </th>
    <th>4</th>
    <th>Fabrizzio Castro</th>
    <th>In Progress </th>
  </tr>
</table>

#### 6.2.1.3 Development Evidence for Sprint Review

Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date)
--- | --- | --- | --- | --- | ---
tech-kitchen-webapp | feature/sidebar | 4eb7589 |feature/sidebar added | - | 19/09/2023
tech-kitchen-webapp | feature/inventory | 13fa79a | feature/inventory added | - | 19/09/2023
tech-kitchen-webapp | feature/sign up | b79d6a8 | feature/sign up added | - | 19/09/2023
tech-kitchen-webapp | feature/login | 597a41e | feature/login added | - | 21/09/2023
tech-kitchen-webapp | feature/profile | 02d5eab | feature/profile added | - | 21/09/2023
tech-kitchen-webapp | feature/product | 9dd841f | feature/product added | - | 21/09/2023
tech-kitchen-webapp | feature/home-project | 239aecd | feature/home-project added | - | 23/09/2023
tech-kitchen-webapp | feature/features | 27abcdf |  feature/features added | - | 23/09/2023
LandingPage | feature/aboutus | 5832e79 |feature/aboutus added | - | 25/09/2023
LandingPage | feature/functionalities | c69748b | feature/functionalities added | - | 25/09/2023
LandingPage | feature/navbar | 457fd51 | feature/navbar added | - | 25/09/2023
LandingPage | develop | 4524261 | footer added | - | 19/09/2023
LandingPage | feature/features | 13c7bbe | feature/features | - | 19/09/2023
LandingPage | develop | 929a124 | fix: general items | - | 19/09/2023


#### 6.2.1.4 Testing Suite Evidence for Sprint Review 
Para este sprint, no se han realizado las actividades requeridas en la sección de pruebas.  

#### 6.2.1.5 Execution Evidence for Sprint Review 

En el Sprint 1 se alcanzó a desarrollar una primera versión de las web apps y la landing page

Vistas desarrolladas: Landing page (Hero section):

<img src="./Resources/Evidences/Landing/1.jpg" >

Landing page (About us):

<img src="./Resources/Evidences/Landing/2.jpg" >

Landing page (Members):

<img src="./Resources/Evidences/Landing/3.jpg" >

Landing page (IOT features):

<img src="./Resources/Evidences/Landing/4.jpg" >

Landing page (Galelry section):

<img src="./Resources/Evidences/Landing/5.jpg" >

Landing page (Contact section y footer):

<img src="./Resources/Evidences/Landing/6.jpg" >

Vistas desarrolladas: Web app (profile):

<img src="./Resources/webapp/1.jpeg" >


Web app (login):

<img src="./Resources/webapp/2.jpeg" >

Web app (sign up):

<img src="./Resources/webapp/3.jpeg" >

Web app (caja):

<img src="./Resources/webapp/4.jpeg" >

Web app (cuentas guardadas):

<img src="./Resources/webapp/5.jpeg" >


Web app (mov. de caja):

<img src="./Resources/webapp/6.jpeg" >

Web app (productos):

<img src="./Resources/webapp/7.jpeg" >






#### 6.2.1.6 Services Documentation Evidence for Sprint Review
Para este entregable en el sprint 1, hemos considerado utilizar una fake api, el cual permite concer la funcionalidades y vistas de la web app.


https://my-json-server.typicode.com/Techstudents-SW74/Kitchen-fakeAPI 


<img src="./Resources/Evidences/fakeapi.jpg" >



#### 6.2.1.7 Software Deployment Evidence for Sprint Review 

Para este entregable se realizó el despliegue de la primera version de la landing page como tambien de la web app.

https://techstudents-sw74.github.io/



https://kitchentech-app.web.app/home-project



#### 6.2.1.8 Team Collaboration Insights during Sprint 

Para este entregable se realizó el despliegue de la primera version de la landing page como tambien de la web app. Es to permitió la presencia de los miembros del grupo para intervenir en el desarrollo como de:

Landing page:

<img src="./Resources/Evidences/landing.jpg" >

Weba app:

<img src="./Resources/Evidences/webapp.jpg" >


### 6.2.2 Sprint 2

#### 6.2.2.1 Sprint Planning 2.

A continuación, se presenta el Sprint Planning 2, donde se muestran las evidencias de planificación e implementación de web aplication, back end y app mobile. Las evidencias se encuentran disponibles dentro del repositorio de GitHub.
| Sprint                        | Sprint 2           |
|-------------------------------|---------------------|
|Sprint Planning Background  | El enfoque de este Sprint es consolidar los componentes críticos de la aplicación móvil, mejorar la interfaz de usuario de la aplicación web y asegurar la funcionalidad del backend. Además, se implementarán las conexiones iniciales para el sistema IoT, habilitando la interacción entre dispositivos y la plataforma para optimizar el flujo en restaurantes. |
|Date  |15 de octubre del 2024 |
|Time  |11:00 horas (GMT-5) |
|Location  |Modalidad remota por Discord  |
|Prepared by  |Fabrizzio Antonio Castro Manrique  |
|Attendees (to planning meeting)  |Todos los integrantes del equipo |
|Sprint 1 – Review Summary  |En el primer sprint se estableció la agrupación de componentes y el despliegue del Landing Page.  |
|Sprint 1 – Retrospective Summary | Para el primer sprint se estableció desarrollar el Landing Page y dividirlo por secciones. Establecimos un acuerdo de la utilización HTML, CSS y JS para seguir una arquitectura lineal y se pueda tener una mejor limpieza de código para eliminar o agregar secciones dentro de este. Se utilizaron diseños sobrios para poder utilizar conceptos de CSS de una forma más eficiente, asimismo como herramientas que permitieron su despliegue rápido dentro de Github |
|Sprint Goal & User Stories                     |
|Sprint 2 Goal | Este sprint se enfocará en desarrollar las primeras versiones funcionales de la aplicación web y móvil, integrándolas con el backend y la edge application. Esto permitirá a los restaurantes gestionar mesas, pedidos y optimizar la atención mediante sensores IoT. Esperamos que la aplicación web permita supervisar mesas, la app móvil facilite la toma de pedidos, y el backend junto a la edge application aseguren una integración fluida. Esto mejorará el servicio y reducirá los tiempos de atención. El objetivo se cumplirá cuando la web, la app móvil y la edge application estén integradas y funcionen correctamente con los sensores para gestionar clientes y pedidos en tiempo real. |
|Sprint 2 Velocity |  |
|Sum of Story Points|  |

#### 6.2.2.2. Sprint Backlog 2.

<table>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item / Task</th>
  </tr>
  <tr>
    <th>Id</th>
    <th>Title</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (hours)</th>
    <th>Assigned to</th>
    <th>Status</th>
  </tr>
  <tr>
    <th>US009</th>
    <th>Implementar botón para Cerrar Sesión</th>
    <td>1</td>
    <td>Botón de Cerrar Sesión en menú desplegable</td>
    <td>Como usuario, quiero un botón de "Cerrar Sesión" en el menú para salir fácilmente.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>2</td>
    <td>Implementar método de Recuperación de contraseña</td>
    <td>Como usuario, quiero un método para recuperar mi contraseña para acceder si la olvido.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>US010</th>
    <th>Implementar método de Recuperación de contraseña</th>
    <td>1</td>
    <td>Implementar vista de recuperar contraseña</td>
    <td>Como usuario, quiero una vista para recuperar mi contraseña para reiniciar el acceso a mi cuenta.</td>
    <td>3</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>2</td>
    <td>Implementar validaciones para vista de recuperar contraseña</td>
    <td>Como usuario, quiero validaciones en la vista de recuperar contraseña para asegurarme de que los datos ingresados sean correctos.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>3</td>
    <td>Implementar ver contraseña en vista de recuperar contraseña</td>
    <td>Como usuario, quiero ver mi contraseña en la vista de recuperar contraseña para asegurarme de que la estoy ingresando correctamente.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>TS001</th>
    <th>Implementar bloqueo de cuenta después de 5 intentos fallidos de inicio de sesión.</th>
    <td>1</td>
    <td>Bloquear acceso a la cuenta tras fallar en iniciar sesión 5 veces</td>
    <td>Como desarrollador, quiero bloquear el acceso a la cuenta tras 5 intentos fallidos de inicio de sesión para mejorar la seguridad del sistema.</td>
    <td>3</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>TS002</th>
    <th>Las contraseñas deben ser cifradas usando JWT</th>
    <td>1</td>
    <td>Cifrar contraseñas con JWT</td>
    <td>Como desarrollador, quiero cifrar contraseñas usando JWT para asegurar la autenticidad y protección de las credenciales de usuario durante la transmisión.</td>
    <td>3</td>
    <td></td>
    <td>Done</td>
  </tr>
  <th>US014</th>
    <th>Implementar navegación a perfil de usuario.</th>
    <td>1</td>
    <td>Crear botón para desplegar menú de opciones de usuario</td>
    <td>Como usuario, quiero desplegar el menú de opciones de usuario.</td>
    <td>1</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>2</td>
    <td>Implementar botón de ver perfil en menú desplegable</td>
    <td>Como usuario, quiero ver mi perfil en el menú desplegable.</td>
    <td>1</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <th>US015</th>
    <th>Ver y editar datos de usuario.</th>
    <td>1</td>
    <td>Backend Implementar edición de datos de usuario</td>
    <td>Como desarrollador, quiero implementar la edición de datos de usuario en el backend.</td>
    <td>3</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>2</td>
    <td>Backend - Endpoint del método update del usuario</td>
    <td>Como desarrollador, quiero implementar un endpoint para actualizar los datos del usuario en el backend.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>US016</th>
    <th>Implementar creación de usuario mesero</th>
    <td>1</td>
    <td>Implementar botón de crear nuevo mesero en menú desplegable</td>
    <td>Como usuario, quiero crear un nuevo mesero en el menú desplegable.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>2</td>
    <td>Crear validaciones para registro de nuevo mesero</td>
    <td>Como usuario, quiero validar el registro de un nuevo mesero para asegurar que la información ingresada sea correcta.</td>
    <td>1</td>
    <td></td>
    <td>In Process</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>3</td>
    <td>Implementar ver contraseña en la vista de crear nuevo mesero</td>
    <td>Como usuario, quiero ver la contraseña en la vista de crear nuevo mesero para asegurarme de que la estoy ingresando correctamente.</td>
    <td>1</td>
    <td></td>
    <td>In Process</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>4</td>
    <td>Endpoint de métodos de creación y autenticación</td>
    <td>Como desarrollador, quiero implementar un endpoint para los métodos de creación y autenticación de usuarios en el backend.</td>
    <td>3</td>
    <td></td>
    <td>To-Do</td>
  </tr>
    <tr>
    <th>US020</th>
    <th>Agregar productos a una orden.</th>
    <td>1</td>
    <td>Crear vista de caja con searchbar y sección acceso directo de productos</td>
    <td>Como usuario, quiero una vista de caja con una barra de búsqueda y una sección de acceso directo a productos para facilitar la búsqueda y selección rápida de artículos.</td>
    <td>5</td>
    <td></td>
    <td>To Fix</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>2</td>
    <td>Implementar edición de acceso directo de productos</td>
    <td>Como usuario, quiero editar los accesos directos a productos para personalizar y optimizar mi experiencia de compra.</td>
    <td>2</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>3</td>
    <td>Añadir productos a una orden para el servicio</td>
    <td>Como usuario, quiero añadir productos a una orden para el servicio para gestionar eficazmente lo que quiero solicitar.</td>
    <td>3</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <th>US021</th>
    <th>Guardar orden en una mesa.</th>
    <td>1</td>
    <td>Backend - Desarrollo del endpoint de las mesas insertado en una orden de cuenta.</td>
    <td>Como desarrollador, quiero desarrollar el endpoint para insertar mesas en una orden de cuenta para gestionar el seguimiento de las órdenes de manera eficiente.</td>
    <td>3</td>
    <td></td>
    <td>To Review</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>2</td>
    <td>Guardar orden en una mesa</td>
    <td>Como usuario, quiero guardar una orden en una mesa para registrar correctamente los pedidos realizados.</td>
    <td>1</td>
    <td></td>
    <td>To Review</td>
  </tr>
  <tr>
    <th>US022</th>
    <th>Guardar orden en una cuenta.</th>
    <td>1</td>
    <td>Guardar orden en una cuenta</td>
    <td>Como usuario, quiero guardar una orden en una cuenta para asociar los pedidos con el cliente correspondiente.</td>
    <td>2</td>
    <td></td>
    <td>To Fix</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>2</td>
    <td>Backend - Desarrollo del Endpoint de las cuentas</td>
    <td>Como desarrollador, quiero desarrollar el endpoint de las cuentas en el backend para gestionar la creación y actualización de cuentas de usuario.</td>
    <td>5</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <th>US028</th>
    <th>Crear nuevos productos</th>
    <td>1</td>
    <td>Crear vista de productos</td>
    <td>Como usuario, quiero crear una vista de productos para explorar y seleccionar artículos disponibles.</td>
    <td>3</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>2</td>
    <td>Crear botón de agregar nuevos productos</td>
    <td>Como usuario, quiero agregar nuevos productos para poder añadir artículos al inventario fácilmente.</td>
    <td>1</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>3</td>
    <td>Implementar validaciones para el guardado de productos</td>
    <td>Como usuario, quiero validar el guardado de productos para asegurar que la información ingresada sea correcta y completa.</td>
    <td>2</td>
    <td></td>
    <td>To-Review</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>4</td>
    <td>Implementar campo de agregar insumos a nuevo producto</td>
    <td>Como usuario, quiero agregar insumos a un nuevo producto para detallar los componentes necesarios para su elaboración.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>5</td>
    <td>Desarrollo del Endpoint de los productos</td>
    <td>Como desarrollador, quiero desarrollar el endpoint de productos en el backend para gestionar la creación, actualización y eliminación de productos.</td>
    <td>3</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <th>US042</th>
    <th>Ver cuentas guardadas</th>
    <td>1</td>
    <td>Crear vista de cuentas guardadas, debe contar con un searchbar y cards que incluyan el nombre de la cuenta, cliente, costo y botones</td>
    <td>Como usuario, quiero una vista de cuentas guardadas con una barra de búsqueda y tarjetas para acceder fácilmente a la información.</td>
    <td>5</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>2</td>
    <td>Implementar navegación a la página de caja con el pedido guardado al dar click en la cuenta</td>
    <td>Como usuario, quiero navegar a la página de caja con el pedido guardado para revisar y completar mi pedido fácilmente.</td>
    <td>2</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>US043</th>
    <th>Ver mesas creadas</th>
    <td>1</td>
    <td>Implementar botón para cambiar la vista de cuentas guardadas a mesas al costado de la searchbar</td>
    <td>Como usuario, quiero cambiar la vista de cuentas guardadas a mesas para facilitar la navegación entre las diferentes secciones.</td>
    <td>1</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <th>US044</th>
    <th>Editar mesas creadas</th>
    <td>1</td>
    <td>Implementar la vista de mesas con sus métodos CRUD</td>
    <td>Como desarrollador, quiero implementar la vista de mesas con sus métodos CRUD para gestionar eficientemente la creación, lectura, actualización y eliminación de registros de mesas.</td>
    <td>5</td>
    <td></td>
    <td>In-Process</td>
  </tr>
  <tr>
    <th>TS005</th>
    <th>Mantener las cuentas y mesas guardadas actualizadas en tiempo real para todos los usuarios del negocio</th>
    <td>1</td>
    <td>Mantener actualizado en tiempo real los pedidos y mesas</td>
    <td>Como desarrollador, quiero mantener actualizados en tiempo real los pedidos y mesas para que los usuarios vean la información más reciente.</td>
    <td>3</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>US045</th>
    <th>Eliminar cuenta creada</th>
    <td>1</td>
    <td>Implementar botón para eliminar cuenta</td>
    <td>Como usuario, quiero eliminar una cuenta para poder eliminar registros que ya no necesito.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>US023</th>
    <th>Agregar un cliente con DNI o RUC</th>
    <td>1</td>
    <td>Implementar botón para agregar un cliente, este debe solicitar tipo de documento, número de documento y nombre del cliente</td>
    <td>Como usuario, quiero agregar un cliente que solicite el tipo de documento, número de documento y nombre del cliente para poder registrar nuevos clientes de manera sencilla.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>TS009</th>
    <th>El cliente creado debe guardarse en la base de datos para poder acceder a él en caso se solicite nuevamente</th>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>To-Do</td>
  </tr>
<tr>
    <th>US029</th>
    <th>Crear nuevos insumos</th>
    <td>1</td>
    <td>Crear vista de insumos y su servicio</td>
    <td>Como usuario, quiero tener una vista de insumos y su servicio para poder gestionar y visualizar la información relacionada con los insumos utilizados.</td>
    <td>5</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <td>2</td>
    <td>Crear botón de agregar nuevo insumo</td>
    <td>Como usuario, quiero agregar un nuevo insumo para poder registrar insumos de manera rápida y sencilla.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <td>3</td>
    <td>Implementar validaciones para el insumo guardado</td>
    <td>Como usuario, quiero validar el insumo guardado para asegurar que la información ingresada sea correcta y completa.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <td>4</td>
    <td>Desarrollo del Endpoint de los Insumos</td>
    <td>Como desarrollador, quiero desarrollar el endpoint de insumos en el backend para gestionar la creación, actualización y eliminación de insumos.</td>
    <td>3</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <th>US030</th>
    <th>Editar productos existentes</th>
    <td>1</td>
    <td>Implementar botón de editar productos</td>
    <td>Como usuario, quiero editar productos para poder actualizar la información de los artículos existentes.</td>
    <td>1</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <td>2</td>
    <td>Cargar la vista de nuevo producto con los datos del producto guardado para su edición</td>
    <td>Como usuario, quiero una vista de nuevo producto con los datos del producto guardado para poder editar la información de manera eficiente.</td>
    <td>2</td>
    <td></td>
    <td>Done</td>
  </tr>
  <tr>
    <th>US031</th>
    <th>Editar insumos existentes</th>
    <td>1</td>
    <td>Implementar botón de editar insumos</td>
    <td>Como usuario, quiero editar insumos para poder actualizar la información de los insumos existentes.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <td>2</td>
    <td>Cargar la vista de nuevo insumo con los datos del insumo guardado para su edición</td>
    <td>Como usuario, quiero una vista de nuevo insumo con los datos del insumo guardado para poder editar la información de manera eficiente.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>US032</th>
    <th>Eliminar productos existentes</th>
    <td>1</td>
    <td>Crear botón de eliminar producto</td>
    <td>Como usuario, quiero eliminar un producto para poder eliminar artículos que ya no son necesarios.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>US033</th>
    <th>Eliminar insumos existentes</th>
    <td>1</td>
    <td>Crear botón de eliminar insumo</td>
    <td>Como usuario, quiero eliminar un insumo para poder eliminar insumos que ya no son necesarios.</td>
    <td>1</td>
    <td></td>
    <td>To-Do</td>
  </tr>
  <tr>
    <th>TS006</th>
    <th>Asociar productos a categorías</th>
    <td>1</td>
    <td>Crear campo de categoría en la vista de nuevo producto</td>
    <td>Como desarrollador, quiero crear un campo de categoría en la vista de nuevo producto para clasificar los productos de manera adecuada.</td>
    <td>1</td>
    <td></td>
    <td>Done</td>
  </tr>
</table>

#### 6.2.2.3. Development Evidence for Sprint Review.

Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date)
--- | --- | --- | --- | --- | ---
tech-kitchen-webapp | feature/sidebar | 4eb7589 |feature/sidebar added | - | 23/10/2024
LandingPage | feature/aboutus | 5832e79 |feature/aboutus added | - | 23/10/2024
kitchen-tech-backend | feature/aboutus | 5832e79 |feature/aboutus added | - | 23/10/2024
kitchen-tech | feature/aboutus | 5832e79 |feature/aboutus added | - | 32/10/2024
Mobile-aplication | feature/aboutus | 5832e79 |feature/aboutus added | - | 3223/10/2024



#### 6.2.2.4. Testing Suite Evidence for Sprint Review.

Para este sprint, .  

#### 6.2.2.5. Execution Evidence for Sprint Review.


En el Sprint 2, se logró desarrollar la aplicacion mobile, back end y version mejorada del front end:

Mejoras de desarrollo del front end():
Mejoras de desarrollo del front end():

Capturas de desarrolo: Back end ():
Capturas de desarrolo: Back end ():

Vistas desarrolladas: Mobile aplication ():
Vistas desarrolladas: Mobile aplication ():


#### 6.2.2.6. Services Documentation Evidence for Sprint Review.



#### 6.2.2.7. Software Deployment Evidence for Sprint Review.



#### 6.2.2.8. Team Collaboration Insights during Sprint.



## 6.3. Validation Interviews.




### 6.3.1. Diseño de Entrevistas.

- ¿Qué tan fácil te resultó navegar por la landing page y encontrar información relevante sobre el sistema?

- ¿La información proporcionada en la landing page te ayudó a comprender cómo la solución IoT podría mejorar la atención en el restaurante?
- ¿Qué aspectos de la aplicación te resultaron intuitivos o confusos al tomar un pedido?
- ¿Qué tan fácil te resultó recibir y gestionar notificaciones sobre el estado de las mesas (como la llegada de clientes o platos por recoger)?
- ¿Sientes que el proceso de enviar pedidos a cocina y caja desde la aplicación agiliza tu flujo de trabajo?
- ¿Cómo evaluas la velocidad y precisión de la aplicación al registrar cambios en los pedidos?
- ¿La interfaz de la aplicación facilita la gestión de cuentas y pagos de los clientes? ¿Por qué?
- ¿Qué tan útil te resulta la opción de recibir alertas cuando los clientes entran o salen del restaurante?
- ¿Crees que el sistema IoT implementado mejora la experiencia de servicio para el cliente? ¿En qué aspectos?
- ¿Qué cambiarías o mejorarías en la aplicación para facilitar aún más la atención a los clientes?

### 6.3.2. Registro de Entrevistas.




### 6.3.3. Evaluaciones según heurísticas.



## 6.4. Video About-the-Product.

Link del video: 

