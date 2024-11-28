# Sistema Oscilatorio Amortiguado de un vehiculo

[English version](https://github.com/maxogod/Numerical-Modeling/blob/main/README.eng.md)

* [Informe completo](https://github.com/maxogod/Numerical-Modeling/blob/main/informe.pdf)
* [Notebook de analisis y resolucion](https://github.com/maxogod/Numerical-Modeling/blob/main/resolucion.ipynb)

**Se utilizan y se comparan diferentes metodos numericos** para efectuar un análisis del comportamiento dinámico del sistema de suspensión de un vehículo mediante un modelo matemático que representa un oscilador amortiguado bajo diferentes condiciones de excitación. El sistema de suspensión tiene como objetivo principal garantizar el confort de los pasajeros al reducir las aceleraciones verticales generadas por irregularidades en el terreno y mantener el contacto adecuado entre los neumáticos y el suelo, incrementando la seguridad en la conducción.

El modelo matemático utilizado es la siguiente ecuación diferencial a la cual se llega mediante la aplicación de la ley de Newton *(∑F = m × a)*:

- *y'' = (k / m) * (c - y) + (λ / m) * (c' - y')*

Siendo:

- *y: la posición de la carrocería*
- *y': la velocidad*
- *y'': la aceleración*
- *c: la cota o elevación del terreno*
- *k: la constante elástica del muelle*
- *λ: la constante de amortiguación*

Se logra optimizar constante elastica y constante de amortiguacion respecto a las restricciones, esto se puede observar en el siguiente grafico:

<img src="https://github.com/user-attachments/assets/53a888e4-c378-4762-8e0c-da91e15fa4a5" alt="final result" width="600"/>
