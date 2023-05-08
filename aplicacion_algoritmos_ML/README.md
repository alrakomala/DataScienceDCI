# Aplicación de modelos de aprendizaje automatizado (Machine Learning, ML)

El aprendizaje automatizado es una rama de la inteligencia artificial que se enfoca en el diseño, desarrollo y aplicación de algoritmos y modelos que permiten a la computadora **aprender a partir de datos para generar predicciones** y tomar decisiones automatizadas.

### Algoritmos Supervisados

El modelo se entrena con datos previamente etiquetados. 

- Regresión lineal: se utiliza para predecir una variable continua a partir de una o varias variables independientes.

- Regresión logística: se utiliza para predecir una variable categórica binaria (por ejemplo, sí/no, verdadero/falso) a partir de una o varias variables independientes.

- Árboles de decisión: se utilizan para predecir una variable categórica a partir de una o varias variables independientes. 

- Support Vector Machine: se utilizan para clasificar datos en dos o más categorías a partir de una o varias variables independientes.

- Redes neuronales: se utilizan para predecir una variable continua o categórica a partir de una o varias variables independientes.

### Algoritmos No Supervisados

El modelo trabaja con datos no etiquetados para encontrar patrones y estructuras _ocultas_ en los datos. 

- K-means clustering: agrupa datos en k grupos basados en su similitud.

- Análisis de componentes principales (PCA): un algoritmo que encuentra las direcciones principales en los datos y reduce la dimensionalidad de los mismos al proyectarlos en un espacio de menor dimensión.

- Algoritmo de agrupamiento jerárquico: un algoritmo que agrupa datos de manera jerárquica basándose en su similitud.

- Algoritmo de detección de anomalías: un algoritmo que encuentra observaciones inusuales o anómalas en los datos.

- Mapas auto-organizados (SOM): un algoritmo que encuentra una representación de baja dimensionalidad de los datos, generalmente en forma de una cuadrícula de neuronas.

- Redes de Kohonen: una forma de SOM que utiliza una topología de red.

- Algoritmo de reducción de la dimensionalidad t-SNE: un algoritmo que encuentra una representación de baja dimensionalidad de los datos preservando las estructuras no lineales de los datos originales.

- Algoritmo de asociación de reglas: un algoritmo que encuentra patrones frecuentes en los datos y construye reglas de asociación para describir esos patrones.

### Algoritmos de Refuerzo

El algoritmo aprende a tomar decisiones en un entorno interactivo (con incertidumbre y sujeto a cambio) a través de prueba y error buscando acciones con las mayores recompensas (o minimizando el castigo). 
agente: la componente que toma las decisiones\
ambiente: todo con lo que el agente interactúa\
acciones: lo que el agente puede hacer

- Q-learning: el agente aprende a través de la exploración y la experiencia. Utiliza una tabla de valores Q (cada Q es la recompensa de una acción en un estado determinado). Después de cada acción, se recibe la recompensa y se actualiza el valor Q. 

- State-Action-Reward-State-Action (SARSA)

- Actor-Critic: aprender una política óptima para un agente interactuando con un entorno desconocido a través de ensayo y error.

- Deep Deterministic Policy Gradient (DDPG)

- Trust Region Policy Optimization (TRPO)

- Proximal Policy Optimization (PPO)

- Asynchronous Advantage Actor-Critic (A3C)

--- 
--- 

## Librería [scikit-learn](https://scikit-learn.org/stable/user_guide.html)

Librería mas usada para análisis de datos utilizando aprendizaje automatizado (variedad de erramientas y algoritmos). 

Pasos básicos:

- Elegir el método adecuado [ver](https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html). 

- Separación del dataset en entrenamiento y prueba: Antes de aplicar un método de análisis a nuestros datos (limpios) hay que separar el dataset en muestras para entrenamiento y prueba (y validación en caso que se requiera hacer pruebas intermedias).

- Ajuste del modelo con los datos de entrenamiento

- Predicción con los datos de prueba

- Evaluación del desempeño del modelo
    - Validación cruzada
    - Matriz de confusión
    - Curvas ROC
    - $r^2$, MSE


> X, y = ...   # definir variables
> X_train, X_test, y_train, y_test   # particionar datos
> model.fit(x_train,y_train)
> model.predict(y_train)
> evaluar
