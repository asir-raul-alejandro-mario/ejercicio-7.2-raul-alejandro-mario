# ejercicio-7.2-raul-alejandro-mario

Este ejercicio trata de lo siguiente:Realizar mediante script de Linux un programa que simule un pequeño juego de Rol por terminal.

El juego consistirá en un marcador donde se apunte los pasos que quedan para escaparse de
un castillo. Y otro marcador donde se lleve los puntos de vida.
En cada ronda el jugador tirará dos dados. La puntuación obtenida se restará del marcador de
los pasos. Después del movimiento podrá aparecerle uno de los tipos de monstruo o no.
Deberás hacer un random y según el resultado sucederá un evento u otro.
Todos los monstruos tienen solo un punto de vida. Dependiendo del monstruo que crees,
tendrán más o menos dados de ataque o defensa.
Cuando aparece un monstruo el héroe ataca al monstruo o se defiende. Si decide atacar Tira 3
dados de ataque y si la suma de sus dados es mayor que la suma de los dados de defensa del
monstruo, el héroe mata al mostro. Si decide defenderse retrocede 5 pasos, pero puede tirar
un dado extra de defensa en ese turno. Si no consigue matar al monstruo en la siguiente ronda
le toca atacar al monstruo. Esta lanza sus dados de ataque y el héroe 3 dados de defensa, si la
suma de los dados del monstruo es mayor que la del héroe, este pierde un punto de vida. El
héroe no puede avanzar hasta que finalice el monstruo.
El juego acaba cuando el marcador de pasos se pone a cero, por tanto, se ha escapado del
castillo el héroe. O cuando el marcador de vidas se pone a cero.
Ejemplo de monstruos
Orco: 3 dados ataque, 2 dados defensa.
Trol: 2 dados ataque, 1 dados defensa.
Esqueleto: 1 dados ataque, 2 dados defensa.
Ejemplo de marcador inicial
Vida: 4 puntos
Pasos: 60
