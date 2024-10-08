# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines
A continuación, se presentan las directrices generales de estilo que definirán la presentación y consistencia visual de nuestra solución, enfocada los servicios de nuestros clientes. Estas guías aseguran que el diseño mantenga una coherencia en todos los puntos de contacto con el usuario, garantizando una experiencia visual fluida y profesional. 

### 5.1.1. General Style Guidelines
#### Branding
<img src="./Resources/images/branding.png">

#### Typography
<img src="./Resources/images/typography.png">

#### Colors
<img src="./Resources/images/colors.png">

#### Spacing
El diseño utiliza un sistema de espaciado basado en múltiplos de 8px para asegurar consistencia entre los distintos elementos de la interfaz. Este sistema permite mantener un ritmo visual agradable y ordenado, mejorando la experiencia de usuario.

Margen y Padding: 8px, 16px, 32px 

Separación entre secciones principales: 64px 
#### Icons
<img src="./Resources/images/icons.png">

#### Images or Illustrations
<img src="./Resources/images/images.png">

### 5.1.2 Web, Mobile and IoT Style Guidelines
#### Web Style Guidelines
En nuestras pautas de estilo web, priorizamos la adaptación de nuestros principios de diseño a la experiencia de usuario en entornos de navegación en línea. Esto incluye: 

+ **Diseño Responsivo:** Establecemos directrices para la adaptación de la interfaz a diferentes tamaños de pantalla, como los formatos 16:9, desde computadoras de escritorio hasta tabletas. Garantizamos que la experiencia de usuario sea óptima en diversos dispositivos.
+ **Navegación:** Para una navegación intuitiva, utilizaremos una barra de navegación (Navbar) para organizar los menús en el caso de la landing page, para la web app utilizaremos un sidebar para un mayor entendimiento y mayor rapidez en la adaptabilidad del usuario para con la aplicación. Además, como parte de las prácticas de diseño responsivo, implementaremos un "Botón hamburguesa" en el menú para facilitar la navegación en pantallas más pequeñas.

#### Mobile Style Guidelines
Para nuestra versión móvil, nos enfocamos en optimizar la experiencia en dispositivos móviles, asegurando una interfaz eficiente y amigable para el usuario. Esto incluye: 

+ **Diseño de Pantalla:** Definimos la disposición de elementos en pantallas más pequeñas, considerando proporciones específicas para Android y iOS, para garantizar una usabilidad efectiva y una navegación sencilla. 
+ **Adaptación de Contenido:** Ofrecemos recomendaciones para adaptar y priorizar el contenido en dispositivos móviles, manteniendo su relevancia y utilidad, y asegurando una experiencia de usuario coherente en diferentes sistemas operativos móviles. 
+ **Compatibilidad de Dispositivos:** Aseguramos que la aplicación móvil sea compatible con una amplia variedad de dispositivos y sistemas operativos móviles, abarcando tanto Android como iOS.

#### IoT Style Guidelines
Nuestro enfoque en las pautas de estilo para dispositivos IoT, como sensores de movimiento y sonido, se centra en la presentación clara de datos y la eficiencia en la comunicación de información esencial. Aquí están los aspectos clave: 

+	Tendremos una seccion  de simulación donde consumiremos las respuestas de los sensores y en base a este en la seccion de simulación se mostrará una imagen representativa del estado de los comensales en una mesa.

## 5.2 Information Architecture
### 5.2.1 Organization Systems
Establecer una jerarquía visual clara es fundamental para la creación de una página web altamente optimizada. Esto se debe a la forma en que nuestros sistemas visuales están interconectados; tenemos la tendencia natural de escanear y procesar rápidamente diversos elementos visuales, como bordes, contrastes, tamaños y movimientos, para evaluar y comprender nuestro entorno. Esta dinámica es aplicable tanto si estamos contemplando un paisaje impactante como si estamos navegando por una página web. Luego se presentarán ejemplos de la jerarquía visual que se prevé implementar en nuestras aplicaciones. 

El flujo que deseamos que los usuarios experimenten al ingresar a la aplicación se describe de la siguiente manera: 

