# DeepDreams

Este proyecto explora la técnica de **DeepDream**, que utiliza redes neuronales convolucionales (CNN) para generar imágenes psicodélicas y surrealistas. La idea es visualizar las características aprendidas por una CNN maximizando la activación de ciertas neuronas en capas intermedias.

## ¿Qué es DeepDream?

DeepDream se basa en el gradiente ascendente: se ajusta iterativamente una imagen de entrada para maximizar la activación de una neurona específica de la red, generando patrones y formas visuales característicos.

## Contenido

- `DeepDreams.ipynb` — notebook con la implementación de la técnica.
- `stary_night.jpg`, `1339248.png` — imágenes de entrada utilizadas como base.
- `requirements.txt`, `Pipfile` — dependencias del proyecto.

## Cómo usar este repositorio

```bash
git clone https://github.com/HoracioLaphitz/DeepDreams.git
cd DeepDreams
pip install -r requirements.txt
jupyter notebook DeepDreams.ipynb
```

## Tecnologías

Python · TensorFlow · NumPy

## Autor

Horacio Laphitz — [GitHub](https://github.com/HoracioLaphitz) · [LinkedIn](https://www.linkedin.com/in/horacio-laphitz)
