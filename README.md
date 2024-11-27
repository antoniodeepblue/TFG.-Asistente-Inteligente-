# Asistente Inteligente para el Canal de Isabel II

I. Resumen del Proyecto

Objetivo: Desarrollo y evaluación de un asistente inteligente basado en modelos de lenguaje natural para mejorar la atención al usuario del Canal de Isabel II.

Motivación: Necesidad de respuestas precisas y eficientes a las consultas de los usuarios.

Resultados: Se establecieron las bases para un asistente efectivo, demostrando la viabilidad de usar modelos preentrenados para mejorar la atención al cliente y la resolución de problemas.

II. Metodología y Diseño

Metodología: Enfoque en cascada con recolección y análisis progresivo de datos.

Modelo de Lenguaje: Mixtral, seleccionado por su capacidad de seguir instrucciones y guiar en la resolución de problemas.

Entrenamiento: Fine-tuning del modelo BERT con datos etiquetados de preguntas y respuestas del Canal de Isabel II.

Optimización: Mecanismo de filtrado basado en la puntuación de confianza para mejorar la calidad de las respuestas.

Interfaz: Desarrollo utilizando el framework Hugging Face para aplicaciones de NLP.

III. Evaluación y Resultados

Métricas: Se utilizaron métricas léxicas para evaluar la precisión de las respuestas de diferentes modelos LLM.

Análisis: Comparación de la capacidad de los modelos para proporcionar respuestas precisas a consultas específicas del Canal de Isabel II.

Hallazgos: El proyecto demostró la capacidad del asistente inteligente para brindar respuestas precisas y mejorar la atención al usuario.

IV. Trabajo Futuro

Mejoras: Ajustes para optimizar la precisión y la calidad de las respuestas.

Expansión: Ampliación del conjunto de datos de entrenamiento.

Innovación: Exploración de modelos de lenguaje más avanzados.

Integración: Incorporación de la retroalimentación de los usuarios para un desarrollo continuo.

V. Recursos Adicionales

Repositorio Institucional (O2) de la Universitat Oberta de Catalunya: http://hdl.handle.net/10609/150520

# TFG.-Asistente-Inteligente-
# Desarrollo de un Asistente Inteligente para la  atención al cliente y solución técnica en  empresas del sector del agua mediante  modelos preentrenados.
El proyecto aborda el desarrollo y evaluación de un asistente inteligente basado 
en modelos preentrenados de lenguaje natural, con el objetivo de crear un 
sistema capaz de ofrecer respuestas precisas y mejorar la atención a los 
usuarios del Canal de Isabel II mediante técnicas de inteligencia artificial y NLP. 
La metodología sigue un enfoque en cascada, con la recolección progresiva y el 
análisis continuo de un conjunto de datos de preguntas y respuestas etiquetadas 
del Canal de Isabel II. Se selecciona, ajusta y entrena el modelo BERT mediante 
técnicas de fine-tuning. Además, se implementa un mecanismo de filtrado 
basado en el score de confianza para mejorar la calidad de las respuestas 
generadas.  
Para realizar las inferencias se elige el modelo Mixtral debido a su capacidad 
para seguir instrucciones específicas y guiar a los clientes o técnicos del Canal 
de Isabel II en la resolución de problemas o la realización de tareas. En el diseño 
del interfaz se utiliza el framework Hugging Face. 
En la evaluación del rendimiento de los modelos se utilizan diversas métricas 
léxicas. También, se analiza y compara la capacidad de diferentes modelos de 
LLM para proporcionar respuestas a consultas específicas de los usuarios de la 
empresa Canal de Isabel II. 
En conclusión, el proyecto sienta las bases para un asistente inteligente efectivo 
en la atención a usuarios del Canal de Isabel II. Además, se proponen trabajos 
futuros con ajustes y mejoras adicionales para alcanzar su máximo potencial en 
términos de precisión y calidad de las respuestas. 

## Contenidos:

1. Introducción
   
1.1 Contexto y justificación del Trabajo: Describe la necesidad de un asistente inteligente para mejorar la atención al usuario en el Canal de Isabel II, destacando los beneficios de la automatización y la disponibilidad 24/7.

1.2 Objetivos del Trabajo: Define los objetivos del proyecto, incluyendo la creación de un asistente que responda preguntas frecuentes, ofrezca soluciones técnicas y guíe a los usuarios en la resolución de problemas.

1.3 Enfoque y método seguido: Detalla el enfoque metodológico, que incluye la investigación de la literatura existente, el análisis de modelos pre-entrenados, la recopilación de datos, el fine-tuning de modelos y la evaluación del rendimiento.

1.4 Planificación del Trabajo: Presenta el plan de trabajo con las etapas del proyecto y su cronograma.

1.5 Breve sumario de productos obtenidos: Resume los productos del proyecto, incluyendo el modelo BERT con fine-tuning, el modelo Mixtral para inferencia y la asistencia de expertos.

1.6 Breve descripción de los otros capítulos de la memoria: Ofrece una visión general de los capítulos restantes del trabajo.

2. Investigar la aplicabilidad de modelos preentrenados
   
2.1. Revisar la literatura existente sobre el uso de modelos preentrenados: Examina el estado del arte en la utilización de LLMs para la creación de asistentes inteligentes, centrándose en modelos como BERT y sus aplicaciones en diferentes dominios.

