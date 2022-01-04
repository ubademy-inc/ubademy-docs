---
layout: default
title: Aplicación
nav_order: 3
---

# Aplicación Movile

![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

* [Link al repo](https://github.com/ubademy-inc/ubademy-app)

* [Link al maquetado](https://www.figma.com/file/FWvM5qmqIpvzVuXfd0QGhR/Ubademy?node-id=0%3A1)


## Inicio

Primero que nada, al entrar en la app verá las opciones de registrarse si no tiene cuenta o loggearse si ya tiene una:

<img src="../app/assets/Home.png" width="300" heigh="500"/>


## Login/Registro 

La app le permite al usuario registrarse tanto normalmente como mediante su cuenta de google.

<img src="../app/assets/Login.png" width="300" heigh="500"/>
<img src="../app/assets/Register.png" width="300" heigh="500"/>

## Buscador de Cursos
 
Una vez ingresado, el usuario puede buscar cualquier curso creado por su nombre, tipo de suscripción y/o tags asociados.

Si no se escribe ningún nombre, el buscador devolverá todos los cursos con los filtros de suscripción y tag elegidos.

<img src="../app/assets/HomeLoggedIn.png" width="300" heigh="500"/>
<img src="../app/assets/Courses.png" width="300" heigh="500"/>


## Drawer

Dentro de la App, el usuario tendrá varias opciones, mostradas mediante un navegador drawer:
<img src="../app/assets/Drawer.png" width="300" heigh="500"/>

## Perfil general

Aquí podrá ver sus datos como:

### Estudiante

<img src="../app/assets/Profile.png" width="300" heigh="500"/>

### Creador

Creador, si no tiene creado un perfil de creador, le mostrará la opción de crearse uno. Al seleccionar crear, se le abrirá un modal para completar la información

<img src="../app/assets/CreatorProfile.png" width="300" heigh="500"/>
<img src="../app/assets/CreatorCard.png" width="300" heigh="500"/>

Si ya tiene un perfil creado, le mostrará los valores de dichos campos llenados

<img src="../app/assets/CreatorProfileCreated.png" width="300" heigh="500"/>

## Colaborador

El perfil de colaborador funciona del mismo modo que el de creador.

<img src="../app/assets/CollaboratorProfile.png" width="300" heigh="500"/>

# Acciones como estudiante

Aquí podrá ver los cursos a los que está anotado como estudiante,
<img src="../app/assets/CourseAsStudent.png" width="300" heigh="500"/>

a los cuales podrá acceder para dejar comentarios sin haber sido todavía inscripto al curso

<img src="../app/assets/LeaveCommentInCourse.png" width="300" heigh="500"/>

## Acciones como Creador

Si no tiene perfil de creador creado, primero deberá crearse uno, esta página le dará dicha opción.
![CreatorMenu](https://github.com/ubademy-inc/ubademy-app/blob/main/assets/manual/CreatorMenu.png)

Si lo tiene, podrá acceder a todos los cursos que haya creado, o crear un nuevo curso.
![CreatorCourses](https://github.com/ubademy-inc/ubademy-app/blob/main/assets/manual/CreatorCourses.jpeg)

### Curso creado

A cada curso podrá acceder para corregir exámenes, responder comentarios, asignar colaboradores o editar información de dicho curso

<img src="../app/assets/CourseAsCreator.jpeg" width="300" heigh="500"/>
<img src="../app/assets/AddAndSeeCollaborators.jpeg" width="300" heigh="500"/>
<img src="../app/assets/StudentOfCourse.jpeg" width="300" heigh="500"/>

### Creación de Cursos

También podrá crear nuevos cursos, junto con sus exámenes
<img src="../app/assets/CourseCreation.png" width="300" heigh="500"/>
<img src="../app/assets/ExamCreation.png" width="300" heigh="500"/>


## Acciones como Colaborador

Si no tiene perfil de colaborador creado, primero deberá crearse uno, esta página le dará dicha opción.

<img src="../app/assets/CollaboratorMenu.png" width="300" heigh="500"/>
 
Si lo tiene, podrá acceder a todos los cursos en los que esté anotado como colaborador

<img src="../app/assets/CollaboratorCourses.jpeg" width="300" heigh="500"/>

Podrá acceder a los mismos para corregir exámenes o responder comentarios. Se puede ver que tiene menos acciones disponibles que un creador.

<img src="../app/assets/CourseAsCollaborator.jpeg" width="300" heigh="500"/>

## Suscripciones

En esta página se le indicará qué nivel de suscripción tiene comprado, y se le detallará las demás suscripciones que tenga disponibles para comprar

<img src="../app/assets/Subscription.png" width="300" heigh="500"/>


## Buscar otros usuarios
Aquí podrá ingresar el nombre del usuario que desee buscar y, de encontrarlo, podrá ver sus datos básicos:
* Nombre
* Apellido
* Email
* Nivel de suscripción
* Fecha de creación del perfil

<img src="../app/assets/Users.png" width="300" heigh="500"/>

## Cerrar sesión

Desde el drawer se da la opción de salir de la sesión

<img src="../app/assets/CloseSession.png" width="300" heigh="500"/>
