Marcador de Puntos Avanzado 🎱
Este es el repositorio de una aplicación web de marcador de puntos, diseñada desde cero para ser moderna, intuitiva y perfectamente funcional en dispositivos pequeños como smartwatches y móviles. La aplicación está contenida en un único archivo HTML, lo que la hace extremadamente portátil y fácil de usar.

✨ Características Principales
La aplicación ha evolucionado para incluir una lógica de puntuación y funcionalidades avanzadas, manteniendo siempre la simplicidad de uso.

Múltiples Jugadores: Soporte para tres jugadores, cada uno con su propio bloque de estadísticas.

Nombres Editables: Toca sobre el nombre de cualquier jugador para editarlo al instante.

Contadores Detallados: Cada jugador tiene contadores individuales para:

Saque: Un contador especial en formato Perdidos / Ganados (X / Y).

Bola en Mano: Contador simple de incremento/decremento.

Fallos: Contador simple de incremento/decremento.

Lógica de Puntuación Inteligente:

+ en "Saque" suma 1 punto al marcador principal del jugador.

- en "Saque" suma 1 punto al marcador de los otros dos jugadores.

Persistencia de Datos: ¡No pierdas nunca tu partida! El estado completo del marcador se guarda automáticamente en el localStorage del navegador, sobreviviendo a refrescos accidentales de la página.

Reseteo Inteligente:

Reset Total: Un botón principal Reset borra todos los datos de la partida y limpia la memoria.

Corrección de Errores: Haz doble clic en el contador "X / Y" de un jugador para resetear sus saques y recalcular automáticamente los marcadores de todos los jugadores según la lógica del juego.

Diseño Moderno y Responsivo:

Interfaz limpia, basada en tarjetas, que agrupa visualmente los datos de cada jugador.

Uso de fuentes modernas (Poppins) y una paleta de colores cuidada.

Optimizado para interacción táctil, incluyendo la prevención del zoom por doble toque en los contadores interactivos.

🚀 Cómo Usar
Dado que es una aplicación autocontenida, empezar es increíblemente fácil:

Descarga el archivo index.html.

Ábrelo con cualquier navegador web moderno (Chrome, Firefox, Safari, etc.) en tu ordenador, móvil o smartwatch.

¡Y listo! Empieza a registrar los puntos.

🛠️ Tecnologías Utilizadas
Este proyecto es un excelente ejemplo de lo que se puede lograr con las tecnologías web fundamentales, sin necesidad de frameworks complejos.

HTML5: Para la estructura semántica del marcador.

CSS3: Para todo el diseño visual. Se utilizan características modernas como:

CSS Variables para una paleta de colores fácil de mantener.

Flexbox para el layout.

border-spacing y box-shadow para el diseño de tarjetas.

touch-action para mejorar la experiencia en dispositivos táctiles.

JavaScript (Vanilla JS): Para toda la lógica de la aplicación, incluyendo:

Manipulación del DOM.

Gestión de eventos (click, dblclick, blur).

Interacción con la API de localStorage.