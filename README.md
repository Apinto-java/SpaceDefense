# SpaceDefense
Proyecto final para Curso Unity 2D

# Temática del juego
El juego trata sobre manejar una nave, mientras nos defendemos de oleadas enemigas. Con tal fin, se deberá agregar defensas a nuestra nave en el modo "Construir", mientras que en el modo de Combate, nos defenderemos de las oleadas de enemigos y, una vez implementado, nos moveremos por el mapa en búsqueda de naves espaciales Capitales más fuertes

# Controles
Tecla B - Cambiar entre el modo construcción y combate. Para poder cambiar al modo de combate, la nave espacial debe tener al menos una torreta construida
Click izquierdo del mouse - En modo construcción sirve para seleccionar y construir torretas en los espacios de color negro que se encuentran en la nave espacial. En modo Combate, dispara los proyectiles de todas las torretas que nuestra Nave Espacial tenga equipadas. Las mismas dispararán en la dirección en la que se encuentre el mouse en la pantalla

# Mecánicas
Construcción, disparo y puntaje por destrucción de enemigos

# Colisiones
Las colisiones fueron configuradas a nivel proyecto en el menú "Edit >> Project Settings >> Physics 2D >> Layer Collision Matrix" y deberían de verse de la siguiente manera
![image](https://github.com/user-attachments/assets/538deea3-37e6-43fb-b8ea-20455bc14cac)

- Entre las naves enemigas y los proyectiles del jugador
- Entre los proyectiles del enemigo y los de la nave del jugador
- Entre los proyectiles y los límites alrededor del mapa
- Entre el punto invisible creado por "OverlapPoint" y los puntos de construcción dentro de la nave

# Animaciones
Actualmente el juego cuenta con dos animaciones. Una para el disparo de la torreta de cañon, y otro cuando el enemigo muere

# Mecánicas aún no implementadas
- Game Over (cuando la nave espacial ya no tiene más hit points)
- Movimiento por el mapa
- IA más avanzada para los enemigos, que permitan seguirlo por el mapa
- Combate con otras naves espaciales Capitales
- Escudos
- Seleccionar grupo de torretas que se desea disparar
- "Override" que permita disparar más rápido
