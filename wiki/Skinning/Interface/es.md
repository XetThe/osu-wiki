# Skinning de la interfaz

*Ver también: [Interface](/wiki/Client/Interface)*

Los elementos de skinning de la interfaz son utilizados en múltiples modos de juego o partes de la Interfaz de Usuario del juego

## Menú principal

`menu-background.jpg`

![](img/menu-background.jpg)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | 1366x768 (ver notas) |

Notas:

- [osu!supporter](/wiki/osu!supporter) requerido.
- Este elemento esta posicionado en el centro, y esta en modo 'cover' (cubrir toda la pantalla, manteniendo la relación de aspecto, y recortando el contenido fuera de la ventana del juego).
- Por defecto, osu! tiene varias imágenes de fondo que ciclan constantemente.
  - Si este elemento esta presente en un skin, y el usuario tiene osu! supporter, este elemento anulara este comportamiento.
- Este elemento es usado como fondo si el mapa no tiene uno propio.
- Los fondos de temporada pueden afectar la visibilidad de este elemento.
  - Si están activados `Siempre` los fondos de temporada anularan este elemento.
  - Si están activados `A veces` los fondos de temporada anularan este elemento mientras estén en uso.
- Solo soporta la extensión `.jpg`.
  - Si el tipo de imagen es `.png` cambia la extensión a `.jpg`.
    - Si alguna parte de la imagen tiene transparencia, será cambiada a negro.
- El jugador puede arrastrar una imagen hacia la ventana del juego para cambiar el fondo. **Esto reemplaza la imagen en la carpeta del skin!**

---

`welcome_text.png`

