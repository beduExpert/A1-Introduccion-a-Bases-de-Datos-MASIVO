[`Introducción a Bases de Datos`](../Readme.md) > `Sesión 4`

## Sesión 4: Fundamentos de MongoDB

<img src="../imagenes/pizarron.png" align="right" height="100" width="100" hspace="10">
<div style="text-align: justify;">

### 1. Objetivos :dart: 

- Establecer la conexión a una base de datos no relacional
- Analizar la estructura de distintas colecciones en una base de datos
- Realizar consultas básicas que permitan filtrar documentos, ordenar y limitar los resultados

### 2. Contenido :blue_book:

---
#### <ins>Conexión a __MongoDB__</ins>
<img src="imagenes/imagen1.png" align="right" height="200" width="200">

Para conectarnos a mongo haremos uso del cliente __MongoDB Compass__ este cliente proporciona una interfaz gráfica y amigable que permite distintas tareas como:

- Creación y consulta de bases de datos
- Creación y consulta de colecciones
- Creación y consulta de documentos
- Generación de consultas
- Generación de agregaciones
- Generación de vistas

Para conectarnos con un servidor de bases de datos de __MongoDB__ debe usar, al igual que con __MySQL__ la arquitectura cliente servidor.

> *Platicar brevemente qué es MongoDB y MongoDB Compass. Repasar el modelo cliente-servidor.*

- [**`EJEMPLO 1`**](Ejemplo-01/Readme.md)

---
#### <ins>Colecciones, Documentos y Proyecciones</ins>
<img src="imagenes/imagen2.jpg" align="right" height="200" width="300">

En __MongoDB__ los datos son almacenados en *colecciones* que incluyen documentos. Estos documentos se representan usando el formato de intercambio de información __JSON__. Un __JSON__ se conforma de un conjunto de elementos de la forma *clave-valor* separados por comas y delmitados por llaves. Los tipos de datos de __JSON__ son:

- Números
- Booleanos
- Cadenas
- Arreglos
- Objetos

Para realizar consultas u otras operaciones en __MongoDB__ debe usarse este lenguaje. En particular, para realizar proyecciones, se usa __JSON__. Se indica el campo a proyectar y se coloca un uno si queremos mostrarlo o cero en caso contrario.

- `{campo: 0}`
- `{campo: 1}`

> *Realizar ejemplos de construcción de __JSON__, mostrar las colecciones de la base de datos del módulo y mostrar algunas colecciones en formato __JSON__. Explicar a grandes rasgos las diferencias entre bases de datos relacionales y no relacionales. Cuándo y por qué usar una o la otra. Explicar en qué parte de Compass hacer proyecciones.*

- [**`EJEMPLO 2`**](Ejemplo-02/Readme.md)
- [**`RETO 1`**](Reto-01/Readme.md)	

---
#### <ins>Filtros básicos</ins>
<img src="imagenes/imagen3.png" align="right" height="200" width="300">

Al igual que con las proyecciones, los filtros se construyen usando __JSON__. En su forma más básica se debe escribir el nombre del campo, dos puntos y el valor que queremos filtrar. Existen varias funciones que se pueden combinar con los filtros y las iremos estudiando a lo largo del módulo.

```json
{campo: "valor"}
```

> *Explicar qué es un filtro y en qué parte de Compass deben realizarse.*

- [**`EJEMPLO 3`**](Ejemplo-03/Readme.md)
- [**`RETO 2`**](Reto-02/Readme.md)

---

### 3. Ejercicios :hammer:

Aplica lo todo lo que aprendiste durante la sesión en estos ejercicios. 

- [**`EJERCICIOS SESIÓN 4`**](Ejercicios/Readme.md)

</br>

[`Anterior`](../Sesion-03/Readme.md) | [`Siguiente`](../Sesion-05/Readme.md)

</div>	
