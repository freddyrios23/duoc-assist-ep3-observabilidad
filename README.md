# DUOC-Assist EP3 - Observabilidad

## Descripción

Este repositorio corresponde a la Evaluación Parcial N°3 de la asignatura Ingeniería de Soluciones con IA.

El proyecto continúa el desarrollo de DUOC-Assist, un agente académico básico. En esta etapa se agregó observabilidad para analizar su comportamiento mediante métricas, logs, gráficos y validaciones de seguridad.

## Funcionalidades implementadas

* Agente académico básico basado en documentos simples.
* Métricas de observabilidad.
* Medición de latencia por consulta.
* Registro del estado de ejecución.
* Archivo CSV con los resultados de las pruebas.
* Logs de ejecución del agente.
* Dashboard básico con gráficos en Google Colab.
* Validación de seguridad para rechazar consultas con datos sensibles.
* Mejora mediante normalización de texto para evitar errores con tildes.

## Métricas utilizadas

* Latencia.
* Estado de ejecución.
* Consultas con información encontrada.
* Consultas sin información encontrada.
* Precisión final.
* Consultas rechazadas por seguridad.

## Tecnologías utilizadas

* Python
* Google Colab
* Pandas
* Matplotlib
* CSV
* Logging

## Archivos del repositorio

* `duoc_assist_ep3_observabilidad.ipynb`: notebook principal del proyecto.
* `Informe_EP3_DUOC_Assist_Freddy_Rios.pdf`: informe técnico de la evaluación.
* `metricas_duoc_assist.csv`: archivo generado con las métricas de prueba.

## Cómo ejecutar el proyecto

1. Abrir el archivo `duoc_assist_ep3_observabilidad.ipynb` en Google Colab.
2. Ejecutar las celdas en orden.
3. Revisar la generación del archivo CSV con las métricas.
4. Revisar los gráficos del dashboard.
5. Verificar la prueba de seguridad con una consulta que contiene un dato sensible.

## Resultados generales

Durante las pruebas finales, el agente logró responder correctamente las consultas académicas disponibles, rechazar preguntas fuera del contexto institucional y bloquear una consulta con información sensible.

Además, se detectó una falla inicial relacionada con el uso de tildes en la palabra “matrícula”, la cual fue corregida mediante normalización de texto.

## Autor

Freddy Alexander Rios Nilo
