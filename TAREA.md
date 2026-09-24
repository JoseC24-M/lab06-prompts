# Tarea: Mi prompt profesional 
## Funcionalidad elegida 
estión de inventario: Módulo CRUD (Crear, Leer, Actualizar, Eliminar) de productos para una aplicación desktop de tienda de abarrotes desarrollada en Java Swing.
## Version 1 prompt basico 
text Hazme un CRUD de productos en Java.

## Version 2 
Actúa como desarrollador Java Senior. Crea una interfaz gráfica Swing para un CRUD de productos (Crear, Leer, Actualizar, Eliminar) de una tienda de abarrotes. Incluye los campos: código, nombre, precio y stock. Explica el código paso a paso.

## Version 3 prompt final 
Actúa como Arquitecto de Software y Desarrollador Java Senior.

Diseña y programa un módulo CRUD (Crear, Leer, Actualizar, Eliminar) de productos para el sistema desktop de una tienda de abarrotes.

Estructura el código organizándolo estrictamente en dos clases: 'Producto' (modelo con los atributos codigo [String], nombre [String], precio [double], stock [int]) y 'ProductoForm' (interfaz Swing con un JTable para visualizar el listado y un JPanel con un formulario de entrada).

Usa este estilo de diseño para las validaciones:
- Si el precio es <= 0 o el stock es < 0, muestra un aviso de error mediante 'JOptionPane.showMessageDialog(null, "Error: Valores numéricos inválidos")'.

RESTRICCIONES OBLIGATORIAS:
- No uses librerías externas (utiliza únicamente el JDK estándar con javax.swing y java.awt).
- No uses base de datos externa; utiliza una lista 'ArrayList<Producto>' en memoria para simular la persistencia.

Presenta el resultado estructurado en las siguientes 3 secciones:
1. Explicación breve de la arquitectura de las dos clases.
2. Código fuente completo y documentado de ambas clases en bloques de código Java separadas.
3. Instrucciones rápidas paso a paso para compilar y ejecutar el programa desde la terminal.

## Componentes del prompt final 

| **Componente** | **Texto exacto de mi prompt** |
|---|---|
| **Rol** | "Actúa como Arquitecto de Software y Desarrollador Java Senior." |
| **Instrucción** | "Diseña y programa un módulo CRUD (Crear, Leer, Actualizar, Eliminar) de productos..." |
| **Contexto** | "...para el sistema desktop de una tienda de abarrotes." |
| **Ejemplo** | "Usa este estilo de diseño para las validaciones: Si el precio es <= 0 o el stock es < 0, muestra un aviso de error mediante JOptionPane.showMessageDialog(null, "Error: Valores numéricos inválidos")." |
| **Formato** | "Presenta el resultado estructurado en las siguientes 3 secciones: 1. Explicación breve... 2. Código fuente completo... 3. Instrucciones rápidas..." |
| **Restricción** | "RESTRICCIONES OBLIGATORIAS: No uses librerías externas... No uses base de datos externa..." |

## Evaluacion del resultado 

| Criterio de Evaluación | Cumple (Sí / No) |
|---|---|
| ¿El código está escrito en Java Swing sin librerías externas ni dependencias complejas? | Sí |
| ¿Implementa funcionalmente las 4 operaciones del CRUD (Crear, Leer, Actualizar, Eliminar)? | Sí |
| ¿Valida que el precio y stock sean positivos usando JOptionPane? | Sí |
| ¿Separa la lógica en una clase modelo (Producto) y una de interfaz (ProductoForm)? | Sí |
| ¿Presenta la respuesta dividida exactamente en las 3 secciones de formato solicitadas? | Sí |

## Errores que evite

Evité ser demasiado general al especificar desde el inicio que el CRUD sería para un sistema desktop en Java Swing, indicando además el contexto de una tienda de abarrotes y los atributos exactos de los productos. También definí claramente el formato de respuesta para que la IA entregara la información de manera ordenada, con la arquitectura, el código completo y las instrucciones de ejecución, evitando explicaciones desordenadas o código incompleto.
