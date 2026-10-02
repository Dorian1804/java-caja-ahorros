# Caja de ahorros BANCETI (Java Swing)

Aplicación de escritorio con interfaz gráfica que simula una caja de ahorros. Permite registrar los datos de un titular y realizar operaciones básicas sobre su saldo.

## Características
- Registro de datos: ID del titular, nombre, domicilio, teléfono y saldo inicial.
- Cálculo informativo del saldo con un 5% de interés anual.
- Depósitos con validación de monto (número válido y mayor a cero).
- Retiros con validación de monto y verificación de saldo suficiente.
- Consulta del saldo actual.
- Botones para limpiar los campos y cancelar, con ventanas de confirmación.
- Manejo de errores con `JOptionPane` y `try/catch` (`NumberFormatException`).

## Tecnologías
- Java
- Swing (`JFrame`, `JOptionPane`)
- NetBeans (diseñador de formularios)

## Requisitos
- JDK 8 o superior
- NetBeans (recomendado para abrir el diseño del formulario)

## Cómo ejecutarlo
1. Clona el repositorio.
2. Ábrelo en NetBeans.
3. Ejecuta la clase `Entrada`.

## Autor
Dorian Emiliano Rivera Mendez – [@Dorian1804](https://github.com/Dorian1804)
