🛫 Análisis de Retrasos y Cancelaciones de Vuelos (Enero 2023)
📌 Descripción

Este proyecto combina Python en Google Colab y herramientas de Inteligencia Artificial como ChatGPT y Gemini para realizar un análisis integral sobre los retrasos y cancelaciones de vuelos en EE.UU. durante enero de 2023.

El conjunto de datos utilizado proviene del Departamento de Transporte de EE.UU., e incluye información sobre rutas aéreas, aerolíneas, aeropuertos, horarios y causas atribuidas a retrasos y cancelaciones.

🎯 Objetivo

Analizar la eficiencia operacional de los vuelos en enero de 2023, identificando patrones de demoras y cancelaciones según variables temporales y operativas. El fin es determinar los principales factores que afectan la puntualidad aérea y proponer estrategias de mejora y optimización de recursos.

❓ Preguntas de negocio
1. Eficiencia operacional

¿Cuál es el porcentaje de vuelos cancelados y retrasados respecto al total?

¿Qué aerolíneas presentan mayor tasa de cancelación/retraso?

¿Existen aeropuertos con mayor probabilidad de incidentes?

¿Cuál es la duración promedio de los retrasos?

¿Qué rutas origen-destino son más propensas a demoras/cancelaciones?

2. Impacto temporal

¿En qué horarios (mañana, tarde, noche) se concentran más los retrasos?

¿Existen patrones según día de la semana y franja horaria?

¿Se incrementan cancelaciones en fechas específicas?

3. Causas y correlaciones

¿Qué factores influyen más en los retrasos (clima, congestión, aerolínea, tipo de vuelo, distancia de la ruta)?

¿Los vuelos más largos tienen mayor probabilidad de retraso?

¿Existe correlación entre el tamaño del aeropuerto (volumen de vuelos) y la puntualidad?

🛠️ Proceso realizado

Selección de dataset → Flight Delay and Cancellation (Jan 2023).

Exploración y preparación de datos:

Identificación y manejo de nulos, duplicados y atípicos.

Conversión de tipos de datos.

Creación de variables adicionales (ej. franjas horarias).

Análisis exploratorio:

Medidas de tendencia central y dispersión.

Distribuciones de demoras por día, hora y aerolínea.

Comparación entre aeropuertos y rutas.

Técnicas analíticas:

Análisis de correlaciones.

Segmentación por categorías (aerolínea, aeropuerto, ruta).

Modelado exploratorio con regresión.

Visualización de resultados:

Gráficos descriptivos (barras, líneas, boxplots).

Dashboards y resúmenes visuales.

Comunicación de hallazgos:

Informe estructurado con conclusiones.

Video de presentación con insights principales.

🤖 Herramientas utilizadas

Python (Google Colab) → Exploración, limpieza y análisis de datos.

Pandas, NumPy, Matplotlib, Seaborn → Procesamiento y visualización.

ChatGPT & Gemini → Asistencia en análisis, documentación e interpretación de hallazgos.

Estadística & ML básico → Validación de hipótesis y correlaciones.

🚀 Resultados esperados

Identificación de las aerolíneas, aeropuertos y rutas más críticas en términos de puntualidad.

Patrones de retrasos y cancelaciones según día, hora y condiciones operativas.

Detección de factores principales que influyen en los retrasos.

Recomendaciones estratégicas para mejorar la eficiencia y gestión de recursos en la industria aérea.

📌 Conclusión

El uso de IA y análisis de datos aplicado a la industria de la aviación permite transformar grandes volúmenes de información en insights accionables. Este proyecto demuestra cómo la combinación de Python, herramientas de IA y visualización facilita la comprensión de patrones complejos y la propuesta de soluciones estratégicas para la optimización del transporte aéreo.
