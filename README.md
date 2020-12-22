<img src="https://getduna.com/svg/duna-logo.svg" width="300">

# Ruby on Rails Senior Challenge

## 👩‍💻 Proyect Overview

El objetivo es diseñar e implementar una aplicación con Ruby on Rails para el manejo de solicitudes de reparaciones en una cadena de tiendas.

## 🦶 Pasos

* Crea una aplicación Ruby on Rails, implementando los casos de uso
* Versiona tus cambios
* Crea un pull request

## ❓ Casos de uso a implementar

* Existe un formulario abierto que permite al cliente, solicitar una cotización de reparación a un determinado producto (Ejemplo: Laptop, Smartphone, Consola, TV).
* La solicitud debe llegar a la tienda que tenga más prioridad (1 es mayor prioridad) y que ofrezca el servicio de reparación al tipo de producto.
* Cuando se aprueba la solicitud de cotización, el usuario de la tienda debe ingresar un precio estimado en el panel de admin.
* Si la tienda asignada no aprueba la solicitud dentro de 30 minutos, se asigna a la siguiente tienda con menor prioridad. 
* Si la solicitud no se aprueba, se envía un correo al cliente informando que no es posible realizar el trabajo.
* El usuario puede ver todas las cotización pendientes, aprobadas y descartadas.
* Los productos y sus atributos se deben consumir de un servicio externo. Además se debe ampliar la funcionalidad para persistir y mantener actualizada la data. [API EXTERNA](https://fakestoreapi.com/products/category/electronics)

## 🔑 Restricciones técnicas

Los requisitos obligatorios son usar Ruby on Rails como tecnología de desarrollo, seguir las convenciones de Rails, validar lo que estimes necesario y utilizar testing unitarios.
Eres libre de usar cualquier gem.

## 🎯 Bonificaciones

Se consideran bonificaciones los siguientes puntos:

* Gitflow
* Utilizar patrones de diseño
* API REST con autenticación
* Manejar la importación en una gem
* Utilizar estrategia eficiente de importación
* Implementar herramientas para una mejor suite de test
* Diseño responsive
* Manejo en docker
* README actualizado
* Entrega de MER y Casos de uso. Puedes usar Lucidchart
* Planificación y estimación de tareas

## 📃 Disclaimer

Esto es un desafío técnico sin proposito comercial y D-Una de ninguna manera:

* Compartirá o usará tu código
* Obligarte a realizar este desafío
* Compensarte de cualquier forma por realizar este desafío

# Buena suerte 🚀
