# Temario-de-aplicaciones
Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.
* 1.-Introducción al desarrollo web

El desarrollo web es una rama de la programación que lo que busca es la creación y el mantenimiento de las páginas web.
En el pasado las páginas web eran muy sencilla, pero con el avance de la tecnología se ha conseguido que en una página web se puede hacer de todo.
En la actualidad el desarrollo web es una de las partes más populares de la programación, y también una de las más demandadas.

* Historia y evolución del desarrollo web

a Web 1.0 se caracterizaba por ser estática, donde los usuarios solo podían consumir información.
Con la llegada de la Web 2.0, se introdujeron interacciones más dinámicas, permitiendo a los usuarios crear contenido y participar en redes sociales.

* Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)
<img width="200" height="130" alt="image" src="https://github.com/user-attachments/assets/56620ccb-8e8c-40cd-9c09-63e1994312bb" />


1 Aplicaciones web estáticas: Proporcionan contenido fijo y sencillo, como sitios personales o portafolios, que no requieren interacción del usuario. 
2 Aplicaciones web dinámicas: Generan contenido en tiempo real, permitiendo interacciones y personalización, como tiendas en línea y 3 redes sociales. 
3 SPA (Single Page Applications): Ofrecen una navegación fluida y rápida, mostrando el contenido en una sola página. 
4 PWA (Progressive Web Apps): Combinan funcionalidades de aplicaciones web con la experiencia de aplicaciones nativas, permitiendo un acceso más nativo en dispositivos móviles. 
5 Aplicaciones web de comercio electrónico: Diseñadas para facilitar la compra y venta de productos en línea, como plataformas de venta y sistemas de gestión de pedidos. 
6 Estos tipos de aplicaciones web tienen características y funcionalidades específicas que las hacen adecuadas para diversas finalidades en el ecosistema digital.

* 2.Arquitectura de aplicaciones web

La arquitectura de aplicaciones web define cómo se estructuran y organizan los componentes de una aplicación para garantizar su funcionalidad, escalabilidad y mantenimiento. Existen varios enfoques arquitectónicos que se adaptan a diferentes necesidades y contextos

* Cliente-Servidor
La expresión cliente servidor se utiliza en el ámbito de la informática. En dicho contexto, se llama cliente al dispositivo que requiere ciertos servicios a un servidor. La idea de servidor, por su parte, alude al equipo que brinda servicios a las computadoras (ordenadores) que se hallan conectadas con él mediante una red.
La arquitectura de tres capas es un modelo de diseño de software que organiza las aplicaciones en tres niveles distintos:
Nivel de Presentación: Interfaz de usuario donde los usuarios interactúan con la aplicación. Se encarga de mostrar información y recopilar datos del usuario. 

* Arquitectura de tres capas (presentación, lógica, datos)
Nivel de Lógica de Negocio: También conocido como capa lógica, donde se procesan los datos y se aplican las reglas de negocio. Este nivel es el corazón de la aplicación, donde se realizan las operaciones necesarias. 
Nivel de Datos: Gestiona la información almacenada, como bases de datos. Este nivel se encarga de la persistencia de los datos y las operaciones CRUD (Crear, Leer, Actualizar, Eliminar). 
Este enfoque permite una mejor modularidad, escalabilidad y mantenimiento de las aplicaciones, ya que cada nivel puede ser desarrollado y actualizado de manera independiente.

* REST y API-first design
¿Qué es REST?
REST (Representational State Transfer) es un estilo arquitectónico para diseñar servicios web. Se basa en principios como:
Recursos: Todo en el sistema se trata como un recurso (por ejemplo, usuarios, productos).
HTTP Verbs: Se utilizan métodos HTTP estándar como GET, POST, PUT, DELETE para interactuar con los recursos.
Stateless: Cada solicitud del cliente al servidor debe contener toda la información necesaria para procesarla, sin depender de un estado almacenado en el servidor.
Formatos estándar: Los datos suelen intercambiarse en formatos como JSON o XML.
URLs significativas: Las rutas deben ser claras y representar recursos (por ejemplo, /users/123 para un usuario específico).

3. -Lenguajes y tecnologías fundamentales
Tecnologías de rutina: Ejemplos incluyen el software de consumo masivo y los procedimientos burocráticos en entidades gubernamentales. 
Tecnologías no rutinarias: Estas tecnologías carecen de procedimientos estandarizados y son utilizadas en contextos innovadores. 
Tecnologías existentes: Se clasifican en diversos tipos según su aplicación y fin, como la automatización y la inteligencia artificial.

-Control de versiones
 Control de versiones se refiere a un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo, permitiendo volver a versiones anteriores si es necesario y comparar las diferencias entre ellas.

* Git y GitHub
GitHub es una plataforma basada en la web para alojar repositorios Git. Facilita la colaboración al permitir que múltiples desarrolladores trabajen en un proyecto desde cualquier lugar. Además, ofrece herramientas adicionales como gestión de problemas, revisiones de código, integración continua y GitHub Pages para publicar sitios web. 

*Flujo de trabajo con ramas (branching, merge, pull requests)
El flujo de trabajo con ramas en Git se refiere a la forma en que los desarrolladores gestionan las ramas de código en un proyecto. Existen diferentes modelos, como Git Flow, GitHub Flow y GitLab Flow, que ofrecen estructuras y procedimientos específicos para la colaboración y el desarrollo de software.
--------------------------------------------------------------------------------------------------------------------------------------
                             Desarrollar componentes y funcionalidades de una aplicación web
  1.-Diseño e implementación del frontend 
  El desarrollo web front-end se refiere a la práctica de construir y diseñar la interfaz de usuario de un sitio web o aplicación. Esto implica trabajar con tecnologías del lado del cliente, como HTML, CSS y JavaScript, para crear páginas web interactivas y visualmente atractivas.

  2.-Diseño e implementación del backend
  El backend se refiere al lado del servidor de una aplicación web, encargado de procesar datos y lógica. Incluye componentes como servidores, bases de datos y APIs que permiten la comunicación entre el frontend y el servidor.

  3.-Bases de datos
  Una base de datos es una recopilación organizada de información o datos estructurados, que se almacena electrónicamente en un sistema informático. Normalmente, una base de datos está controlada por un sistema de gestión de bases de datos (DBMS), que permite acceder, gestionar, modificar y organizar los datos de manera eficiente.

  4.-Seguridad básica en aplicaciones web
 Validación de entrada: Asegúrate de que todas las entradas de usuarios sean validadas para prevenir inyecciones de código malicioso. 
Cifrado de datos: Utiliza HTTPS para cifrar las comunicaciones entre el cliente y el servidor, protegiendo la integridad de los datos durante la transferencia. 
Actualizaciones de software: Mantén todas las bibliotecas y plataformas actualizadas para corregir vulnerabilidades conocidas. 
Autenticación y autorización: Implementa mecanismos de autenticación robustos y verifica la identidad de los usuarios. 
Políticas de privacidad: Establece políticas claras de privacidad y proporciona entrenamiento a los empleados sobre buenas prácticas de seguridad. 


<img width="200" height="130" alt="image" src="https://github.com/user-attachments/assets/56ee33e7-5260-487b-9080-768590ff5d95" />


 
