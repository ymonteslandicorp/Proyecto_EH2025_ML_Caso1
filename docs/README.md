# Deserción Escolar en Bolivia — EH 2025 (Caso 1)

## Objetivo
Identificar los factores sociodemográficos, económicos y geográficos que influyen
en la deserción escolar en Bolivia usando la Encuesta de Hogares 2025.

## Contenido
- `data/` — archivos fuente EH2025 (.sav/.dta) + dataset procesado
- `notebooks/EH2025_Analisis_ML.ipynb` — análisis completo en Colab/Jupyter
- `outputs/` — storytelling.pdf, predicciones.csv, imágenes
- `docs/` — documentación

## Cómo ejecutar
1. Abrir el notebook en Google Colab
2. Instalar dependencias: `pip install -r requirements.txt`
3. Subir `EH2025_Persona.sav` a `/content/` (o montar Drive)
4. Ejecutar todas las celdas en orden

## Resultados principales
- Tasa de deserción 6-18 años: X% (ver notebook)
- Departamentos más afectados: Santa Cruz, Pando, Beni...
- Variables más influyentes: edad, zona, sexo...