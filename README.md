# Análisis de Eficiencia: Alura Store.

Este proyecto tiene como objetivo asesorar al Sr. Juan en la toma de decisiones estratégicas para su cadena de tiendas.
A través del análisis de datos con Python, identificamos cuál de las tiendas presenta el menor rendimiento para 
ser vendida y así financiar un nuevo emprendimiento.

## Contexto del Desafío
Evaluar el desempeño de 4 tiendas basándose en datos reales de ventas, satisfacción del cliente y logística para recomendar la venta de la unidad menos eficiente.

## Herramientas Utilizadas.

* **Google Colab**: Como entorno de desarrollo basado en la nube.
* **Python**: Lenguaje de programación para la lógica del análisis.
* **Pandas**: Biblioteca principal para la manipulación y limpieza de los datos CSV.
* **Matplotlib**: Para la generación de visualizaciones gráficas.

## Pasos Realizados.

1.  **Carga de Datos**: Importación de archivos CSV mediante Pandas.

   #### Metodología de Análisis de Datos

   Para garantizar la fiabilidad de los resultados, se ejecutó un proceso de validación y limpieza en cuatro etapas:

   ### i). Auditoría de Estructura
   * **Validación de dimensiones:** Se confirmaron las dimensiones de cada base (Tiendas 1, 2 y 3 con 2,360 registros; Tienda 4 con 2,359).
   * **Consistencia de columnas:** Se verificó que las 4 fuentes compartieran exactamente el mismo esquema de datos para permitir la integración.

   ### ii). Diagnóstico de Salud (Data Quality)
   Se implementó un script de auditoría que confirmó:
   * **Integridad:** 0% de valores nulos en todas las columnas críticas.
   * **Unicidad:** Ausencia total de registros duplicados en los conjuntos de datos.
   * **Lógica de Negocio:** Validación de la columna `Precio` (100% de valores positivos) y consistencia en el catálogo de ciudades.

   ### iii). Procesamiento y Limpieza
   * **Normalización de Fechas:** Conversión de formatos temporales para asegurar un rango consistente entre el **01/01/2020** y el **31/03/2023**.
   * **Estandarización:** Ajuste de nombres y nomenclaturas para la consolidación final.

2.  **Análisis de Métricas**: 
    * Cálculo de ingresos totales por tienda.
    * Identificación de categorías y productos más vendidos.
    * Evaluación de la satisfacción del cliente.
    * Análisis del costo de envío promedio.
3.  **Visualización**: Creación de al menos 3 gráficos para sustentar la decisión.
