# Chatbot de Servicios Escolares

### Proyecto académico | Procesamiento de Lenguaje Natural con Python

## 1. Descripción del proyecto

Este proyecto consiste en el desarrollo de un chatbot orientado a brindar información sobre trámites administrativos de Servicios Escolares de una institución educativa.

El sistema permite que los usuarios realicen consultas mediante lenguaje natural y reciban respuestas relacionadas con los procedimientos disponibles, acompañadas de infografías informativas.

El chatbot se desarrolló en Python utilizando herramientas básicas de Procesamiento de Lenguaje Natural (PLN).

## 2. Objetivo

Desarrollar un prototipo funcional de chatbot capaz de identificar intenciones en consultas escritas por los usuarios y proporcionar orientación sobre trámites escolares, utilizando técnicas de normalización, tokenización y reconocimiento de palabras clave.

## 3. Tecnologías utilizadas

- **Python:** lenguaje de programación principal.
- **NLTK:** biblioteca utilizada para el procesamiento y tokenización del texto.
- **Google Colab:** entorno de desarrollo y ejecución del prototipo.
- **GitHub:** repositorio para almacenar y compartir el proyecto.
- **IPython:** visualización de las infografías durante la interacción.

## 4. Funcionalidades principales

El chatbot incorpora las siguientes funcionalidades:

- Recepción de consultas mediante texto.
- Normalización del texto para facilitar su interpretación.
- Tokenización de las consultas.
- Identificación de intenciones mediante palabras clave y reglas.
- Generación de respuestas predefinidas.
- Visualización de infografías asociadas a los trámites.
- Manejo de consultas no reconocidas.
- Finalización de la conversación mediante el comando `salir`.

## 5. Trámites disponibles

El prototipo proporciona orientación sobre 13 procedimientos:

1. Constancias de estudios.
2. Certificado parcial.
3. Duplicado de certificado total.
4. Recuperación de documentos electrónicos.
5. Historial académico.
6. Transcript.
7. Constancia de autenticidad.
8. Apostilla de documentos oficiales.
9. Transferencia de campus.
10. Cambio de programa académico.
11. Baja definitiva.
12. Reposición de credencial.
13. Reposición de marbete.

## 6. Funcionamiento general

El sistema sigue el siguiente proceso:

**Consulta del usuario → Normalización del texto → Tokenización → Identificación de intención → Generación de respuesta → Visualización de infografía.**

El reconocimiento de intenciones se realiza mediante reglas y palabras clave previamente definidas. Por lo tanto, el prototipo no utiliza un modelo de aprendizaje automático entrenado.

## 7. Instrucciones de ejecución

1. Abrir el archivo `Chatbot_Servicios_Escolares (1).ipynb` desde GitHub utilizando Google Colab.
2. Conectar el entorno de ejecución.
3. Ejecutar las celdas del notebook en el orden correspondiente.
4. Ejecutar la celda que descarga las 13 infografías genéricas desde GitHub.
5. Iniciar el chatbot.
6. Escribir una consulta relacionada con los trámites escolares.
7. Escribir `salir` para finalizar la conversación.

**Ejemplo de interacción:**

Usuario: Hola

Chatbot: ¡Hola! Soy el asistente de Servicios Escolares. ¿En qué puedo ayudarte?

Usuario: Necesito una constancia.

Chatbot: Puedo orientarte sobre el trámite de constancias de estudios.

## 8. Pruebas realizadas

Durante el desarrollo se realizaron pruebas de reconocimiento de intenciones y funcionamiento general.

- 10 pruebas de reconocimiento de intenciones completadas satisfactoriamente.
- Registro de 10 interacciones como evidencia del funcionamiento.
- Descarga exitosa de las 13 infografías desde GitHub.
- Ejecución del notebook en una sesión nueva de Google Colab.
- Comprobación de la visualización de una infografía asociada a una consulta.

Estas pruebas corresponden al alcance inicial del prototipo y no constituyen una evaluación exhaustiva de precisión.

## 9. Consideraciones

Este proyecto tiene fines académicos y demostrativos.

Las infografías publicadas en el repositorio son versiones genéricas elaboradas para la demostración del sistema. Los costos, requisitos y procedimientos incluidos en ellas son ilustrativos y no deben considerarse información institucional oficial.

El chatbot no realiza trámites reales ni consulta sistemas administrativos institucionales.

## 10. Estado del proyecto

**Prototipo funcional — Primera etapa de desarrollo.**

El proyecto constituye una base para incorporar posteriormente mejoras en el reconocimiento de intenciones, ampliación de consultas y mecanismos de evaluación.
