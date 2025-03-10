# TFG-UAX
Repositorio del TFG  de la Universidad Alfonso X el Sabio
Bienvenido a mi repositorio de TFG. Este proyecto se centra en el desarrollo de una solución  para garantizar la seguridad en redes empresariales a través de la autenticación segura de dispositivos, el análisis en tiempo real del tráfico de red y la aplicación dinámica de políticas de acceso.

Objetivos del Proyecto
Autenticación Segura:
Integrar la API de ClearPass para la autenticación de dispositivos, utilizando OAuth2 para gestionar de forma segura el proceso de validación. Se implementa un endpoint con FastAPI que simula la autenticación desde dispositivos reales, facilitando pruebas y validación de la solución.

Registro y Gestión de Dispositivos:
Registrar cada dispositivo autenticado en una base de datos PostgreSQL, lo que permite un seguimiento detallado del estado de los dispositivos conectados. Además, se implementa una función para actualizar dicho estado, lo que posibilita acciones como la desconexión en situaciones críticas.

Análisis de Tráfico en Tiempo Real:
Recolectar y procesar los logs generados por el NAC (Network Access Control) mediante la API de ClearPass. Se incorpora un modelo de inteligencia artificial para detectar anomalías en el tráfico, asegurando la identificación temprana de comportamientos potencialmente maliciosos.

Aplicación Dinámica de Políticas de Acceso y Alertas:
Automatizar la modificación de políticas de acceso para desconectar dispositivos que presenten comportamientos anómalos. Se desarrollan funciones para el envío de alertas y se crea un dashboard que visualiza datos actualizados, facilitando el monitoreo y la respuesta ante incidentes.

Estructura del Repositorio
/src – Contiene el código fuente del proyecto, organizado en módulos para la autenticación, registro de dispositivos, análisis de tráfico y gestión de políticas.

/docs – Documentación del proyecto, incluyendo diagramas, justificación técnica y guías de uso.

/tests – Pruebas unitarias e integradas para asegurar el correcto funcionamiento de cada componente.

README.md – Este archivo, que explica el propósito, la estructura y el funcionamiento del proyecto.

LICENSE – Archivo de licencia, en el que se especifica cómo se puede utilizar, modificar y distribuir el código.

Conclusión

Este proyecto integra diversas tecnologías y metodologías con el fin de crear una solución robusta y escalable para la seguridad en redes. Con la integración de ClearPass, FastAPI, PostgreSQL y técnicas de inteligencia artificial, se busca no solo autenticar y registrar dispositivos de forma segura, sino también monitorizar y responder de manera proactiva ante amenazas.

¡Gracias por tu interés en mi TFG!
