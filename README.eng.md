# Damped Oscillatory System of a Vehicle

* [Full Report](https://github.com/maxogod/Modelacion-Numerica-TP/blob/main/informe.pdf)
* [Analysis and Solution Notebook](https://github.com/maxogod/Modelacion-Numerica-TP/blob/main/resolucion.ipynb)

**Different numerical methods are used and compared** to analyze the dynamic behavior of a vehicle's suspension system using a mathematical model representing a damped oscillator under different excitation conditions. The primary purpose of the suspension system is to ensure passenger comfort by reducing vertical accelerations caused by terrain irregularities and to maintain proper contact between the tires and the ground, increasing driving safety.

The mathematical model used is the following differential equation, derived from Newton's law *(∑F = m × a)*:

- *y'' = (k / m) * (c - y) + (λ / m) * (c' - y')*

Where:

- *y: the position of the vehicle body*
- *y': the velocity*
- *y'': the acceleration*
- *c: the terrain elevation*
- *k: the spring constant*
- *λ: the damping constant*

The spring constant and damping constant are optimized according to the constraints. This can be observed in the following graph:

<img src="https://github.com/user-attachments/assets/53a888e4-c378-4762-8e0c-da91e15fa4a5" alt="final result" width="600"/>
