# Tarea: Mi prompt profesional
 
## Funcionalidad elegida

Sistema de Registro de Clientes
 
## Version 1: prompt basico

Crea un sistema de registro de clientes
 
## Version 2

Actúa como un Desarrollador Senior de Software especializado en Java y arquitectura limpia y crea un sistema de registro de clientes 

 
## Version 3: prompt final

Actúa como un Desarrollador Senior de Software especializado en Java y arquitectura limpia. Crea un módulo para el registro de nuevos clientes en un sistema de gestión comercial. El sistema necesita registrar clientes que ingresan al negocio, donde los datos requeridos por cliente son: ID único, Nombre Completo, Correo Electrónico y Teléfono. Como ejemplo de la estructura o sintaxis descriptiva que espero, el módulo debe organizar el código separando conceptos en texto como: un Registro/Record para la entidad Cliente(id, nombreCompleto, email, telefono), una Interfaz/Puerto para el almacenamiento como ClienteRepository (con métodos de verificación y guardado), un Caso de Uso RegistrarClienteUseCase para la lógica de negocio, y Excepciones de dominio personalizadas descriptivas como ClienteDuplicadoException (cuando el ID ya existe) e EmailInvalidoException (cuando falla el formato del correo). El módulo debe validar que el correo contenga un '@' y un '.' válido, y que el ID no esté duplicado. Restricción obligatoria: NO uses librerías externas o de terceros.
 
## Componentes del prompt final

| Nivel | Componente Agregado | Prompt |
| :--- | :--- | :--- |
| **1** | Prompt base | Crea un sistema de registro de clientes. |
| **2** | **+ Rol** | Actúa como un Desarrollador Senior de Software especializado en Java y arquitectura limpia. Crea un sistema de registro de clientes. |
| **3** | **+ Contexto** | Actúa como un Desarrollador Senior de Software especializado en Java y arquitectura limpia. Crea un módulo para el registro de nuevos clientes en un sistema de gestión comercial. El sistema necesita registrar clientes que ingresan al negocio, donde los datos requeridos por cliente son: ID único, Nombre Completo, Correo Electrónico y Teléfono. |
| **4** | **+ Instrucción / Validaciones** | ... El módulo debe validar que el correo contenga un '@' y un '.' válido, y que el ID no esté duplicado. |
| **5** | **+ Ejemplo / Estructura** | ... Como ejemplo de la estructura o sintaxis descriptiva que espero, el módulo debe organizar el código separando conceptos en texto como: un Registro/Record para la entidad `Cliente(id, nombreCompleto, email, telefono)`, una Interfaz/Puerto para el almacenamiento como `ClienteRepository` (con métodos de verificación y guardado), un Caso de Uso `RegistrarClienteUseCase` para la lógica de negocio, y Excepciones de dominio personalizadas descriptivas como `ClienteDuplicadoException` (cuando el ID ya existe) e `EmailInvalidoException` (cuando falla el formato del correo). |
| **6** | **+ Restricción** | ... Restricción obligatoria: NO uses librerías externas o de terceros. |
 
## Evaluacion del resultado

| Criterio | Versión 1 (Básico) | Versión 2 (Intermedio) | Versión 3 (Estructurado) |
| :--- | :---: | :---: | :---: |
| Define un rol específico (desarrollador/experto) | No | Sí | Sí |
| Especifica el contexto de negocio y datos de entrada | No | No | Sí |
| Incluye validaciones y reglas de negocio claras | No | No | Sí |
| Proporciona un ejemplo de estructura/sintaxis esperada | No | No | Sí |
| Define restricciones técnicas explícitas (sin librerías externas) | No | No | Sí |
| Genera un resultado listo para uso profesional/académico | No | No | Sí |
 
## Errores que evite

| Error Frecuente | Estado Inicial (V1 / V2) | Solución en Prompt Final (V3) |
| :--- | :--- | :--- |
| **Ser demasiado general** | "Crea un sistema de registro..." (Sin lenguaje, datos ni arquitectura). | Especificó el lenguaje java, Arquitectura Limpia y los 4 datos exactos a registrar. |
| **No dar contexto** | Petición aislada sin entorno de uso ni validaciones. | Contextualizó el entorno (gestión comercial) e incluyó reglas de negocio explícitas. |

