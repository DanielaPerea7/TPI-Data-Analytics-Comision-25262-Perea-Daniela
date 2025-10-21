
# 📊 Pre-Entrega 2 - Limpieza y Análisis Exploratorio de Producción de Gas Natural en Argentina

Este proyecto forma parte de la **Preentrega** del curso de *Data Analytics*.  
El objetivo es demostrar habilidades iniciales en **Python básico**, **Pandas**, y **Análisis exploratorio de datos**, aplicando buenas prácticas de codificación y presentación de resultados en formato notebook.

---

🎯 **Objetivos del Proyecto**

**1️⃣ Etapa 1 – Recopilación y Preparación:** Carga de datos, uso de estructuras de datos fundamentales de Python (Lista de Diccionarios), EDA inicial, y diagnóstico de calidad.

**2️⃣ Etapa 2 – Procesamiento y Limpieza:**  Normalización de texto y tipado, eliminación de duplicados, transformación de variables y técnicas de agregación para análisis de rendimiento.
---

⚙️ **Proceso de trabajo**

**Etapa 1**
1️⃣ **Carga de datos:** importar datasets en Python utilizando pandas.  
4️⃣ **Análisis Exploratorio inicial:** revisión general del dataset y detección de valores clave.  
5️⃣ **Calidad de datos:** identificar valores nulos y duplicados en los conjuntos de datos

**Etapa 2**
1️⃣ **Limpieza de datos:** combinación de fuentes y análisis por campaña y canal.  
2️⃣ **Transformación de datos:** detección de productos de alto rendimiento.  
3️⃣ **Agregación por categoría:** análisis de métricas agregadas e insights.  
4️⃣ **Integración de Datos:** identificación de patrones e interpretación de resultados.

---

🗂️ **Datasets utilizados**

📘 Dataset1: Ventas
  * Granularidad: Por Transacción.
  * Variables: id_venta, producto, precio, cantidad, fecha_venta, categoria.
  * Utilidad: Permite calcular métricas de rendimiento (ingreso, ticket promedio), analizar tendencias temporales y filtrar productos de alto rendimiento mediante la agregación por producto y categoría.

📘 Dataset2: Clientes
  * Granularidad: Por Cliente.
  * Variables: id_cliente, nombre, edad, ciudad, ingresos.
  * Utilidad: Es fundamental para segmentar y perfilar a los clientes (por edad o ingresos) y para futuras integraciones con el dataset de Ventas.

📘 Dataset3: Marketing
  * Granularidad: Por Campaña.
  * Variables: id_campanha, producto, canal, costo, fecha_inicio, fecha_fin.
  * Utilidad: Permite analizar la inversión y el esfuerzo de marketing. Su integración con Ventas a través del producto permite medir la efectividad y la rentabilidad de cada canal de adquisición.

---

🛠️ **Herramientas utilizadas**
  * Lenguaje: Python 3.10
  * Análisis y visualización: pandas
  * Entorno: Google Colab, GitHub

---

👩‍💻 **Nombre del Alumno**

- Daniela Perea
- 
---

**Fecha de entrega**: 22/10/2025
