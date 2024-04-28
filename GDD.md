# CANNONMAN: ENDLESS-RUN

## GAME DESIGN DOCUMENT

Creado por: Martín Gago Chorén

Versión del documento: 1.0

## HISTORIAL DE REVISIONES

| Versión | Fecha      | Comentarios |
| 1.0     | 28/04/2024 | Creación y redacción del GDD  |

## RESUMEN

### Concepto

> Cannonman: Endless-run es un juego singleplayer en el que manejamos la figura del famoso hombre bala o Cannonman. Nuestro objetivo es mejorar los atributos nuestro personaje para cada vez lograr un nuevo récord y superarnos a nosotros mismos alcanzando nuevas metas. La gracia del juego radica en que se trata de un juego infinito con progresión exponencial, lo que lo convierte en un juego adictivo sin fin. 

### Puntos Clave

> *En forma de lista, explica las características principales del juego, de forma que permita entender la experiencia de juego. Enfatiza los elementos más importantes, divertidos y/o innovadores. Procura que haya un mínimo de 5 puntos clave*

Los puntos clave que hacen que Cannonman sea un juego adictivo que incentive al jugador a continuar jugando son:

>1.- Sencillez de los controles: Los controles simples permiten que jugadores de todos los niveles de habilidad puedan disfrutar del juego, desde aquellos experimentados hasta los más casuales que buscan pasar un rato divertido.
>2.- Gestión de recursos: A medida que el juego avanza, mejorar los atributos del jugador se vuelve cada vez más costoso, lo que obliga al jugador a tomar decisiones estratégicas sobre cómo invertir sus recursos para maximizar su progreso de manera eficiente.
>3.- Crecimiento exponencial: El progreso del jugador y la dificultad del juego aumentan de manera exponencial, lo que proporciona una sensación de logro gratificante cuando se alcanzan nuevos récords y metas que parecían inalcanzables anteriormente.
>4.- Gameplay infinito: Cannonman ofrece una experiencia de juego sin fin, donde el único límite es la determinación del jugador por superar sus propias marcas y alcanzar nuevas distancias.
>5.-Variedad de obstáculos: A lo largo del recorrido, los jugadores se encontrarán con una variedad de obstáculos y enemigos que desafiarán su habilidad y destreza. Además, hay elementos que ayudarán al jugador a superar los desafíos y avanzar aún más.
>6.- Paisaje y entorno cambiantes: Conforme el jugador avanza, el paisaje y el entorno se transforman, lo que sirve como indicador visual del progreso del jugador y añade variedad visual a la experiencia de juego.
>7.- Juego multitarea: Un punto clave es que este juego es compatible con realizar otras tareas (escuchar música, ver la televisión, realizar tareas monotonas) puesto que no requiere del 100% de la atención del usuario para poder jugarlo debido a la naturaleza del gameplay
### Género

> Aventura, Arcade, Gestión de recursos, Clicker, Endless-runner, Incremental-games

### Público Objetivo

El juego está dirigido a un público amplio y diverso, con un enfoque principal en jugadores casuales que buscan entretenimiento ligero durante tiempos muertos. El rango de edad al que se dirige abarca desde adolescentes de 16 años hasta adultos de 35 años, lo que refleja su accesibilidad y atractivo intergeneracional. No se hace distinción de género, ya que el juego está diseñado para ser disfrutado por cualquier persona interesada en una experiencia de juego relajada y adictiva.

El tipo de jugador al que se dirige son aquellos que prefieren actividades de ocio simples y poco demandantes, donde puedan disfrutar de la jugabilidad sin la presión de tener que prestar atención constante. Para los adolescentes, el juego puede ser una distracción divertida durante viajes en transporte público o en momentos de aburrimiento, aunque no recomendamos su uso durante clases. Para los adultos, el juego ofrece una forma fácil y rápida de desconectar durante pausas en el trabajo o en momentos de relax en casa.

Otros tipos de juegos que podrían interesar a este público objetivo incluyen otros títulos casuales y adictivos como juegos de puzzles, juegos de ritmo, simuladores simples, y juegos de gestión de recursos. Además, podrían disfrutar de juegos móviles similares que ofrecen una experiencia de juego rápida y gratificante para jugar en cualquier lugar y en cualquier momento.

### Experiencia de Juego

Cuando el jugador se sumerje en Cannonman: Endless-Run, experimentará una experiencia de juego emocionante y adictiva. Visualmente, verá a su personaje (Hombre bala) siendo lanzado desde un cañón, volando a través de paisajes coloridos y variados que cambian a medida que avanza. Los escenarios van desde un bosque hasta desiertos áridos o paisajes nevados, ofreciendo una variedad visual estimulante.

Los obstáculos y enemigos aparecerán en el camino del jugador, desafiándolo a esquivarlos. Desde simples rocas hasta rinocerontes en movimiento o abejas que intentarán entorpecerte. Cada elemento del entorno presenta una amenaza que pondrá a prueba los reflejos del jugador. Pero no todo es negativo; también hay elementos beneficiosos como trampolines que ayudarán al jugador, impulsándolo y proporcionándole una velocidad extra para alcanzar nuevos récords.

