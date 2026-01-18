# Aplicación Web de Análisis de Vehículos con Streamlit

## Descripción
Este proyecto consiste en una aplicación web interactiva desarrollada con
Streamlit para realizar un análisis exploratorio de datos de anuncios de
venta de vehículos en Estados Unidos.

La aplicación permite al usuario visualizar de forma dinámica la
distribución del kilometraje y la relación entre el odómetro y el precio
de los vehículos.

## Funcionalidades
- Visualización interactiva de un histograma del odómetro.
- Gráfico de dispersión para analizar la relación entre kilometraje y precio.
- Interfaz sencilla mediante botones y checkboxes.
- Gráficos interactivos generados con Plotly.

## Dataset
- Archivo: `vehicles_us.csv`
- Contiene información sobre anuncios de venta de vehículos, incluyendo:
  - Precio
  - Kilometraje (odometer)
  - Otras características del vehículo

## Tecnologías utilizadas
- Python
- Pandas
- Streamlit
- Plotly

## Cómo ejecutar la aplicación
1. Clonar este repositorio.
2. Instalar las dependencias necesarias:
   ```bash
   pip install pandas streamlit plotly