# Modelo GI - Notebooks de Modelos Generativos

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Diffusion](https://img.shields.io/badge/Modelos-Difusión-green)
![HuggingFace](https://img.shields.io/badge/HuggingFace-OpenSource-orange)
![GPU](https://img.shields.io/badge/Modo-GPU%20%2F%20CPU-lightgrey)
![Entorno](https://img.shields.io/badge/Entorno-venv%20%7C%20Conda-yellow)
![Status](https://img.shields.io/badge/Estado-Activo-brightgreen)

<!-- Badges específicos de modelos y frameworks -->
![SDXL](https://img.shields.io/badge/Stable%20Diffusion-SDXL-blueviolet)
![SD3](https://img.shields.io/badge/Stable%20Diffusion-SD3-red)
![Flux](https://img.shields.io/badge/Flux-Model-orange)
![LoRA](https://img.shields.io/badge/LoRA-FineTuning-yellowgreen)
![CUDA](https://img.shields.io/badge/CUDA-Enabled-9cf)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red)

Este repositorio reúne notebooks y recursos para practicar generación de imágenes y video con modelos de difusión, además de ejemplos de fine-tuning.

## Modos de trabajo

Este material contempla dos modos de ejecución:

- **Modo CPU**
  Enfocado en pruebas funcionales, validación de prompts y ejecuciones en equipos sin GPU.

- **Modo GPU**
  Enfocado en generación más rápida y en tareas de entrenamiento/fine-tuning con mayor carga computacional.

## Opciones de entorno

También se documentan dos formas de preparar el entorno:

- **Entorno con venv**
  Flujo basado en entorno virtual de Python.

- **Entorno con Conda**
  Flujo basado en ambiente Conda para control de dependencias y compatibilidad de librerías.

## Notebooks

- **1.uso_modelos_opensource.ipynb**  
  Notebook principal para uso de modelos open source, orientado a generación base de contenido con prompts.

- **1.uso_modelos_opensource_bk.ipynb**  
  Versión de respaldo/alternativa del flujo de uso de modelos open source.

- **1.uso_modelos_opensource_video.ipynb**  
  Variante enfocada en generación o experimentación con video a partir de prompts/modelos generativos.

- **1-2.modelo_difusion_from_scratch.ipynb**  
  Ejercicio introductorio para entender y construir conceptos de un modelo de difusión desde cero.

- **1.finetuning_diffusion_model.ipynb**  
  Proceso de fine-tuning de un modelo de difusión, incluyendo preparación y ajuste del entrenamiento.

- **2.finetuning_stable_diffusion.ipynb**  
  Flujo de fine-tuning aplicado específicamente a Stable Diffusion (versión actual de trabajo).

- **2.finetuning_stable_diffusion_oldbook.ipynb**  
  Versión anterior del notebook de fine-tuning de Stable Diffusion (referencia histórica/comparativa).

## Ejecución recomendada

1. Elegir modo de cómputo: **CPU** o **GPU**.
2. Elegir tipo de entorno: **venv** o **Conda**.
3. Configurar el kernel según el tipo de trabajo (imagen/video) y el tipo de entorno.
4. Abrir el notebook correspondiente y ejecutar celdas en orden.

## Otros archivos relevantes

- **kernel_imagen.txt / kernel_imagen_conda.txt**  
  Guías de kernel para notebooks de imagen en modo venv y modo Conda.

- **kernel_video.txt / kernel_video_conda.txt**  
  Guías de kernel para notebooks de video en modo venv y modo Conda.

- **data/FashionMNIST/**  
  Datos de ejemplo para experimentos de entrenamiento/pruebas.

- **output*.png** y **video_estilo_prompt_cpu.mp4**  
  Resultados generados durante ejecuciones de los notebooks.

- **Archivos PDF**  
  Material de clase/apoyo teórico.

## Objetivo del repositorio

Contar con una base práctica para:

1. Probar generación de contenido con modelos open source.
2. Entender fundamentos de difusión.
3. Experimentar fine-tuning en modelos de imagen.
4. Trabajar de forma flexible en CPU o GPU.
5. Configurar el entorno tanto con venv como con Conda.
6. Documentar resultados y configuraciones de entorno.
