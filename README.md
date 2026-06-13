# TFE-Codigo-Retinopatia-IA
Este repositorio contiene el código fuente utilizado para el Trabajo Fin de Estudios (TFE) titulado: "Evaluación de modelos de Deep Learning (CNN, U-Net y Transformers) para la detección temprana de la enfermedad retiniana Retinopatía diabética".

# TFE: Evaluación de Modelos Deep Learning para Detección de Retinopatía Diabética

**Autor:** Donny Alexander Rodríguez Cáceres  
**Director:** Carlos Manuel Moreno Negrin  
**Universidad:** Internacional de La Rioja (UNIR)  
**Fecha:** 2026

## Descripción
Este repositorio contiene el código fuente del Trabajo de Fin de Máster que compara tres arquitecturas de deep learning (CNN ResNet18, U-Net y Vision Transformer) para el diagnóstico automático de retinopatía diabética a partir de imágenes de fondo de ojo. El estudio utiliza el conjunto de datos público **Messidor-2** y evalúa métricas como sensibilidad, especificidad, AUC-ROC y eficiencia computacional.

## Estructura del repositorio
- `notebooks/TFE_Codigo_DonnyRodriguez.ipynb`: Cuaderno principal con todo el flujo de trabajo.
- `requirements.txt`: Dependencias necesarias.
- `results/`: Carpeta donde se guardan las figuras y métricas generadas.
- `models/`: Almacena los mejores modelos entrenados (`.pth`).

## Requisitos de instalación
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/donny-rodriguez/TFE_DeepLearning_Retinopatia.git
   cd TFE_DeepLearning_Retinopatia
