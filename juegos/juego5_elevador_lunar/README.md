# 🎮 Elevador Lunar

## Descripción
Shooter espacial en el que la nave del jugador avanza en línea recta disparando automáticamente contra asteroides y enemigos. El nivel no se mide por cantidad de enemigos eliminados, sino por una distancia fija de recorrido, con dificultad auto-incremental a medida que se avanza.

**Objetivo del jugador:** Completar el recorrido de cada nivel resolviendo correctamente los desafíos matemáticos que van apareciendo, hasta vencer al jefe matemático de cada etapa.

**Mecánica principal — 3 capas:**
1. **Recorrido:** La nave dispara sola; el jugador esquiva asteroides mientras avanza.
2. **Mini-preguntas matemáticas:** Durante el recorrido aparecen operaciones simples (ej. "9 + 3 = ?") con 3 opciones, una correcta. Responder mal resta una vida.
3. **Jefes matemáticos:** Al final de cada etapa aparece un jefe que exige responder correctamente una serie de preguntas para avanzar — jefe 1 y jefe 2: 3 preguntas cada uno; jefe final: 4 preguntas.

**Mejoras entre niveles:** Al pasar de nivel se ofrecen 3 mejoras a elegir (ej. disparo doble). Elegir una mejora dispara un mini-quiz matemático: si se responde bien, se obtiene la mejora; si se falla, no se otorga.

## Género
Shooter / Educativo (matemáticas)

## Tecnología
HTML5 Canvas + JavaScript vanilla

## Controles
| Tecla / Acción | Efecto |
|---|---|
| ← / → o A / D | Mover la nave |
| 1 / 2 / 3 (o click) | Seleccionar respuesta / mejora |
| ESC | Pausa |

## Capturas de pantalla
![pantalla inicial](../../assets/capturas/juego5_inicio.png)
![gameplay](../../assets/capturas/juego5_gameplay.png)
![jefe matemático](../../assets/capturas/juego5_jefe.png)

## Apoyo de IA
- **IA:** Apoyo en el brainstorming inicial de mecánicas y generación de la estructura base del código (HTML, CSS y JavaScript).
- **Desarrollo propio:** Concepción y diseño integral de la lógica del juego, definición del flujo de ideas y dirección del proyecto. Adicionalmente, participación activa en el debugging para corregir errores del código generado y en la implementación/mejora de funcionalidades adicionales.

## Qué aprendí / qué mejoraría
- **Aprendí:** La importancia de estructurar el desarrollo por etapas de forma organizada, la optimización del flujo de trabajo en equipo sin depender estrictamente de un marco GTD, y la interacción dinámica con herramientas de IA para refinamiento e integración de código.
- **Mejoraría:**
  - Diseñar e integrar un menú principal y de configuración más completo.
  - Implementar un sistema de audio con efectos de sonido (SFX) y un soundtrack espacial envolvente.
  - Diseñar una mayor diversidad y progresión de niveles.

## Jugar
👉 [Abrir juego](index.html)