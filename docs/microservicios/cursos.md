---
layout: post
title: Cursos
parent: Microservicios
has_toc: false
---

# Cursos 

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

[![codecov](https://codecov.io/gh/ubademy-inc/ubademy-usuarios/branch/main/graph/badge.svg?token=PV9A3O1TUS)](https://codecov.io/gh/ubademy-inc/ubademy-cursos)

* [Link a servicio](https://ubademy-grupo-13-cursos.herokuapp.com/)

* [Link a docs de API](https://ubademy-grupo-13-cursos.herokuapp.com/docs)

* [Link al repo](https://github.com/ubademy-inc/ubademy-cursos)

## Descripción

El microservicio de cursos maneja todas las acciones relacionadas a la entidad curso. 

Se permite:

* Creación: creación de un curso completo con secciones y exámenes.
* Modificación: actualización de los campos del curso y sus secciones.
* Bloqueo: el administrador puede bloquear y desbloquear un curso
* Listado: se puede buscar un curso con su id y también está permitido listarlos todos filtrando por roll , categoria, suscripción, etc.

## Elementos de cursos

### Secciones

Las secciones de un curso son las lecciones compuestas por un título, un video y una descripción. En la actualización se pueden agregar nuevas o modificar las existentes.

### Colaboradores

Es posible agregar, borrar y listar los colaboradores de un curso.

## Alumnos

Es posible agregar y listar los alumnos de un curso.

## Comentarios

Cualquier persona loggeada en la app puede agregar preguntas sobre los cursos, estas son respondidas por los docentes del curso.

## Métricas 

Se optó por pushear las métricas a Prometheus y tener un dashboard en Grafana.