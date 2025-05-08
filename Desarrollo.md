# Control de movimiento con esqueleto robótico con ESP32 y servomotores
El código desarrollado permite el control de cuatro servomotores que representan los movimientos de los brazos del esqueleto de un robot. Se definen dos
servomotores para cada brazo: hombro y codo, tanto para el derecho como para el izquierdo. En la fase de configuración setup(),
se asignan los pines correspondientes a cada servomotor para establecer su conexión con la ESP32.
# Reconocimiento eficiente usando MediaPipe y OpenCV
La visión por computadora es un campo que permite a los equipos informáticos interpretar y comprender su entorno. A través del uso de algoritmos
avanzados y técnicas de aprendizaje automático, estos sistemas son capaces de analizar imágenes y videos para llevar a cabo tareas complejas, como la detección de rostros y cuerpos humanos.

# Ubicación de puntos clave de hombros, codos y muñecas
Se creó una función llamada calcular_angulo la cual recibe tres puntos en coordenadas (x, y) y calcula el ángulo entre los segmentos formados por esos
puntos. Para que los servomotores interpreten correctamente los datos recibidos por Python es necesario convertir el ángulo de radianes a grados implementando
 la función math.degrees().
