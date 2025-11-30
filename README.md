
Contenido Audiovisual – Sistema con Manejo de Archivos, MVC y Pruebas Unitarias

Este proyecto implementa un sistema de gestión de Contenido Audiovisual con soporte para Películas Series Documentales Actores Temporadas e Investigadores, el desarrollo aplica principios de Programación Orientada a Objetos con enfoque en calidad mantenibilidad y escalabilidad del código, se aplican buenas prácticas como SOLID refactorización código limpio y arquitectura MVC, además se desarrollan pruebas unitarias con JUnit garantizando la fiabilidad del sistema

Características principales

Lectura y escritura de datos mediante archivos CSV para persistencia

Manejo estructurado de contenidos audiovisuales mediante clases bien definidas

Código mejorado mediante refactorización y principios de código limpio

Implementación del patrón MVC separando responsabilidades en modelo vista y controlador

Pruebas unitarias desarrolladas con JUnit

Diagrama de clases actualizado y documentación incluida

Estructura del proyecto
ContenidoAudiovisual
 ├── src
 │   ├── model         Clases de entidades y lógica del dominio
 │   ├── controller    Conexión Model - View y manejo de procesos
 │   ├── view          Interfaz de usuario en consola
 │   └── Main.java     Punto de ejecución del programa
 │
 ├── data              Archivos CSV de lectura y guardado de información
 ├── docs              Diagramas e imágenes de documentación
 ├── test              Pruebas unitarias con JUnit
 │
 └── README.md         Documento principal del repositorio

Requisitos de instalación

Java 8 o superior

IDE recomendado: IntelliJ IDEA, NetBeans o Eclipse

Biblioteca JUnit para pruebas

Git para clonado del repositorio

Instrucciones de ejecución

Clonar el repositorio con el comando

git clone https://github.com/usuario/ContenidoAudiovisual.git


Abrir el proyecto en el IDE de preferencia

Ejecutar la clase Main.java

Utilizar el menú por consola para navegar por las funcionalidades del sistema

Ejecución de pruebas unitarias

Para ejecutar todas las pruebas desde consola o terminal

mvn test


También pueden ejecutarse desde el IDE seleccionando los archivos dentro de la carpeta test/

Las pruebas verifican creación de objetos manejo de archivos comportamiento del MVC validación de datos y funcionamiento completo del sistema incluyendo casos límite

Entregables incluidos
Entregable	Estado
Código refactorizado	Completado
Manejo de archivos	Completado
Implementación de MVC	Completado
Aplicación de principios SOLID	Completado
Pruebas unitarias	Completadas
Diagrama de clases actualizado	Incluido
README.md	Incluido
Conclusión del proyecto

El sistema desarrollado demuestra un enfoque correcto en diseño modular buenas prácticas de programación orientación a objetos y calidad mediante pruebas, la separación en capas mediante MVC además de la aplicación de principios SOLID permite crecimiento del sistema de forma ordenada reduciendo complejidad y facilitando mantenimiento, con esto se obtiene una herramienta funcional escalable y confiable para el manejo de información audiovisual
