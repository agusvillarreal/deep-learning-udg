# Multilayer Perceptron
Es un tipo de ANN donde las neuronas están conectadas entre sí (fully connected) en múltiples capas y flujo de la información es unidireccional (feedforward)

No tratan valores discretos, sino, valores REALES -> neuronas sigmoides
Dependiendo el flujo de información, la salidaes distinta

_El MLP tiene tres tipos de capas: input, hidden y output_

|input|$$x_n^{(0)}$$|
|-----|--------|
|1st hidden|$$a_n^{(1)}$$|
|2nd hidden|$$a_n^{(2)}$$|
|output| $$y^{(3)}$$|

numero de capa -> super indice

Parametros -> w, b
Hiperparametros -> numero de neuronas que tengo en capa capa

Percibir distintas caracteristicas -> composición de cada clase
Profundida

### Calcular el numero de parametros del bias
Bias -> 1 bias = numero de nuerona

# Forward propagation

# Backpropagation
Algoritmo que ajusta los parametros utilizando gradient descendt hasta alcanzar el valor mínimo global de la función de costo
## Función de costo
Medida del error para encontrar la diferencia entre la predicción y el resultado esperado

El objetivo es encontrar el valor mínimo
### $$C = w^2$$

# Que es el _gradient descent?_
Algoritmo de optimización donde el gradiente se calcula de manera iteratia

# Autoencoder
Reducir la dimensión de nuestra entrada buscando las caracteristicas principales emergentes, encontrar la minima expresión de la entrada (abstracción)




