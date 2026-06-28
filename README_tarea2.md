# Tarea 2 - Cálculo del Impuesto Sobre la Renta (ISR)

## ¿Qué hace el programa?
El programa calcula el Impuesto Sobre la Renta (ISR) que debe pagar un empleado, según la escala salarial vigente publicada por la Dirección General de Impuestos Internos (DGII) de la República Dominicana. Si el sueldo del empleado está por debajo del mínimo exento, el programa indica que no aplica el descuento de ISR (N/A).

## ¿Qué datos recibe de entrada?
- Sueldo mensual del empleado (RD$).

## ¿Qué datos procesa?
- Convierte el sueldo mensual a sueldo anual (sueldo mensual × 12).
- Ubica el sueldo anual dentro de la escala progresiva de la DGII y calcula el ISR anual correspondiente:
  - Hasta RD$416,220.00: exento (0%).
  - Desde RD$416,220.01 hasta RD$624,329.00: 15% del excedente de RD$416,220.00.
  - Desde RD$624,329.01 hasta RD$867,123.00: RD$31,216.00 más 20% del excedente de RD$624,329.00.
  - Más de RD$867,123.00: RD$79,776.00 más 25% del excedente de RD$867,123.00.
- Divide el ISR anual entre 12 para obtener el monto mensual a retener.

## ¿Qué datos imprime?
- El sueldo del empleado.
- El monto de ISR a pagar (o "N/A" si el sueldo está exento de este impuesto).
<img width="1090" height="918" alt="WhatsApp Image 2026-06-28 at 12 05 07" src="https://github.com/user-attachments/assets/b29c3e82-4e0e-4771-aa78-a7ea5c2012ec" />
