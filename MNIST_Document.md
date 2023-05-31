# Proyecto: MNIST

Problema: Categorización de números (y letras) escritas a mano.

---
# Descripción del Dataset MNIST


---
# Historia del MNIST


---
# Redes Neuronales para solucionar el problema

## El "Problema" de las Redes Neuronales

A pesar de que las redes neuronales han ganado una enorme popularidad en los últimos 10 años (especialmente tras el uso de las GPUs y TPUs para el entrenamiento de datos), para la mayoria de 
científicos de datos y estadísticos la mayoría de las familias de modelos tienen el problema de que son **difíciles de interpretar**. Es por esto que muchas personas tratan a las redes neuronales y su estructura como si fuese una *caja negra* porque es dificil pensar en cómo se modela y transmite la información.

Frecuentemente, las redes neuronales tienen cientos de miles de parámetros, con millones de pesos que son individualmente tuneados durante el entrenamiento par minimizar el error que puede existir.

## Arquitectura de las Redes Neuronales

Con el MNIST se pueden aplicar varios diseños al ser un conjunto de datos relativamente sencillo de estudiar. Incluso se han desarrollo modelos que no necesariamente tienen que ver con el uso de redes neuronales. Sin embargo, podemos usar los siguientes modelos:

### Fully-Connected Neural Networks (FCN)
![FCN](./img/fcn.png)

### Convolutional Meural Networs (CNN)
![CNN](./img/cnn.png)