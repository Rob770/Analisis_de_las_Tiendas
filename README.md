# Analisis_de_las_Tiendas
Proyecto de Data Science en Python que analiza ventas de múltiples tiendas de Alura Store, generando insights de negocio mediante análisis exploratorio y visualización de datos. Ideal como proyecto de portafolio para Data Analyst Junior.
# 📊 Análisis de las Tiendas – Alura Store

## 📌 Propósito del análisis

Este proyecto tiene como objetivo analizar el desempeño de las cuatro tiendas de la cadena **Alura Store** para apoyar al Sr. Juan en la toma de decisión sobre **qué tienda vender** para iniciar un nuevo emprendimiento.

A través del análisis de datos de ventas, calificaciones de clientes y costos operativos, se busca identificar la tienda **menos eficiente** desde un punto de vista económico y de satisfacción del cliente.

---

## 🧱 Estructura del proyecto

```
Analisis_de_las_Tiendas/
│
├── Analisis_Alura_Store.ipynb   # Notebook principal con todo el análisis
├── README.md                   # Descripción del proyecto
└── data/                        # (Opcional) Datos si se descargan localmente
```

El análisis se realizó directamente desde archivos CSV alojados en GitHub, lo que permite que el proyecto sea **reproducible** sin necesidad de descargar datos manualmente.

---

## 📈 Análisis realizados

### 1️⃣ Facturación total por tienda

Se calculó la suma total de ingresos por tienda para identificar cuál genera menor facturación.

**Insight:** Se observan diferencias claras en los ingresos entre las tiendas.

---

### 2️⃣ Ventas por categoría

Se analizó la facturación por categoría de producto para identificar cuáles impulsan el negocio.

**Insight:** Algunas categorías concentran la mayor parte de las ventas, siendo clave para la rentabilidad.

---

### 3️⃣ Calificación promedio por tienda

Se calculó el promedio de calificaciones otorgadas por los clientes a los productos de cada tienda.

**Insight:** La satisfacción del cliente varía entre tiendas, lo cual impacta directamente en la reputación del negocio.

---

### 4️⃣ Productos más y menos vendidos

Se identificaron los productos con mayor y menor volumen de ventas.

**Insight:** Un grupo reducido de productos concentra la mayoría de las ventas.

---

### 5️⃣ Envío promedio por tienda

Se comparó el costo promedio de envío entre las tiendas.

**Insight:** Algunas tiendas presentan costos de envío más altos, lo que afecta su competitividad.

---

## 📊 Visualizaciones

Durante el análisis se utilizaron distintos tipos de gráficos:

* Gráficos de barras
* Gráficos de barras horizontales
* Gráficos circulares

Estos gráficos permiten interpretar los resultados de forma clara y visual.

---

## 🏁 Conclusión y recomendación

Tras evaluar todas las métricas analizadas, se concluye que **la Tienda 4 presenta el desempeño más bajo en conjunto**, con menor facturación, peor calificación promedio y costos de envío menos competitivos.

👉 **Se recomienda vender la Tienda 4**, ya que representa la menor eficiencia dentro de la cadena Alura Store.

---

## ▶️ Instrucciones para ejecutar el proyecto

1. Abrir el notebook `Analisis_Alura_Store.ipynb` en Google Colab.
2. Ejecutar las celdas en orden desde el inicio.
3. Asegurarse de tener conexión a internet para cargar los archivos CSV.
4. Revisar los gráficos y conclusiones generadas.

---

## 🛠️ Tecnologías utilizadas

* Python
* Pandas
* Matplotlib
* Google Colab
* GitHub
