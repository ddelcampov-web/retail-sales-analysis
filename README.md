# retail-sales-analysis
Análisis integral de un conjunto de datos de ventas de una tienda de retail. 
git clone https://github.com/ddelcampov-web/retail-sales-analysis.git
cd retail-sales-analysis
git checkout main
git checkout -b development
git add README.md
git commit -m "Add README1.md"
import numpy as np

def cargar_datos(ruta_archivo):
    # Carga los datos del archivo CSV utilizando NumPy
    datos = np.genfromtxt(ruta_archivo, delimiter=',', skip_header=1)
    return datos

if __name__ == "__main__":
    ruta_archivo = '../data/retail_sales.csv'
    datos = cargar_datos(ruta_archivo)
    print(datos)
# 2.2. Primeras filas (vista rápida)
$ git df.head(10)