Auditivamente, el jugador será envuelto por una banda sonora enérgica y motivadora que añade dinamismo y emoción a la experiencia de juego. Además de esto, el juego ofrece una variedad de efectos sonoros que complementan la acción: desde el estruendo del cañón al dispararse, hasta los sonidos de impacto al chocar con obstáculos, el golpeteo al caer al suelo, y el zumbido de salir disparado por los aires tras un encuentro con un trampolín. Estos elementos auditivos trabajan juntos para sumergir al jugador en una experiencia inmersiva y emocionante.

En términos de jugabilidad, el jugador controla los movimientos de Cannonman con simples controles de teclado, utilizando la barra espaciadora para lanzarlo desde el cañón y la flecha hacia abajo para realizar impulsos verticales. A lo largo del juego, el jugador tendrá la oportunidad de mejorar los atributos de Cannonman, como velocidad, golpeo, deslizamiento y aerodinámica, lo que le permitirá alcanzar distancias aún mayores y superar sus récords anteriores.

En resumen, el jugador experimentará una emocionante carrera infinita llena de desafíos visuales y auditivos, donde cada partida ofrece la oportunidad de superarse a sí mismo y alcanzar nuevas metas.


## DISEÑO

### Metas de Diseño

>1.- Metas de ambientación:
    - Crear paisajes variados y visualmente atractivos que cambien a medida que el jugador avanza para dar feedback de progreso al jugador.
    - Utilizar efectos de sonido envolventes para aumentar la inmersión del jugador  cada vez que realiza una acción o sudece algún evento dentro del mundo del juego.

>2.- Metas de jugabilidad:
    - Diseñar obstáculos y enemigos desafiantes que requieran habilidad y reflejos por parte del jugador para superarlos y que obliguen al jugador a esquivarlos para evitar ser penalizado.
    - Diseñar un sistema de enemigos en base al nivel de progresión del jugador de forma que cuando más avanzado esté enemigos más peligrosos pueda encontrarse. (NO DISPONIBLE EN LA DEMO)
    - Generación aleatorio de los elementos interactivos (tanto aliados como enemigos) dentro del terreno de juego para evitar que todas las partidas sean iguales.
    - Implementar elementos de progresión, como mejoras de atributos, para motivar al jugador a continuar jugando y superando sus récords.
    - Proporcionar elementos de ayuda (trampolines) que incentiven al jugador a atreverse a asumir el riesgo de poder ser golpeado por un enemigo a cambio de ser impulsado por un trampolín.
    - Evitar pantallas de carga y otros menús para hacer el gameplay mucho más fluido y agradable para el jugador. (De hecho el menú de gameover tengo previsto eliminarlo, únicamente lo he puesto para cumplir con los requisitos de entrega)

>3.- Metas de interacción:
    - Desarrollar controles simples que permitan a los jugadores disfrutar del juego sin dificultad independientemente si están familiarizados con los videojuegos o no.
    - Incorporar elementos interactivos como trampolines que proporcionen al jugador ventajas estratégicas y añadan diversidad al gameplay.
    - Botones de mejora para los atributos del jugador que le ayudarán a alcanzar nuevas metas.

>4.- Metas de rejugabilidad:
    - Implementar sistemas de logros y desafíos que incentiven a los jugadores a regresar y explorar nuevas formas de jugar. (NO DISPONIBLE EN LA DEMO)
    - Ofrecer actualizaciones periódicas con contenido nuevo, como niveles adicionales o eventos especiales, para mantener fresca la experiencia del juego a largo plazo. (EN CURSO)

Metas de rendimiento y optimización:
    - Optimizar el rendimiento del juego para garantizar una experiencia fluida y sin interrupciones en una variedad de dispositivos tanto móviles como ordenadores de baja gamma. (EN CURSO)
    - Minimizar los tiempos de carga y optimizar los recursos para garantizar una experiencia de juego rápida eficiente.

## MECÁNICAS DE JUEGO

### Núcleo de Juego

> *Explica las mecánicas en la que se basará el juego. Se deben indicar las reglas del juego, describir a detalle cómo funciona cada una de ellas y cómo interactúan entre ellas. Es recomendable explicarlo como si fuera una simulación del mundo. Esta sección es la más importante y larga*

En Cannonman: Endless-Run, las mecánicas del juego se basan en la acción de lanzar al personaje principal, Cannonman, desde un cañón y controlarlo a medida que avanza por un entorno infinito lleno de obstáculos y desafíos. Aquí se describen las principales mecánicas del juego y cómo interactúan entre sí:

