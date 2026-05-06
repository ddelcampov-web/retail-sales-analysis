# retail-sales-analysis
Análisis integral de un conjunto de datos de ventas de una tienda de retail. 
git clone https://github.com/ddelcampov-web/retail-sales-analysis.git
cd retail-sales-analysis
git checkout main
git checkout -b development
git add README.md
git commit -m "Add README1.md"
import numpy as np

$ git def cargar_datos(ruta_archivo):
    # Carga los datos del archivo CSV utilizando NumPy
$ git    datos = np.genfromtxt(ruta_archivo, delimiter=',', skip_header=1)
$ git    return datos

$ git if __name__ == "__main__":
$ git    ruta_archivo = '../data/retail_sales.csv'
$ git    datos = cargar_datos(ruta_archivo)
$ git    print(datos)

https://colab.research.google.com/drive/1WS8nus3F24T1WtZVrjYwtVOtpOmdE4-7?usp=sharing
