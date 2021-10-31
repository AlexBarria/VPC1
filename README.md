# VPC1

## **Carrera de especialización en Inteligencia Artificial (CEIA)**

## **Universidad de Buenos Aires (UBA)**

En este repositorio se encuentran los trabajos prácticos relacionados a la materia de visión por computadora I de la CEIA.

Temario de la asignatura:

> **Clase 1:** Introducción a imágenes y OpenCV.
> 
> **Clase 2:** Operadores de píxel, histogramas, binarización, White patch y coordenadas cromáticas.
> 
> **Clase 3:** Filtros: lineales, separables, padding, DoG, Fourier y bordes (Canny).
> 
> **Clase 4:** Bordes, Harris, transformada de Hough y pirámides.
> 
> **Clase 5:** Extracción de características, SIFT, SURF, ORB y FAST.
> 
> **Clase 6:** Segmentación: K-means, watersheed, mean-shift, texturas y graph-cut.
> 
> **Clase 7:** Introducción a clasificación y detección: PCA, SVMs y AdaBoost.
> 
> **Clase 8:** Tracking, Kalman y filtro de partículas.

## Trabajo práctico I: Coordenadas cromáticas y White Patch
- Implementar el algorítmo de pasaje a coordenas cromáticas para obtener un descriptor invariante a las variaciones de contraste.
<img src="https://github.com/AlexBarria/VPC1/blob/main/TP1/Images/original_coord_chrom.png" width="700" height="225">
<img src="https://github.com/AlexBarria/VPC1/blob/main/TP1/results/coord_chrom.png" width="700" height="225">

- Implementar el algorítmo White Patch para solucionar las variaciones de color de iluminación en cada escena.

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP1/results/wp_hands.png" width="700" height="225">

## Trabajo práctico II: Detección de bordes
Implementación de un algorítmo que realice lo siguiente:

- Calcule los gradientes en la imagen.
- Muestre imágenes de ángulo y módulo.
- Marque en color las direcciones de gradientes más altos.

Original:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP2/Images/metalgrid.jpg" width="350" height="175">

Detección de bordes:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP2/results/metal_grid_detection.png" width="700" height="225">

Original:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP2/Images/tela2.jpg" width="350" height="225">

Detección de bordes:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP2/results/spyder_detection.png" width="700" height="225">

## Trabajo práctico III: Transformada de Hough
Implementación de un algorítmo que realice lo siguiente:

- Encuentre la posición de los iris de cada par de ojos y mida su distancia en píxeles.
- Encuentre la posición de las pupilas de cada par de ojos y mida su distancia en píxeles.

Detección de iris:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP3/results/iris_detection.png" width="255" height="300">

Detección de pupilas:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP3/results/pupil_detection.png" width="255" height="300">


## Trabajo práctico IV: Local binary patterns (LBP)

Implementación del algorítmo LBP

Original:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP4/Images/original_LBP.png" width="700" height="300">

Aplicando LBP:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP4/results/using_LBP.png" width="700" height="300">


## Trabajo práctico V: Seguimiento utilizando camshift

Implementación de un algorítmo de seguimiento utilizando CamShift que permita:
- Elegir la ROI del objeto a seguir.
- Cambiar la escala de la ventana de seguimiento.

ROI:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP5/Images/ROI.PNG" width="100" height="150">


Seguimiento:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP5/results/ezgif.com-gif-maker%20(1).gif" width="250" height="250">


## Trabajo práctico VI: Filtros de Haar

Implementación de un algorítmo de detección de rostros utilizando filtros de Haar en cascada.

Detección:

<img src="https://github.com/AlexBarria/VPC1/blob/main/TP6/results/ezgif.com-gif-maker%20(2).gif" width="250" height="250">
