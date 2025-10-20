# Clasificación de Asteroides Potencialmente Peligrosos


Clasificación de Asteroides Potencialmente Peligrosos (PHA)

Proyecto de Aprendizaje Automático enfocado en el desarrollo y evaluación de un modelo de Clasificación Binaria para predecir si un asteroide debe ser catalogado como Potencialmente Peligroso (PHA). El modelo utiliza parámetros orbitales y físicos del Asteroid_Dataset.csv y está implementado en Python con la librería scikit-learn.

---
## Dataset
* Nombre del archivo: Asteroid_Dataset.csv.

* Instancias: Más de 100.000 registros (asteroides).

* **Características Clave (Columnas):**

H: Magnitud absoluta (relacionada con el tamaño)
diameter: Diámetro estimado en kilómetros.
e, a, i, om, w, ma: Parámetros orbitales fundamentales (excentricidad, semieje mayor, inclinación, etc.).
moid: Mínima Distancia de Intersección Orbital. Parámetro crucial para la peligrosidad.
pha: Variable Objetivo. Categórica binaria ('Y' / 'N').

**Tipos de datos:**

La mayoría son números flotantes (parámetros orbitales y físicos).
Categórico/Booleano para la clase objetivo (pha).
Categórico para la clase orbital (class).

---
## Origen del Dataset

* Fuente Principal: El dataset es de dominio público, obtenido inicialmente de la plataforma Kaggle.
* Fuente Primaria: Los datos originales provienen de bases de datos astronómicas oficiales como el JPL Small-Body Database de la NASA 
* Adquisición: Los datos fueron descargados en formato .csv.

Organización del proyecto
------------

    ├── LICENSE
    ├── README.md          <- Este readme.
    ├── artifacts          <- Repositorio de artefactos, como logs, transformadores, etc.
    ├── data
    │   ├── preprocessed   <- Data intermedia con algunas transformaciones.
    │   ├── stage          <- La data lista para ser utilizada en un modelo.
    │   └── raw            <- La data de origen, inmutable.
    │
    ├── docs               <- Proyecto default de Sphinx.
    │
    ├── models             <- Modelos listos.
    │
    ├── notebooks          <- Jupyter notebooks. Dejamos una convención sugerida:
    │                         iniciales-numero-descripcion corta. Ejemplo:
    │                         `he-1.0-eda-base-clientes`.
    │
    ├── references         <- Manuales de la data, documentación, todo lo relevante para trabajar.
    │
    ├── reports            <- Reportes en HTML, PDF, LaTeX, etc.
    │   └── figures        <- Carpeta para guardar imágenes de rápido acceso.
    │
    └── src                <- Código del proyecto.
    
    


