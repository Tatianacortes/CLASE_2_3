# CLASE_2_3
# Sistemas de Transmisión 

## Tornillo Sin Fin

El objetivo de un tornillo sin fin es convertir **movimiento rotacional** (usualmente generado por un motor) en **movimiento lineal**. Existen diferentes tipos de dientes y geometrías en estos tornillos, siendo dos los más comunes:

### Tipos de Dientes en Tornillos Sin Fin

- **Dientes Cuadrados**:  
  - Permiten realizar movimientos de menor escala.
  - Son menos robustos a nivel estructural, ya que las cargas tienden a concentrarse en un punto, lo que puede causar flexión.

- **Dientes Trapezoidales** (usualmente con ángulo de 29° o 30°):  
  - Permiten mover cargas mucho más altas.
  - La cápsula se acopla mejor y las fuerzas se distribuyen de manera más uniforme a lo largo de todos los dientes, lo que mejora la resistencia y la capacidad de carga.

### Tipos de Cápsulas en Tornillos Sin Fin

- **Tornillo ACME**:  
  - La cápsula es una tuerca con rosca interna que se desplaza a lo largo de la trayectoria helicoidal del tornillo.
  - Es una opción más económica, pero presenta mayor fricción.

- **Cápsula con Esferas Recirculantes (Ball Screw)**:  
  - Incorpora esferas dentro de la cápsula para reducir la fricción y mejorar la distribución de las fuerzas.
  - Permite transportar cargas más altas de forma más eficiente, aunque su costo es más elevado.

### Características Importantes para la Selección

- **Cabeceo (Pitch)**: Número de revoluciones necesarias para que la cápsula se desplace una distancia determinada (por ejemplo, 1 metro o 1 pulgada en sistema inglés).
- **Paso (Lead)**: Distancia que se desplaza la cápsula con una revolución del tornillo (en metros o pulgadas, según el sistema).

### Simulación en Simscape

### Inercia Reflejada

Se calcula a partir de la energía cinética de la carga en movimiento. Dado que el movimiento es lineal, existe una velocidad asociada. En el caso del tornillo, la **inercia reflejada es despreciable**, ya que está conectado directamente al motor y no hay una transformación adicional debido al mecanismo.

### Torque Reflejado

El torque reflejado depende de la fuerza ejercida sobre la cápsula o carro.

---

## Piñón-Cremallera

Convierte **movimiento rotacional** en **movimiento lineal** mediante el acoplamiento de:
- Un **piñón** (rueda dentada).
- Una **cremallera** (barra dentada).

La velocidad tangencial del piñón se transmite a la cremallera, generando movimiento lineal. Este sistema es ampliamente usado en la industria debido a su facilidad de diseño, montaje sencillo y capacidad para obtener relaciones de transmisión altas en espacios reducidos.

### Relación de Transmisión

Se obtiene al comparar la velocidad del motor con la velocidad de la carga.

### Simulación en Simscape

### Inercia Reflejada

Se calcula según la masa y la configuración del sistema.

### Torque de Carga

Depende de la fuerza necesaria para mover la carga.

### Simulación en Simscape Multibody

Permite analizar el comportamiento dinámico del sistema de manera más detallada.

---

## Banda Transportadora

Sistema que convierte una **entrada rotacional** en **movimiento lineal**. Puede tener más de dos poleas para transmitir el movimiento mediante una banda.

### Relación de Transmisión

Depende del tamaño de las poleas y la configuración del sistema.

### Inercia Reflejada

Se calcula en función de la masa en movimiento y las características de la banda y las poleas.

### Torque de Carga

Se determina según la fuerza requerida para desplazar la carga a lo largo de la banda.

---

## Bandas con Más de Dos Rodillos



### Relación de Transmisión



### Inercia Reflejada



### Torque de Carga




