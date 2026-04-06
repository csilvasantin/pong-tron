# Proyecto 25 — Pong Tron

> Juego Pong estilo TRON con interfaz arcade pixelada, dos jugadores, primero a 7 gana.

## Contexto
Pong Tron es un juego arcade clásico Pong reimaginado con estética TRON (neon, lines, dark). Se juega en navegador con canvas HTML5, soporta dos jugadores locales. Interfaz minimalista con paleta de colores cian (#004466) sobre fondo negro.

## Arquitectura
- **pong-tron.html**: archivo único HTML5 con CSS incrustado y JavaScript vanilla
- Canvas: 900×600px, escala responsiva según viewport
- Controles: W/S o ↑/↓ para mover, P para pausar
- Renderización pixelada (image-rendering: pixelated)
- Fuente monospace (Courier New) para ambiance retro

## Controles
- **W/S** o **↑/↓**: mover raqueta
- **P**: pausar/reanudar
- Primer jugador a 7 gana

## Notas para IAs
- Archivo único, fácil de desplegar (no requiere servidor)
- Canvas redimensiona automáticamente en resize
- Paleta limitada a blanco, negro y cian (#004466)
- Próximos pasos: sonidos, efectos visuales, guardar puntuación, opciones de dificultad
- Compatible con navegadores modernos (ES6+, Canvas API)
