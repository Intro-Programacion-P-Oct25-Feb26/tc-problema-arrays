## EJERCICIO – USO DE ARRAYLIST
### PROBLEMA
> Una facultad universitaria gestiona la evaluación de 8 proyectos académicos. Cada proyecto es evaluado mediante 7 criterios definidos por un comité académico. Además, cada proyecto tiene un responsable y pertenece a una área académica. Para facilitar futuras ampliaciones (más proyectos), se ha decidido utilizar estructuras dinámicas (ArrayList). Los CRITERIOS DE EVALUACIÓN son:
```
0 = Impacto
1 = Innovación
2 = Viabilidad
3 = Pertinencia
4 = Metodología
5 = Presupuesto
6 = Sostenibilidad
```

### INDICACIONES GENERALES
- Usar un proyecto Java (NetBeans).
- Usar 4 paquetes, usted distribuye los archivos (clases de Java)
- NO usar librerías externas.
- Comentar adecuadamente el código.
- Ingresar por teclado el nombre de cada proyecto en una función
- No ingresar los responsables por teclado; deben ser asignados directamente
```  
    Responsable de Proyecto Leonardo DiCaprio
    Responsable de Proyecto Meryl Streep
    Responsable de Proyecto Denzel Washington
    Responsable de Proyecto Natalie Portman
    Responsable de Proyecto Tom Hanks
    Responsable de Proyecto Cate Blanchett
    Responsable de Proyecto Joaquin Phoenix
```  
- La áreas académicas que se debe usar son (no ingresar por teclado):
```  
    Ciencias Sociales
    Ingeniería
    Ciencias de la Salud
    Ingeniería
    Ciencias Sociales
    Artes y Humanidades
    Ingeniería
    Ciencias de la Salud
```  
- NO ingresar puntuaciones por teclado; deben asignarse directamente.
```  
    Proyecto 1
    85, 90, 85, 88, 85, 80, 90
    Proyecto 2
    92, 95, 92, 90, 92, 88, 95
    Proyecto 3
    78, 80, 78, 82, 78, 75, 80
    Proyecto 4
    88, 90, 88, 85, 88, 90, 92
    Proyecto 5
    90, 92, 90, 88, 90, 85, 92
    Proyecto 6
    95, 97, 95, 93, 95, 90, 97
    Proyecto 7
    82, 85, 82, 80, 82, 78, 85
    Proyecto 8
    88, 90, 88, 86, 88, 84, 90
```  

### FUNCIONES OBLIGATORIAS

1. Función que ingrese los nombres de los proyectos.
2. Función que cargue las áreas académicas de cada proyecto.
3. Función que cargue los responsables de cada proyecto.
3. Función que cargue las puntuaciones de cada proyecto.
4. Desde el método principal (main), se deben invocar las funciones anteriores según corresponda.

> Analizar las siguientes recomendaciones para el problema

a) Generar una función que permita obtener el promedio de puntuaciones por criterio por proyecto, resptando las estructuras usadas.

b) Una función para obtener el puntaje total por proyecto. Calcular la suma total de los 7 criterios 
para cada proyecto.

c) Una función que sume todos las puntuaciones (todos los criterios, todos los proyectos).

d) Una función que obtenga el promedio de puntuaciones de todos los proyectos

e) Una función que devuelva por cada proyecto el número de puntuaciones que son mayores al promedio general

f) Una función que devuelva por cada proyecto el número de puntuaciones impares

g) Una función que devuelva la varianza poblacional por cada proyecto

La varianza poblacional, tiene los siguientes pasos
```
1. Datos ejemplo: 10, 12, 14, 14
2. Promedio: x = (10 + 12 + 14 + 14)/4 = 12.5
3. Restas al promedio y cuadrados
(10−12.5)² = 6.25
(12−12.5)² = 0.25
(14−12.5)² = 2.25
(14−12.5)² = 2.25
4. Suma 6.25 + 0.25 + 2.25 + 2.25 = 11
5. Variaza poblacional: 11/4 = 2.75
```
i) Implementar un procedimiento que muestre la información generada en las funciones. Usar variable acumuladora
