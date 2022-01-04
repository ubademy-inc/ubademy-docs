---
layout: post
title: Administrador
nav_order: 3
has_children: false
has_toc: true
---

# Sitio Administrador

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

* [Link al servicio](https://ubademy-grupo-13.herokuapp.com/)

* [Link al repo](https://github.com/ubademy-inc/ubademy-front)

<img src="../admin/assets/front-office-1.png" width="500"/>

## Descripción

Este servicio es el frontOffice para los administradores del sitio Ubademy. A continuación se detallan las acciones que se pueden realizar en el mismo:

* Listar cursos creados y ver a los mismos
* Listar usuarios creados y ver a los mismos
* Visualizar métricas de usuarios y cursos
* Visualizar los servicios de la arquitectura
* Crear nuevos usuarios administradores


## Log in

Como solo un usuario administrador puede crear a otro. En la primera pantalla no se permite registrar un usuario, pero solamente ingresar de tener las credenciales correctas

<img src="../admin/assets/front-office-2.png" width="500"/>

## Usuarios

Si accedemos a Usuarios vamos a poder ver un listado con todos los usuarios.

<img src="../admin/assets/front-office-6.png" width="500"/>

Si se clickea uno, se puede ver toda la información del mismo

<img src="../admin/assets/front-office-7.png" width="500"/>

## Cursos

Si accedemos a Cursos vamos a poder ver un listado con todos los cursos.

<img src="../admin/assets/front-office-8.png" width="500"/>

Si se clickea uno, se puede ver la información resumida del mismo

<img src="../admin/assets/front-office-9.png" width="500"/>

En esta sección se puede además bloquear y desbloquear un curso. En caso de ser bloqueado, el curso podrá solamente ser visualizado en la app, pero lo usuario no podrán utilizarlo o anotarse al mismo.

## Métricas

Para las métricas se utilizaron dos acercamientos distintos para obtener y mostrar la información.

### Cursos

Si se accede a métricas de cursos se pueden ver las distintas mediciones en el servicio Grafana. Podemos acceder a información como la cantidad de actividad que tuvo cada endpoint en el tiempo indicando.

<img src="../admin/assets/front-office-3.png" width="500"/>

### Usuarios

Si se accede a métricas de usuarios se puede ver la actividad en el la app respecto a usuarios registrados e usuarios que ingresaron a la aplicación. La información se dividie, en ambos casos, por tipo de registro/login. Diferenciando los usuario que ingresan con entidades federadas (Google en nuestro caso) y los que lo hacen utilizando puramente nuestra aplicación.

<img src="../admin/assets/front-office-4.png" width="500"/>

## Crear usuario administrador

En esta sección se puede crear un nuevo usuario administrador. El mismo podrá ingresar a este mismo sitio y realizar todas las acciones antes mencionadas.

<img src="../admin/assets/front-office-5.png" width="500"/>

## Salir

Finalmente el menu da la opción de abandonar la sesión en el sitio, para poder in
gresar con uno nuevo o simplemente cerrar la sesión actual.