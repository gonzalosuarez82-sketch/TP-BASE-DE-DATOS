# Proyecto Final Integrador - Herramientas básicas para el Análisis de Datos

Suárez Gonzlo
Curso: Herramientas básicas para el Análisis de Datos  
  

---
## Objetivo
Este proyecto busca analizar la evolución de las **ventas minoristas entre 2019 y 2024**, integrando Python (pandas, matplotlib, seaborn), Power BI y GitHub en un flujo end-to-end.  
La pregunta principal es:  
**¿Cómo evolucionaron las ventas mensuales por categoría y canal entre 2019-2024 y qué factores explican los picos y caídas más relevantes?**

Subpregunta/KPI:  
**¿Qué categorías impulsaron el crecimiento neto por trimestre?**

---

## Dataset
- **Fuente:** Kaggle – *Retail Sales Dataset* (Linda Lang’at)  
- **Enlace:** (https://www.kaggle.com/datasets/lindacheruto/retail-sales-dataset?utm_source=copilot.com) 
- **Tamaño:** ~1M registros, 12 columnas.  
- **Variables principales:** Fecha, Categoría, Canal (online/físico), Monto de venta, Región, Cliente, Método de pago.  

---

## Pasos realizados
1. **Ingesta y limpieza (Python):**
   - Conversión de fechas a formato `datetime`.
   - Eliminación de duplicados.
   - Imputación de nulos en categorías.
   - Filtrado de outliers con IQR.

2. **Exploración y visualización (EDA):**
   - Gráfico de línea: ventas mensuales totales.
   - Barras agrupadas: ventas por categoría y trimestre.
   - Pie chart: participación de canal online vs físico.
   - Boxplot: variabilidad de ventas por región.

3. **Dashboard en Power BI:**
   - Visualizaciones interactivas (5).
   - KPIs: crecimiento trimestral, participación de canales.
   - Panel de filtros por año, categoría y canal.

4. **Publicación en GitHub:**
   - Carpeta `/data/raw/` con dataset.
   - Carpeta `/notebooks/` con notebook de EDA.
   - Carpeta `/dashboard/` con archivo `.pbix` y capturas.
   - Este archivo `README.md`.

---

## Resultados principales
- El canal **online** creció un 45% entre 2020-2022, impulsado por electrónica y hogar.  
- Los picos de ventas coinciden con campañas de **Black Friday** y **Navidad**.  
- Las regiones urbanas muestran mayor variabilidad en ventas.  

---

## Reproducibilidad
- Clonar este repositorio.  
- Instalar dependencias: `pandas`, `matplotlib`, `seaborn`.  
- Abrir el notebook en `/notebooks/EDA_retail.ipynb`.  
- Explorar el dashboard en Power BI (`/dashboard/retail_dashboard.pbix`).  

---

## Bibliografía
- Kaggle Datasets: [Retail Sales Dataset](https://www.kaggle.com/datasets/lindalangat/retail-sales-dataset)  
- Our World in Data  
- World Bank Data  

