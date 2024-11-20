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
Las reglas de interacción en el modelo de Net Interaction definen cómo los nodos interactúan entre sí a través de las conexiones (aristas). Estas reglas son fundamentales para entender cómo un sistema evoluciona y cómo las interacciones locales pueden dar lugar a comportamientos globales complejos. <br>

### 1. Reglas de interacción entre nodos
Estas determinan cómo los nodos se relacionan entre sí.

- Regla de propagación: Un nodo transmite su estado o información a los nodos vecinos.
- Regla de acumulación: Un nodo actualiza su estado basado en las señales que recibe de otros nodos mediante una función de agregación.
- Regla de filtrado: Un nodo interactúa con otro solo si se cumplen ciertas condiciones específicas.
### 2. Reglas de flujo en las conexiones (aristas)
Estas especifican cómo los datos, recursos o señales fluyen por las conexiones.

- Capacidad: La cantidad máxima de recurso o dato que puede fluir por una conexión.
- Latencia: El tiempo que tarda en completarse una interacción a través de una conexión.
- Dirección: Indica si el flujo es unidireccional o bidireccional.
### 3. Reglas de estado de los nodos
Definen cómo cambia el estado de un nodo a lo largo del tiempo.

- Actualización en función del entorno: El estado de un nodo se modifica según las condiciones externas.
- Actualización basada en interacciones: El estado cambia dependiendo del flujo recibido de otros nodos.
### 4. Reglas de comunicación
Especifican las condiciones y restricciones para la transferencia de datos o recursos.

- Disponibilidad: Un nodo solo transmite datos si tiene suficiente capacidad o recursos disponibles.
- Prioridad: Algunos flujos tienen prioridad sobre otros en caso de competencia por recursos.
### 5. Reglas de topología de la red
Regulan cómo se crean, eliminan o modifican las conexiones entre nodos.

- Creación dinámica de conexiones: Nuevas conexiones pueden aparecer si se cumplen ciertas condiciones.
- Eliminación de conexiones: Las conexiones pueden desaparecer cuando ya no son necesarias.
- Reconfiguración: Las conexiones pueden cambiar de peso o dirección dependiendo del contexto.
### 6. Reglas de sincronización
Definen el momento en que las interacciones y actualizaciones ocurren.

- Sincronización global: Todos los nodos actualizan sus estados al mismo tiempo.
- Sincronización local: Solo ciertos nodos actualizan sus estados en un momento dado, dependiendo de su contexto.
## 2. Estructura
Un Net tiene la siguiente estructura:

- Nodos: Representan agentes con un comportamiento definido (por ejemplo, sumar, borrar, duplicar).
- Cables: Conectan los puertos de los nodos.
### Puertos:
- Principal: Es el punto principal de interacción.
- Auxiliares: Son las entradas/salidas adicionales.
