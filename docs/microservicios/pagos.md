---
layout: post
title: Pagos
parent: Microservicios
has_toc: false
---

# Pagos 

![Fastify](https://img.shields.io/badge/fastify-%23000000.svg?style=for-the-badge&logo=fastify&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)


* [Link a servicio](https://ubademy-grupo-13-smartcontract.herokuapp.com/wallet)

* [Link al repo](https://ubademy-grupo-13-smartcontract.herokuapp.com/wallet)

## Descripción

El presente microservicio es una aplicación de pago que permite realizar pagos a través de una API REST. Este se encarga de todo el proceso de pago, conectándose a ethers para generar las distintas transacciones.

Se basó en una base presentada por la cátedra en solidity y luego se setteó en una base de datos en mongoDB junto a la incorporación del mnemonic y su infura api key para el manejo de la transacción.


## Funcionalidades:

* Crear una billetera a cada usuario en la creación
* Pago a un usuario o creador.
* Depósito al contrato al realizarse una suscripción
* Obtener una o todas las billeteras guardadas en la base de datos
* Obtener una transacción realizada en particular.