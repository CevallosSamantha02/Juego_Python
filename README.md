# 🌲 Simulador de Vida Salvaje

Un videojuego 2D desarrollado en Python utilizando la biblioteca **Pygame**, en el que controlas a un personaje que debe sobrevivir recolectando recursos, administrando energía, comida, sed y stamina.

## 🎮 ¿Cómo jugar?

### Controles:
- **Flechas del teclado**: Mover al personaje.
- **Shift izquierdo**: Correr (consume stamina).
- **E**: Interactuar con objetos cercanos (recolectar madera o piedra).
- **I**: Abrir/cerrar el inventario.
- **F**: Recuperar comida (debug).
- **T**: Recuperar agua (debug).
- **ESC**: Volver al menú principal o cerrar inventario.

## ⚙️ Requisitos del Sistema

- Python 3.9 o superior
- Librerías necesarias:
  - `pygame`
  - (opcionalmente: `numpy`, `pymunk`, etc. si se expandiera)

Puedes instalar los requisitos con:

```bash
pip install pygame

🗂️ Estructura del Proyecto

Simulador/
├── main.py               # Lógica principal del juego
├── character.py          # Clase del personaje y su interacción
├── constants.py          # Constantes globales del juego
├── inventory.py          # Sistema de inventario
├── world.py              # Mundo y entorno del juego
├── assets/
│   ├── images/
│   ├── sounds/
└── README.md             # Este archivo

🧠 Funcionalidades Clave
Sistema de inventario visual con hotbar.

Interacción con árboles y piedras para recolectar recursos.

Sistema de día y noche.

Estado del personaje: energía, comida, sed, stamina.

Menú principal y menú de opciones.

Sonidos de ambiente y efectos (pasos, recolección).

Diseño modular siguiendo buenas prácticas de programación.

🚀 Cómo ejecutar
Asegúrate de tener los assets en la carpeta assets/ como se especifica.
Ejecuta el juego desde main.py:
python main.py
¡Disfruta sobreviviendo en la naturaleza! 🌳🪓🪵

📌 Nota
Este juego fue desarrollado como proyecto académico para demostrar el uso de programación estructurada, modularidad, manejo de eventos en tiempo real, y creación de videojuegos en Python con Pygame.
