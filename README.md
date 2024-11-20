# Net Interactions
1. El Net Interaction o Modelo de Interacción en Redes es una forma gráfica y conceptual de representar la computación como un 
conjunto de interacciones locales entre elementos básicos llamados agentes. Este modelo es una extensión natural de las 
estructuras gráficas utilizadas en lógica lineal y programación funcional, y puede implementarse para representar algoritmos, realizar operaciones aritméticas y manejar estructuras de datos. En este informe, exploraremos los fundamentos del 
modelo, explicaremos los conceptos asociados y analizaremos cómo se relacionan con otros temas computacionales.

El Net Interaction es una representación computacional basada en grafos. En este modelo:

Agentes: Representan operaciones o elementos computacionales (como sumar, duplicar, borrar, etc.). Cada agente tiene:

Un puerto principal (entrada o salida principal).
Puertos auxiliares, cuyo número depende de la operación que realice (su aridad).
Red (Net): Es un conjunto de agentes conectados mediante cables, formando una estructura que puede transformarse dinámicamente.

## Reglas de Interacción: <br> 
Definen cómo los agentes conectados en sus puertos principales interactúan para transformarse en otros agentes o estructuras. Por ejemplo, una regla es:

Agente A⋆Agente B→Nuevo Net

donde ⋆ indica que los puertos principales están conectados.
2. Estructura y Reglas en Nets
Un Net tiene la siguiente estructura:

Nodos: Representan agentes con un comportamiento definido (por ejemplo, sumar, borrar, duplicar).
Cables: Conectan los puertos de los nodos.
Puertos:
Principal: Es el punto principal de interacción.
Auxiliares: Son las entradas/salidas adicionales.
Ejemplo visual:

Un agente α con aridad 2 tiene un puerto principal y dos auxiliares:
