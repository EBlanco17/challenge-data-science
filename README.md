# StoresAlura - Análisis de ventas

Resumen rápido
- Propósito: analizar ventas, categorías, calificaciones y costos de envío de 4 tiendas usando un notebook de pandas/matplotlib para obtener métricas y visualizaciones que apoyen decisiones comerciales.

### Estructura del proyecto
- StoresAlura.ipynb — notebook con todo el flujo:
  - Importación de datos (lectura con `pd.read_csv`)
  - Cálculo de ventas totales por tienda
  - Ventas por categoría (top 3)
  - Calificación promedio por tienda
  - Los 3 Productos más y menos vendidos por tienda
  - Envío promedio por tienda
  - Gráficas

Ejemplos de gráficos
- Gráficos generados en el notebook:
  - Ventas Totales por Tienda ("Ventas Totales por Tienda") — barras con etiquetas de monto.
  - Ventas por Categoría por Tienda ("Ventas por Categoría de Producto por Tienda") — barras agrupadas.
  - Calificación Promedio por Tienda ("Calificación Promedio por Tienda") — pie chart.
  - Productos más y menos vendidos por tienda — barras horizontales apiladas con etiquetas.
  - Valor promedio de envío por Tienda ("Valor promedio de envió por Tienda") — barras con valores.

Instrucciones para ejecutar el notebook
1. Requisitos
   - Python 3.10+ (recomendado)
   - Instalar dependencias:
     ```
     pip install pandas matplotlib numpy jupyterlab
     ```
2. Abrir el proyecto
   - Desde la raíz del proyecto abrir JupyterLab/Notebook:
   - O abrir el notebook directamente en VS Code.
3. Ejecutar
   - Abrir StoresAlura.ipynb.
   - Ejecutar las celdas en orden (Importación → Cálculos → Gráficas).
4. Notas
   - El notebook lee CSVs desde URLs públicas; se requiere acceso a internet.
   - Para reproducir gráficos interactivamente usar JupyterLab o VS Code con extensión de notebooks.


- El notebook contiene comentarios y celdas organizadas por secciones para facilitar su lectura y modificación. Revisa las variables listadas arriba para acceder directamente a los resultados calculados.