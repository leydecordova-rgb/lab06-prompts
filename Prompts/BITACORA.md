# Bitacora de prompts
 
Laboratorio 06: Fundamentos de Ingenieria de Prompts.
 
Herramienta de IA usada: (Gemini-3.6 flash)
 
## Ejercicio 2: Tokens y ventana de contexto

| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. |34|7|
| The students program in Java. |29|6 |
| desafortunadamente |18 |4|

 
## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 | 100| BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec|
| 0.5 |65.3 |PrestaLibro, BiblioTec, LibroYa, LibroYa, BiblioTec|
| 1 |44.5 |LibroYa, LibroYa, BiblioTec, BiblioTec, BiblioTec|
| 1.8 |32.2 |PrestaLibro, BiblioTec, LibroYa, BiblioTec, LibroYa |

 
## Ejercicio 4: Prompt vago vs estructurado

| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema |Si|Si|
| Menciona a los usuarios principales |estudiantes, profesores, público general, administradores |Administradores/Bibliotecarios y Lectores/Socios (estudiantes, docentes o público general)|
| Tiene exactamente 3 funcionalidades |No |Si |
| Esta en 3 parrafos |No|Si|
| Lo usaria en un informe real |No|Si con algunos cambios|

 
## Ejercicio 5: Anatomia de un prompt

| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | A diferencia de la pregunta básica donde creo una aplicación simple, en esta consulta, pregunto que tipo de programa se debe crear.|
| Instruccion |Cuando el prompt incluye la instrucción, nos indica el método de programación y las clases que está usando junto al detalle del código.|
| Contexto |A diferencia de la anterior respuesta, el programa ha creado la clase productos con los atributos solicitados y la clase main de forma más estructurada. |
| Ejemplo |A diferencia del caso anterior, lo único que hizo fue explicar la estructura y luego agrego el código solicitado|
| Formato |Es esta consulta no se evidencio cambios, dado que al definir al inicio el paradigma de progración POO, ha utilizado los métodos correctos|

