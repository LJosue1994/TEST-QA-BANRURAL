1. Error en la asignación del número aleatorio: En la línea 44, la generación del número aleatorio está mal implementada. En lugar de Math.random() * 10, debería ser Math.floor(Math.random() * 100) + 1 para obtener un número entero aleatorio entre 1 y 100.

2. Error en la referencia del elemento lowOrHi: En la línea 49, falta el punto antes de 'lowOrHi'. Debe ser document.querySelector('.lowOrHi') para seleccionar el elemento correctamente.

3. Error en la asignación de eventos: En la línea 87, 'addeventListener' debe ser 'addEventListener' (con 'e' en minúscula) para vincular correctamente el evento click al botón guessSubmit.

4. Error en la asignación de eventos al botón resetButton: En la línea 95, 'addeventListener' también debe ser 'addEventListener' para vincular correctamente el evento click al botón resetButton.
