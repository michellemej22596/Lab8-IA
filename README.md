# Laboratorio 8 - Inteligencia Artificial: Programación de Exámenes (CSP)
Michelle Mejía 22596 y  Silvia Illescas 22376

Este proyecto implementa tres algoritmos de satisfacción de restricciones (CSP) para resolver un problema de programación de exámenes para cuatro estudiantes que toman siete exámenes diferentes. El objetivo es asignar los exámenes a días específicos respetando diversas restricciones, utilizando los siguientes algoritmos:

- **Backtracking Search**
- **Beam Search**
- **Local Search**

## Descripción del Proyecto

Se nos asignó el desafío de programar los exámenes para cuatro estudiantes en tres días (lunes, martes, y miércoles) bajo las siguientes restricciones:
- Todos los exámenes deben realizarse en días diferentes (lunes, martes, miércoles).
- Ningún estudiante debe tener más de un examen en el mismo día.
- Los estudiantes que toman el mismo curso no pueden tener exámenes en el mismo día.

El proyecto resuelve este problema utilizando tres algoritmos de búsqueda, cada uno con características y enfoques diferentes.

### Algoritmos Implementados

1. **Backtracking Search**:
   - Realiza una búsqueda exhaustiva utilizando retroceso (backtracking) para asignar los días a los exámenes.
   - Verifica que las restricciones sean respetadas antes de avanzar en la búsqueda.
   - Si se encuentra una asignación inválida, retrocede y prueba una asignación diferente.

2. **Beam Search**:
   - Una variante de búsqueda en anchura donde se limitan los caminos a explorar, manteniendo solo los más prometedores.
   - Utiliza una heurística para decidir qué caminos explorar en cada paso.

3. **Local Search**:
   - Comienza con una solución inicial y mejora iterativamente explorando soluciones vecinas.
   - Utiliza una heurística para evaluar y seleccionar la mejor solución vecina en cada iteración.

### Cómo Ejecutar el Proyecto

1. **Instalar Dependencias**:
   Asegúrate de tener Python instalado en tu entorno. Si no lo tienes, puedes descargarlo desde [python.org](https://www.python.org/).

2. **Ejecutar el Notebook**:
   1. Clona este repositorio o descarga el archivo `task2.ipynb`.
   2. Abre el archivo `Laboratorio_8_CSP.ipynb` en tu Jupyter Notebook.
   3. Ejecuta cada celda en el orden en que aparece para obtener los resultados de los algoritmos.
   4. El código mide el tiempo de ejecución de cada algoritmo y presenta las soluciones obtenidas.

3. **Requisitos**:
   Este proyecto está diseñado para ejecutarse en un entorno de Jupyter Notebook. Si no tienes Jupyter instalado, puedes instalarlo utilizando el siguiente comando:

   - pip install notebook
