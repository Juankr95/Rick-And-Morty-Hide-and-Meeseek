![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/HideAndMeeseeks/Material/Img/Otros/Logo.png "Rick and Morty: Hide and Meeseek")

---

# Tabla de Contenidos

  #### 1. Autores
  #### 2. Descripción del juego
  #### 3. Reglas del juego
  #### 4. Referencias
  #### 5. Copyright disclaimer 
  #### 6. Diagrama de navegación <br>

---

## 1. Autores

**Nombre y Apellidos:** Guillermo Amigó Urda <br>
**Correo corporativo:** g.amigo@alumnos.urjc.es <br>
**Cuenta de GitHub:** *Yaryhus* <br>

**Nombre y Apellidos:** Alejandro Camuñas Casas <br>
**Correo corporativo:** a.camunasc@alumnos.urjc.es <br>
**Cuenta de GitHub:** *Aleviux* <br>

**Nombre y Apellidos:** Sergio García Aloguín <br>
**Correo corporativo:** s.garciaalo@alumnos.urjc.es <br>
**Cuenta de GitHub:** *mrWester* <br>

---

## 2. Descripción del juego

*Rick and Morty: Hide and Meeseek* es un juego de mesa por turnos, online y multijugador, cuyas mecánicas principales se inspiran en gran medida en el juego de mesa *Zombicide*, y, en menor grado, en los juegos de mesa *Dead of Winter* y *Arcadia Quest*, y cuya estética y ambientación se corresponden con las de la serie animada *Rick and Morty* (*Adult Swim*, *Cartoon Network*).

El desarrollo del juego consiste en la alternancia de turnos entre jugadores y la máquina, de forma que ambos controlarán diferentes avatares o personajes por el tablero, cada uno de los cuales podrá realizar diversas acciones para lograr su objetivo (escapar del mapa, matar al jefe final, etc.). Para ello, el juego cuenta con un sistema de diferentes personajes con sus respectivas características, y distintas acciones que podrán realizar en el desarrollo de la partida. A continuación, se exponen sus reglas más detalladamente.

---

## 3. Reglas del juego

*Nota: para una lista completa de personajes, objetos, escenarios y misiones, consultar el anexo incluido en este repositorio.*

El juego soporta de 2 a 4 jugadores de forma online, de manera que se irán sucediendo los turnos de cada jugador y la máquina, hasta dar lugar a que el desarrollo de la partida siga una estructura similar a la siguiente: <br><br>

**1º Introducción:** 
- **Jugadores/Personajes:** Se escoge el número de jugadores (2-4), y cada uno de ellos eligirá un personaje con el que jugar. Cada personaje tiene unos atributos o características propios.

- **Escenario/Misión:** se establece la configuración inicial del tablero y comienza la partida. <br><br>

**2º Fases de la partida:** El desarrollo de la partida viene dado por la sucesión de dos fases determinadas:
- **Fase de los jugadores:** Los jugadores jugarán por turnos, en función del personaje escogido, y durante su turno podrán realizar 4 acciones (diferentes o no) a elegir entre varias posibilidades:
  - *Hacer ruido:* el jugador puede elegir hacer ruido en la casilla en la que está, de forma que atraerá a los enemigos al final de la ronda. El ruido se disipa en la ronda siguiente, tras la fase de los enemigos. Esta acción genera 5 de ruido.
  - *Moverse:* el jugador podrá moverse 1 casilla. Por cada enemigo que haya en la casilla en que se encuentra el jugador, éste deberá tirar un dado para ver si logra escapar satisfactoriamente, o de lo contrario sufrir una herida. Esta acción no genera ruido.
  - *Atacar:* si el jugador tiene dentro de su alcance a algún enemigo lanzará tantos dados como corresponda a su personaje. El daño total será el número de aciertos. Esta acción genera 3 de ruido.
 
- **Fase de los enemigos:** Los enemigos en juego realizarán las siguientes acciones: 
  - *Movimiento:* Una vez finalizado el turno de todos los jugadores (tras realizar cada uno sus acciones), los enemigos se mueven 1 hacia la casilla adyacente que más ruido tenga, o, de lo contrario, de forma impredecible.
  - *Ataque/Defensa:* Acto seguido, si se encuentran en la misma casilla que un jugador tras haberse movido, atacan. Para ello, lanzan tantos dados como se indique según el enemigo (normal, jefe final, etc.), y el jugador atacado lanza los dados de su personaje para intentar defenderse. Cada acierto del enemigo es un impacto, y cada acierto del jugador, una defensa que lo contrarresta. Por cada impacto no defendido, el jugador sufre una herida. Cada jugador puede sufrir hasta 3 heridas, antes de morir.
  - *Aparición:* Una vez los enemigos han realizado sus acciones, aparecen más enemigos en los puntos designados del escenario. En función de cómo de avanzada vaya la partida, aparecerá un número mayor o menor de ellos. Si durante la aparición alcanza el número máximo de enemigos posibles en el tablero, de forma que no puedan aparecer más porque no "quepan", todos los enemigos actualmente en juego se "activan" y vuelven a realizar las acciones de movimiento y ataque/defensa. Tras esto, ya se hayan "activado" o no, se reinicia la ronda, volviendo a la fase de los jugadores.

Esta sucesión se producirá indefinidamente, hasta que se obtenga la victoria (se cumple el objetivo) o la derrota (muerte de algún jugador), finalizando así la partida. <br><br>

En cuanto a la parte online del juego, éste dispondrá de una consola de chat para introducir comandos a la máquina, así como comunicarse de forma asíncrona con otros jugadores.

---

## 4. Referencias

1. Web oficial de *Rick and Morty*: [http://www.adultswim.com/videos/rick-and-morty/] <br>
2. Manuales de *Zombicide*: [https://zombicide.com/en/game-rules/] <br>
3. Manuales de *Dead of Winter*: [https://www.plaidhatgames.com/games/dead-of-winter] <br>
4. Manuales de *Arcadia Quest*: [http://arcadiaquest.com/en/] <br>

---

## 5. Copyright disclaimer

This product is a non-lucrative recreation of the show through a tabletop online game, without any kind of profit or redistribution present, and for educative purposes only. 

All content and images used on this site are owned or licensed by *Adult Swim*, *Cartoon Network* or its affiliates. 
Names of *Adult Swim* products and services are trademarks of *Adult Swim*, *Cartoon Network* or its subsidiaries.
Nothing contained herein shall be construed as conferring any license or right under any *Adult Swim* patent, copyright, or trademark.

If you enjoy this product, please support the creators of the show and their respective affiliates. Thank you!

---

## 6. Diagrama de navegación

**Pantalla 1** - Menú principal del juego, pulsando espacio comenzamos la partida.

![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/DiagramaNav/IMG%20(1).PNG "Rick and Morty: Hide and Meeseek")

**Pantalla 2** - Tablero inicializado, mensaje de bienvenida. Para empezar a jugar, pulsamos el botón de Continuar.

![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/DiagramaNav/IMG%20(2).PNG "Rick and Morty: Hide and Meeseek")

**Pantalla 3** - Partida comenzada, podemos realizar nuestras acciones.

![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/DiagramaNav/IMG%20(3).PNG "Rick and Morty: Hide and Meeseek")

**Pantalla 4** - Acción de moverse, el jugador se mueve una casilla.

![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/DiagramaNav/IMG%20(4).PNG "Rick and Morty: Hide and Meeseek")

**Pantalla 5** - Acción de moverse, el jugador escoge una casilla adyacente (rojo) para moverse de nuevo.

![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/DiagramaNav/IMG%20(5).PNG "Rick and Morty: Hide and Meeseek")

**Pantalla 6** - Acción de ataque, en una casilla con enemigos, el jugador lanza dados para atacar. 

![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/DiagramaNav/IMG%20(6).PNG "Rick and Morty: Hide and Meeseek")

**Pantalla 7** - Turno de los enemigos, el jugador es atacado, por lo que lanza dados para defenderse.

![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/DiagramaNav/IMG%20(7).PNG "Rick and Morty: Hide and Meeseek")

**Pantalla 8** - Acceso a la meta, el jugador debe moverse a la casilla verde para ganar.

![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/DiagramaNav/IMG%20(8).PNG "Rick and Morty: Hide and Meeseek")

**Pantalla 9** - El jugador ha ganado llegando a la meta, el juego se resetea. 

![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/DiagramaNav/IMG%20(9).PNG "Rick and Morty: Hide and Meeseek")

**Pantalla 10** - El jugador ha perdido recibiendo 3 heridas, el juego se resetea. 

![alt text](https://github.com/Yaryhus/Rick-And-Morty-Hide-and-Meeseek/blob/master/DiagramaNav/IMG%20(10).PNG "Rick and Morty: Hide and Meeseek")

---