![](img/welcome_text.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- [osu!supporter](/wiki/osu!supporter) requerido.
- Este elemento aparece al iniciar el juego.
- Este elemento se despliega y expande, y finalmente desaparece.

---

`menu-snow.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 32x32 |

Notas:

- Si no esta presente en el skin, el icono del modo de juego actual lo reemplazará
- Debe estar habilitado en [opciones](/wiki/Client/Options).
  - Esta opción puede ser habilitada automáticamente en los días festivos (Navidad, y Halloween).

## Botón

`button-left.png`

![](img/button-left.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Multiplicativo | Esquina Superior Derecha | - |

Notas:

- Usa la misma altura que las otras piezas del botón.
- El color de tinte varia dependiendo del estado del botón.

---

`button-middle.png`

![](img/button-middle.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Multiplicativo | Superior | - |

Notas:

- Este elemento se estira a la anchura requerida
- Usa la misma altura que las otras piezas del botón.
- El color de tinte varia dependiendo del estado del botón.

---

`button-right.png`

![](img/button-right.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Multiplicativo | Esquina Superior Izquierda | - |

Notas:

- Usa la misma altura que las otras piezas del botón.
- El color de tinte varia dependiendo del estado del botón.

## Cursor

`cursor.png`

![](img/cursor.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Por defecto, este elemento gira y se expande (al hacer clic).
- Comandos de [skin.ini](/wiki/Skinning/skin.ini):
  - Para desactivar el efecto de expansión (al hacer clic), cambia `CursorExpand` a `0`.
  - Para desactivar la rotación, cambia `CursorRotate` a `0`.

---

`cursormiddle.png`

![](img/cursormiddle.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Este elemento no gira o se expande (al hacer clic).
- Este elemento esta posicionado sobre `cursor.png`.

---

`cursor-smoke.png`

![](img/cursor-smoke.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Este elemento se usa cuando el jugador presiona la tecla de humo.
  - Por defecto, esta tecla es `C`.

---

`cursortrail.png`

![](img/cursortrail.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Este elemento esta debajo de `cursor.png`.
- si `cursormiddle.png` esta presente, el rastro del cursor será mas largo.
- Por defecto, este elemento no gira.
- Comando de [skin.ini](/wiki/Skinning/skin.ini):
  - Para habilitar la rotación de cursortrail, cambia `CursorTrailRotate` a `1`.

---

`cursor-ripple.png`

![](img/cursor-ripple.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Aditivo | Centro | - |

Notas:

- Este elemento se usa cuando el jugador presiona click izquierdo o click derecho en el teclado o mouse.
  - Por defecto, la tecla de click izquierdo es `Z`.
  - Por defecto, la tecla de click derecho es `X`.

## Iconos de mods

*Pagina principal: [Modificadores del juego](/wiki/Game_modifier)*

---

`selection-mod-autoplay.png`

![](img/selection-mod-autoplay.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-cinema.png`

![](img/selection-mod-cinema.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Click the Auto mod icon to see this icon.

---

`selection-mod-doubletime.png`

![](img/selection-mod-doubletime.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-easy.png`

![](img/selection-mod-easy.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-fadein.png`

![](img/selection-mod-fadein.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).

---

`selection-mod-flashlight.png`

![](img/selection-mod-flashlight.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-halftime.png`

![](img/selection-mod-halftime.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-hardrock.png`

![](img/selection-mod-hardrock.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-hidden.png`

![](img/selection-mod-hidden.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- En [osu!mania](/wiki/Game_mode/osu!mania), presiona el mod de 'Fade-In' para ver este icono.

---

`selection-mod-key1.png`

![](img/selection-mod-key1.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).
- Cicla a través de los modos de teclas.

---

`selection-mod-key2.png`

![](img/selection-mod-key2.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).
- Cicla a través de los modos de teclas.

---

`selection-mod-key3.png`

![](img/selection-mod-key3.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).
- Cicla a través de los modos de teclas.

---

`selection-mod-key4.png`

![](img/selection-mod-key4.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).

---

`selection-mod-key5.png`

![](img/selection-mod-key5.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).
- Cicla a través de los modos de teclas.

---

`selection-mod-key6.png`

![](img/selection-mod-key6.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).
- Cicla a través de los modos de teclas.

---

`selection-mod-key7.png`

![](img/selection-mod-key7.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).
- Cicla a través de los modos de teclas.

---

`selection-mod-key8.png`

![](img/selection-mod-key8.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).
- Cicla a través de los modos de teclas.

---

`selection-mod-key9.png`

![](img/selection-mod-key9.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).
- Cicla a través de los modos de teclas.

---

`selection-mod-keycoop.png`

![](img/selection-mod-keycoop.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).

---

`selection-mod-mirror.png`

![](img/selection-mod-mirror.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).

---

`selection-mod-nightcore.png`

![](img/selection-mod-nightcore.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Presiona el mod de 'Double Time' para ver este icono.

---

`selection-mod-nofail.png`

![](img/selection-mod-nofail.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-perfect.png`

![](img/selection-mod-perfect.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Presiona el mod de 'Sudden Death' para ver este icono.

---

`selection-mod-random.png`

![](img/selection-mod-random.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!mania](/wiki/Game_mode/osu!mania).

---

`selection-mod-relax.png`

![](img/selection-mod-relax.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!](/wiki/Game_mode/osu!), [osu!taiko](/wiki/Game_mode/osu!taiko), y [osu!catch](/wiki/Game_mode/osu!catch).

---

`selection-mod-relax2.png`

![](img/selection-mod-relax2.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!](/wiki/Game_mode/osu!).
- Este mod mueve el cursor por el jugador, mientras que el jugador solo tiene que hacer click.

---

`selection-mod-scorev2.png`

![](img/selection-mod-scorev2.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-spunout.png`

![](img/selection-mod-spunout.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Este elemento es exclusivo para [osu!](/wiki/Game_mode/osu!).

---

`selection-mod-suddendeath.png`

![](img/selection-mod-suddendeath.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-target.png`

![](img/selection-mod-target.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

- Este mod solo esta disponible en la versión 'cuttingedge'
- Este elemento es exclusivo para [osu!](/wiki/Game_mode/osu!).

---

`selection-mod-freemodallowed.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

- Este mod no tiene una imagen por defecto.
- Este mod no aparece en la selección de mods o en las tablas de clasificación.
- Indica el uso de ciertas combinaciones de mods.
  - No aparece si 'Score V2', 'Auto', 'Double Time', 'Nightcore', o 'Half Time' son usados por si solos, solo aparece si se combinan con otros mods.

---

`selection-mod-touchdevice.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

- Este mod no tiene una imagen por defecto.
- Este mod no aparece en la selección de mods.
- Indica el uso de una pantalla táctil.
  - El juego usa un algoritmo en segundo plano para calcular si se esta usando una pantalla táctil, si el cursor cambia de posición instantáneamente muy seguido, puede que se active.

## Asistente de compensación de sonido global

*Pagina principal: [Asistente de compensación de sonido global](/wiki/Guides/How_to_Use_the_Offset_Wizard)*

---

`options-offset-tick.png`

![](img/options-offset-tick.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Multiplicativo | Centro | - |

Notas:

- El color de tinte varia dependiendo del estado del tick.

## Area de juego

`play-skip.png`

![](img/play-skip.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] | ![Yes][true] | Normal | Bottom Right | - |

Notas:

- Nombre de animación: `play-skip-{n}.png`

---

`play-unranked.png`

![](img/play-unranked.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Este elemento aparece cuando se usan mods que deshabilitan el envío de puntuación.

---

`play-warningarrow.png`

![](img/play-warningarrow.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] (see notes) | Multiplicativo | Centro | - |

Notas:

- El estado de skin de mapa parece ser un bug.
- El color de tinte varia por versión de skin.ini.
  - Pantalla de pausa:
    - Todas las versiones: Azul
  - Terminando los descansos:
    - v1.0: Blanco
    - v2.0+: Rojo

---

`arrow-pause.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] (see notes) | Normal | Centro | - |

Notas:

- El estado de skin de mapa parece ser un bug.
- Si esta presente, este elemento anula a `play-warningarrow.png`.
- Este elemento se usa en la pantalla de pausa y de falla
- No se tinta.

---

`arrow-warning.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] (see notes) | Normal | Centro | - |

Notas:

- El estado de skin de mapa parece ser un bug.
- Si esta presente, este elemento anula a `play-warningarrow.png`.
- Se usa para indicar el final de un descanso.
- No se tinta.

---

`masking-border.png`

![](img/masking-border.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Derecha | max height: 768px |

Notas:

- Se usa cuando se juega un mapa con storyboard de 4:3 en pantalla ancha
- En el archivo [.osu](/wiki/Client/File_formats/Osu_(file_format)), cambia `WidescreenStoryboard` a `0` para que este elemento aparezca.
- Este elemento se estira a la anchura requerida
- El pilar derecho esta volteado horizontalmente.

---

`multi-skipped.png`

![](img/multi-skipped.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Bottom Right | 60x30 |

Notas:

- Este elemento se usa en partidas multijugador, junto al puntaje del jugador (al lado izquierdo) cuando el jugador vota por omitir el inicio del mapa.

---

`section-fail.png`

![](img/section-fail.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Este elemento es visible cuando el jugador tiene menos del 50% de HP, durante un descanso lo suficientemente largo.

---

`section-pass.png`

![](img/section-pass.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Este elemento es visible cuando el jugador tiene mas del 50% de HP, durante un descanso lo suficientemente largo.

### Cuenta regresiva

`count1.png`

![](img/count1.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Centro | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Debería decir "1" o "3".

---

`count2.png`

![](img/count2.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Derecha | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Debería decir "2".

---

`count3.png`

![](img/count3.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Izquierda | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Debería decir "3" o "1".

---

`go.png`

![](img/go.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Debería decir "Vamos!".

---

`ready.png`

![](img/ready.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- Debería decir "Estas listo?" or "Listo?".

### Hit bursts

*Pagina principal: [Skinning/FAQ § Jerarquía de puntuación de la pantalla de clasificación](/wiki/Skinning/FAQ#ranking-screen-hit-score-hierarchy)*

---

`hit0.png`

![](/wiki/shared/judgement/osu!/hit0.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit0-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit50.png`

![](/wiki/shared/judgement/osu!/hit50.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit50-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit100.png`

![](/wiki/shared/judgement/osu!/hit100.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit100-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit100k.png`

![](/wiki/shared/judgement/osu!/hit100k.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit100k-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit300.png`

![](/wiki/shared/judgement/osu!/hit300.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit300-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit300g.png`

![](/wiki/shared/judgement/osu!/hit300g.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit300g-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit300k.png`

![](/wiki/shared/judgement/osu!/hit300k.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit300k-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.
- This element is not shown on the ranking screen.

### Input overlay

`inputoverlay-background.png`

![](img/inputoverlay-background.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Esquina Superior Derecha | 193x55 |

Notas:

- This element is positioned at 320px height.
- Since the image is rotated, the origin on the image itself is Top Left.
- This element is used in [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch).
- This element is rotated 90 degrees clockwise and stretched by 1.05x in-game.
- Must be enabled in the [options](/wiki/Client/Options) to see.

---

`inputoverlay-key.png`

![](img/inputoverlay-key.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Centro | 43x46 |

Notas:

- This element is used in [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch).
- Positioning varies for each key:
  - 24px away from screenborder
  - K1/L: at 350px height
  - K2/R: at 398px height
  - M1/D: at 446px height
  - M2: at 492px height
- Toggleable in the [options](/wiki/Client/Options).
- Shrinks briefly when the keys are pressed.
- Tinting varies by button location and state:
  - White, if key is not pressed.
  - Yellow, if the key is pressed and located on the top half.
  - Purple, if the key is pressed and located on the bottom half.

### Pause screen

`pause-overlay.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 1366x768 |

Notas:

- When the game is paused, the playfield will be dimmed and this file will overlay on top of it.
- This element will not stretch to fit.
- Full image height is 768px.
- Smaller images are shown with transparent borders while larger images are partially shown.
- This can also be a `.jpg` file (and can have the `.jpg` extension).
  - osu! prefers `.png` over `.jpg`.

---

`fail-background.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 1366x768 |

Notas:

- When the player has failed, the playfield will be dimmed and this file will overlay on top of it.
- This element will stretch to fit.
- This can also be a `.jpg` file (and can have the `.jpg` extension).
  - osu! prefers `.png` over `.jpg`.

---

`pause-back.png`

![](img/pause-back.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This element is positioned at 576px height.
- This element is seen in the fail and pause screens.

---

`pause-continue.png`

![](img/pause-continue.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

- This element is positioned at 224px height.
- This element is seen in the pause screen.

---

`pause-replay.png`

![](img/pause-replay.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Derecha | - |

Notas:

- This element appears on the ranking screen (after finishing a map or viewing a score).
- This element is positioned at 672px height or at 576px height, if `pause-retry.png` is not available.

---

`pause-retry.png`

![](img/pause-retry.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | - |

Notas:

- Positioning varies:
  - pause or fail screen:
    - Centre, positioned at 400px height
  - ranking screen:
    - Right, positioned at 576px height
- This element appears on the ranking screen after finishing a map and on the pause and fail screens.

### Scorebar

`scorebar-bg.png`

![](img/scorebar-bg.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Esquina Superior Izquierda | - |

Notas:

- This element has no size restrictions.
- When used in [osu!mania](/wiki/Game_mode/osu!mania), this element is rotated 90 degrees anti-clockwise and is placed at the bottom right of stage.

---

`scorebar-colour.png`

![](img/scorebar-colour.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] | ![Yes][true] | (Varies) | Esquina Superior Izquierda | max height: 120px |

Notas:

- Animation name: `scorebar-colour-{n}.png`.
- Blend mode varies:
  - Multiplicative, if `scorebar-marker.png` is used.
    - Tinted black over time when near critical zone and tinted red in the critical zone.
  - Normal, otherwise.
- Positioning varies:
  - If a marker is used, positioned at (12,12).
  - Otherwise, positioned at (5,16).
- This element has no size restrictions.
- When used in [osu!mania](/wiki/Game_mode/osu!mania), this element is rotated 90 degrees anti-clockwise and is placed at the bottom right of stage.

---

`scorebar-ki.png`

![](img/scorebar-ki.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- `scorebar-marker.png` has higher priority.
- This element represents the "passing" zone.
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania).
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`
- A `scorebar-colour.png` is required for this element to appear.

---

`scorebar-kidanger.png`

![](img/scorebar-kidanger.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- `scorebar-marker.png` has higher priority.
- this element represents the "warning" zone
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania)
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`
- A `scorebar-colour.png` is required for this element to appear.

---

`scorebar-kidanger2.png`

![](img/scorebar-kidanger2.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- `scorebar-marker.png` has higher priority.
- This element represents the "critical" zone.
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania)
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`
- A `scorebar-colour.png` is required for this element to appear.

---

`scorebar-marker.png`

![](img/scorebar-marker.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Aditivo | Centro | - |

Notas:

- If skinned, this element overrides the `scorebar-ki.png`, `scorebar-kidanger.png`, and `scorebar-kidanger2.png` elements.
- The marker fades out if the player reaches the critical zone.
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania).
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`.

### Score numbers

`score-0.png`

![](img/score-0.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- Por defecto, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-1.png`

![](img/score-1.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- Por defecto, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-2.png`

![](img/score-2.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- Por defecto, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-3.png`

![](img/score-3.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- Por defecto, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-4.png`

![](img/score-4.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- Por defecto, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-5.png`

![](img/score-5.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- Por defecto, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-6.png`

![](img/score-6.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- Por defecto, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-7.png`

![](img/score-7.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- Por defecto, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-8.png`

![](img/score-8.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- Por defecto, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-9.png`

![](img/score-9.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- Por defecto, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-comma.png`

![](img/score-comma.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 5x14 |

Notas:

- Por defecto, this is also used for the combo numbers.
- This element is for the accuracy.
- The usage is dependent on your selected language.

---

`score-dot.png`

![](img/score-dot.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 5x14 |

Notas:

- Por defecto, this is also used for the combo numbers.
- This element is for the accuracy.
- The usage is dependent on your selected language.

---

`score-percent.png`

![](img/score-percent.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 12x14 |

Notas:

- This element is for the accuracy.

---

`score-x.png`

![](img/score-x.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | 10x14 |

Notas:

- This element is for the combo, only used in [osu!](/wiki/Game_mode/osu!).
- Blend mode varies:
  - If used for combo counter:
    - Additive for the expanding after images.

## Ranking grades

`ranking-XH.png`

![](img/ranking-XH.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screenborder
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-XH-small.png`

![](img/ranking-XH-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-X.png`

![](img/ranking-X.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screenborder
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-X-small.png`

![](img/ranking-X-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-SH.png`

![](img/ranking-SH.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-SH-small.png`

![](img/ranking-SH-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-S.png`

![](img/ranking-S.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-S-small.png`

![](img/ranking-S-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-A.png`

![](img/ranking-A.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-A-small.png`

![](img/ranking-A-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-B.png`

![](img/ranking-B.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-B-small.png`

![](img/ranking-B-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-C.png`

![](img/ranking-C.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-C-small.png`

![](img/ranking-C-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-D.png`

![](img/ranking-D.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-D-small.png`

![](img/ranking-D-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

## Ranking screen

`ranking-accuracy.png`

![](img/ranking-accuracy.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] (see notes) | ![No][false] | Normal | Esquina Superior Izquierda | - |

Notas:

- Can be animated, but only the zeroth frame will be used.
  - Animation name: `ranking-accuracy-{n}.png`
- Positioning varies:
  - v1.0: (291,500)
  - v2.0+: (291,480)

---

`ranking-graph.png`

![](img/ranking-graph.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | min: 308x156 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | min: 308x148 |

Notas:

- Positioning varies:
  - v1.0: (256,576)
  - v2.0+: (256,608)
- The box itself is 301x141.
- The first 7 pixels at the top and at the left should be transparent.
  - In v1 it's shifted down by 8px.

---

`ranking-maxcombo.png`

![](img/ranking-maxcombo.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] (see notes) | ![No][false] | Normal | Esquina Superior Izquierda | - |

Notas:

- Can be animated, but only the zeroth frame will be used.
  - Animation name: `ranking-maxcombo-{n}.png`
- Positioning varies:
  - v1.0: (8,500)
  - v2.0+: (8,480)

---

`ranking-panel.png`

![](img/ranking-panel.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | max height: 694px |
| 2.0+ | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | max height: 666px |

Notas:

- Positioning varies:
  - v1.0: (0,74)
  - v2.0+: (0,102)

---

`ranking-perfect.png`

![](img/ranking-perfect.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] (see notes) | ![No][false] | Normal | Centro | - |

Notas:

- Can be animated, but only the zeroth frame will be used.
  - Animation name: `ranking-perfect-{n}.png`
- Positioning varies:
  - v1.0: (320,688)
  - v2.0+: (416,688)

---

`ranking-title.png`

![](img/ranking-title.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Esquina Superior Derecha | - |

Notas:

- x-position 32px away from the right side

---

`ranking-replay.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Derecha | - |

Notas:

- Position varies:
  - at 672px height.
  - at 576px height, if retry is not available.

---

`ranking-retry.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Derecha | - |

Notas:

- Positioned at 576px height.
- If skinned, this element overrides `pause-retry.png`.

---

`ranking-winner.png`

![](img/ranking-winner.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 200x214 |

Notas:

- This element is used in [multi](/wiki/Client/Interface/Multiplayer) only.

## Score entry

`scoreentry-0.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-1.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-2.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-3.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-4.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-5.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-6.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-7.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-8.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-9.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-comma.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 5x14 |

Notas:

- This element is used for the in-game leaderboards.
- This element is used as the decimal separator.
  - Usage depends on your selected language.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right

---

`scoreentry-dot.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Esquina Superior Izquierda | 5x14 |

Notas:

- This element is used for the in-game leaderboards.
- This element is used as the decimal separator.
  - Usage depends on your selected language.
- Tinted white.

---

`scoreentry-percent.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Esquina Superior Izquierda | 12x14 |

Notas:

- This element is used for the in-game leaderboards.
- This element is used in [Multi](/wiki/Client/Interface/Multiplayer) games when the win condition is set to Accuracy.
- Tinted white.

---

`scoreentry-x.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Esquina Superior Derecha | 10x14 |

Notas:

- This element is used for the in-game leaderboards.
- This element is used as the multiplier symbol.
- Tinted cyan.

## Song selection

`menu-back.png`

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] | ![No][false] | Normal | Bottom Left | 200x214 |

Notas:

- Animation name: `menu-back-{n}.png`.
- The native back button is not skinnable.
  - If this element is skinned, it will override the new one everywhere, except for the [options](/wiki/Client/Options).

---

`menu-button-background.png`

![](img/menu-button-background.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Bottom Left | min: 690x85 |

Notas:

- Skin versións 2.2+ can support thumbnails (must be enabled in the [options](/wiki/Client/Options)) for song selection
  - Thumbnails get positioned 9px away from the left image border
  - Thumbnail size is 115x85
- This element is used in various places:
  - scoreboards in song selection
  - button for the beatmap difficulty in song selection
  - scoreboards on the left while playing
  - button that shows the selected beatmap while waiting in a room in multiplayer
- Tinting varies by button state.

---

`selection-mode.png`

![](img/selection-mode.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 92x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 92x90 |

Notas:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-mode-over.png`

![](img/selection-mode-over.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 92x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 92x90 |

Notas:

- Hover over `selection-mode.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-mods.png`

![](img/selection-mods.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-mods-over.png`

![](img/selection-mods-over.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- Hover over `selection-mods.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-random.png`

![](img/selection-random.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-random-over.png`

![](img/selection-random-over.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- Hover over `selection-random.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-options.png`

![](img/selection-options.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-options-over.png`

![](img/selection-options-over.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- Hover over `selection-options.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-tab.png`

![](img/selection-tab.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Esquina Superior Izquierda | 142x24 |

Notas:

- Depending on the client's window size, 4 to 5 tabs will be displayed.

---

`star.png`

![](img/star.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Multiplicativo | Centro | 50x50 |

Notas:

- This element is used for difficulty star ratings (seen in song selection).
  - v2.2+ will scale down the last star, if necessary
  - v2.1- will crop the last star, if necessary
- Tinting depends on the state of `menu-button-background.png`

---

`star2.png`

![](img/star2.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Aditivo | Centro | 24x24 |

Notas:

- This element is used for song selection (the stars that fly from right to left), cursor, kiai time, combobursts.

### Mode select

`mode-osu.png`

![](img/mode-osu.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 256x256 |

Notas:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!](/wiki/Game_mode/osu!) for this to be visible.

---

`mode-taiko.png`

![](img/mode-taiko.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 256x256 |

Notas:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!taiko](/wiki/Game_mode/osu!taiko) for this to be visible.

---

`mode-fruits.png`

![](img/mode-fruits.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 256x256 |

Notas:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!catch](/wiki/Game_mode/osu!catch) for this to be visible.

---

`mode-mania.png`

![](img/mode-mania.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 256x256 |

Notas:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!mania](/wiki/Game_mode/osu!mania) for this to be visible.

---

`mode-osu-med.png`

![](img/mode-osu-med.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | 128x128 |

Notas:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-taiko-med.png`

![](img/mode-taiko-med.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | 128x128 |

Notas:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-fruits-med.png`

![](img/mode-fruits-med.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | 128x128 |

Notas:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-mania-med.png`

![](img/mode-mania-med.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | 128x128 |

Notas:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-osu-small.png`

![](img/mode-osu-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 32x32 |

Notas:

- This element is on top of the `selection-mode.png` element.
- Select [osu!](/wiki/Game_mode/osu!) for this to be visible.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

---

`mode-taiko-small.png`

![](img/mode-taiko-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 32x32 |

Notas:

- This element is on top of the `selection-mode.png` element.
- Select [osu!taiko](/wiki/Game_mode/osu!taiko) for this to be visible.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

---

`mode-fruits-small.png`

![](img/mode-fruits-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 32x32 |

Notas:

- This element is on top of the `selection-mode.png` element.
- Select [osu!catch](/wiki/Game_mode/osu!catch) for this to be visible.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

---

`mode-mania-small.png`

![](img/mode-mania-small.png)

| Versión de skin.ini | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 32x32 |

Notas:

- This element is on top of the `selection-mode.png` element.
- Select [osu!mania](/wiki/Game_mode/osu!mania) for this to be visible.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

[true]: /wiki/shared/true.png
[false]: /wiki/shared/false.png
