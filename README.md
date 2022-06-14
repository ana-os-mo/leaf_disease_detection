1. Clone el repositorio del proyecto
2. Instale la distribución Anaconda de Python si no la tiene
3. Vaya a la raíz del proyecto desde la línea de comando y ejecute `conda env create -f environment.yml` para crear el entorno de trabajo. Activarlo y asignarlo al proyecto actual

Descargar los datos en formato .zip desde https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data usando la opción “Download All” que se encuentra en la parte inferior izquierda.

Luego actualice la ruta hacia el archivo .zip en el siguiente bloque de código del archivo leaf_disease_detection.ipynb:
`!unzip -qq "su/ruta/aqui/plant-pathology-2020-fgvc7.zip" -d dstdir`