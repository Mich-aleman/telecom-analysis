# telecom-analysis
# Análisis ConnectaTel

El objetivo será evaluar el comportamiento de los clientes de una empresa de telecomunicaciones en Latinoamérica, ConnectaTel. 
Se trabajó con información registrada hasta el año 2024, lo cual permitirá analizar el comportamiento del negocio dentro de ese periodo.
Se trabajaron con tres datasets:  
- **plans.csv** → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)  
- **users.csv** → información de los clientes (edad, ciudad, fecha de registro, plan, churn)  
- **usage.csv** → detalle del uso real de los servicios (llamadas y mensajes)  

En este proyecto se deben explorar, limpiar y analizar estos datos para construir un perfil estadístico de los clientes, detectar comportamientos atípicos y crear segmentos de clientes.  
Este análisis permitirá identificar patrones de consumo, diseñar estrategias de retención y sugerir mejoras en los planes ofrecidos por la empresa.

En la limpieza de valores sucios se encontraron datos con valores futuros en las fechas (0.12%), valores faltantes en cuidades (11.72%) y valores imposibles en edades, por lo que se rellenaron con Nan para no perder datos.
Se detectó una mayor contratación y uso tanto de llamadas como mensajes del plan Básico en clientes de entre 40 y 50 años, mientras que en el plan Premium las edades que más lo consumen son adultos mayores.
Los segmentos más valiosos para la empresa, como área de oportunidad es el uso, mejorando los planes.
Los outliers encontrados no fueron muy extremos, por lo que se mantuvieron ya que son valores altos reales.
Se podrían mejorar los planes como el Premium con promociones para captar clientes de edades jovénes y adultas.
# Análisis ejecutivo

⚠️ **Problemas detectados en los datos**
- Datos con valores faltantes
- Datos con valores atípicos
- Datos con valores futuros


🔍 **Segmentos por Edad**
- Menos contrataciones en edades jóvenes


📊 **Segmentos por Nivel de Uso**
- Baja cantidad de usuarios tienen alto uso del servicio 
- Baja cantidad de usuarios tienen bajo uso del servicio



➡️ Esto sugiere que ...


💡 **Recomendaciones**
- Mejorar el plan Premium para captar clientes jóvenes, con promociones atractivas y costos no excesivos.
- Mejorar el servicio en ambos planes para captar un mayor uso por los usuarios.

**Abrir archivo desde Google Colab**
- Abre el archivo `.ipynb` en GitHub
- Haz clic en **Open in Colab**

**Cómo reproducir el análisis**
- Abre ´S7 Version-Estudiante-Project-ConnectaTel.ipynb´
- Ejecuta las celdas en orden
- El notebook carga automáticamente el dataset desde (https://github.com/Mich-aleman/telecom-analysis).
