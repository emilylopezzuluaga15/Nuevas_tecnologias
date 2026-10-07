# Análisis de pingüinos


## Configurar el entorno

Abran la terminal dentro de la carpeta `analisis_pinguinos` y sigan estos pasos.

**1. Crear el entorno virtual**

    python -m venv .venv

**2. Activarlo**

En Windows:

    .venv\Scripts\activate

En Mac o Linux:

    source .venv/bin/activate

Si quedó activo, aparece `(.venv)` al comienzo de la línea de la terminal.

**3. Instalar las librerías**

    pip install -r requirements.txt

Esto instala pandas, matplotlib y seaborn, con las versiones que están en `requirements.txt`.

## Trabajar en el proyecto

Siempre activen el entorno antes de correr algo. El código del análisis va en `analisis.py` y se ejecuta con:

    python analisis.py

Cuando terminen, pueden cerrar el entorno con:

    deactivate

## Notas para el equipo

- No suban la carpeta `.venv` a GitHub (ya está en el `.gitignore`). Cada persona crea la suya.
- Si alguien instala una librería nueva, debe actualizar la lista antes de subir los cambios:

      pip freeze > requirements.txt

- Si algo falla al instalar, revisen que el entorno esté activado y que la versión de Python sea parecida en todo el equipo.