2.2. Análisis de modelos preentrenados para fine-tuning: Evalúa diferentes modelos pre-entrenados (BERT, DistilBERT) y sus características, incluyendo tamaño, arquitectura y rendimiento, para determinar el más adecuado para el fine-tuning.

2.3. Recopilación y análisis del conjunto de datos: Describe la creación del conjunto de datos utilizado para entrenar y evaluar el asistente, incluyendo el formato (JSON), las fuentes (oficina virtual) y la estructura (ID, título, contexto, pregunta, respuestas).

3. Realizar fine-tuning e inferencia en modelos preentrenados para adaptarlos al contexto del Canal de Isabel II
   
3.1. Seleccionar modelos preentrenados adecuados para fine-tuning: Justifica la elección del modelo BERT para el fine-tuning, considerando factores como el tamaño, el idioma y el rendimiento en tareas similares.

3.2. Definir los parámetros y características específicas del fine-tuning para adaptar el modelo al contexto del Canal de Isabel II: Detalla el proceso de fine-tuning del modelo BERT, incluyendo la selección de hiperparámetros (tasa de aprendizaje, tamaño del lote, épocas), la función de pérdida y la evaluación del rendimiento.

4. Desarrollar un asistente que guíe a los clientes y ofrezca soluciones técnicas especializadas
   
4.1 Implementar el asistente inteligente utilizando el modelo preentrenado ajustado: Describe la implementación del asistente con el modelo BERT ajustado, incluyendo la configuración del entorno, las bibliotecas utilizadas y la integración con la interfaz de usuario.

4.2 Diseñar la interfaz del asistente para facilitar la interacción con los clientes y técnicos del Canal de Isabel II: Define la interfaz de usuario del asistente, considerando la usabilidad, la accesibilidad y la claridad en la presentación de la información.

4.2 Incorporar capacidades de ofrecer soluciones técnicas especializadas a consultas específicas del sector del agua: Explica cómo el asistente ofrece soluciones técnicas a consultas sobre averías, suministro, facturación y otros temas relevantes al sector del agua.

5. Evaluar el rendimiento del asistente inteligente
   
5.1. Definir métricas de evaluación relevantes para el contexto del asistente: Establece las métricas para medir el rendimiento del asistente, incluyendo la precisión, la exhaustividad (recall), la puntuación F1 y la precisión general (accuracy), considerando la relevancia de las respuestas y la satisfacción del usuario.

5.2. Valorar la precisión de las respuestas: Analiza la precisión de las respuestas del asistente, utilizando ejemplos específicos y comparándolas con las respuestas de referencia.

5.3. Evaluar y comparar las respuestas con otros LLM: Compara el rendimiento del asistente con otros modelos LLM como Mixtral, analizando sus fortalezas y debilidades en la generación de respuestas y la comprensión del contexto.

5.4. Identificar áreas de mejora: Identifica áreas de mejora para el asistente, considerando las limitaciones del modelo, la calidad del conjunto de datos y la interfaz de usuario, con propuestas para futuras iteraciones.

6. Resultados y productos obtenidos
   
Presenta los resultados obtenidos durante el desarrollo del asistente, incluyendo la precisión alcanzada, la eficiencia del modelo y ejemplos de su funcionamiento en diferentes escenarios. Se listan los productos obtenidos: modelo BERT ajustado, modelo Mixtral para inferencia, documentación, código fuente y la interfaz del asistente.

7. Conclusiones

Resume las principales conclusiones del trabajo, destacando la viabilidad de utilizar LLMs para crear un asistente inteligente para el Canal de Isabel II. Se subraya la importancia de la selección del modelo, el fine-tuning y la evaluación del rendimiento para lograr resultados satisfactorios. Se propone el modelo Mixtral como la mejor opción para el asistente.

8. Glosario
    
Define los términos técnicos utilizados en el trabajo, incluyendo conceptos relacionados con LLMs, fine-tuning, inferencia, métricas de evaluación y procesamiento del lenguaje natural.

9. Bibliografía
 
Lista las fuentes bibliográficas utilizadas en el trabajo, incluyendo artículos científicos, libros, sitios web y documentación técnica.

10. Anexos
    
Contiene información adicional relevante para el trabajo.

### Aspectos relevantes del trabajo

El trabajo describe en detalle el proceso de desarrollo del asistente, incluyendo la selección del modelo, el fine-tuning, la implementación y la evaluación del rendimiento.

Se exploran diversos modelos como BERT, DistilBERT y Mixtral, analizándose sus ventajas y desventajas en el contexto del proyecto.

Se destaca la importancia de la calidad del conjunto de datos para el entrenamiento del modelo, así como la necesidad de realizar una evaluación exhaustiva del rendimiento del asistente.

Se proporcionan recomendaciones para futuras mejoras, incluyendo la ampliación del conjunto de datos, la exploración de nuevos modelos y la optimización de la interfaz de usuario.

El trabajo se presenta de forma clara y organizada, utilizando lenguaje técnico adecuado y apoyándose en recursos visuales como diagramas y tablas.

En general, este trabajo ofrece una valiosa contribución al campo de la aplicación de LLMs para la creación de asistentes inteligentes en el sector del agua.
