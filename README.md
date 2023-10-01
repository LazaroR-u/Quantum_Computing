# Quantum_Computing
En este repositorio se encuentran los principales trabajos que realizo en computación cuántica de manera independiente.

## Congreso Nacional de Física

En esta investigación, se aplicaron modelos de quantum machine learning utilizando la paquetería
Qiskit en Python para predecir la profundidad atmosférica del máximo desarrollo de lluvias de rayos
cósmicos, Xmax, a partir de una base de datos de lluvias de partículas obtenida mediante simulaciones
computacionales. Se consideraron núcleos de hierro y protones usando el software CONEX para
simular las lluvias atmosféricas de rayos cósmicos con la configuración del Observatorio Pierre Auger
y el poder de procesamiento del Laboratorio Nacional de Supercómputo del Sureste de México (LNS). 

Modelos utilizados
En esta investigación, se implementan dos modelos de regresión cuántica de Qiskit: el Neural Network
Regressor (NNR) y el Variational Quantum Regressor (VQR).

![image](https://github.com/LazaroR-u/Quantum_Computing/assets/80428982/1e53b351-f065-4913-9dac-69f6c894d3b2)



Para estos modelos, consideramos los circuitos cuánticos que se muestran en la figura 4. Cada qubit
está asociado con una característica de los datos. En los modelos de un qubit, consideramos el logaritmo
de la energía de la lluvia de partículas, lgE. Mientras que en los modelos de tres qubits se usaron
dos configuraciones; una donde se escogieron las tres variables con mayor correlación a la variable
objetivo y otra donde se realizó un análisis de componentes principales a tres dimensiones.


![image](https://github.com/LazaroR-u/Quantum_Computing/assets/80428982/044f088a-486a-4f8f-bd9b-a1d8c6b39b4a)

En el primer circuito cuántico de un qubit, se observa que su rendimiento, al aplicar el modelo de NNR,
se asemeja al de los modelos clásicos de regresión lineal. En contraste, el segundo modelo cuántico de
un qubit con NNR exhibe un rendimiento superior al incorporar efectos cuánticos de superposición y
tener más parámetros en el circuito variacional. Ambos usando el EstimatorQNN.

En relación a los modelos que involucran tres qubits, se han identificado desafíos en el proceso de entrenamiento,
los cuales están siendo objeto de estudio y desarrollo continuo con el objetivo de mejorar
los resultados obtenidos. Este aspecto representa una área de investigación activa y en evolución, en
la que se busca optimizar la eficiencia y efectividad de los modelos.


[1] Qiskit Machine Learning Development Team. Qiskit Machine Learning.

https://qiskit.org/ecosystem/machine-learning/index.html, 2023.

[2] Konrad Bernlöhr. Max Planck Institute. Cosmic ray air showers.

https://www.mpi-hd.mpg.de/hfm/CosmicRay/Showers.html
