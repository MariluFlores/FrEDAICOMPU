# Syntetic Data Generation using open source sofwere

## Authors:
Luis Carlos Ramos Zazueta

Marilu Flores Turon Ramirez

Ricardo Ruiz Almanza

Cuauhtemoc Maldonado

## Abstract
Para generar modelos de inteligencia artificial precisos se necesitan grandes cantidades de información, esta es procesada por el propio modelo para así dar una salida de información acertada al objetivo. Los modelos que detectan objetos de manera visual requieren de una gran cantidad de imágenes y clasificaciones. You Only Look Once, es un algoritmo de visión por computadora utilizado para la detección de objetos en tiempo real creando cuadros delimitadores. Uno de los mayores problemas en la generación de modelos para detección de objetos es la recopilación de datos ya sean imágenes o video. Esto debido a la cantidad de fotos, etiquetas y organización de las clasificaciones que los modelos necesitan para su continuo entrenamiento, haciendo más laboriosa la recopilación de información que el generar el modelo. Nuestro objetivo es generar un modelo eficiente de inteligencia artificial de clasificación utilizando modelos 3D renderizados para una recolección de datos rápida, esto aplicado al proyecto FrED Factory y los más de 100 componentes mecánicos utilizados durante la construcción de uno de los extrusores. Durante la investigación y trabajo de este proyecto utilizando Blender hemos desarrollado un código utilizando el API integrado del programa para poder automatizar el proceso de aleatoriedad de diferentes factores ambientales y de posición con el objetivo de mejorar la calidad y diversidad de los datos. Así mismo este automatiza el etiquetado de las imágenes al inferir las coordenadas de los polígonos dentro del render. Estos datos son transferidos a un código de python que utiliza el programa de You Only Look Once que procesa la imagen completa en tiempo real utilizando una webcam. Utilizando un raspberry pi 4 los datos de entrenamiento se procesan para que teniendo en mano uno de los componentes de FrED se identifique en tiempo real el nombre y número de la pieza con precisión.
