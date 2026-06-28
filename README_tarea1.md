# Tarea 1 - Cálculo de Cuota de Préstamo

## ¿Qué hace el programa?
El programa calcula la cuota mensual que debe pagar una persona por un préstamo, utilizando la fórmula del sistema de amortización de cuota fija (sistema francés). A partir del monto del préstamo, la tasa de interés anual y el tiempo a pagar en meses, calcula cuánto debe pagar mensualmente.

## ¿Qué datos recibe de entrada?
- Monto del préstamo (RD$).
- Tasa de interés anual (%).
- Tiempo a pagar (en meses).

## ¿Qué datos procesa?
- Convierte la tasa de interés anual a una tasa de interés mensual.
- Aplica la fórmula de la cuota fija: Cuota = Monto × i / (1 - (1 + i)^-n), donde "i" es la tasa mensual y "n" es la cantidad de meses.
- Contempla el caso especial en que la tasa de interés sea 0%, dividiendo el monto entre la cantidad de meses.

## ¿Qué datos imprime?
- El monto del préstamo.
- La tasa de interés anual.
- El tiempo a pagar en meses.
- La cuota mensual a pagar.
