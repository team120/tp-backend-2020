# Checklist

## Backend

|Requerimiento funcional|cant. mín.<br>1 o 2 integ|cant. máx.<br>3 o 4 integ|Detalle/Listado de casos|Cumple|
|:-|-:|-:|:-|-|
|ABMC simple|1 x integ|1 x integ|1- Universidades <br> 2- Habilidades| 
|ABMC dependiente|1|2|1- Usuarios <br> 2- Proyectos <br> 3- Publicaciones <br> 4- Departamentos|
|Listado simple|1|1|Universidades|
|Listado complejo obligatorio|1|2|1- Usuarios por proyecto<br>2- Proyectos por usuario
|Listado adicional con filtro|0|0|1- Proyectos de una facultad en un año
|Detalle básico|1(*)|2(*)|1- Usuario (en listado complejo 1: datos básicos, universidad del usuario) <br>2- Proyecto (en listado complejo 2: cantidad de integrantes, lider, y datos básicos del proyecto)
|Detalle parametrizable|0|0|
|Otros|0|0|

(\*) Los detalles básicos pueden ser reemplazado por un detalle parametrizados en los

## Frontend

|Requerimiento|Cumple|
|:-|-|
|Invocar API listado||
|Invocar API detalle||
|Mostrar detalle al hacer click <br>en elemento del listado||

## Requerimientos Técnicos

|Requerimiento técnico|Cumple|
|:-|-|
|Framework frontend||
|Framework CSS o preprocesador CSS||
|Framework backend||
|Uso de API REST o GraphQL||
|ORM/ODM||
|Base de datos persistente||
