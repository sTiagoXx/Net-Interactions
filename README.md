# Net Interactions
## 1. El Net Interaction o Modelo de Interacción 
Es una forma gráfica y conceptual de representar la computación como un 
conjunto de interacciones locales entre elementos básicos llamados agentes. Este modelo es una extensión natural de las 
estructuras gráficas utilizadas en lógica lineal y programación funcional, y puede implementarse para representar algoritmos, realizar operaciones aritméticas y manejar estructuras de datos.

El Net Interaction es una representación computacional basada en grafos. En este modelo:

Agentes: Representan operaciones o elementos computacionales (como sumar, duplicar, borrar, etc.). Cada agente tiene:

a. Un puerto principal (entrada o salida principal). <br>
b. Puertos auxiliares, cuyo número depende de la operación que realice (su aridad). <br>
c. Red (Net): Es un conjunto de agentes conectados mediante cables, formando una estructura que puede transformarse dinámicamente. <br>

## Reglas de Interacción: <br> 
Las reglas de interacción en el modelo de Net Interaction definen cómo los nodos interactúan entre sí a través de las conexiones (aristas). Estas reglas son fundamentales para entender cómo un sistema evoluciona y cómo las interacciones locales pueden dar lugar a comportamientos globales complejos.
## 2. Estructura y Reglas en Nets
Un Net tiene la siguiente estructura:

Nodos: Representan agentes con un comportamiento definido (por ejemplo, sumar, borrar, duplicar).
Cables: Conectan los puertos de los nodos.
Puertos:
Principal: Es el punto principal de interacción.
Auxiliares: Son las entradas/salidas adicionales.
Ejemplo visual:

Un agente α con aridad 2 tiene un puerto principal y dos auxiliares:
