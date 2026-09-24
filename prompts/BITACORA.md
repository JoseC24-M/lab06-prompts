# Bitacora de prompts 
Laboratorio 06: Fundamentos de Ingenieria de Prompts. 
Herramienta de IA usada: (Gemini) 
'En el paso 4 al preguntar la IA me respondio exactamente lo que indica el laboratorio'
'En el paso 5 al hacer la misma pregunta la IA me indica que no tiene acceso a esa informacion'
## Ejercicio 2: Tokens y ventana de contexto 

| Texto | Caracteres | Tokens |
| :--- | :---: | :---: |
| Los estudiantes programan en Java. | 35 | 8 |
| The students program in Java. | 30 | 7 |
| desafortunadamente | 18 | 4 |

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos | 
|-------------|----------------|---------------------------| 
| 0 | 100% | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec | 
| 0.5 | 65.3% | BiblioTec, BiblioTec, BiblioTec, PrestaLibro, BiblioTec
 | 
| 1 | 44.5% | BiblioTec, BiblioTec, LibroYa, LectoGo, LibroYa | 
| 1.8 | 32.2% | LibroYa, PrestaLibro, LibroYa, BiblioTec, BiblioTec |
|Al subir la temperatura las probabilidades cambian y dan mas nombres|

## Ejercicio 4: Prompt vago vs estructurado 

| Criterio | Prompt vago | Prompt estructurado | 
|----------|-------------|---------------------|
| Menciona el objetivo del sistema | Hazme una descripcion de un sistema de biblioteca. | Actua como analista de sistemas. Redacta una descripcion breve de un sistema web para gestionar prestamos de libros en una biblioteca. 
Incluye objetivo, usuarios principales y 3 funcionalidades clave. 
Utiliza un lenguaje claro y profesional y presenta el resultado en 3 parrafos.
| 
| Menciona a los usuarios principales | NO | SI | 
| Tiene exactamente 3 funcionalidades | SI | SI | 
| Esta en 3 parrafos | NO | SI | 
| Lo usaria en un informe real | NO | SI |


## Ejercicio 5: Anatomia de un prompt 

| Componente | Texto de mi prompt | 
|------------|--------------------|
| Rol |Actua como desarrollador Java. Crea un programa en Java. | 
| Instruccion |Crea un programa en Java. | 
| Contexto | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de  una tienda | 
| Ejemplo | Crea un programa en Java para gestionar los productos de  una tienda.
 | 
| Formato | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de  una tienda.usando una clase Producto con los atributos codigo, nombre, precio y stock.Explica primero la estructura de la clase y luego presenta el codigo Java.
|

## Ejercicio 6: Del prompt basico al profesional

| Qué revisar | Cumple (Sí / No) |
|---|---|
| ¿Está escrito en Java y usa Swing? | SI |
| ¿Pide correo y contraseña? | SI |
| ¿Explica el funcionamiento antes o después del código? | SI |
| ¿El código está organizado en clases? | SI |
| ¿Valida los datos que ingresa el usuario? | SI |

