# Laboratorio #7: Snake Game
 
Juego Snake desarrollado con React 18 y Babel, ambos cargados desde CDN. Todo el código está en un único archivo `index.html`, sin herramientas de build.

> Marco Carbajal (23025)

## Cómo ejecutar

Abrir el archivo `index.html` directamente en el navegador. Se requiere conexión a internet para cargar React y Babel desde CDN.

## Cómo jugar

Usa las teclas de flecha para mover la serpiente. Come la comida roja para crecer y sumar puntos. El juego termina si chocas con una pared o con tu propio cuerpo. Al terminar puedes reiniciar desde la pantalla de Game Over.

## Componentes

- `Game` — estado global del juego
- `Board` — tablero (grilla 20x20)
- `Snake` — segmentos de la serpiente
- `Food` — comida
- `Score` — puntaje
- `Overlay` — pantalla de inicio y game over

## Extras implementados

- Pantalla de inicio y reinicio al terminar la partida
- Animaciones suaves al actualizar el tablero
- La comida nunca aparece sobre la serpiente