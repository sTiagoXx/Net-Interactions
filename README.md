# Net Interactions
## 1. El Net Interaction o Modelo de Interacción 
Es una forma gráfica y/o conceptual de representar la computación como un 
conjunto de interacciones locales entre elementos básicos llamados agentes. Este modelo es una extensión natural de las 
estructuras gráficas utilizadas en lógica lineal y programación funcional, y puede implementarse para representar algoritmos, realizar operaciones aritméticas y manejar estructuras de datos.

El Net Interaction es una representación computacional basada en grafos. En este modelo:

- Agentes: Representan operaciones o elementos computacionales (como sumar, duplicar, borrar, etc.). Cada agente tiene:

b. Un puerto principal (entrada o salida principal). <br>
c. Puertos auxiliares, cuyo número depende de la operación que realice (su aridad). <br>
d. Red (Net): Es un conjunto de agentes conectados mediante cables, formando una estructura que puede transformarse dinámicamente. <br>

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
  Entonces...

Un agente de tipo 𝛼
α y con aridad ar(α)=n≥0 tiene un puerto principal y 𝑛 puertos auxiliares. Cada puerto puede estar conectado a lo sumo a una sola arista. Cada arista está conectada 
exactamente a dos puertos. Los puertos que no están conectados a ninguna arista se denominan puertos libres. Los puertos libres, en conjunto, forman la 
interfaz de una red de interacción. Todos los tipos de agentes pertenecen a un conjunto Σ llamado firma (signature).

Una red de interacción que consiste únicamente en aristas se denomina un cableado (wiring) y se suele denotar como 𝜔. Un árbol 𝑡 con su raíz 
𝑥 se define inductivamente ya sea como:

Una arista 𝑥, o
Como un agente 𝛼 con su puerto principal libre 𝑥
y sus puertos auxiliares 𝑥𝑖 conectados a las raíces de otros árboles 𝑡𝑖

Gráficamente, las estructuras primitivas de las redes de interacción pueden representarse de la siguiente manera:
![image](https://github.com/user-attachments/assets/5b71ca6e-b556-4c1c-a72c-860c701857f6)

Cuando dos agentes están conectados entre sí a través de sus puertos principales, forman un par activo. Para los pares activos, se pueden introducir reglas de interacción que describen cómo el par activo se reescribe en otro net de interacción. Un net de interacción sin pares activos se dice que está en forma normal. Una firma Σ (con ar : Σ→N definida en ella) junto con un conjunto de reglas de interacción definidas para agentes α∈Σ constituyen un sistema de interacción.

### Explicación:

En términos más simples, un par activo es como dos piezas de un rompecabezas que encajan perfectamente. Cuando estas piezas se conectan, pueden transformarse en una nueva configuración. Las reglas de interacción son las instrucciones que dictan cómo se realiza esta transformación.

Un net de interacción es como un conjunto de estas piezas conectadas. Cuando todas las piezas han encontrado su pareja y se han transformado, el net está en forma normal.

Una firma es como un catálogo de las diferentes tipos de piezas que pueden existir en un net. Un sistema de interacción es el conjunto completo de piezas y las reglas de cómo pueden interactuar entre sí.

