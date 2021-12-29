---
layout: post
title: Gateway
parent: Microservicios
has_toc: false
---

# Gateway

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

* [Link al servicio](https://ubademy-gateway.herokuapp.com/)

* [Link al repo](https://github.com/ubademy-inc/ubademy-gateway)

## Descripción

Este servicio funciona como punto de entrada a todos nuestros microservicios. Para que tanto la app como el frontOffice no deban conocer distintas urls para cada servicio agregado, las mismas pueden comunicarse unicamente con el gateway para acceder al servicio deseado.

La existencia del mismo no es solo conveniente para nuestro desarrollo, pero si en un futuro un agente externo consumiera nuestro servicio, es clave tener un único punto en donde toca comunicación se realiza.

Por no utilizar ningún tipo de base de dato o guardar un estado dentro de su ejecución, este servicio es facilmente escalable, por ende de aumentar el tráfico el mismo no debería ser un cuello de botella en nuestra aplicación.