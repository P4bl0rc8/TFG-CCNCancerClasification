# CNN Para Clasificación de imágenes histopatológicas (Colon y Pulmón)


Este proyecto contiene el código realizado para mi TFG. En este proyecto se construyen dos modelos de clasificación de imágenes histopatológicas, y posteriormente se emplean ataques de enveneamiento contra dichos modelos para evaluar su robustez.

---

## Tabla de Contenidos
1. [Descripción](#descripción)
2. [Características](#características)
3. [Instalación](#instalación)
4. [Uso](#uso)

---

## Descripción
Este proyecto busca explorar el campo de las CNN en la clasificación de imágenes tumorales, para ello se trabaja sobre un Dataset de 25000 imágenes. Para este proyecto se ha buscado crear 2 modelos, uno basado en Transfer Learning y otro creado desde cero, durante la ejecución del proyecto se planteó el uso de distintos ataques para evaluar la robustez de los modelos. Para generar dichos ataques se ha usado Foolbox, los modelos se han evaluado contra ataque FGSM y Gaussian Blur. Posteriormente se optó por intentar mejorar la robustez de los modelos usando Free Adversarial Training.

---

## Advertencias
- Se recomienda el uso de al menos 16gb de RAM.
- El proyecto se ha ejecutado en un ordenador con 32gb de RAM, una RTX 2070 y un procesador Intel I7. Es posible observar un aumento drástico en los tiempos de entrenamiento de los modelos si se usa un ordenador con características inferiores.

---

## Instalación
Lo único necesario para la ejecución del proyecto son las siguientes dependencias:

```bash
# Únicamente es necesario instalar las dependencias correspondientes
pip install tensorflow
pip install foolbox
pip install pandas
pip install matplotlib
pip install numpy
pip install scikit-learn
pip install jupyter
```
Para mayor comodidad se recomienda ejecutarlo en VSCode

## Uso

Para visualizar la ejecución del proyecto es recomendable ir ejecutando las celdas 1 a 1, por motivos de tamaño el modelo con transfer learning no ha podido ser subido al repositorio, los modelos se generarán en caso de que el proyecto se ejecute en orden.


