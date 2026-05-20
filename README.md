#  Sistema Hospitalario — Proyecto de Paradigmas de Programación

Aplicación de consola desarrollada en **C#** que simula la gestión básica de un sistema hospitalario utilizando conceptos fundamentales de **Programación Orientada a Objetos (POO)** y algunos principios del **Paradigma Funcional** mediante el uso de **LINQ**.

El proyecto permite administrar:

* Pacientes * Doctores * Habitaciones * Hospitalizaciones * Historiales médicos * Persistencia de datos con archivos CSV usando CsvHelper

---

#  Objetivo del Proyecto
Este proyecto fue desarrollado con fines académicos para aplicar:

* Programación Orientada a Objetos * Relaciones UML * Principios de cohesión y acoplamiento
* Persistencia de datos * Programación funcional básica con LINQ * Arquitectura por capas simple


#  Paradigmas Aplicados

##  Programación Orientada a Objetos (POO)
Se implementaron los principales pilares de POO:

###  Encapsulamiento
Uso de propiedades y clases para proteger y organizar los datos.

###  Herencia
Las clases `Paciente` y `Doctor` heredan de `Persona`.

###  Polimorfismo
Uso de métodos `virtual` y `override` para mostrar información diferente según el tipo de objeto.

###  Abstracción
Separación entre lógica del sistema y la interacción con el usuario.


#  Paradigma Funcional
Se implementaron funciones LINQ para:

* Filtrar datos * Buscar elementos * Consultar habitaciones libres
* Reducir ciclos repetitivos

## Funcionalidades Implementadas

##  Gestión de Pacientes

* Registrar pacientes
* Listar pacientes
* Editar pacientes
* Eliminar pacientes
* Consultar historial médico

##  Gestión de Doctores

* Registrar doctores
* Asociar especialidad
* Listar doctores

##  Gestión de Habitaciones

* Visualizar habitaciones ocupadas
* Visualizar habitaciones libres
* Asignar habitaciones automáticamente


##  Hospitalización

* Registrar ingreso de pacientes
* Registrar fecha de alta
* Asociar paciente a habitación


##  Historial Médico

* Registrar diagnósticos
* Registrar tratamientos
* Registrar observaciones


# Persistencia de Datos

El sistema utiliza la librería **CsvHelper** para almacenar la información en archivos `.csv`.Los datos permanecen guardados incluso después de cerrar la aplicación.



#  Conceptos de Ingeniería de Software Aplicados

* Cohesión alta
* Bajo acoplamiento
* Separación de responsabilidades
* Organización modular
* CRUD por entidad
* Repository Pattern básico

#  Posibles Mejoras Futuras

* Interfaz gráfica
* Base de datos SQL
* Validaciones avanzadas
* Sistema de autenticación
* Reportes médicos
* Estadísticas hospitalarias
* API REST

Proyecto desarrollado únicamente con fines educativos y académicos.
