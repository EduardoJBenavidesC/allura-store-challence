# Análisis de Eficiencia: Alura Store.

Este proyecto tiene como objetivo asesorar al Sr. Juan en la toma de decisiones estratégicas para su cadena de tiendas.
A través del análisis de datos con Python, identificamos cuál de las tiendas presenta el menor rendimiento para 
ser vendida y así financiar un nuevo emprendimiento.

## Contexto del Desafío
Evaluar el desempeño de 4 tiendas basándose en datos reales de ventas, satisfacción del cliente y logística para recomendar la venta de la unidad menos eficiente.


## Metodología de Análisis de Datos
Para garantizar la fiabilidad de los resultados, se ejecutó un proceso de validación y limpieza estructurado en las siguientes etapas:

### 1. Carga y Auditoría de Estructura
* **Carga de Datos:** Importación de archivos fuente mediante la librería Pandas.
* **Validación de Dimensiones:** Confirmación de registros por unidad de negocio:
  * Tiendas 1, 2 y 3: 2,360 registros.
  * Tienda 4: 2,359 registros.
* **Consistencia de Columnas:** Verificación de esquemas idénticos en las cuatro fuentes para permitir la integración técnica.

### 2. Diagnóstico de Salud (Data Quality)
Se implementó un script de auditoría que confirmó los siguientes indicadores:
* **Integridad:** 0% de valores nulos en columnas críticas.
* **Unicidad:** Ausencia total de registros duplicados en los conjuntos de datos.
* **Lógica de Negocio:** Validación de la columna Precio (100% de valores positivos) y consistencia en el catálogo de ciudades.

### 3. Procesamiento y Limpieza
* **Normalización de Fechas:** Conversión de formatos temporales para asegurar un rango consistente entre el 01/01/2020 y el 31/03/2023.
* **Estandarización:** Ajuste de nombres y nomenclaturas para la consolidación de la base de datos maestra.

### 4. Análisis de Métricas y Visualización
El análisis se centró en la evaluación de los siguientes pilares:
* **Ingresos:** Cálculo de ingresos totales por tienda.
* **Productos:** Identificación de categorías y artículos de mayor rotación.
* **Satisfacción:** Evaluación de indicadores de experiencia del cliente.
* **Logística:** Análisis del costo promedio de envío.
* **Sustentación:** Creación de representaciones gráficas para el apoyo en la toma de decisiones.
  

## Herramientas Utilizadas.

* **Google Colab**: Como entorno de desarrollo basado en la nube.
* **Python**: Lenguaje de programación para la lógica del análisis.
* **Pandas**: Biblioteca principal para la manipulación y limpieza de los datos CSV.
* **Matplotlib**: Para la generación de visualizaciones gráficas.

## Pasos Realizados.

