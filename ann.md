Que son las Artificial Neural Networks

Mecanismo biologico se simula en las redes neuronales artificiales, que contienen unidades de cálculo que se denominan neuronas:

Nueronas: unidades de calculo, procesar estimulo (entrada) obtener una salida, evaluar entradas, entra el umbral

`input -> unidad de cálculo -> ouput`

## Perceptrón
tipo de neurona artificial caracterizado por operar con valores enteros


### Weights
Cada variable de entrada está asociada con un _weight_

importancia asociada (_weights_) en los valores de entrada

parámetros -> valores que la red va a entrenar, encontrar con los valores optimos para que la regresión funcione

hiperparámetros -> valores modificados manualmente

## Neurona
Valor de entrada por el _weight_ asociado y nos da una sumatoria

$$\Sigma = x_1 \cdot w_1 + x_2 \cdot w_2 + x_3 \cdot w_3$$

## Función de activación
función signo -> evalua a 1 si la etrada es 0 o superior y -1 en caso contrario, escalonada
filtrar valores negativos y positivos, 0 y 1, si y no

## Evaluación
$$y = sign(x_1 \cdot w_1 + x_2 \cdot w_2 + x_3 \cdot w_3)$$

función de activación evalúa la sumatoria de productos para obtener un resultado binario

## Sesgo
problema -> distintos ajustes de la función de activación

# Neurona sigmoide
artificial que utiliza la función de activación sigmoide para operar con valores reales

$$\sigma = \frac{1}{(1 + e^{-\Sigma})}$$

utilizar distintas funciones de activación
diferentes opciones de funciones de activación para simular distintos tipos de mdoelos utilizados en el ML