> Lanzamiento desde el cañón:
Regla: Al iniciar cada partida, el jugador lanza a Cannonman desde un cañón con velocidad inicial indeterminada.
Funcionamiento: Para determinar la velocidad a la que sale despedido el jugador, éste deberá realizar una prueba de habilidad en el que deberá pulsar la tecla espaciadora en el momento de mayor potencia del cañon. La forma en la que se calcula la velocidad máxima con la que podrá salir despedido el jugador es gracias al atributo de **Velocidad** del jugador y al nivel que éste tenga. El cálculo de la velocidad máxima proviene de la siguiente función matemática: **Base + Mathf.Pow(1.07f, Level) + (0.5f * Level)** Dónde:
    - La velocidad base (**Base**) es un valor constante.
    - La velocidad máxima se determina mediante una suma exponencial que depende del nivel del atributo de velocidad de Cannonman (**Level**). Esta suma exponencial se obtiene elevando el valor 1.07 a la potencia del nivel del atributo velocidad.
    -Además, se agrega un incremento lineal de 0.5 por cada nivel del atributo de velocidad.
El resultado de esta operación matemática proporciona la velocidad máxima a la que Cannonman puede ser lanzado. La velocidad mínima se establece como el **40%** de la velocidad máxima, asegurando un rango de velocidad adecuado para el jugador.

### Flujo de Juego

> *Describe la secuencia del juego durante la partida, en una ejecución normal. Se debe escribir en orden de secuencia, desde el inicio hasta el final de la partida. Debería ser por medio de un diagrama de flujo*

### Fin de Juego

> *Explica, por medio de una lista, todas las maneras en las que puede concluir la partida. El orden debe ser el siguiente: primero las derrotas, luego las victorias y, al final, cualquier otra situación. En cada una de ellas, se debe describir lo que sucede en caso de que ocurra esa situación. Siempre debe haber una manera de dar fin al juego*

### Física de Juego

> *Explica la física del juego. Es decir, describe sobre qué elementos se aplica y cómo funciona la física que se ejerce en el universo del juego*

### Controles

> *Describe cuáles serán los controles a usar dentro del juego, tanto durante la partida como en el manejo de menú. Es recomendable utilizar una tabla y/o imágenes para indicar los botones a usar y sus funciones. En caso de haber más de un tipo de control, explícalos por separado*

## MUNDO DEL JUEGO

### Descripción General

> *Describe la apariencia básica y la sensación general del mundo en el que se desarrolla el juego. Añade cualquier información relevante con el fin de identificar la situación del jugador en el entorno*

### Personajes

> *Describe cada uno de los personajes que forman parte del juego. Indicar su nombre, apariencia, comportamiento y habilidades en caso de que las tenga. Sepáralos en 3 grupos, dependiendo de la existencia de ellos en el juego: Jugables, Secundarios y Enemigos. Es necesario incluir una imagen de cada personaje junto a su descripción*

### Objetos

> *Describe cada uno de los objetos que existen dentro del juego y pueden ser utilizados por el jugador. Escribe su nombre y su rINTERFAZ
### Flujo de Pantallas

> *Describe todas las pantallas del juego. Explica su apariencia general, los elementos de cada pantalla y la interconexión entre ellas. Es recomendable indicar primero la interacción de las pantallas usando un diagrama de flujo*

### HUD

> *Describe el HUD del juego durante el desarrollo de la partida. Todos los elementos que se muestran en ella deben ser indicados, incluyendo una descripción de su propósito. Es preferible incluir además una imagen con la composición gráfica conceptual de sus elementos*

> **HUD**: *acrónimo del término inglés Heads-Up Display (Presentación de Información). Conjunto de iconos, números, mapas, etc. que durante el juego nos dan información sobre el estado de nuestra partida y/o nuestro personaje, como por ejemplo vida restante, ubicación, munición, objetos en uso, etc.*

## ARTE

### Metas de Arte

> *Explica los objetivos que se quieren lograr en el arte del juego. Describe, de manera general, el estilo de arte aplicado además de indicar el concepto visual que se desea lograr en los elementos. Explica, por separado, el significado de la apariencia general de escenarios y personajes*

### Assets de Arte

> *Indica, en forma de lista ordenada, todas las imágenes y animaciones incluidas en el juego. Agrupa los assets por contenido relacionado. Por ejemplo, un personaje puede contener animaciones de salto, reposo, ataque, etc*

## AUDIO

### Metas de Audio

> *Explica el enfoque musical y sonoro del juego. Indica el objetivo general del audio dentro del juego y cómo se piensa alcanzarlo. También se debe describir, por separado, el concepto general de la música y los efectos de sonido del juego, incluyendo el silencio, en caso de haber un uso intencional de él*

### Assets de Audio

> *Indica, en forma de lista ordenada, todos los audios incluidos en el juego. Se debe agrupar los assets en dos grupos, Música y Sonidos. En el grupo Sonidos, internamente se debe agrupar en base al contenido en el cual es usado. Por ejemplo, un personaje puede contener sonidos de salto, golpe, muerte, etc*

## DETALLES TÉCNICOS

### Plataformas Objetivo

> *Indica las plataformas en las cuales sería publicado el juego. También se debe agregar cualquier especificación técnica que deba tener la plataforma para la normal ejecución del videojuego*

### Herramientas de Desarrollo

> *Indica todas las herramientas de desarrollo utilizadas para la creación del juego. Incluye el motor del juego y sus complementos, los programas usados en el arte y la música y cualquier otro programa usado durante su desarrollo*
