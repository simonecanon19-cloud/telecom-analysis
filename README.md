# Análisis de Telecomunicaciones - ConnectaTel

## 🎯 Objetivo del Proyecto
El objetivo principal es analizar el comportamiento de uso de los clientes de ConnectaTel para identificar patrones de consumo, segmentar a los usuarios por edad y nivel de uso, y detectar oportunidades comerciales para optimizar la oferta de planes.

## 📊 Datasets Utilizados
- **`users`**: Contiene información demográfica (edad, plan, ciudad).
- **`usage`**: Registro histórico de mensajes, llamadas y minutos consumidos.

## 🛠️ Etapas del Análisis
1. **Limpieza y Preparación**: Carga de datos y corrección de tipos.
2. **Análisis de Outliers**: Identificación de valores extremos mediante el método IQR para limpiar el ruido estadístico.
3. **Segmentación**: Creación de perfiles de usuario por edad (Joven, Adulto, Adulto Mayor) y por nivel de intensidad de uso.
4. **Visualización**: Histogramas y countplots para validar la distribución de los segmentos.
5. **Insights Ejecutivos**: Conclusiones accionables para los stakeholders.

## 🚀 Cómo ejecutar el notebook
Para reproducir este análisis:
1. Sube el archivo `.ipynb` a **Google Colab** o ábrelo en un servidor local de **Jupyter Notebook**.
2. Asegúrate de tener instaladas las librerías `pandas`, `seaborn` y `matplotlib`.
3. Carga los archivos CSV correspondientes cuando el código lo solicite.

## 🧪 Guía de Reproducción
- Ejecutar las celdas en orden secuencial.
- El filtrado de outliers se aplicó a las columnas de mensajes, llamadas y minutos basados en los límites calculados.
