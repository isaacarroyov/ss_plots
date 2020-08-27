# Gráficas de los Boletines de Ecuaciones Diferenciales y Análisis Vectorial 

## Proyecto de Servicio Social (en resumen):
Durante el primer semestre del 2020, estuve realizando mi Servicio Social en la Facultad de Ingeniería de la UADY (FIUADY) en el proyecto "Programa de Ayudantías en Ciencias Básicas para el Reforzamiento del Desarrollo Académico" (PACB), sin embargo, para la comunidad estudiantil de la FIUADY es mayormente conocido como "Ayudantías.

Este proyecto tiene como objetivo (y como su nombre lo dice) ayudar a los estudiantes de la FIUADY con las asignaturas del bloque de Ciencias Básicas, tales como: Álgebra I, Álgebra II, Cálculo Diferencial e Integral I (univariable), Cálculo Diferencial e Integral II (multivariable), Análisis Vectorial (tambien conocido como Cálculo Vectorial) y Ecuaciones Diferenciales. El equipo de alumnos involucrados en este proyecto de Servicio Social se encargaba de dos asignautas cada quien, en mi caso, estuve a cargo de Ecuaciones Diferenciales y Análisis Vectorial. 

La principal ayuda o servicio que ofrece este programa es brindar a los estudiantes asesorías en los temas en los que ellos requieran ayuda, además de darles un seguimiento de su progreso durante el semestre, sin costo alguno.

## Mini-proyectos + distanciamiento social.
La principal tarea que teníamos era brindar asesorías, pero no era la única. Como tarea secundaria se nos pidió resolver y explicar a detalle un problema relacionado a un concepto de la asignatura en que eres responsable. Esta explicación debía ser lo más clara posible, mostrando de manera amable el concepto nuevo y con apoyo visual (imágenes, gráficas o fotografías).

Debido al nuevo coronavirus SARS-Cov-2 que causa la pandemia de la enfermedad COVID19 se dejé de brindar las asesorías de manera presencial pero continué realizando los boletines. Los conocimientos de Python que adquirí durante las asignaturas optativas de **Introducción a la Ciencia de Datos** y **Ciencia de Datos** son las bases que me ayudaron a poder realizar este tipo de gráficas.

## Objetivo del repositorio
El principal objetivo de este repositorio es mostrar lo que se puede hacer con librerías del lenguaje de programación de **Python**, esto como una alternativa al uso de otros softwares de paga como por ejmplo: _Wolfram Mathematica_ y _MATLAB_. ¿Por qué? Python es un lenguaje de código abierto (tambien llamado _open source_, o como me gusta decir **es gratis**) con una ampia gama de librerías que facilitan las tareas que queramos realizar. Python es muy conocido debido a su popular uso en el área de **Ciencia de Datos** pero en este repositorio mostraré el uso en la visualización de gráficas en el área de las matemáticas básicas (el área de Ciencia de Datos se dejará para otra ocasión).

