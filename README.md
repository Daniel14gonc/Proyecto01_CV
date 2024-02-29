
# Proyecto 1: Imágenes de vasos sanguíneos

## Project description
El presente proyecto consisitió de dos fases. La primera fue la binarización de imágenes de vasos sanguíneos en escala de grises, por medio de métodos tradicionales de visión por computadora. La segunda parte consistió
en la generación de una estructura discretizada y simplificada en forma de grafo, de cada vaso sanguíneo en cada imagen.

## Organización de archivos

### Primera parte del proyecto
- [X] **canny_edge.ipynb**: Contiene el algoritmo para binarización de las imágenes haciendo uso de filtrado de Canny.
- [X] **Adaptive_thresholding.ipynb**: Contiene el algoritmo para binarización de las imágenes haciendo uso de una binarización adaptativa.
- [X] **binarization_LoC.ipynb**: Contiene el algoritmo para binarización que hace uso de Laplacian of Gaussians.
- [X] **loc_images**: Imágenes de los vasos binarizados por el algoritmo que hace uso de Laplacian of Gaussians.
- [X] **adaptative_res**: Carpeta que contiene las imágenes de la binarización de vasos sanguíneos usando adaptative thresholding.
- [X] **datasets_binarization**: Contiene los datasets de los resultados de las métricas obtenidos para cada algoritmo implementado. 

### Segunda parte del proyecto

- [X] **graph_creation.ipynb**: Contiene el algoritmo para discretización de la estructura del vaso sanguíneo.
- [X] **grafo_estructura**: Carpeta que contiene imágenes de los vasos sanguíneos, a partir de solamente los nodos y aristas generados.
- [X] **grafo_resultado**: Carpeta que contiene imágenes superponiendo los nodos encontrados con la imagen esqueletizada, comparada con Ground Truth.

