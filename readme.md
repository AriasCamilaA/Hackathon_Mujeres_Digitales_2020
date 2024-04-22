# Detección de Teléfonos Celulares con RetinaNet
Este proyecto fue desarrollado como parte del hackatón de 24 horas en un bootcamp en diciembre de 2020. La tarea consistió en identificar y abordar una problemática mediante la implementación de una solución utilizando inteligencia artificial. Para ello, se utilizó la arquitectura RetinaNet para la detección de objetos en imágenes.

## Descripción del Problema
La problemática abordada en este proyecto se centra en la necesidad de detectar y prevenir el uso de teléfonos celulares en lugares donde su uso está prohibido, como instituciones financieras, salas de examen, entre otros. El objetivo es desarrollar un sistema de detección en tiempo real que pueda identificar la presencia de teléfonos celulares en imágenes y alertar al personal correspondiente.

## Solución Propuesta
Para abordar este problema, se implementó un modelo de detección de objetos utilizando la arquitectura RetinaNet. Se generaron conjuntos de datos de imágenes simulando escenarios donde se prohíbe el uso de teléfonos celulares, como bancos, salas de examen, y otros espacios cerrados con presencia de personas utilizando teléfonos celulares.

## Funcionamiento del Sistema
El sistema funciona de la siguiente manera:

Adquisición de imágenes: Se capturan imágenes en tiempo real (video) de lugares donde se desea detectar el uso de teléfonos celulares.

Procesamiento de imágenes: Las imágenes capturadas son procesadas por el modelo de RetinaNet para identificar la presencia de teléfonos celulares.

Identificación de celulares: En caso de detectar la presencia de teléfonos celulares, el sistema pondrá un recuadro para informar al personal correspondiente.
Instrucciones de Uso

## Para utilizar este sistema, sigue los siguientes pasos:

- Clona este repositorio en tu máquina local.
Instala las dependencias necesarias.
- Ejecuta el script principal para iniciar el sistema de detección.
- Captura imágenes de los lugares donde se desea detectar el uso de teléfonos celulares.
- El sistema mostrará los resultados de la detección en tiempo real y emitirá alertas si es necesario.

## Contribuciones y Sugerencias
¡Este proyecto está abierto a contribuciones y sugerencias! Si tienes ideas para mejorar el sistema de detección de teléfonos celulares o deseas colaborar en su desarrollo, no dudes en crear un issue o enviar un pull request.

## Contacto
- Nombre: Camila Alexandra Arias Ruiz
- Correo Electrónico: ariasruizcamilaa@gmail.com