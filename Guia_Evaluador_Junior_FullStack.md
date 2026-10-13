# Documento de evaluación – Examen práctico Full Stack Junior

## Propósito
Evaluar la capacidad de un candidato para desarrollar una solución funcional con:
- NestJS
- React
- MySQL
- Git

La prueba está diseñada para un perfil junior, por lo que debe priorizar:
- comprensión del flujo full-stack
- capacidad de construir una solución funcional
- orden del código
- manejo de errores
- uso de buenas prácticas básicas

---

## Objetivo de la prueba
Evaluar si el candidato puede:
- crear una API REST con NestJS
- conectar la API a MySQL
- modelar datos simples
- construir un frontend en React
- consumir la API
- validar entradas
- manejar errores
- documentar el proyecto
- usar Git de forma básica

---

## Requisitos mínimos para considerarse aprobado
Se considera un entregable aceptable si cumple estas condiciones:

- Backend funcionando con CRUD de productos
- MySQL conectado y datos persistidos
- Validaciones básicas implementadas
- Frontend funcional para crear, listar, editar y borrar
- Al menos una búsqueda o filtro
- Mensajes de error claros
- README ejecutable
- Repositorio Git con historial visible

---

## Rúbrica de evaluación

| Área | Peso | Criterio |
|---|---:|---|
| Funcionalidad CRUD | 25% | El backend permite crear, listar, actualizar y eliminar registros correctamente |
| Validaciones y errores | 20% | Se validan campos obligatorios, números, SKU único y errores se manejan correctamente |
| Frontend y consumo de API | 20% | La interfaz funciona, hace llamadas a la API y muestra estado de carga/error |
| Modelo de datos y base de datos | 15% | El esquema es correcto y existe relación entre productos y categorías |
| Calidad del código | 10% | Código limpio, organizado, con nombres claros y estructura entendible |
| Git y documentación | 10% | README claro, comandos correctos, historial de commits ordenado |

### Puntuación sugerida
- 90–100: Excelente, apto para perfil junior con buen potencial
- 75–89: Aprobado, cumple la mayoría de objetivos
- 60–74: Aprobado con observaciones, requiere apoyo adicional
- 0–59: No satisfactorio, faltan requisitos básicos

---

## Indicadores de evaluación por criterio

### 1. Funcionalidad CRUD – 25%
Evaluar si:
- GET /products funciona
- GET /products/:id funciona
- POST /products crea registros
- PATCH /products/:id actualiza
- DELETE /products/:id elimina
- El backend responde con códigos HTTP adecuados

### 2. Validaciones y errores – 20%
Evaluar si:
- nombre es obligatorio
- precio es mayor que 0
- stock es mayor o igual a 0
- SKU es único
- si no existe el registro, responde 404
- si hay datos inválidos, responde 400
- mensajes son claros y útiles

### 3. Frontend y consumo de API – 20%
Evaluar si:
- la UI lista productos
- existe formulario para crear/editar
- existe botón para eliminar
- se muestran mensajes de éxito/error
- se manejan tiempos de carga
- hay búsqueda o filtro mínimo

### 4. Modelo de datos y base de datos – 15%
Evaluar si:
- hay tablas apropiadas
- existe relación entre categorías y productos
- se usan tipos correctos
- los registros se guardan en MySQL
- la base de datos está bien conectada

### 5. Calidad del código – 10%
Evaluar si:
- hay separación de responsabilidades
- el nombre de variables y funciones es claro
- la estructura es comprensible
- el código no es caótico ni duplicado

### 6. Git y documentación – 10%
Evaluar si:
- hay varios commits
- los mensajes son entendibles
- README explica instalación y ejecución
- el proyecto puede ser ejecutado por otra persona sin ayuda extra

---

## Observaciones recomendadas para el evaluador
Durante la revisión, conviene anotar:
- qué tan intuitiva es la solución
- si el candidato entendió el flujo de datos
- si el manejo de errores fue consistente
- si documentó bien el proyecto
- si tuvo capacidad para iterar y corregir errores
- si la arquitectura es simple pero clara

---

## Versión corta para enviar al evaluador
“Se evaluará la capacidad del candidato para construir un CRUD completo con NestJS y React, conectado a MySQL. Se revisará la funcionalidad, validaciones, manejo de errores, orden del código, consumo del backend desde el frontend y la calidad de la documentación y del repositorio Git.”

---

## Enunciado para el candidato
### Examen práctico take-home – Junior Full Stack

#### Duración
3 a 4 horas

#### Tecnologías
- NestJS
- React
- MySQL
- Git

#### Objetivo
Crear una aplicación full-stack para gestionar un catálogo de productos de una tienda. El backend debe estar desarrollado en NestJS, conectarse a MySQL y exponer un CRUD para productos y categorías. El frontend debe estar desarrollado en React y consumir la API para listar, crear, editar y eliminar productos. Debe incluir validaciones, manejo de errores, búsqueda por nombre/SKU y una interfaz simple.

#### Requisitos mínimos
- CRUD de productos
- CRUD de categorías
- Validaciones básicas
- Base de datos MySQL
- Frontend para consumir la API
- Documentación con README
- Repositorio Git

#### Entregable
Repositorio funcional con backend, frontend, DB local y README claramente ejecutable.

---

## Resumen ejecutivo
Este examen busca comprobar que el candidato pueda aplicar los fundamentos de desarrollo full-stack en un escenario realista, con foco en la integración entre backend, base de datos y frontend, y dejando claro que se prioriza funcionalidad, orden, y capacidad de entregar un proyecto ejecutable y documentado.
