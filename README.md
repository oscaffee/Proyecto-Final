# 📊 Proyecto Final – Máster Data Analytics

## 1. Objetivo del proyecto  

El objetivo de este proyecto ha sido trabajar con **dos datasets complementarios**:  
- **Global Superstore2**: contiene información de pedidos y transacciones.  
- **Customers**: incluye datos demográficos y de perfil de los clientes.  

Tras un proceso de limpieza, transformación y unión de ambas fuentes, se ha creado un **dataset final con más de 50.000 registros y 20+ variables**, sobre el que se ha realizado un **Exploratory Data Analysis (EDA)** en Python y un **dashboard interactivo en Power BI**.

---


## 2. Estructura del repositorio  

```text
📂 Proyecto-Final  
├── 📂 data_raw/          # Raw data (CSV originales)  
├── 📂 data_processed/    # Final dataset procesado  
├── 📂 notebooks/         # Jupyter/VS Code notebooks con el EDA  
├── 📂 reports/           # Informe en PDF/Word  
├── 📂 dashboard/         # Power BI (.pbix) + capturas  
└── README.md             # Este archivo  




---

## 3. Procesos realizados  

1. **Limpieda y transformacion de los datos**  

   - Eliminación de duplicados.  
   - Normalización de variables (fechas, ingresos, regiones).  
   - Unión de los datasets por `CustomerID`.  



2. **Analisis descriptivo**  

   - Tendencias de `Sales` a lo largo del tiempo.  
   - Distribución de clientes por género, profesión e ingresos.  
   - Ranking de productos y categorías más vendidos.  



3. **Analisis estadistico**  

   - Correlation matrix (ej. `Sales–Profit = 0.48`).  
   - Comparación de medias por segmentos.  
   - Variabilidad de variables clave (`Coefficient of Variation`).  



4. ** Dashboard para visualizacion de datos interactiva** (Power BI)  

   - **KPIs principales**: `Total Sales`, `Total Profit`, `Orders with Discount`.  
   - **Time series** con filtros por fecha.  
   - **Segmentación** por categoría de producto y perfil de cliente.  
   - **Comparativas** por regiones y segmentos.  

---



## 4. Resultados principales  

- Los **`Discounts` afectan negativamente al `Profit`**.  
- El **`Average Ticket` por género es prácticamente idéntico**.  
- El segmento *Home Office* muestra un `Average Profit` ligeramente superior.  
- Las **`Sales` presentan gran variabilidad** y outliers de alto valor.  

---



## 5. Conclusiones  

El análisis combinado de los datasets permite obtener una visión completa de la actividad comercial, uniendo la parte transaccional (`Sales`, `Profit`, `Discount`) con la parte de perfil de cliente (Customers).

El dashboard en **Power BI** facilita la exploración de estos resultados de forma visual e interactiva, ofreciendo insights útiles para la toma de decisiones.  

---



## 6. Tecnologías utilizadas  

- **Python** (Pandas, Matplotlib, Seaborn)  
- **Power BI**  
- **GitHub** para control de versiones y organización del proyecto  

---



## 7. Autor  

👤 Óscar García Sempere – Proyecto Final Máster Data Analytics  
