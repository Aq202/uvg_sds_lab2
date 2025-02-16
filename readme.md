# Laboratorio 2 - Curso de Gen AI

Diego Andrés Morales Aquino - 21762

1. ¿Hubo alguna aplicación o caso de uso de los LLMs que le llamó más la atención? ¿Por qué?

En general, todas las aplicaciones de uso de la API de Gemini me parecieron bastante útiles. 
Sin embargo, dos me resultaron especialmente interesantes. En primer lugar, el uso de Langgraph para
construir aplicaciones más completas que hagan uso de la IA generativa. El ejemplo que se desarrolló
en el laboratorio fue bastante impresionante, pues el mismo agente era capaz de ejecutar acciones
según el contexto en el que se encontraba la conversación con el usuario. Por ejemplo, obtener el menú
del restaurante (sin inventar productos nuevos) o ejecutar una función para la creación de una nueva órden.  Esto puede ser de gran utilidad para desarrollar asistentes inteligentes más sofisticados, capaces de adaptarse dinámicamente a las necesidades del usuario. Además, la capacidad de estructurar flujos de trabajo en forma de grafos dirigidos permite una mayor flexibilidad y eficiencia en la toma de decisiones del agente.

Por otro lado, la capacidad de que el mismo modelo de AI sea capaz de ejecutar funciones y procesar sus resultados me parece fascinante. En el ejercicio en el que interactúa con una base de datos se ejemplifica muy bien dicho potencial, pues se puede interactuar con la BD de manera más rápida y eficiente. De manera personal, esto me serviría bastante para comprender bases de datos de las cuales no tengo mucha información en un inicio.

2. Proponga un caso de ciberseguridad que considere se puede solucionar mediante un LLM y
describa de forma general cómo lo resolvería.


Un caso de ciberseguridad que puede resolverse con un LLM es la detección y mitigación de ataques de phishing sofisticados. Mediante RAG, el modelo puede analizar correos electrónicos, mensajes y sitios web sospechosos en tiempo real, comparándolos con una base de datos actualizada de amenazas conocidas y patrones fraudulentos. También, con finetuning, se puede entrenar el modelo con ejemplos específicos de phishing dirigidos a una organización, mejorando su capacidad de detección. Un LLM puede identificar inconsistencias en el lenguaje, enlaces sospechosos o intentos de suplantación de identidad con mayor precisión que los métodos tradicionales. 

De igual manera, un LLM puede examinar fragmentos de código en archivos sospechosos, scripts o ejecutables, identificando patrones maliciosos utilizadas por los atacantes. Mediante aprendizaje supervisado o fine-tuning con muestras de malware previamente analizadas, el modelo puede reconocer amenazas emergentes incluso si no están registradas en bases de datos de firmas tradicionales. Además, puede explicar el propósito del código malicioso en lenguaje natural, facilitando la labor de los analistas de seguridad.

Sin embargo, es importante tomar en cuenta que el uso de un LLM puede introducir falsos positivos que podrían llegar a generar un exceso de alertas, causando fatiga en los encargados de seguridad o incluso dañando la reputación de recursos legítimos. Además, los falsos negativos permitirían que ataques sofisticados pasen desapercibidos, aumentando el riesgo de brechas de seguridad. 