# Introducción

El proyecto tiene como propósito desarrollar un modelo predictivo que permita identificar a estudiantes en Bolivia con alto riesgo de abandonar sus estudios, utilizando técnicas de minería de datos y algoritmos de aprendizaje supervisado. La investigación emplea datos oficiales del Instituto Nacional de Estadística (INE) y busca aportar evidencia empírica y herramientas analíticas que contribuyan a enfrentar la problemática de la deserción escolar. Este fenómeno, al limitar la formación de capital humano y profundizar la pobreza y desigualdad, requiere respuestas estratégicas desde la política pública educativa, donde el uso de ciencia de datos se plantea como una innovación relevante.  

En cuanto a los antecedentes, se observa que en la región existen estudios que han aplicado modelos de machine learning (ML) para analizar las determinantes de la deserción escolar, destacando factores como pobreza, nivel educativo de los padres y calidad educativa. Sin embargo, en Bolivia la aplicación de metodologías predictivas es aún incipiente, predominando enfoques descriptivos y retrospectivos. Ante esta carencia, el proyecto propone un modelo de clasificación basado en variables sociodemográficas, con el fin de anticipar el riesgo de abandono escolar de manera individualizada y ofrecer una herramienta novedosa para la prevención en el sistema educativo nacional.  

# Requisitos del Sistema

Para garantizar la correcta ejecución del notebook, se deben cumplir los siguientes requisitos:
Versión de Python: Se requiere Python 3.10 o una versión superior. Puede verificar su versión ejecutando en su terminal:  
python --version

Conexión a Internet: Es imprescindible contar con acceso a Internet durante la ejecución, ya que el notebook gestiona automáticamente la descarga de librerías especializadas (como pandas, scikit-learn o plotly) y, en su caso, del dataset desde repositorios públicos.

# Entorno de Ejecución Recomendado

El código ha sido diseñado para ser ejecutado en los siguientes entornos, siendo Google Colab la opción recomendada para una puesta en marcha rápida y sin configuración adicional:
-	Google Colab (recomendado)
-	Jupyter Notebook (instalación local)
-	Visual Studio Code con la extensión de Jupyter

# Instalación de Dependencias

Si opta por una ejecución local (Jupyter o VS Code), asegúrese de tener instaladas las librerías necesarias mediante el siguiente comando:  
pip install -U numpy pandas scikit-learn matplotlib seaborn plotly nbformat

En Google Colab, el propio notebook incluye celdas que instalan las dependencias automáticamente.

# Ejecución del notebook

Abra el archivo Proyecto_abandono_escolar_Predict.ipynb en su entorno de preferencia (Google Colab, Jupyter, etc.).
Ejecute las celdas de código en orden secuencial, desde el inicio hasta el final del documento.
Durante la primera ejecución, es normal que la instalación de librerías requiera unos minutos. Le recomendamos aguardar a que este proceso finalice.
Una vez completado, podrá revisar los resultados, que incluyen gráficos, métricas de rendimiento y los coeficientes de los modelos.  

# Recursos

Este proyecto cuenta con los siguientes recursos:
- Base_abandono_escolar.xlsx --> es el dataset original, que contiene un conjunto de variables de la ENDSA 2023 que explican el abandono escolar, el target y más de 20 mil observaciones
- Proyecto final de módulo.pdf --> es el documento de proyecto, que contiene el marco referencial y marco práctico, así como conclusiones e insights
- Proyecto_abandono_escolar_Predict.ipynb --> es el notebook que contiene todo el código desarrollado, resultados, gráficos, métricas de rendimiento y los coeficientes de los modelos

# Enlace a video explicativo: 
https://drive.google.com/file/d/1vK2TvTW8Rb977vSw95N-EpmniGDODBPk/view?usp=sharing
