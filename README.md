# Sprint 7: Análisis de una empresa de telecomunicaciones.
Análisis de una empresa de telecomunicaciones.

## 🧠 Objetivo del análisis
Se busca dar respuesta a las siguientes preguntas del negocio:
 Preguntas del negocio
-	¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
-	¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?
-	¿Cómo varía el uso según la edad y el tipo de plan contratado?
-	¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?
## 📂 Se trabajó con las siguientes fuentes de información:
-	plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
-	users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
-	usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

## 🛠️ Herramientas de la lección
- Jupyter Notebook
- Python: pandas, numpy, seaborn, matplotlib
  

## 🧠 Se procedió con la ejecución de las siguientes etapas:
Paso:  	Acción
1. Cargar y explorar: **Cargar** y explorar plans, users_latam, usage.
2. Identificación de problemas de calidad: **Contar** nulos, detectar sentinels, revisar fechas fuera de rango.
3. Limpieza básica: **Reemplazar** sentinels, convertir fechas, imputar o marcar NA según reglas.
4. Summary statistics:	**Revisar** las medidas clave en variables categóricas y numéricas.
5. Visualización & outliers:	**Crear** histogramas y boxplots.
6. Segmentación:	**Crear** segmentaciones basadas en reglas claras; visualizar proporciones con countplots.
7. Insight ejecutivo:	**Redactar** conclusiones y recomendaciones comerciales basadas en los pasos anteriores.
8. Publicación:	**Subir** tu notebook + README a GitHub.

   
## 📘 Cómo reproducir el análisis

1. Abre `https://github.com/43ferval-dotcom/An-lisis-ConnectaTel`
2. Ejecuta las celdas en orden
