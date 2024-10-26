# CEIA Vision Transformers - Trabajos Prácticos

Este repositorio contiene los trabajos prácticos de la materia **Vision Transformers** del posgrado de la CEIA. La estructura de carpetas sigue la organización de cada trabajo práctico (TP), incluyendo los enunciados, los notebooks de resolución, y los archivos de soporte.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:

```
CEIA_VIT/ 
├─ Images/ 
│   ├─ raccoon.jpg 
│   ├─ vit.gif 
│   └─ vit_gif.gif
├─ TP1/ 
│   ├─ Enunciado/ 
│   │   └─ TP1.ipynb 
│   └─ Resolucion/ 
├─ TP2/ 
|   ├─ Enunciado/ 
|   │   ├─ TP2.ipynb 
|   │   └─ trainer.py 
│   └─ Resolucion/ 
├─ TP3/ 
|   ├─ Enunciado/ 
|   │   └─ TP3.ipynb 
|   └─ Resolucion/ 
├─ .gitignore 
└─ README.md
```

### Descripción de Carpetas

- **TP1**, **TP2**, **TP3**: Cada carpeta corresponde a un trabajo práctico específico.
    - **Enunciado**: Contiene el enunciado y los archivos necesarios para realizar el TP.
    - **Resolucion**: Esta carpeta se utilizará para guardar las soluciones y experimentos realizados en cada TP.

## Levantar el Entorno en WSL con Poetry

Para trabajar en este proyecto, recomendamos usar **Poetry** para gestionar las dependencias del entorno de Python. A continuación se detallan los pasos para configurar el entorno en WSL (Ubuntu 22.04).

### 1. Instalar Poetry

Si no tienes Poetry instalado, puedes instalarlo ejecutando el siguiente comando:

```
curl -sSL https://install.python-poetry.org | python3 -
```

Asegúrate de que la ruta de Poetry esté en tu $PATH. Puedes verificar la instalación usando:
```
poetry --version
```

### 2. Crear el Entorno Virtual

Una vez clonado el repositorio, navega a la carpeta del proyecto y ejecuta el siguiente comando para crear el entorno virtual e instalar las dependencias:

```
poetry install
```

Esto instalará todas las dependencias especificadas en el archivo pyproject.toml.

### 3. Activar el Entorno Virtual

Para activar el entorno virtual de Poetry, usa:

```
poetry shell
```

Con esto, deberías estar listo para ejecutar los notebooks y scripts del repositorio.