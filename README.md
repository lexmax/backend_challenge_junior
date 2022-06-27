DESAFÍOS A ALCANZAR:
-------------------

Se debe crear una aplicación con el proposito de dar mantenimiento a una sola tabla.
Esa tabla debe contar con las siguientes caracteristicas.

| CAMPOS | ATRIBUTOS |
| --- | --- |
| id | INT() NOT NULL |
| name | VARCHAR(100) NOT NULL |
| lastname | VARCHAR(150) NOT NULL |
| email | VARCHAR(200) NOT NULL |
| address | TEXT |
| reference_address | TEXT |
| phone_number | VARCHAR(20) |


### Nivel 1(creación): 
  Se requiere crear una iterface web donde podamos listar a todos los contactos registrados y poder realiza las siguientes acciones:

  - AGREGAR => Para añadir un nuevo item.
  - ACTUALIZAR => Para actualizar un item espefifico.
  - ELIMINAR => Para eliminar un item especifico.

### Nivel 2 (Reglas):

- El listado debe contar con un paginador.
- Para los efectos de actualización y/o creación 3 campos son obligatorios(name, lastname, email).
- Eliminar un registro: La aplicación debe pedir que se confirme la acción.

### Nivel 3 (Seguridad I):
- Las opciones de: crear, editar, y eliminar. Deben estar protegidas por un inicio de sesión. Es decir si se intenta ejecutar alguna de estas acciones. Se te debe re-dirigir a una vista login. 
- El usuario y contraseña pueden ser 2 valores estáticos.

### Nivel 4 (Seguridad II): 
- El usuario y contraseña provienen de una tabla en la base de datos. 
- El diseño de la tabla es libre.
- La contraseña en la base de datos de estar encriptada.


REPOSITORIO:
-------------

El repositirio debe contar con:
- Descripción
- Alcances del desarrollo (nivel desarrollado)
- Indicaciones de como ejecutar la solución.


REQUISITOS:
-----------

En este desafío debes mostrar tu habilidades en el manejo de tecnologías como:

- Lenguaje Python >= 3.7
- Base de datos: SqLite (Para efectos del challenge).
- Frameworks: Flask, Django u otros en python.

Nota: Puedes hacer uso de cualquier otra librería en python que te ayude a superar el challenge. 


Evalución: backend-python nivel 1
