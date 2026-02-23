<!-- Encabezado -->
[![Colaboradores][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Estrellas][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- Título -->
<br />
<div align="center">

<h1 align="center">Fundamentos del Machine Learning</h1>
  <p align="center">
    Material del curso de Fundamentos del Machine Learning.
    <br />
    <a href="https://github.com/andres-merino/Curso-FundMachineLearning/issues">Reportar un Problema</a>
    ·
    <a href="https://github.com/andres-merino/Curso-FundMachineLearning/issues">Solicitar cambio</a>
    </a>
  </p>
</div>

<!-- Cuerpo -->
## Sobre el Proyecto

Este repositorio contiene el material del curso **Fundamentos del Machine Learning**, diseñado para la Sociedad Ecuatoriana de Estadística (SEE), con aval de la Pontificia Universidad Católica del Ecuador (PUCE).

El contenido está organizado para avanzar desde los conceptos introductorios hasta el entrenamiento, evaluación y optimización de modelos supervisados y no supervisados.


### Construido con

[![LaTeX][LaTeX]][LaTeX-url]
![Jupyter Badge](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=fff&style=for-the-badge)


## Resultados de Aprendizaje

- Plantear los conceptos fundamentales del aprendizaje automático.
- Aplicar modelos de aprendizaje automático supervisado y no supervisado.
- Resolver problemas prácticos mediante el uso de modelos de aprendizaje automático.


## Descripción

El curso cubre:

- Introducción al Aprendizaje Automático: conceptos básicos, flujo de trabajo, tipos de aprendizaje y métricas de distancia.
- Preprocesamiento de Datos: transformación y reducción de dimensionalidad (PCA).
- Métodos de Evaluación y Validación de Modelos: partición entrenamiento–prueba, validación cruzada y sobreajuste.
- Aprendizaje No Supervisado: fundamentos, métricas de similitud, clustering jerárquico y k-means.
- Aprendizaje Supervisado: métricas, k-NN, SVM, redes neuronales, árboles de decisión y métodos de ensamble.
- Ajuste y Optimización de Modelos: búsqueda de hiperparámetros, guardado y carga de modelos.

### Estructura y Contenido

```text
0-Cronograma/   -> Planificación académica del curso
1-Webinar/      -> Material de webinar
2-Resumenes/    -> Resúmenes por clase
3-Notebooks/    -> Notebooks del curso
4-Ejercicios/   -> Notebooks de práctica para estudiantes
Fondo/, Logos/  -> Recursos gráficos
```

### Ruta sugerida de estudio

1. Revisar `0-Cronograma/Cronograma.tex`.
2. Leer los resúmenes en `2-Resumenes/`.
3. Desarrollar los notebooks en `3-Notebooks/` en orden numérico.
4. Resolver los ejercicios de `4-Ejercicios/`.


## Requisitos

- Python 3.10 o superior.
- Jupyter Notebook o JupyterLab.

Bibliotecas de Python usadas en el material:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`
- `scikit-learn`
- `plotly`
- `tensorflow`
- `joblib`


## Instalación rápida

1. Clonar el repositorio:

```bash
git clone https://github.com/andres-merino/Curso-FundMachineLearning.git
cd Curso-FundMachineLearning
```

2. Crear y activar entorno virtual:

```bash
python -m venv .venv
```

En Windows (PowerShell):

```powershell
.venv\Scripts\Activate.ps1
```

En Linux/macOS:

```bash
source .venv/bin/activate
```

3. Instalar dependencias principales:

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn plotly tensorflow joblib jupyter
```


## Últimos cambios

```
- 2026-02: Se completa y organiza la estructura del repositorio del curso.
- 2026-02: Se incluyen notebooks de modelado supervisado, no supervisado y redes neuronales.
```

## Tareas pendientes

- [ ] Incorporar un archivo `requirements.txt` con versiones fijas.

## Créditos

**Andrés Merino** (aemerinot@gmail.com, aemerinot@puce.edu.ec) 

- Docente-Investigador en Pontificia Universidad Católica del Ecuador
  
  [![LinkedIn][linkedin-shield]][linkedin-url-aemt]


## Licencia

Distribuido bajo la licencia MIT. 

[![MIT License][license-shield]][license-url]




<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/andres-merino/Curso-FundMachineLearning.svg?style=for-the-badge
[contributors-url]: https://github.com/andres-merino/Curso-FundMachineLearning/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/andres-merino/Curso-FundMachineLearning.svg?style=for-the-badge
[forks-url]: https://github.com/andres-merino/Curso-FundMachineLearning/forks
[stars-shield]: https://img.shields.io/github/stars/andres-merino/Curso-FundMachineLearning?style=for-the-badge
[stars-url]: https://github.com/andres-merino/Curso-FundMachineLearning/stargazers
[issues-shield]: https://img.shields.io/github/issues/andres-merino/Curso-FundMachineLearning.svg?style=for-the-badge
[issues-url]: https://github.com/andres-merino/Curso-FundMachineLearning/issues
[license-shield]: https://img.shields.io/github/license/andres-merino/Curso-FundMachineLearning.svg?style=for-the-badge
[license-url]: https://es.wikipedia.org/wiki/Licencia_MIT
[linkedin-shield]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url-aemt]: https://www.linkedin.com/in/andrés-merino-010a9b12b/
[LaTeX]: https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=fff&style=for-the-badge
[LaTeX-url]: https://www.latex-project.org/