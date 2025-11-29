Graficadora de Tiro Parabólico
===============================

Simula y grafica la trayectoria de un tiro parabólico a partir de parámetros iniciales ingresados por el usuario. 
Se puede usar mediante un ejecutable o ejecutando los archivos fuente en Python.

------------------------------------------------------------
Archivos Principales
------------------------------------------------------------

- calculo.py   : Calcula la trayectoria y el punto final del tiro.
- graficar.py  : Genera el gráfico a partir de los cálculos.
- GUI.py       : Interfaz gráfica para ingresar parámetros y mostrar el gráfico en el navegador.

------------------------------------------------------------
Uso Rápido
------------------------------------------------------------

Ejecutable
----------

El archivo se llama:

    Graficadora tiro parabolico.exe

Nota: Windows puede mostrar una advertencia de seguridad. 
Es seguro hacer clic en "Mas informacion" y "Ejecutar de todos modos".

Archivos Fuente
---------------

Requisitos:

- Python 3
- Bibliotecas: numpy, tkinter, plotly

Windows
-------

1. Abrir terminal en el directorio del proyecto.
2. Instalar Python si no está disponible: https://www.python.org/downloads/
3. Instalar dependencias:

    pip install numpy plotly tk

4. Ejecutar la interfaz:

    python GUI.py

Linux
-----

1. Abrir terminal en el directorio del proyecto.
2. Instalar Python y make:

    sudo apt install python3 make

3. Crear y activar un entorno virtual:

    python3 -m venv venv
    source venv/bin/activate

4. Instalar dependencias y ejecutar:

    make install   # Solo la primera vez
   
    make run

Nota: Si el gráfico no se abre automáticamente, copiar el link mostrado en la terminal en el navegador.

------------------------------------------------------------
Funcionalidades
------------------------------------------------------------

- Cambiar parámetros iniciales y volver a graficar sin cerrar la interfaz.
- Gráficos interactivos en el navegador con Plotly.
- Fácil de ejecutar tanto en Windows como en Linux.

