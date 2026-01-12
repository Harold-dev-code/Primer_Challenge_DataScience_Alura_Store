# Primer_Challenge_DataScience_Alura_Store
Durante este desafío, ayudaré al Sr. Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. Para ello, analizaré datos de ventas, rendimiento y reseñas de las 4 tiendas de Alura Store. El objetivo es identificar la tienda menos eficiente y presentar una recomendación final basada en los datos.
## 🚀 Descripción del Proyecto
En este repositorio se realiza un proceso completo de Ciencia de Datos, que incluye:
- **Exploración de Datos (EDA):** Análisis de estadísticas descriptivas y visualización de tendencias.
- **Limpieza de Datos:** Tratamiento de valores nulos, duplicados y normalización de columnas.
- **Análisis:** Este proyecto analiza el rendimiento financiero y operativo de cuatro tiendas comerciales (tienda1, tienda2, tienda3, tienda4).
- **Visualización:** Creación de gráficos interactivos
- **Interpretación y Storytelling:** Traducción de hallazgos técnicos en un lenguaje de negocio
## 🛠️ Tecnologías Utilizadas
- **Python 3.x**
- **Pandas:** Manipulación y limpieza de datos.
- **Numpy:** Operaciones matemáticas.
- **Matplotlib / Seaborn:** Visualización de datos estáticos.
- **Visualización Interactiva:** Folium (Mapas de calor)
- **Google Colab:** Entorno de desarrollo en la nube.
## ⚙️ Instalación y Uso
1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/Harold-dev-code/Primer_Challenge_DataScience_Alura_Store.git]
    cd [NOMBRE_DEL_REPOSITORIO]
    ```
2.  Abre el archivo Primer_Challenge_DataScience_AluraStore.ipynb en tu entorno Jupyter o súbelo a Google Colab.

3. Ejecuta todas las celdas en orden para replicar el análisis.

## Contenido del Notebook

El notebook está estructurado en las siguientes secciones:

### 1. Importación y Carga de Datos
*   Se importan las librerías necesarias (`pandas`).
*   Se cargan los datos de ventas de las cuatro tiendas desde URLs de GitHub.

### 2. Exploración Inicial de Datos
*   Visualización de las primeras filas de los DataFrames (`.head()`).
*   Revisión de la información general de los DataFrames (`.info()`).
*   Inspección de los tipos de datos (`.dtypes`).
*   Verificación de valores nulos (`.isnull().sum()`).

### 3. Organización de Datos
*   Verificación de la uniformidad de columnas entre los DataFrames.
*   Adición de una columna `Tienda` para identificar el origen de los datos.
*   Concatenación de todos los DataFrames en uno solo (`df_tiendas_completo`).
*   Comprobación de la correcta unión de los datos mediante `sample()` y `shape[0]`.

### 4. Limpieza de Datos
*   Reconfirmación de la ausencia de valores nulos y tipos de datos adecuados en el DataFrame unificado.

### 5. Análisis de Facturación
*   Cálculo del ingreso total por cada tienda.
*   Determinación de la facturación total consolidada.

### 6. Ventas por Categoría
*   Análisis del recaudo total por categoría de producto, tanto a nivel global como por tienda, identificando las categorías más y menos rentables.

### 7. Calificación Promedio de la Tienda
*   Cálculo de la calificación promedio de clientes para cada tienda, ofreciendo una visión de la satisfacción general.

### 8. Productos Más y Menos Vendidos
*   Identificación de los productos que generaron más y menos recaudo en general.
*   Análisis de los productos más y menos rentables por tienda.

### 9. Envío Promedio por Tienda
*   Cálculo del costo de envío promedio para cada tienda.

### 10. Generación de Gráficos
*   **Ventas Totales por Tienda:** Gráfico de barras que muestra el ingreso total de cada tienda, destacando la mejor y la peor.
*   **Evolución del Ranking de Ventas Anuales por Tienda:** Gráfico de líneas que ilustra la posición de cada tienda en el ranking de ventas a lo largo de los años.
*   **Comparación de Ventas Totales por Tienda (Último Año):** Gráfico de barras que compara el rendimiento de ventas de las tiendas en el período más reciente.
*   **Calificación Promedio General de Vendedores por Rango:** Gráfico de dispersión para evaluar la calidad del servicio de los vendedores.
*   **Distribución de Ventas por Ciudad:** Gráficos de torta para cada ciudad que muestran la participación de cada tienda en las ventas locales.
*   **Áreas Geográficas con Mayor Volumen de Ventas:** Mapa de calor interactivo (`folium`) para visualizar las zonas de alta concentración de ventas.

### 11. Recomendación Final
*   Basado en todos los análisis, se elabora un informe de desempeño detallado y una recomendación estratégica para el Sr. Juan sobre la posible venta de una tienda.
## 👤 Autor
Desarrollado por [Harold-dev-code](https://github.com/Harold-dev-code).
Dentro del programa de formación ONE - Oracle Next Education de Oracle y Alura Latam https://www.oracle.com/latam/education/oracle-next-education/
## ⚖️ Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE](LICENSE) para detalles.

     