+ En principio, el usuario ingresa sesión o se registra, para poder acceder a los servicios que brindamos este debe primero adquirir uno de nuestros planes de subscripción. 
+ Luego de iniciar sesión y adquirir una licencia, el usuario puede acceder a nuestros servicios que están ordenados en un sidebar para un mayor entendimiento por parte del usuario. 
+ El flujo es el siguiente, el usuario registra una nueva cuenta indicando la cantidad de comensales, su engargado y más datos relevantes mediante un formulario. 
+ Luego de realizar ello, pasamos a una sección de simulación donde se definirá el estado de los comensales y su mesa en sí, gracias a los datos devueltos por los sensores de movimientos y sonidos. 
+ Con estos datos, la aplicación puede ofrecer un servicio personalizado automático con alertas que se delegará a los meseros, que podrán revisar en qué estado se encuentra cada mesa y cómo afecta a su flujo.

### 5.2.2 Labelling System
En esta sección, presentaremos el sistema de etiquetado que proporcionará una descripción concisa y clara de la información presentada en cada aplicación. Comenzaremos detallando los encabezados que estarán disponibles en nuestra Landing page. \

+ **Inicio/Home:** Esta sección preseleccionada por defecto ofrecerá una breve descripción que representará la aplicación y proporcionará una idea del objetivo principal de esta. 
+ **Conócenos/About Us:** En esta sección, los clientes podrán obtener información sobre nuestro equipo, ver nuestra misión, visión, conocer quiénes somos y qué hacemos. 
+ **IoT:** En esta sección, los clientes pueden ver información sobre cómo se implementará IoT en la aplicación y como este mejorará la administración del negocio del sector alimenticio. 
+ **Servicios/Services:** La sección de características se encuentra dividida en segmentos objetivos, donde mostraremos los beneficios que nuestro sistema ofrece para cada uno de ellos. 
+ **Team:**  En esta sección los clientes pueden ver al equipo de desarrollo de la aplicación. 
+ **Contact:** En esta sección, los clientes pueden comunicarse con el equipo de Kitchentech.

### 5.2.3 SEO Tags and Meta Tags

Para mejorar la visibilidad del servicio en los motores de busqueda, se añadiran etiquetas SEO y meta etiquetas en nuestra landing page. Los títulos y funciones core de nuestra appp están optimizados para atraer a los usuarios y a los motores de búsqueda.

### 5.2.4 Searching System

El sistema de búsquedas de la aplicación permitirá a los meseros buscar sus productos en una lista. Asi mismo, permitira guardarlos en favoritos de manera que aparezcan en la pagina principal a manera de tarjeta para un seleccionado mas eficiente. De la misma manera se desplegaran los pedidos pendientes y las mesas.


### 5.2.5 Navigation System
El sistema de navegacion princpial de la aplicacion sera una barra lateral la cual contara con accesos rapidos a todas las funcionalidades de la aplicacion: Caja, pedidos guardados, historial de ventas, reporte de ventas, inventario, movimientos de caja y productos

## 5.3 Landing Page UI Design
### 5.3.1 Landing Page Wireframe
<img src="./Resources/images/Wireframes/WFLP1.png">
<img src="./Resources/images/Wireframes/WFLP2.png">
<img src="./Resources/images/Wireframes/WFLP3.png">
<img src="./Resources/images/Wireframes/WFLP4.png">
<img src="./Resources/images/Wireframes/WFLP5.png">
<img src="./Resources/images/Wireframes/WFLP6.png">

### 5.3.2 Landing Page Mock-up
<img src="./Resources/images/Mockups/MULP1.png">
<img src="./Resources/images/Mockups/MULP2.png">
<img src="./Resources/images/Mockups/MULP3.png">
<img src="./Resources/images/Mockups/MULP4.png">
<img src="./Resources/images/Mockups/MULP5.png">
<img src="./Resources/images/Mockups/MULP6.png">

## 5.4 Application UX/UI Design
### 5.4.1 Application Wireframes
#### Wireframes Web Application
<img src="./Resources/images/Wireframes/WF1.png">
<img src="./Resources/images/Wireframes/WF2.png">
<img src="./Resources/images/Wireframes/WF3.png">

#### Wireframes Web Application - Segmento Meseros
<img src="./Resources/images/Wireframes/WFM1.png">
<img src="./Resources/images/Wireframes/WFM2.png">
<img src="./Resources/images/Wireframes/WFM3.png">
<img src="./Resources/images/Wireframes/WFM4.png">
<img src="./Resources/images/Wireframes/WFM5.png">
<img src="./Resources/images/Wireframes/WFM6.png">
<img src="./Resources/images/Wireframes/WFM7.png">

