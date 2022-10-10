# TFG
Reconocimiento de vehículos y su movimiento mediante redes neuronales convolucionales en vídeos

Este trabajo tiene como finalidad desarrollar una aplicación, que utiliza técnicas de
Aprendizaje Profundo, o Deep Learning (DL), en Inteligencia Artificial para la
detección de movimiento de vehículos en secuencias de imágenes, con fines de su
identificación dentro del flujo de tráfico y como posible solución en las futuras
ciudades inteligentes.

El objetivo es proporcionar una solución conceptual para el control y seguimiento de
vehículos sobre la vía urbana. Dentro del AP se utilizan concretamente dos modelos
de Redes Neuronales Convolucionales (RNC), exactamente AlexNet y GoogleNet
para la identificación de los vehículos en movimiento, el cual se detecta mediante
técnicas basadas en flujo óptico como técnica propia de Visión por Computador.

Estos modelos requieren de un entrenamiento previo. Así se consigue extraer
rasgos característicos de los vehículos, a partir de una serie de imágenes
secuenciadas en vídeos, que pueden ser previamente seleccionados por el usuario.

La aplicación desarrollada en este proyecto permite al usuario modificar los
parámetros necesarios para el entrenamiento de las RNC, con la finalidad de poder
obtener un resultado más eficiente y óptimo. Tras realizar el entrenamiento, el
usuario también puede seleccionar previamente un video para generar la
clasificación de los vehículos e identificarlos dentro del tráfico de vehículos.

Complementariamente, los datos obtenidos tras la clasificación llevada a cabo se
subirán a la nube mediante el uso de la plataforma ThingSpeak, como servicio
proporcionado por Matlab dentro del paradigma de Internet de las Cosas (IoT,
Internet of Things) que permite el almacenamiento y análisis de distintas categorías
de datos. 

Esta plataforma permite mostrar los resultados y enviar mensajes a través
de la red social Twitter para su posterior valoración e interpretación.
