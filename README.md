# ligth-out
ara desarrollar este minijuego se utilizaron conocimientos de programación orientada a objetos en Python. Se crearon clases para organizar los elementos del juego, como el tablero, las casillas y el control del flujo del programa, lo que permitió separar responsabilidades y reutilizar el código en los tres niveles de dificultad. También se aplicaron ciclos (for y while) para recorrer el tablero y mantener el juego en ejecución, y sentencias condicionales (if, elif, else) para validar movimientos, cambiar el estado de las casillas vecinas y comprobar si el jugador ganó. Además, se trabajó con funciones y métodos para dividir el programa en partes pequeñas, claras y fáciles de mantener.

Otro conocimiento importante fue el manejo de la consola mediante código. Se aprendió a posicionar cada símbolo en el lugar deseado, a agregar color para distinguir las casillas encendidas, apagadas y el cursor, y a dibujar el menú y el título con arte ASCII.

<img width="464" height="287" alt="image" src="https://github.com/user-attachments/assets/ccfb571f-88d0-412d-bc1a-4c23d74e6c20" />

Dificultades encontradas

La principal dificultad fue la detección del teclado. Lograr que la consola leyera las teclas W/A/S/D, la barra espaciadora, H y Q en tiempo real, sin que el usuario tuviera que presionar Enter después de cada una, requirió investigar y probar distintas formas de capturar las pulsaciones. También fue necesario que el cursor se moviera correctamente por el tablero sin salirse de sus límites y que la pantalla se actualizara sin parpadeos.

Otra dificultad fue implementar el sistema de pistas. Se buscó que el minijuego pudiera ayudar al jugador a completarlo, indicándole qué casilla conviene activar en cada momento. Esto implicó diseñar una lógica que analizara el estado actual del tablero y sugiriera un movimiento útil, lo cual exigió pensar con más profundidad en cómo funciona la mecánica del juego.

Funcionalidad de pistas

El juego incluye una función de ayuda que se activa con la tecla H. Al presionarla, el programa resalta una casilla recomendada para acercar al jugador a la solución. Esto vuelve el juego más accesible, especialmente en los niveles medio y difícil, y evita que el jugador se frustre cuando no sabe cómo continuar.

Aprendizajes

Este proyecto permitió reforzar el uso de clases, ciclos, condicionales y funciones, además de aprender a controlar la entrada del teclado y la salida visual en consola. Resolver las dificultades ayudó a desarrollar la lógica de programación y la capacidad de investigar para encontrar soluciones.