#### Wireframes Web Application - Segmento Administradores
<img src="./Resources/images/Wireframes/WFA1.png">
<img src="./Resources/images/Wireframes/WFA2.png">
<img src="./Resources/images/Wireframes/WFA3.png">
<img src="./Resources/images/Wireframes/WFA4.png">
<img src="./Resources/images/Wireframes/WFA5.png">
<img src="./Resources/images/Wireframes/WFA6.png">
<img src="./Resources/images/Wireframes/WFA7.png">
<img src="./Resources/images/Wireframes/WFA8.png">
<img src="./Resources/images/Wireframes/WFA9.png">
<img src="./Resources/images/Wireframes/WFA10.png">
<img src="./Resources/images/Wireframes/WFA11.png">
<img src="./Resources/images/Wireframes/WFA12.png">
<img src="./Resources/images/Wireframes/WFA13.png">
<img src="./Resources/images/Wireframes/WFA14.png">
<img src="./Resources/images/Wireframes/WFA15.png">

#### Wireframes Mobile Application
<img src="./Resources/images/Wireframes/WFMA1.png">
<img src="./Resources/images/Wireframes/WFMA2.png">
<img src="./Resources/images/Wireframes/WFMA3.png">
<img src="./Resources/images/Wireframes/WFMA4.png">
<img src="./Resources/images/Wireframes/WFMA5.png">
<img src="./Resources/images/Wireframes/WFMA6.png">
<img src="./Resources/images/Wireframes/WFMA7.png">
<img src="./Resources/images/Wireframes/WFMA8.png">
<img src="./Resources/images/Wireframes/WFMA9.png">
<img src="./Resources/images/Wireframes/WFMA10.png">

### 5.4.2 Application Wireflow Diagrams

### 5.4.3 Application Mock-ups
#### Mock-ups Web Application
<img src="./Resources/images/Mockups/MU1.png">
<img src="./Resources/images/Mockups/MU2.png">
<img src="./Resources/images/Mockups/MU3.png">

#### Muck-ups Web Application - Segmento Meseros
<img src="./Resources/images/Mockups/MUM1.png">
<img src="./Resources/images/Mockups/MUM2.png">
<img src="./Resources/images/Mockups/MUM3.png">
<img src="./Resources/images/Mockups/MUM4.png">
<img src="./Resources/images/Mockups/MUM5.png">
<img src="./Resources/images/Mockups/MUM6.png">
<img src="./Resources/images/Mockups/MUM7.png">

#### Muck-ups Web Application - Segmento Administradores
<img src="./Resources/images/Mockups/MUA1.png">
<img src="./Resources/images/Mockups/MUA2.png">
<img src="./Resources/images/Mockups/MUA3.png">
<img src="./Resources/images/Mockups/MUA4.png">
<img src="./Resources/images/Mockups/MUA5.png">
<img src="./Resources/images/Mockups/MUA6.png">
<img src="./Resources/images/Mockups/MUA7.png">
<img src="./Resources/images/Mockups/MUA8.png">
<img src="./Resources/images/Mockups/MUA9.png">
<img src="./Resources/images/Mockups/MUA10.png">
<img src="./Resources/images/Mockups/MUA11.png">
<img src="./Resources/images/Mockups/MUA12.png">
<img src="./Resources/images/Mockups/MUA13.png">
<img src="./Resources/images/Mockups/MUA14.png">
<img src="./Resources/images/Mockups/MUA15.png">

#### Wireframes Mobile Application
<img src="./Resources/images/Mockups/MUMA1.png">
<img src="./Resources/images/Mockups/MUMA2.png">
<img src="./Resources/images/Mockups/MUMA3.png">
<img src="./Resources/images/Mockups/MUMA4.png">
<img src="./Resources/images/Mockups/MUMA5.png">
<img src="./Resources/images/Mockups/MUMA6.png">
<img src="./Resources/images/Mockups/MUMA7.png">
<img src="./Resources/images/Mockups/MUMA8.png">
<img src="./Resources/images/Mockups/MUMA9.png">
<img src="./Resources/images/Mockups/MUMA10.png">

## 5.5 Application Prototyping
<img src="./Resources/images/prototyping.png">

Link del Figma: https://www.figma.com/design/nyBckh8w59BwWU4cN4DRW9/IoT?node-id=0-1&t=utGFI0ZMZzi5lOJL-1
