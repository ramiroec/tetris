# Tetris en JavaScript

![Tetris Logo](https://tetris.wiki/images/thumb/a/ae/The_Tetris_Company_logo_2019.png/300px-The_Tetris_Company_logo_2019.png)

## Descripción
Tetris es un clásico juego de puzzle donde los jugadores encajan bloques de diferentes formas que caen desde la parte superior de la pantalla. El objetivo es completar líneas horizontales para eliminarlas y ganar puntos.

## Características
- **Gráficos en Canvas**: Utiliza el elemento canvas de HTML5 para renderizar el juego.
- **Controles**: Usa las teclas de flecha para mover y rotar las piezas.
- **Puntuación**: Aumenta cada vez que se completa una línea.

## Estructura del Código
El código JavaScript principal está compuesto por:

### 1. Inicialización
```javascript
const canvas = document.getElementById('tetris-board');
const context = canvas.getContext('2d');
const scoreDisplay = document.getElementById('score');

const TETROMINOS = [
    [[1, 1, 1], [0, 1, 0]], // T
    [[1, 1], [1, 1]],       // O
    // ... otras piezas
];
```
### 3. Lógica del Juego
Generar Nuevas Piezas: Selecciona aleatoriamente una nueva pieza al inicio del juego.
Movimiento y Rotación: Permite al jugador mover y rotar las piezas usando el teclado.
Detección de Líneas Completas: Comprueba y elimina líneas completas del tablero.

### 4. Instalación
Clona este repositorio
```bash
git clone https://github.com/ramiroec/tetris.git
```