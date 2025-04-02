# Contenido de este repositorio

Este repo cuenta con tres proyectos que usarÃ¡s para tu curso de Git y Github.

Los proyectos son los siguientes:

## Plantilla web para presentaciÃ³n

Una muy colorida plantilla HTML bÃ¡sica para lograr una muy buena presentaciÃ³n y llevar a tu audiencia a todos tus canalaes sociales.

Puedes verla [aquÃ­](/miSitio/).

## API de Python bÃ¡sica

Una API bÃ¡sica con solo tres mÃ©todos de prueba. Â¡Lo que importa es aprender de Github ahora!

Si quieres probarla en modo local solo necesitas escribir los comandos:

```bash
pip install -r requirements.txt
```

Y luego podrÃ¡s ejecutar la aplicaciÃ³n usando [uvicorn](https://www.uvicorn.org/).

```bash
uvicorn app:app --reload
```

Puedes verla [aquÃ­](/API_Python/).

## Paquete de PIP

Un paquete muy simple de PIP que servirÃ¡ para crear un artefacto. Â¿Te imaginas publicando tu primer paquete PIP?

Todos los archivos preconstruidos estÃ¡n ya cargados en este repo, sin embargo los Ãºnicos dos que necesitas son **setup.py** y el contenido de la carpeta **mi_paquete**, todo lo demÃ¡s lo puedes borrar.

Modifica **setup.py** con tu propia informaciÃ³n.

```python
from setuptools import setup, find_packages

setup(
    name="paquetePlatzi",                           # Nombre del paquete
    version="0.1.0",                                # VersiÃ³n inicial
    packages=find_packages(),                       # Paquetes a incluir
    description="Un paquete pip simple de saludo",  # Breve descripciÃ³n
    author="Amin Espinoza",                         # Tu nombre
    author_email="amin@platzi.com",                 # Tu correo electrÃ³nico
    url="https://github.com/platzi/git-github",     # URL del proyecto
)
```

DespuÃ©s de eso si es necesario, instala las herramientas adecuadas para empaquetar el proyecto.

```bash
pip install setuptools wheel
```

Empaqueta tu proyecto.

```bash
python setup.py sdist bdist_wheel
```

AquÃ­ es donde están todos los archivos de esta carpeta y donde la clase comenzarÃ¡.

Puedes verla [aquÃ­](/Paquete/)

### Mi primera contribución

Mi contribución a este repo
.