## Requisitos
Las versiones que uso y usé para la realización del repositorio se enlistan a continuación.
### Software
* **Python 3.8.1** o superior ( [_Página oficial de Python_](https://www.python.org/downloads/) )
* (No necesario pero recomendado) **Jupyter Notebook** ( [_Página oficial de Project Jupyter_](https://jupyter.org/) )

### Librerías
* **Numpy 1.19.0** ([_documentación de NumPy_](https://numpy.org/doc/))

`pip install numpy`
* **Matplotlib 3.1.3** ([_documentación de Matplotlib_](https://matplotlib.org/contents.html#))

`pip install matplotlib`
* **SciPy 1.4.1** ([_documentación de SciPy_](https://docs.scipy.org/doc/))

`pip install scipy`

### Extra: Anaconda Distribution
Existe la opción de descargar Anaconda, un software que ya te trae incluido Python junto con las librerías más populares en la Ciencia de Datos, como: NumPy, Pandas, Matplotlib, SciPy, etc.

[_Link de descarga de Anaconda_](https://www.anaconda.com/products/individual)


## Contenido del repositorio
* **Las gráficas** : Todas las gráficas se realizaron dentro en una libreta de _jupyter_ o _jupyter notebook_, sin embargo las celdas del código están hechas para que se pueda ejecutar en cualquier otro editor de código que se use.
* **El idioma** : Podrán ver que muchos de los comentarios en las celdas de código, el nombre de los archivos y secciones de las _notebooks_ están en inglés, esto lo pensé para los usuarios que llegasen a encontrar mi repositorio, cuya lengua materna no sea el español, puedan entender los comentarios y de lo que trata el archivo. Elegí el inglés a ser el _idioma del mundo_, ya que la mayor cantidad de contenido de algún tema, se encuentra en inglés.
* **Las ecuaciones** :  Las ecuaciones fueron escritas en celdas de Markdown, la manera de escribirlas es como escribir en un documento **.tex** (mejor conocido como **LaTeX**), para saber lo básico de su escritura recomiendo entrar al siguiente [_link_](https://es.overleaf.com/learn)

## Advertencia extra:
De no tener instalado **LaTeX** eliminar o comentar la siguiente línea de código:
```Python
#To recognize LaTeX commands
plt.rc('text', usetex=True)
```
***

# Differential Equation and Vector Analysis Newsletters Plots

## Social Service Project (summary):

During the first semester of 2020, I was doing my Social Service at the Faculty of Engineering of UADY (FIUADY) in the project "Programa de Ayudantías en Ciencias Básicas para el Reforzamiento del Desarrollo Académico" (PACB), however, for the student community of FIUADY it is mostly known as "Ayudantías"

This project aims (and as its name says) to help FIUADY students with the subjects of Basic Sciences, such as: Algebra I, Algebra II, Differential and Integral Calculus I (univariate), Differential and Integral Calculus II (multivariate), Vector Analysis (also known as Vector Calculus) and Differential Equations. The team of students involved in this Social Service project was in charge of two assignments each. In my case, I was in charge of Differential Equations and Vector Analysis.

The main help or service offered by this program is to provide students with advice on the topics in which they require assistance, in addition to monitoring their progress during the semester, at no cost.

## Mini-projects + social distance.
The main task we had was to provide mathematical consultancy, but it was not the only one. As a secondary task we were asked to solve and explain in detail a problem related to a concept of the subject in which you are responsible. This explanation had to be as clear as possible, showing in a friendly way the new concept and with visual support (images, graphics or photographs)

Due to the new SARS-Cov-2 coronavirus causing the COVID19 pandemic, face-to-face counseling was discontinued, but I continued to do the newsletters. The knowledge of Python that I acquired during the elective courses of Introduction to Data Science and Data Science are the bases that helped me to be able to make this type of plots.

## Purpose of the repository
The main objective of this repository is to show what can be done with libraries of the programming language of **Python**, this as an alternative to the use of other paid software as for example: _Wolfram Mathematica_ and _MATLAB_. Why? Python is an open source language (which means that it is **free**) with a wide range of libraries that facilitate the tasks we want to perform. Python is well known due to its popular use in the area of **Data Science** but in this repository I will show the use in the visualization of graphs in the area of basic mathematics (the area of Data Science will be left for another time).

## Requirements
The versions I use (and used) for the realization of the repository are listed below.
### Software
* **Python 3.8.1** or higher ([_Official Python_ page](https://www.python.org/downloads/) )
* (Not necessary but recommended) **Jupyter Notebook** ( [_Project Jupyter's official website](https://jupyter.org/) )

### Libraries
* **Numpy 1.19.0** ([_documentation of NumPy_](https://numpy.org/doc/))

``pip install numpy``
* **Matplotlib 3.1.3** ([_Matplotlib_ documentation](https://matplotlib.org/contents.html#))

``pip install matplotlib``
* **SciPy 1.4.1** ([_SciPy_ documentation](https://docs.scipy.org/doc/))

``pip install scipy``


### Extra: Anaconda Distribution
There is the option to download Anaconda, a software that already brings you included Python along with the most popular libraries in Data Science, such as: NumPy, Pandas, Matplotlib, SciPy, etc.

[_Download Anaconda_](https://www.anaconda.com/products/individual)

## Repository Content
* **The plots** : All the plots were made in a _jupyter notebook_, however the code cells are made to run in any other code editor used.
* **The equations** : The equations were written in Markdown cells, the way to write them is like writing in a **.tex** document (better known as **LaTeX**), to know the basics of its writing I recommend to enter the following [_link_](https://es.overleaf.com/learn)

## Warning:
In case you don't have LaTeX installed , please, erase or comment the following line code:
```Python
#To recognize LaTeX commands
plt.rc('text', usetex=True)
```

