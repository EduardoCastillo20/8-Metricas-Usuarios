# 📊 Proyecto: Análisis de Métricas de Usuarios, Conversiones y Marketing

---

## 📘 Introducción
Este proyecto realiza un análisis completo del comportamiento de usuarios en una aplicación, utilizando datos de visitas, compras y costos de adquisición.  
Incluye carga de datos, validaciones, limpieza, métricas clave (DAU, WAU, MAU), análisis de sesiones, tiempos de conversión, ventas, LTV, costos por fuente y métricas de rentabilidad como CAC y ROMI.  

Además, el notebook incorpora comentarios de revisión tipo “semáforo” (verde, amarillo, rojo y azul) que destacan aciertos, recomendaciones y puntos a mejorar durante el proceso analítico.

---

## ✨ Funcionalidades

### 🔹 1. Carga y validación de datos
- Lectura de tres datasets (`visits`, `orders`, `costs`).
- Verificación de valores nulos y duplicados.
- Conversión correcta de columnas a formato `datetime`.
- Inspección general mediante `head()`, `info()` y conteos.

### 🔹 2. Métricas de uso (DAU, WAU, MAU)
- Cálculo de usuarios activos diarios, semanales y mensuales.
- Identificación de tendencias de uso.

### 🔹 3. Análisis de sesiones
- Cálculo del número de sesiones por día.
- Determinación de la duración de cada sesión.
- Visualización de la distribución de duración.
- Cálculo del tiempo promedio entre sesiones por usuario.

### 🔹 4. Conversión y comportamiento de compra
- Cálculo del tiempo entre la primera visita y la primera compra.
- Análisis de distribución de días hasta la conversión.
- Cálculo del número de pedidos por día.
- Cálculo del tamaño promedio de compra por mes.

### 🔹 5. Métricas financieras
- Cálculo del LTV (Lifetime Value) por usuario.
- Obtención del gasto total de marketing.
- Cálculo del gasto por fuente de adquisición.
- Cálculo del CAC (Costo de Adquisición de Cliente) por fuente.
- Obtención del ROMI (Return on Marketing Investment) por canal.

---

## 🛠️ Herramientas utilizadas
- **Python**  
- **Pandas** para manipulación de datos  
- **Matplotlib** para visualizaciones  
- **Jupyter Notebook** para el desarrollo del análisis  

---

## ✅ Conclusión
- Las métricas revelan el comportamiento de uso, frecuencia de retorno y tiempo de conversión de los usuarios.  
- Las fuentes **3** y **10** no generan un retorno favorable y deben eliminarse.  
- La fuente **1** es altamente rentable al presentar bajo costo y alto beneficio.  
- El análisis estadístico, las visualizaciones y las métricas financieras permiten tomar decisiones fundamentadas sobre inversión en marketing y estrategias de adquisición.

---
